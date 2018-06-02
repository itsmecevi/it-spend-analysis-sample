# it-spend-analysis-sample

This is a Doku for IT spend analysis sample with Power BI.

Source: 
https://docs.microsoft.com/en-us/power-bi/sample-it-spend from http://obvience.com/

The dataset: [Click here](https://drive.google.com/file/d/1KrXIl0PVv0xHs5YTC6oFIRR_7SrZv9tP/view?usp=sharing)

Before going further, we need understand the concept of the data model, please read the link below:
https://en.wikipedia.org/wiki/Data_model

This analysis contains 8 entity (table) and every table has attribute.

1. business area
* Attribute: Business Area,	Business Area ID,

2. cost element
* Attribute: Cost element name,	Cost Element Group,	Cost Element Sub Group,	Cost Element ID

3. country region
* Attribute: Sales Region,	Country/Region,	Country/Region ID

4. date
* Attribute: Date,	Year,	Period,	Month

5. department
* Attribute: VP, Department


6. it-area
* Attribute: IT Area,	IT Sub Area,	IT Sub Area ID

7. scenario
* Attribute: Scenario,	Scenario ID,	ScenarioDescription


8. fact_it
* Attribute: Date,	Value,	Department,	Cost Element ID,	Country/Region ID,	Business Area ID,	IT Sub Area ID,	Scenario ID



### Let's make the data model from the 8 entity. Just drag every [Primary Key](https://en.wikipedia.org/wiki/Primary_key) of the entity in power pivot or power bi data model

![it-spend-data-model](https://user-images.githubusercontent.com/27078712/40880855-0e15d0de-66b9-11e8-9dfc-aa1619bec05d.PNG)



### After that, create [a measure in power bi or power pivot](https://docs.microsoft.com/en-us/power-bi/desktop-tutorial-create-measures)

Below are the measure of every graph,

Note! we use the format of table and attribut with in [DAX language](https://docs.microsoft.com/en-us/power-bi/desktop-quickstart-learn-dax-basics) 

Extras: [Quick Guide DAX](https://support.office.com/en-us/article/quickstart-learn-dax-basics-in-30-minutes-51744643-c2a5-436a-bdf6-c895762bec1a?omkt=en-US&ui=en-US&rs=en-US&ad=US)

---------------------------------------------------------------------------
Drag this entity for every graph: 
.
.
.coming soon!
