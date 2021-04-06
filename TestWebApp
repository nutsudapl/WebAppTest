function doGet(e) {
  var params = e.parameter;
  var a = e.parameter.a;
  var b = e.parameter.b;
  var operation = e.parameter.operation;
  var response;
  switch(operation){
    case "sum" : var ans = parseInt(a)+parseInt(b)
    response = "a + b = " + ans;
    break;
    case "minus" : response = "a - b = " + parseInt(a-b);
    break;
    case "product" : response = "a x b = " + a*b;
    break;
    case "divide" : response = "a / b = " + a/b;
    break;
    case "modulus" : response = "a % b = " + a%b;
    break;
    default: response = "Wrong Operation";
  }

  return HtmlService.createHtmlOutput(response);
  
}
