Download Link: https://assignmentchef.com/product/solved-solvedemmision-limits
<br>
CS1043 LAB-5 Emissions Limits Write a Java program that interacts with a user by printing out a list of pollutants and requests input from the user as follows: 1. Carbon monoxide 2. Hydrocarbons 3. Nitrogen oxides 4. Non-methane hydrocarbons Enter pollutant number = Enter number of grams emitted per mile = Enter odometer reading = Use this table of emissions limits to determine the appropriate output message. Maximum allowed for Maximum allowed for the first 50,000 miles the next 50,000 miles 0  milage  50000 50000  milage 100000 _______________________________________________________________________ Carbon Monoxide 3.4 grams/mile 4.2 grams/mile Hydrocarbons 0.31 grams/mile 0.39 grams/mile Nitrogen Oxides 0.4 grams/mile 0.5 grams/mile Nonmethane hydrocarbons .25 grams/mile .31 grams/mile To receive full credit for this project, you must include, 1. one switch statement 2. nested if-control structure 3. Write a static method with the following header line and arguments: public static boolean mileageGramsLogic( int actualMileage, int firstMileageLimit, int secondMileageLimit, double actualGrams, double firstGramLimit, double secondGramLimit ) (See the next page for more instructions.) Run your program for these three different cases: Enter pollutant number = 2 Enter number of grams emitted per mile = 0.35 Enter odometer reading = 40112 Enter pollutant number = 3 Enter number of grams emitted per mile = 0.61 Enter odometer reading = 101000 Enter pollutant number = 4 Enter number of grams emitted per mile = 0.27 Enter odometer reading = 60200 The mileagGrams Logic return a Boolean: either the emission amount is or is not within the permitted limit. Print messages like this:  Emissions exceed the permitted level.  Emissions are within the permitted level. Note there is no emission limit for mileage beyond 100000 miles.