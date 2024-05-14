### Lecture Notes: Exploring HTML Form Elements and Attributes

**Objective**: To introduce HTML form elements and attributes used for collecting user input on web pages.

#### 1. HTML Form Elements

**I. `<form>` Tag**
- Definition: The `<form>` tag is used to create an HTML form for collecting user input.
- Syntax: `<form action="URL">...</form>`
  - `action`: Specifies the URL where the form data should be submitted.

**II. `<select>` Tag**
- Definition: The `<select>` tag creates a dropdown list from which users can select options.
- Syntax: `<select name="name" id="id">...</select>`
  - `name`: Defines the name of the select element.
  - `id`: Specifies a unique identifier for the element.

**III. `<option>` Tag**
- Definition: The `<option>` tag defines options within a `<select>` element.
- Syntax: `<option value="value">Text</option>`
  - `value`: Specifies the value associated with the option.

**IV. `<textarea>` Tag**
- Definition: The `<textarea>` tag creates a multiline text input control.
- Syntax: `<textarea name="name" id="id"></textarea>`
  - `name`, `id`: Similar to other form elements.

#### 2. `<input>` Tag

**I. Input Types**
- `<input>` tag is used to create various types of input fields.
- Types include `text`, `email`, `password`, `tel`, `number`, `file`, `date`, `radio`, `checkbox`, etc.

#### 3. `<button>` Tag Attributes

**I. `<button>` Tag**
- Definition: The `<button>` tag defines a clickable button.
- Syntax: `<button type="submit/reset/button">Text</button>`
  - `type`: Specifies the behavior of the button.
    - `submit`: Submits the form data.
    - `reset`: Resets the form to its initial state.
    - `button`: Just a clickable button without any default behavior.

#### 4. Form Attributes

**I. `required` Attribute**
- Definition: The `required` attribute specifies that an input field must be filled out before submitting the form.

**II. `selected` Attribute**
- Definition: The `selected` attribute is used with `<option>` elements to specify that an option should be pre-selected when the page loads.

#### 5. Input Field Attributes

**I. Common Attributes**
- `name`: Defines the name of the input field, used for form submission.
- `value`: Specifies the initial value of the input field.
- `placeholder`: Provides a hint or example of the expected value when the field is empty.

### Conclusion
- HTML forms and input elements are essential for collecting user input on web pages.
- Understanding the various attributes and tags allows developers to create interactive and user-friendly forms.

### Additional Resources
- [MDN Web Docs: HTML Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)
- [W3Schools: HTML Form Elements](https://www.w3schools.com/html/html_forms.asp)


Notes : 
1. The for attribute in the <label> tag specifies which form control the label is associated with. Its value should match the id attribute of the form control element.
2.The name attribute in HTML is used to specify the name of a form element. It is primarily used when submitting form data to a server. Each form element (such as <input>, <textarea>, <select>, etc.) should have a unique name attribute within the form.