### Software Requirements Specification
Review the software requirements specification below. Identify potential issues and document them in a way that could be useful to the author.

|SRS|
|-|
|The application will consist of a data entry window and a data display window, which will obtain data from the former. It will include a printing option to print the information to a printer, pdf file, etc.<br><br>The data entry window will require the user to input the following customer information: first name, surname, address, city, postal code, phone number, date of birth, and preferred display colour (red, yellow, violet…). If the latter shows that the customer is under 18 years old, the text “Under-aged” will be displayed, showing the text “Adult” if the customer is over 18 years old.<br><br>Once the “Ok” button is clicked, the data display window will show all the information.|

---
**Potential problems found**

|Issues|
|-|
|The application **[what is its name?]** will consist of a data entry window and a data display window, which will obtain data from the former **[“the former”: difficult to read. It could even refer to the application itself]**. It **[who? The application, the data entry window or the data display window?]** will include a printing option to print the information **[which information?]** to a printer, pdf file, etc. **[etc? Does this include/exclude json, xml, Excel, Powerpoint…? AVOID OPEN LISTS!]**<br><br>The data entry window will require the user to input the following customer information: first name, surname, address, city **[from a list of cities, or will the user type the city’s full name (in which case s/he might type Copenhagen or København, or even misspell)?]**, postal code **[which format?]**, phone number **[are international phone numbers allowed?]**, date of birth, and preferred display colour (red, yellow, violet…) **[open list! Are burgundy, light green, and indigo included?]**. If the latter **[Error: the date of birth is not the latter in the list]** shows that the customer is under 18 years old, the text “Under-aged” will be displayed [where? When? How (on the window **[which one?]** or via an alert?)?], showing the text “Adult” if the customer is over 18 years old **[what if the customer is exactly 18 years old?]**.<br><br>Once the “Ok” button is clicked **[does this mean immediately after it is clicked, or later?]**, the data display window will show all the information **[in which format?]**.|
