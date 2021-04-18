# UFO
## 1.Overview
The purpose of this exercise was to create a website to display UFO data collected in a data.js file. To display the data and create filtering functions, an app.js file was created to convert the js array of dictionaries into a table. The table was then uploaded through HTML to the website template and a filtering function was added to the page. 
## 2.Result
Multiple input fields were implemented to be able to filter the data by keys in the data set. All the data could be obtained through searching one or more keys. For example image 1 shows a search by date which will filter the data by date and refresh the webpage with only fields that match the inputed date. 

![Filter By Date](https://github.com/cchoi22/UFO/tree/main/static/images/date_filter.png)

Image 2 shows that by adding additional inputs would narrow the return fields. 

![Multi Filter Fields](https://github.com/cchoi22/UFO/tree/main/static/images/multi_field.png)

To return to the original data set each field needed to be cleared maually. Once all fields are cleared an extra click was required to refresh the unfiltered data set.

## 3.Summary
Returning to the original data set can be tedious, if multiple fields were entered. Additionally just clearing the fields does not automatically return to the unfiltered data set. An extra input is required to refresh the table. 

To address this, a clear field button was implemented, however the functionality was commented out. The button would clear the inputs, however the data would refresh. Additional code would need to be added to this function to be able to refresh the data. Another function to add to the webpage would be the total amount of data and field restrictions would be useful for the user. For example, if no data was found in Washington, when this search is inputed a no data found message would appear. This would make it easier for the user to understand the limitations of the data set.
