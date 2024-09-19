


---
layout: page
title: Binary Calculator
permalink: /Binary Calculator/
---



<form name="calculator">
  <input type="text" name="display" id="display" style="width: 100px;" disabled>
  <br>
  <input type="button" value="1" onclick="calculator.display.value += '1'">
  <input type="button" value="2" onclick="calculator.display.value += '2'">
  <input type="button" value="3" onclick="calculator.display.value += '3'">
  <input type="button" value="+" onclick="calculator.display.value += '+'">
  <br>
  <input type="button" value="4" onclick="calculator.display.value += '4'">
  <input type="button" value="5" onclick="calculator.display.value += '5'">
  <input type="button" value="6" onclick="calculator.display.value += '6'">
  <input type="button" value="-" onclick="calculator.display.value += '-'">
  <br>
  <input type="button" value="7" onclick="calculator.display.value += '7'">
  <input type="button" value="8" onclick="calculator.display.value += '8'">
  <input type="button" value="9" onclick="calculator.display.value += '9'">
  <input type="button" value="*" onclick="calculator.display.value += '*'">
  <br>
  <input type="button" value="0" onclick="calculator.display.value += '0'">
  <input type="button" value="=" onclick="calculate()">
  <input type="button" value="C" onclick="calculator.display.value = ''">
  <input type="button" value="/" onclick="calculator.display.value += '/'">
</form>

<p id="binaryResult"></p> <!-- This will show the binary result -->

<script>
  function calculate() {
    const displayValue = calculator.display.value;
    let result;

    try {
      // Perform the calculation
      result = eval(displayValue);

      // Convert the result to binary, handle decimals separately
      let binaryResult = convertToBinary(result);

      // Display the binary result
      document.getElementById('binaryResult').textContent = "Binary: " + binaryResult;

      // Update the calculator display with the result
      calculator.display.value = result;

    } catch (e) {
      calculator.display.value = 'Error';
      document.getElementById('binaryResult').textContent = '';
    }
  }

  // Function to convert the result to binary
  function convertToBinary(number) {
    if (Number.isInteger(number)) {
      // If it's an integer, simply convert to binary
      return number.toString(2);
    } else {
      // If it's a decimal, handle fractional part separately
      const integerPart = Math.floor(number);
      const decimalPart = number - integerPart;

      // Convert the integer part to binary
      let binaryInteger = integerPart.toString(2);

      // Convert the decimal part to binary
      let binaryDecimal = '';
      let fraction = decimalPart;
      let precision = 10; // Precision limit for the decimal part conversion
      
      // Multiply the fractional part by 2 and capture each "1" or "0"
      while (fraction > 0 && precision > 0) {
        fraction *= 2;
        if (fraction >= 1) {
          binaryDecimal += '1';
          fraction -= 1;
        } else {
          binaryDecimal += '0';
        }
        precision--;
      }

      return binaryDecimal ? `${binaryInteger}.${binaryDecimal}` : binaryInteger;
    }
  }
</script>
