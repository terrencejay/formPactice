# formPactice

a webpage With basic forms
also demonstrating how to create accessible Rich Internet Applications also known as ARIA

##OVERVIEW 
index.html includes form examples and how to add accessibility for users with disabilities.
These features include:
***aria-labelledby** Links form elements to groups of elements to their corresponding label or description

***aria-required ** links an input field with its label or description, providing additional information.
* **Semantic HTML:** Using HTML elements like `<label>`, `<input>`, `<select>`, `<radio>`, and'<checkbox>'
* **Clear Labels:** All input fields have labels, making them understandable.
##Examples
*Email Input
Demonstrates a required Email Input field with HTML5 validation and ARIA attributes
*Number Input
a numerical input field with a min and maximum value constraint
##How to use

1.  **Clone the Repository:**
    ```bash
    git clone [repository URL]
    ```
2.  **Open `index.html`:** Open the `index.html` file in your web browser.
3.  **Interact with the Forms:** Test the forms with a screen reader or by navigating using the keyboard to experience the accessibility enhancements.

## ARIA Attributes Explanation

* **`aria-labelledby`**: This attribute is used to associate a label or heading with a form element or a group of form elements. This is especially helpful for form groups, like my radio button and checkbox examples.
* **`aria-required`**: This attribute let's screen readers know that a form field is required.
* **`aria-describedby`**: This attribute is used to relate an input field with its label or other descriptive text. This is useful for giving additional context or instructions for my input field example.
