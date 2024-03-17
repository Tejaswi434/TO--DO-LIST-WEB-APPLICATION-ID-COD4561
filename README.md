**Title: CodTech IT Solutions Internship- TaskDocumentation:TO -DO LIST WEB APPLICATION**

**Introduction :**
This documentation provides detailed explanation of the task assigned during the CodTech IT Solutions internship program.The task involves in Creating  a TO -DO LIST WEB PAGE using HTML,CSS,JAVASCRIPT. This documentation will cover the implementation details,Rationale behind the code structure,and insights into the programming techniques utilised. Additionally it will include information about the intern ,Kolavanti Tejaswi, and her assigned ID COD4561.

**Intern Information**
Name:Kolavanti Tejaswi
Intern Id: COD4561 

**Task Description**
The task assigned to Kolavanti Tejaswi during the CodTech IT Solutions Internship program is to Create a TO -DO LIST WEB PAGE using HTML,CSS,JAVASCRIPT

**Implementation**
```**HTML:**
@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');

.todos-container{
    width:1000px;
}
.text {
    text-align: center;
    font-size: 60px;
}

.create {
    font-size: 40px;
    text-align: left;
    margin-top: 30px;
    padding-left: 0px;
}

.main-container {
    height: 100vh;
    width: 100vw;
    display:flex;
    flex-direction:row;
    background-image: url("https://t3.ftcdn.net/jpg/01/28/87/04/240_F_128870437_TXj1QawSYdsDbmIy0KnIOv1ytIiiDOrX.jpg"); 
    background-size:cover;
}

.inputelement {
    width: 60%;
    padding: 10px;
    border-radius: 4px;
}

.adding {
    margin-top: 10px;
}

.tasks {
    margin-top: 50px;
}

.todo_item_list {
    padding: 10px;
    width:1000px;
    margin-right:800px;
}

.label_container {
    width: 100%;
    background-color: #e6f6ff;
    border-radius: 4px;
    padding: 20px;
    margin-left: 4px;
    border-left: 5px solid #096f92;


}

.delete_icon {
    width: 100%;
    text-align: right;
}

.checked {
    text-decoration: line-through;
}
.labelwidth{
    width:500px;
}

.first_half{
    width:800px;
}
.second_half{

margin-right:1900px; 

}
.image_sizing{
    height:500px;
    width:500px;
}

**CSS**
@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');

.todos-container{
    width:1000px;
}
.text {
    text-align: center;
    font-size: 60px;
}

.create {
    font-size: 40px;
    text-align: left;
    margin-top: 30px;
    padding-left: 0px;
}

.main-container {
    height: 100vh;
    width: 100vw;
    display:flex;
    flex-direction:row;
    background-image: url("https://t3.ftcdn.net/jpg/01/28/87/04/240_F_128870437_TXj1QawSYdsDbmIy0KnIOv1ytIiiDOrX.jpg"); 
    background-size:cover;
}

.inputelement {
    width: 60%;
    padding: 10px;
    border-radius: 4px;
}

.adding {
    margin-top: 10px;
}

.tasks {
    margin-top: 50px;
}

.todo_item_list {
    padding: 10px;
    width:1000px;
    margin-right:800px;
}

.label_container {
    width: 100%;
    background-color: #e6f6ff;
    border-radius: 4px;
    padding: 20px;
    margin-left: 4px;
    border-left: 5px solid #096f92;


}

.delete_icon {
    width: 100%;
    text-align: right;
}

.checked {
    text-decoration: line-through;
}
.labelwidth{
    width:500px;
}

.first_half{
    width:800px;
}
.second_half{

margin-right:1900px; 

}
.image_sizing{
    height:500px;
    width:500px;
}

**JAVASCRIPT**
@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');

.todos-container{
    width:1000px;
}
.text {
    text-align: center;
    font-size: 60px;
}

.create {
    font-size: 40px;
    text-align: left;
    margin-top: 30px;
    padding-left: 0px;
}

.main-container {
    height: 100vh;
    width: 100vw;
    display:flex;
    flex-direction:row;
    background-image: url("https://t3.ftcdn.net/jpg/01/28/87/04/240_F_128870437_TXj1QawSYdsDbmIy0KnIOv1ytIiiDOrX.jpg"); 
    background-size:cover;
}

.inputelement {
    width: 60%;
    padding: 10px;
    border-radius: 4px;
}

.adding {
    margin-top: 10px;
}

.tasks {
    margin-top: 50px;
}

.todo_item_list {
    padding: 10px;
    width:1000px;
    margin-right:800px;
}

.label_container {
    width: 100%;
    background-color: #e6f6ff;
    border-radius: 4px;
    padding: 20px;
    margin-left: 4px;
    border-left: 5px solid #096f92;


}

.delete_icon {
    width: 100%;
    text-align: right;
}

.checked {
    text-decoration: line-through;
}
.labelwidth{
    width:500px;
}

.first_half{
    width:800px;
}
.second_half{

margin-right:1900px; 

}
.image_sizing{
    height:500px;
    width:500px;
}
```

**CODE EXPLANATION**


1. **Variable Declarations**:
   - `checkbox_id`, `label_id`, `list_no`: These variables are used to generate unique IDs for elements in the to-do list.
   - `element`: This variable creates a new list item (`<li>`) element.
   - `input_element`: This creates a checkbox input element within the list item.
   - `label_container`: This creates a container for the label associated with the checkbox.
   - `label_element`: This creates a label element for displaying the text of the to-do item.
   - `delete_container`, `delete_item`: These create a container and an icon for deleting the to-do item.

2. **Setting Attributes and Appending Elements**:
   - Attributes like IDs, type, text content, and event listeners are set for various elements.
   - Elements are appended to each other and ultimately to the DOM (`todos_container`).

3. **Event Handling**:
   - `input_element.onclick`: This event listener triggers the `ontodo_change` function when the checkbox is clicked.
   - `delete_item.onclick`: This event listener removes the corresponding to-do item when the delete icon is clicked.

4. **Functions**:
   - `create_new`: This function creates a new to-do item based on the text entered in the input field (`new_input_item`). It adds this item to the `todos_list` array and then appends it to the DOM using the `appending` function.
   - `appending`: This function appends a new to-do item to the DOM based on the provided item object.
   
5. **Event Handling**:
   - `add_input.onclick`: This event listener calls the `create_new` function when the add button (`add_input`) is clicked.
   
6. **Loop**:
   - A loop iterates over each item in the `todos_list` array and appends them to the DOM using the `appending` function.

This code essentially creates a dynamic to-do list interface where users can add, check, and delete items. The state of each item (checked or unchecked) is stored in the `todos_list` array.

**Rationale:**
● Streamlined task management through a combination of HTML, CSS, and Bootstrap for an intuitive interface.
● Seamless CRUD operations through JavaScript event listeners and dynamic UI updates.
● Secure task persistence with local storage methods, ensuring that your tasks are always available.


**Conclusion:**

In conclusion the task assigned to kolavanti.Tejaswi during the CodTech IT Solutions internship program involved building a webpage using HTML,CSS,JAVASCRIPT. The implemented solution successfully accomplish the task using the Event handling,loops,localstorage methods and using the css for polish look.This document provides insights into the implemented details,code explanation,and rationale behind the choosen approach.
Kolavanti Tejaswi,with the intern ID COD4561 has effectively completed the task as part of the internship program.

This concludes the documentation for the task "building TO -DO LIST WEB APPLICATION " assigned during the CodTech IT Solutions Internship program.
