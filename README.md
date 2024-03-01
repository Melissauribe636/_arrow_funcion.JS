const sinParametros = () => {
    console.log("Esta función no recibe ningún parámetro");
};

sinParametros();

const unParametro = (valor) => {
    console.log("El valor recibido es: " + valor);
};

unParametro(10);

const masDeDosParametros = (...parametros) => {
    let resultado = 0;
  
    parametros.forEach((parametro) => {
        resultado += parametro;
    });
    console.log("La suma de los parámetros es: " + resultado);
};


masDeDosParametros(1, 2, 3, 4, 5);
