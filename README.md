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

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Index Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        table, th, td {
            border: 1px solid #333;
            border-collapse: collapse;
            padding: 8px;
        }
        form {
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Ordered List (Roman Numerals)</h2>
        <ol type="I">
            <li>Introduction</li>
            <li>Goals</li>
            <li>Methods</li>
            <li>Results</li>
            <li>Conclusion</li>
        </ol>
    </section>

    <!-- External Image from Pexels (Team Discussion) -->
    <section>
        <h2>Team Discussion</h2>
        <img src="https://images.pexels.com/photos/3182759/pexels-photo-3182759.jpeg" alt="Team having a discussion" width="600">
    </section>

    <!-- Contacts Table -->
    <section>
        <h2>Contact Table</h2>
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
                    <td>Abubakar Juma </td>
                    <td>Mumias, Kenya</td>
                    <td>(123) 456-7890</td>
                    <td>abujuma@example.com</td>
                </tr>
                <tr>
                    <td>Jane Ndirangu</td>
                    <td>Kangemi, Nairobi Kenya</td>
                    <td>(234) 567-8901</td>
                    <td>jane.ndigz@example.com</td>
                </tr>
                <tr>
                    <td>Bob Kanyari</td>
                    <td>Kikuyu, Kiambu, Kenya</td>
                    <td>(345) 678-9012</td>
                    <td>bob.kanyari@example.com</td>
                </tr>
                <tr>
                    <td>Abdullahi Farah</td>
                    <td>Parklands, Nairobi, Kenya</td>
                    <td>(456) 789-0123</td>
                    <td>farah.abdul@example.com</td>
                </tr>
                <tr>
                    <td>Charles Kiarie</td>
                    <td>Langata, Nairobi, Kenya</td>
                    <td>(567) 890-1234</td>
                    <td>charlie.k@example.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form action="#" method="POST">
            <!-- Name -->
            <label for="name">Full Name:</label><br>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>

            <!-- Email -->
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

            <!-- Password -->
            <label for="password">Password:</label><br>
            <input type="password" id="password" name="password" placeholder="Enter your password" required minlength="6"><br><br>

            <!-- Date -->
            <label for="dob">Date of Birth:</label><br>
            <input type="date" id="dob" name="dob" required><br><br>

            <!-- Dropdown -->
            <label for="country">Select your country:</label><br>
            <select id="country" name="country" required>
                <option value="">--Choose a country--</option>
                <option value="somalia">Somalia</option>
                <option value="kenya">Kenya</option>
                <option value="uganda">Uganda</option>
                <option value="ethiopia">Ethiopia</option>
            </select><br><br>

            <!-- Radio Buttons -->
            <label>Gender:</label><br>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="male">Male</label><br>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label><br>
            <input type="radio" id="other" name="gender" value="other">
            <label for="other">Other</label><br><br>

            <!-- Checkboxes -->
            <label>Hobbies:</label><br>
            <input type="checkbox" id="reading" name="hobbies" value="Reading">
            <label for="reading">Reading</label><br>
            <input type="checkbox" id="sports" name="hobbies" value="Sports">
            <label for="sports">Sports</label><br>
            <input type="checkbox" id="coding" name="hobbies" value="Coding">
            <label for="coding">Coding</label><br><br>

            <!-- Submit Button -->
            <button type="submit">Register</button>
        </form>
    </section>

</body>
</html>
