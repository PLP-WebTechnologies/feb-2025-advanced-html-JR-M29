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

<!-- 
  Document: index.html
  Description: HTML5 document with advanced elements and form validation
-->

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HTML5 Advanced Elements and Form Validation</title>
  <style>
    /* Add some basic styling to make the page look decent */
    body {
      font-family: Arial, sans-serif;
    }
    table {
      border-collapse: collapse;
    }
    th, td {
      border: 1px solid #ddd;
      padding: 10px;
    }
  </style>
</head>
<body>
  <!-- Ordered list with roman numerals -->
  <h2>Ordered List with Roman Numerals</h2>
  <ol type="I">
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
  </ol>

  <!-- External image from pexels.com -->
  <h2>External Image</h2>
  <img src="https://images.pexels.com/photos/1236701/pexels-photo-1236701.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" alt="External Image from Pexels">

  <!-- Table with 5 contacts -->
  <h2>Contacts Table</h2>
  <table>
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
        <td>John Doe</td>
        <td>123 Main St</td>
        <td>123-456-7890</td>
        <td>johndoe@example.com</td>
      </tr>
      <tr>
        <td>Jane Doe</td>
        <td>456 Elm St</td>
        <td>987-654-3210</td>
        <td>janedoe@example.com</td>
      </tr>
      <tr>
        <td>Bob Smith</td>
        <td>789 Oak St</td>
        <td>555-123-4567</td>
        <td>bobsmith@example.com</td>
      </tr>
      <tr>
        <td>Alice Johnson</td>
        <td>321 Pine St</td>
        <td>901-234-5678</td>
        <td>alicejohnson@example.com</td>
      </tr>
      <tr>
        <td>Mike Brown</td>
        <td>901 Maple St</td>
        <td>111-222-3333</td>
        <td>mikebrown@example.com</td>
      </tr>
    </tbody>
  </table>

  <!-- Registration form with validation attributes -->
  <h2>Registration Form</h2>
  <form>
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required placeholder="Enter your name">

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required placeholder="Enter your email">

    <label for="password">Password:</label>
    <input type="password" id="password" name="password" required placeholder="Enter your password" pattern=".{8,}" title="Password must be at least 8 characters long">

    <label for="date">Date of Birth:</label>
    <input type="date" id="date" name="date" required>

    <label for="country">Country:</label>
    <select id="country" name="country" required>
      <option value="">Select a country</option>
      <option value="USA">USA</option>
      <option value="Canada">Canada</option>
      <option value="Mexico">Mexico</option>
    </select>

    <label for="gender">Gender:</label>
    <input type="radio" id="male" name="gender" value="male" required>
    <label for="male">Male</label>
    <input type="radio" id="female" name="gender" value="female" required>
    <label for="female">Female</label>

    <label for="hobbies">Hobbies:</label>
    <input type="checkbox" id="reading" name="hobbies" value="reading">
    <label for="reading">Reading</label>
    <input type="checkbox" id="hiking" name="hobbies"
