# function
function BMI(weight, height) {     var bmi = weight / (height ** 2);     alert('your bmi is:' + bmi.toFixed(2)); } var weight = (prompt('enter your weight (KG):')); var height = (prompt('enter your height (CM):')) / 100; BMI(weight, height)
