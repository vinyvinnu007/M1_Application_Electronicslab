REQUIREMENTS

Introduction

- Electronics lab:- When doing electronic  projects the main problem occurs at the calculation of power ,resistance and some other significant parameters. So, this application  help in the following factors and make it easier.

1.calculating the resistance of the circuit a)series and b)parallel

2.calculating the passing current and voltage through out the circuit.

\3. calculating the power consumption of the circuit.

` `RESEARCH

- As an electrical and electronics engineer every core project highly depends on electronic components and design of electronic circuit. When we are doing this type of projects we require to calculate the various parameters like power consumption, resistance of the circuit. overall current and voltage passed through the circuit. By knowing this parameters design of  circuit becomes easier and we can restrict the mistakes before building the circuit by checking parameters. Although, we have many applications for calculating this parameters but the main feature of this application i.e., electronics lab is it is actually act like a lab where we can able to know every parameter by integrating it into a  single program.
- By considering the user inputs we can able to know the lifetime of the given project. By color code of resistors this application will calculate the resistance.  

BENIFITS

This application has following Benefits

Gives the Accurate results by considering given inputs for basic electronics circuits

- When we are configuring with more than 10 resistors and capacitors there will be high chances of occurring errors in calculation. So by using this application we can regulate the errors. 

`    `Helpful for beginners

- For beginners it is a tough task to calculate the parameters in a circuit. By using this application it is much more helpful for beginners and get solution in no time.

Cost and Functions

\*In view of evolution of  electronics, the cost of every component and the device for calculating the parameters also high rates approximately 1200rs. i.e.,  Multi meter. But using this application it is most sufficient to calculate the various parameters and gives the accurate results for given inputs   

|Feature | Description

\|--------| -----------------------------------------

|`F1`    | Gives the resistor values based on the color codes

|`F2`    | GIves the reactance values for capacitor and inductor based on the inputs

|`F3`    | Gives battery information based on curent input, voltage and circuit type and usage

|`F4`    | Gives analysis and output for the following types of circuits: 1) Series 2) parallel 3) RLC (resistive, capacitive and inductive all together)

|`F5`    | Gives the power consumption data of a device and also based on the input predicts how long will the device last

This system is very cost effective when compared to various other apps because this system integrates all the factors that are present in multiple apps into one and also can interlink and use all these functions after the other.

EXEMPLIFY OUR SYSTEM

The Electronics lab can able to perform  the following actions: 1)calculate the resistance based on color code. 2)Consumption of battery based on battery type. 3)calculating the lifetime of project based on user inputs. 4)Current , power and voltage across the circuit.

SWOT ANALYSIS

What

Many students will deal with the issue of calculating the parameters when the circuit is configured with 12 or more components. Power calculations will play a major role in projecting the life time of project.

Who

1.For Every person who are going to calculate the complex calculations.

\2. All the students starting from beginning to utmost level when dealing with high configured electronics circuits.

Where

Electronic labs, electrical institutes, electrical projects and more.

When

There is no question like when because until and unless we have hardware technology we have necessity of this application.

How

Handling  this application is very easier because it is just like u give some input it considers some parameters and gives output i.e., input output application. For example if a person wants power consumption of circuit he/she needs to gives some inputs then he will get calculated power in the circuit.

HIGH LEVEL REQUIREMENTS

|ID|Description|category|Status|
| - | - | - | - |
|HLR01|User must be able to identify the resistor values by considering the color code of resistor|Technical|TBD|
|HLR02|User will be able to identify the voltage and power consumption of circuit |Technical|TBD|
|HLR03|Able to identify the life time of circuit by considering the power and voltage of the circuit|Technical|TBD|
|HLR04|User will Able to identify the type of battery using in the project|Technical|TBD|
|HLR05|User will able to identify the impedence of the circuit by considering the inductor and capacitance values of the circuit|Technical|TBD|

LOW LEVEL REQUIREMENTS

|ID|Description|Category|Status|
| - | - | - | - |
|01|The total resistance output depends on the user input.If the user doesn’t provide necessary details the intermediate function will provide the same by asking color codes|HLR1|TBD|
|02|The life time of the input circuit will be given based upon past given data and type of battery calculation and current pull of the circuit given by the user|HLR4|TBD|
|03|The required datasheet of types of batteries will be created to used in basic electronic circuits and same will be provided to user battery id.|HLR4|TBD|
|04|Based on the given inductor and capacitors values of a given  circuit the impedence will be provided as output.|HLR5|TBD|
|05|The impedence/reactance of a circuit will be calculated based on given formulas and user input|HLR5|TBD|


















**DESIGN**

HLR\_STRUCTURAL\_DIAGRAM![Structural\_UML.png](Aspose.Words.7a1ca51f-ea60-458d-adbf-9a72031f4df4.001.png) 

HLR\_BEHAVIOURAL\_DIAGRAM

![1\_Behavioural\_UML.png](Aspose.Words.7a1ca51f-ea60-458d-adbf-9a72031f4df4.002.png)






LLR\_STRUCTURAL\_DIAGRAM

![2\_Structural\_UML.png](Aspose.Words.7a1ca51f-ea60-458d-adbf-9a72031f4df4.003.png)

