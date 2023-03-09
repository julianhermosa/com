function sumOfOddNumbers(n) {
  // calcular la suma de los primeros n números impares utilizando la fórmula n²
  return n * n;
}

// demuestra la fórmula por inducción matemática imprimiendo la suma de los primeros n números impares para diferentes valores de n
for (let n = 1; n <= 10; n++) {
  let sum = 0;
  for (let i = 1; i <= n; i++) {
    sum += (2 * i) - 1;
  }
  console.log("La suma de los primeros " + n + " números impares es: " + sum + " (fórmula: " + sumOfOddNumbers(n) + ")");
}
