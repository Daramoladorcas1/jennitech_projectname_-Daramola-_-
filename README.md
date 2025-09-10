# jennitech_projectname_-Daramola-_-
// Function to print multiplication table for a given number function multiplicationTable(num) {   console.log(`Multiplication Table for ${num}`);   for (let i = 1; i &lt;= 12; i++) {     console.log(`${num} x ${i} = ${num * i}`);   } }  // Example usage: if group number is 6 multiplicationTable(6);
// Calculator function to perform Arithmetic, Logical and Comparison operations
function calculator(a, b) {
  console.log("=== Arithmetic Operations ===");
  console.log(`${a} + ${b} = `, a + b);
  console.log(`${a} - ${b} = `, a - b);
  console.log(`${a} * ${b} = `, a * b);
  console.log(`${a} / ${b} = `, a / b);
  console.log(`${a} % ${b} = `, a % b);

  console.log("\n=== Comparison Operations ===");
  console.log(`${a} > ${b} = `, a > b);
  console.log(`${a} < ${b} = `, a < b);
  console.log(`${a} == ${b} = `, a == b);
  console.log(`${a} === ${b} = `, a === b);
  console.log(`${a} != ${b} = `, a != b);

  console.log("\n=== Logical Operations ===");
  console.log(`${a} > 0 && ${b} > 0 = `, (a > 0 && b > 0));
  console.log(`${a} > 0 || ${b} > 0 = `, (a > 0 || b > 0));
  console.log(`!(${a} > 0) = `, !(a > 0));
}

// Example usage:
calculator(8, 3);
