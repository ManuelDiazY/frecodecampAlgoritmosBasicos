# frecodecampAlgoritmosBasicos
Ejecicios de frecodecamp Programación de Algoritmos Basicos

# 1. Convierte de Grados Celsius a Fahrenheit

function convertToF(celsius) {
  let fahrenheit=(celsius*9/5)+32;
  return fahrenheit;
}

convertToF(30);

# 2. Invierte una cadena

function reverseString(str) {
  let arr = Array.from(str);
  arr= arr.reverse();
  return arr.join("");
}

reverseString("hello");

# 3. Factoriza un número

function factorialize(num) {
  let factorial=1;
  for(let i=1;i<=num;i++){
      factorial=factorial*i;
  }
  return factorial;
}

factorialize(5);

# 4. Encuentra la palabra más larga en una cadena

function findLongestWordLength(str) {
  let palabras=str.split(" ");
  let maximo=0;
  for(let i=0; i<palabras.length; i++){
    if(palabras[i].length>maximo){
        maximo=palabras[i].length;
    }
  }
  return maximo;
}

findLongestWordLength("The quick brown fox jumped over the lazy dog");



