Download Link: https://assignmentchef.com/product/solved-csci4380-lab-7
<br>



For this lab, you will create an XML file that conforms to the structure defined in an XML Schema and contains data as described below.

`restaurant-schema.xsd` defines the structure of xml data that could be used by a restaurant.

`xml_validator` is a simple python script that will parse and validate an xml file. It requires the `lxml` pip package to be installed (`pip install lxml`), and then it can be run on the command line:

“`python xml_validator.py restaurant-data.xml“`

By default, it will look for `restaurant-schema.xsd` to use as the schema, but you can optionally define another schema as another command line argument.

## Assignment

You need to construct an xml file: `restaurant-data.xml` that’s structured according to the schema. It needs to include data that describes the following:

– The restaurant name should be “Data Bites Restaurant”– The menu should contain at least two recipes– The menu should contain a recipe named “Chili”, which would be in the “Fall” season.– There should be exactly three employees– There should be exactly one employee whose job is “dishwasher” and they should be paid “10.00”.– Some recipe should contain exactly 6 ingredients





