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

Happy Coding! 💻✨
**MY WEBPAGE**
<!DOCTYPE html>
<html>
  <head>
    <title>Hello, World!</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
      <h1 class="title">Hello World! </h1>
      <p id="currentTime"></p>
      <script src="script.js"></script>
  </body><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Enhanced Webpage</title>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Welcome to My Webpage</h1>
    </header>
    
    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Ordered List</h2>
        <ol type="I">
            <li>First Item</li>
            <li>Second Item</li>
            <li>Third Item</li>
            <li>Fourth Item</li>
            <li>Fifth Item</li>
        </ol>
    </section>
    
    <!-- External Image -->
    <section>
        <h2>External Image</h2>
        <img src="https://assets.onecompiler.app/43dbxytfk/43dbxnqfx/WIN_20241018_05_58_58_Pro.jpg" alt="Pexels Sample Image" width="600">
    </section>
    
    <!-- Contacts Table -->
    <section>
        <h2>Contacts Table</h2>
        <table border="1">
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
            <tr>
                <td>rotich elkana</td>
                <td>Langata road,Nairobi</td>
                <td> 254 7567 8101</td>
                <td>rotichelkana3@gmail.com</td>
            </tr>
            <tr>
                <td>cody paul</td>
                <td>456 Elm St, CA</td>
                <td>+1 237 652 3210</td>
                <td>cody.paul@calllibrity.comm</td>
            </tr>
            <tr>
                <td>kevin emigh</td>
                <td>789 Oak St, TX</td>
                <td>+1 236 789 1204</td>
                <td>kevin.emigh@calllibrity.com</td>
            </tr>
            <tr>
                <td>micheal james</td>
                <td>101 Pine St, FL</td>
                <td>+1 321 654 9871</td>
                <td>micheal.james@cylontec.com</td>
            </tr>
            <tr>
                <td>patrick towle</td>
                <td>202 Cedar St, WA</td>
                <td>+1 567 890 2345</td>
                <td>patrick.towle@vennminder.com</td>
            </tr>
        </table>
    </section>
    
    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="mobile">Mobile:</label>
            <input type="tel" id="mobile" name="mobile" required>
            
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>
            
            <button type="submit">Register</button>
        </form>
    </section>
    
    <!-- Footer Section -->
    <footer>
        <p>Contact us at: <a href="mailto:info@example.com">rotichelkana3@gmail.com</a></p>
        <p>&copy; 2025 rotich</p>
    </footer>
</body>
</html>

</html>