LLR\_BEHVIOURAL\_DIAGRAM

![2\_Behavioural\_UML.png](Aspose.Words.7a1ca51f-ea60-458d-adbf-9a72031f4df4.004.png)

**IMPLEMENTATION**

FOLDER STRUCTURE

|`                  `Folder|`                `Description|
| - | - |
|`                   `inc|The main header file for the analyzer|
|`                   `src|Main source codes for the multi file implementation|
|`                   `test|Code for various testing scenarios|
|`                  `unity|It Contains all the required unity files|

**# TEST PLAN**

**## Table no: High level test plan**

**| \*\*Test ID\*\* | \*\*Description\*\*                                              | \*\*Exp I/P\*\* | \*\*Exp O/P\*\* | \*\*Actual Out\*\* |\*\*Type Of Test\*\*  |**    

**|-------------|--------------------------------------------------------------|-------------|-------------|----------------|------------------|**

**|  H\_01       | Testing the values of the Resistor color codes for the two given bands|Color bands depending on the type|resistance value  | Session cannot be tested as it contains input parameters inside functions | Requirement based  |**

**|  H\_02       | Testing capacitive and inductive reactance value generation | capacitor/inductor vales and frequency values | Capacitive/inductive reactance  |Capacitive/inductive reactance PASS | Requirement based    |**

**|  H\_03       | Testing battery data values based on voltage, current and power rating | voltage,current,resistance input and structure pointer function to reference the values | Battery power rating and type | same and testing status PASSED | Requirement based    |**

**|  H\_04       | Testing series resistance based on the input parameters for resistive, capacitive, inductive and RLC circuits | checking parameter, function pointers based on the respective reactance values | Series overall reactance based on circuit type and current value | Not passed | Scenario based |**

**|  H\_05       | Testing parallel resistance based on the input parameters for resistive, capacitive, inductive and RLC circuits | checking parameter, function pointers based on the respective reactance values | parallel overall reactance based on circuit type and current value | Not passed | Scenario based |**

**|  H\_06       | Testing power and life expectancy of the battery based on the voltage, current, time and power rating inputs | voltage, current, time and power rating | power rating of the battery and batter life in days depending on the user choice | Same as expected, Action passed | Requirement based |**

**## Table no: Low level test plan**

**| \*\*Test ID\*\* | \*\*Description\*\*                                              | \*\*Exp IN\*\* | \*\*Exp OUT\*\* | \*\*Actual Out\*\*  |\*\*Type Of Test\*\*  |**    

**|-------------|--------------------------------------------------------------|------------|-------------|-----------------|------------------|**

**|  L\_01       | Entering the values of the resistor color codes as a seperate function and calling the function to check the output|1. resistor band value: a) for 4 band, 3 values b) for 5 band, 4 values and store in an array |overall resistance value |  Session cannot be tested as it contains input parameters inside functions | Requirement based |**

**|  L\_02       | Entering capacitor value, frequency value and passing them as function parameters in the form of arguments, using structure pointers in main| 1. capacitor value, 2. Capacitor units, 3. Frequency value, 4. Frequency units | Net capacitance|Status same as expected, PASSED | Scenario based    |**

**|  L\_03       | Entering inductor value, frequency value and passing them as function parameters in the form of arguments, using structure pointers in main| 1. inductor value, 2. inductor units, 3. Frequency value, 4. Frequency units|Net inductance|Status same as expected, PASSED | Scenario based    |**

**|  L\_04       | Checking the series resistance function for various known and unknown input values of resistances, known values of inductances and capacitance to calculate series overall resistance and current | 1.) Resistor input: a) known- resistor value and units b) unknown - color codes 2) capacitor and inductor value and unit input | Overall series resistance of the system and current requirement of the system | Test cases fail as argument does not take structure pointers | Scenario based |**

**|  L\_05       | Checking the parallel resistance function for various known and unknown input values of resistances, known values of inductances and capacitance to calculate parallel overall resistance and current | 1.) Resistor input: a) known- resistor value and units b) unknown - color codes 2) capacitor and inductor value and unit input | Overall parallel resistance of the system and current requirement of the system | Test cases fail as argument does not take structure pointers | Scenario based |**

**|  L\_06       | Calculating battery input values as battery data input using funmction pointers and sending variables as arguments | 1. checking variable 2. voltage variable 3. current variable 4. resistance value 5. units | Battery information based on voltage and power rating and print power rating | Same as expected, PASSED | Scenario based |**

**|  L\_07       | Testing the series and parallel RLC function for various known and unknown input values of resistances, known values of inductances and capacitance to calculate series and parallel overall RLC resistance and current | 1.) Resistor input: a) known- resistor value and units b) unknown - color codes 2) capacitor and inductor value and unit input 3. frequency input 4. checker variable for series or parallel | Overall series and parallel RLC resistance of the system and current requirement of the system | Test cases fail as argument does not take structure pointers | Scenario based |**

**| L\_08        | Testing power and life function by giving the respective structure pointers as arguments to find the power rating and circuit life as parameters | 1. Input pointer variables stored as structure to access dynamic memory 2. input voltage and resistance values | Overall power consumption and rating, lifetime in number of days | Session cannot be tested as it contains other input parameters in the function | Requirement based |**
