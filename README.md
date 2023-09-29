# text_box_srch_js" 

# Array Search Web Application

This is a simple web application that allows you to input an array of values and search for specific elements within that array. The application is built using HTML and JavaScript and provides a user-friendly interface for entering values and conducting searches.

## Getting Started

To use the Array Search web application, follow these steps:

1. **Clone the Repository:** If you haven't already, clone this repository to your local machine using the following command:

   ```
   git clone https://github.com/your-username/array-search-web-app.git
   ```

2. **Open the HTML File:** Navigate to the directory where you cloned the repository and open the `index.html` file in your web browser.

## How to Use

The Array Search web application consists of a simple user interface with the following elements:

### Input for the Array

- Label: "Enter values separated by commas"
- Input Field: Enter the values you want in the array, separated by commas (e.g., "1, 2, 3, 4, 5").
- Button: Click the "Submit" button to update the array.

### Input for Searching

- Label: "Search:"
- Input Field: Enter the term you want to search for within the array.
- As you type, the application will dynamically filter the array to show matching elements.

### Display Area for the Array

- The array you enter or update will be displayed here.
- The filtered array, based on your search term, will also be displayed in this area.

## Functions

### `updateArray()`

- This function is triggered when you click the "Submit" button.
- It takes the values entered in the "Input for the Array" field, splits them by commas, and trims any leading/trailing spaces.
- The original array is then updated with these values, and it's displayed in the "Display Area for the Array."

### `searchArray()`

- This function is triggered as you type in the "Input for Searching" field.
- It takes the search term entered, trims it, and converts it to lowercase.
- It filters the original array to find elements that include the search term (case-insensitive).
- The filtered array is displayed in the "Display Area for the Array."

## Example

Here's how you might use the Array Search web application:

1. Enter values in the "Enter values separated by commas" field (e.g., "apple, banana, cherry, date, grape").
2. Click the "Submit" button to update the array display.
3. In the "Search:" field, start typing a term (e.g., "ban").
4. The application will dynamically filter the array and display the matching elements (e.g., "banana").

## License

This web application is open-source and available under the [MIT License](LICENSE).

---

Happy searching! If you encounter any issues or have suggestions for improvements, please feel free to contribute or reach out to us.