# fs-loan-qualification-checker

In this workshop, you will continue to learn how to work with conditionals by building a loan qualification checker app.

You will learn more about if statements, and how to use comparison operators and multiple conditions in an if statement.

Step 1
In this workshop, you'll review JavaScript conditionals by building a loan qualification checker app.

The app will check whether the user is eligible for a duplex, car, and condo loan based on their annual income and credit score. A credit score is a number that represents how good you are at managing borrowed money.

To get started, create the following variables and values.

Variable Name	Value
minIncomeForDuplex	60000
minCreditScoreForDuplex	700
minIncomeForCondo	45000
minCreditScoreForCondo	680
minIncomeForCar	30000
minCreditScoreForCar	650

Step 2
When the user is eligible for a loan, you'll want to display a message to them in the console.

For that, you'll build out a function inside which you'll have some checks that'll return what loan the applicant is eligible for.

Create an empty getLoanMessage function with an annualIncome and creditScore parameters.