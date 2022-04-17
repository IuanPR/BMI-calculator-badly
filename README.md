weight = float(input('weight:  '))
height = float(input('height:  '))
#
BMI = weight / height ** 2
#
if BMI < 18.5:
    print('Underweight')
if BMI >= 18.5 and BMI < 25:
    print('Normal')
if BMI >= 25 and BMI < 35:
    print('Overweight')
if BMI >= 30:
    print('Obesity')
