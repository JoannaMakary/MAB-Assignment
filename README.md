# MAB-Assignment

<h2>Description</h2>

With the excel file 'example.xlsx', write a html file with the following requirements:

1. Write a function in javascript to parse the 'Fitment Description' column of all the rows in the excel file into a variable with the following format:

2016|Kia |Optima |- 305mm (12.01") Diameter Rotor
2017|Kia |Optima |- 305mm (12.01") Diameter Rotor
2018|Kia |Optima |- 305mm (12.01") Diameter Rotor
2018|Hyundai|Kona |- 1.6 L4 Engine - 2.0 L4 Engine, AWD
2004|Honda |Civic |
etc.

2. Present this data as four dropdowns (Year, Make, Model, Notes). Each dropdown should constrain its options so that only parsed cars can be selected.

3. Use pure css to style dropdowns so that hovering over a dropdown makes it flash briefly while shaking slightly.

<h2>Self-notes</h2>

I believe this assignment was deceptively challenging. There were many assumptions I had to make, such as:

- Writing everything into "one HTML file"
- Importing an excel sheet onto a webpage without a server is difficult - I used SheetJS.
- Asked to format into a text version but also into a drop-down menu, I was not sure what was expected so I created buttons to do a bit of everything.

It was difficult to extract the correct data through my method of using regex as the formatting was different pretty often.

It was very difficult to figure out the logic of the dropdowns because of the way I set up the data structures the first time. I initially created them without thinking about the ability to parse through the dropdowns. Once I re-read the assignment, I realized I had to change most of my code.
