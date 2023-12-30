## Project Name: Zentrades Task - 2

### Description:
This project is an interactive web application designed to fetch, parse, and display JSON data retrieved from an external API. The provided API contains a dataset comprising 1000 product records, each having attributes such as Subcategory, Title, Price, and Popularity.

### Task:
The primary objectives of this project were:
1. Download the JSON file programmatically from the provided API endpoint.
2. Create a user interface allowing users to import the data and control the display of columns in a table format.
3. Display the data in a table, showcasing Title and Price ordered by descending Popularity.

### Implementation Details:
The project was entirely implemented using HTML and JavaScript. The key functionalities are as follows:

1. **JSON Data Retrieval:** The application fetches the JSON file from the provided API (`https://s3.amazonaws.com/open-to-cors/assignment.json`) and downloads it to the user's browser.

2. **Dynamic UI:** The application offers an interactive interface allowing users to import and control the display of columns in a table. This functionality includes multi-select options and buttons (`>>` and `<<`) for adding or removing selected options from the available fields list to the fields to be displayed list, and vice versa.

3. **Table Display:** The fetched data is presented in a table format using HTML. The table showcases product information, specifically Title and Price, which are sorted based on descending Popularity as per the project requirements.

### Deployment:
The application is deployed on GitHub Pages and can be accessed through the following link: [JSON Parsing App with Dynamic UI](https://harshul14.github.io/Zentrades-Task-2/)

### Repository Structure:
- `index.html`: Contains the HTML structure for the interactive web application.
- `script.js`: JavaScript file managing the logic for fetching, parsing, and displaying JSON data, along with dynamic UI functionalities.
- `style.css`: CSS file responsible for styling the web application's appearance.

### Usage:
To utilize or contribute to this project:
1. Clone the repository: `git clone <repository_url>`
2. Open `index.html` in a web browser to interact with the application.

### Credits:
This project was developed by Harshul Varshney as part of a specific task or assignment.

![image](https://github.com/Harshul14/Zentrades-Task-2/assets/71930077/298f44e6-97ff-4cd3-a3be-e9d99f5ddb77)

![image](https://github.com/Harshul14/Zentrades-Task-2/assets/71930077/fb2f0cfe-25f4-40ca-afda-720105344670)

