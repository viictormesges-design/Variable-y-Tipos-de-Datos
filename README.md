let mesaje = "¡Hola mundo!";
let texto = "Soy"; 
let nombre = "Victor";
let numero = [1,2,3,4,5];
numero.push(6);// Agrega un elemento al final del array
let texto1 = 'La lluvia en sevilla es una maravilla';
let patron = /lluvia/; // Patrón de búsqueda
let resultado = texto1.match(patron); // Realiza la búsqueda del patrón en el texto


console.log(mesaje + " " + texto + " " + nombre);// Concatenación de cadenas
console.log("Mi nombre en mayúsculas es: " + nombre.toUpperCase());//Maytusculas
console.log("Mi nombre en minúsculas es: " + nombre.toLowerCase());//minúsculas
console.log("Mi nombre tiene " + nombre.length + " caracteres.");//Longitud de la cadena
console.log("El tercer numero del array con valores '1,2,3,4,5' es: " + numero[2]);// Muestra el tercer elemento del array
console.log("se añade que sigue el orden al final del arreglo y es: "+numero[numero.length-1]);// Muestra el último elemento del array
console.log("El resultado de la búsqueda de la palabra 'lluvia' en la frase 'La lluvia en sevilla es una maravilla' es: " + resultado);// Muestra el resultado de la búsqueda
