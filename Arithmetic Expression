function evaluateExpression(expression) {
    // Remove any whitespace from the expression
    expression = expression.replace(/\s+/g, '');

    // Define a regular expression to match numbers and operators
    const tokens = expression.match(/[+\-]?\d+/g);

    // Initialize the result
    let result = 0;

    // Iterate over the tokens and compute the result
    tokens.forEach(token => {
        result += parseInt(token, 10);
    });

    return result;
}


console.log(evaluateExpression("3 + 7 - 2")); 
console.log(evaluateExpression("10 + 20 - 7 + 3 - 7"));
