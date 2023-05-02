// დავალება პირველი

function isEqual(a, b) {
  return a === b;
}

console.log(isEqual(5, 4));

// დავალება მეორე

function fahrenheitToCelsius(fahrenheit) {
  if (isNaN(fahrenheit)) {
    return false;
  }
  const celsius = ((fahrenheit - 32) * 5) / 9;
  return celsius;
}

console.log(fahrenheitToCelsius(50));

// დავალება მესამე

function calculate(num1, num2, operator) {
  if (isNaN(num1) || isNaN(num2)) {
    return false;
  } else {
    if (operator === "+") {
      return num1 + num2;
    } else if (operator === "-") {
      return num1 - num2;
    } else if (operator === "*") {
      return num1 * num2;
    } else if (operator === "/") {
      return num1 / num2;
    } else {
      return "Invalid operator";
    }
  }
}
console.log(calculate(5, 6, "*"));
