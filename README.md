# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Answer
<!DOCTYPE html>
  <html lang="en">
    <head>
        <title>Week 2 Assignment</title>
    </head>
    <body>
        <h1>HTML lists</h1>
        <h3>Ordered Lists</h3>
        <ol type="i">
             <li>Read Instructions</li>
             <li>Research on instructions</li>
             <li>Draft changes</li>
             <li>Submit assignment</li>
        </ol>
        <h1>HTML Images</h1>
        <img src="iPhone.jpg" alt="image of an iPhone" width="350" height="350">
        <h1>HTML Tables</h1>
        <table border="1">
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Rhay</td>
                    <td>1234, Nairobi</td>
                    <td>0711223690</td>
                    <td>rodahannie65@gmail.com</td>
                </tr>
                <tr>
                    <td>Easter</td>
                    <td>10, Nairobi</td>
                    <td>0741366659</td>
                    <td>easterk@gmail.com</td>
                </tr>
                <tr>
                    <td>Carol</td>
                    <td>234, Nairobi</td>
                    <td>0707284736</td>
                    <td>carolw@gmail.com</td>
                </tr>
                <tr>
                    <td>Maureen</td>
                    <td>340, Nairobi</td>
                    <td>0728521861</td>
                    <td>maureeng@gmail.com</td>
                </tr>
                <tr>
                    <td>Tsoni</td>
                    <td>410, Nairobi</td>
                    <td>0711826034</td>
                    <td>tsoni@gmail.com</td>
                </tr>

                <tfooter>
                    <tr>
                        <td colspan="3">Developed by Rhay</td>
                    </tr>
                </tfooter>
            </tbody>
        </table>
        <h1>HTML Forms</h1>
        <form action="" method=""> 
            <label for="name">Name</label>
            <input type="text" id="cleint name" name="client_name" required>
            <br><br>
            <label for="Email">Email</label>
            <input type="text" id="email" name="email" required>
            <br><br>
            <label for="password">password</label>
            <input type="password" id="password" name="password" required>
            <br><br>
            <label for="date">Date</label>
            <input type="date" id="date" name="date" required>
            <br><br>
            
        </form>

    </body>
  </html>

Happy Coding! 💻✨
