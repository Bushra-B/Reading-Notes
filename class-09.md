# HTML Forms

**HTML froms are elements that allow you to collect information from visitors to your site.**  

**Form Controls:**

- adding text

- making choices

- submitting forms

- uploading files

## Form structure :

- forms are created using `<form>` element that carry two attributes, the `action` and the `method`

- the value of the `action` attribute is the URL for the page on the server that will receive the information in the form when it is submitted

- `method` attributes have two types :
    - psot
    - get
- in `get method`, the values from the form are added to the end of the URL specified in the action attribute
    - used with short forms 
    - used for retrieving data from the web server 
- in the `post method`, the values are sent in what are known as HTTP headers  
    - used to allow users to upload a file 
    - used with very long forms
    - used with forms that contain sensitive data 
    - used to add information to, or delete information from, a database

----------------------------------------------------------------------------------

# CSS List, Tables and Forms

**There are several CSS properties that are specifically used to control the appearance of lists, tables, and forms**

- List markers can be given different appearances using the `list-style-type` and `list-style` image properties.

- Table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent

- Forms are easier to use if the form controls are vertically aligned using CSS.

- Forms benefit from styles that make them feel more interactive


-------------------------------------------------------------------------------

# JS Events

**Events are the browser's wasy to indicate that something has happend**

- Binding: the proccess of stating which event you are waiting to happen, and which  element you are waiting for that event to happen upon

- when an event occures on an element, it can trigger a JS function

- the most commonly used events are W3C DOM
 