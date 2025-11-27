<!DOCTYPE html>
<html>
<head>
    <title>Attendance System</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            background: #f2f2f2;
        }

        h2 {
            text-align: center;
            color: #222;
        }

        /* Navigation Buttons */
        .nav {
            text-align: center;
            margin-bottom: 20px;
        }

        .nav a {
            text-decoration: none;
            background: #0078D7;
            padding: 10px 15px;
            color: white;
            border-radius: 6px;
            margin: 0 5px;
        }

        .nav a:hover {
            background: #005fa3;
        }

        /* Table Styling */
        table {
            width: 100%;
            border-collapse: collapse;
            background: white;
            margin-top: 20px;
        }

        th, td {
            border: 1px solid #999;
            padding: 10px;
            text-align: center;
        }

        /* Form Styling */
        form {
            background: white;
            padding: 25px;
            width: 350px;
            margin: auto;
            margin-top: 25px;
            border-radius: 10px;
            box-shadow: 0 0 10px #ccc;
        }

        label {
            font-weight: bold;
        }

        input {
            width: 100%;
            padding: 8px;
            margin: 6px 0 15px 0;
            border: 1px solid #aaa;
            border-radius: 5px;
        }

        button {
            width: 100%;
            padding: 10px;
            background: #0078D7;
            border: none;
            color: white;
            font-size: 16px;
            border-radius: 5px;
        }

        button:hover {
            background: #005fa3;
        }

        hr {
            margin: 40px 0;
        }
    </style>
</head>
<body>

    <!-- Navigation -->
    <div class="nav">
        <a href="#table">📋 Attendance Table</a>
        <a href="#form">➕ Add Student</a>
    </div>

    <!-- ATTENDANCE TABLE -->
    <h2 id="table">Student Attendance Table</h2>

    <table>
        <tr>
            <th>Student ID</th>
            <th>Last Name</th>
            <th>First Name</th>
            <th>Course</th>
            <th>Present</th>
            <th>Participated</th>
        </tr>

        <tr>
            <td>—</td>
            <td>—</td>
            <td>—</td>
            <td>Web Development</td>
            <td>No</td>
            <td>No</td>
        </tr>
    </table>

    <hr>

    <!-- FORM -->
    <h2 id="form">Add a New Student</h2>

    <form>
        <label>Student ID:</label>
        <input type="text" required>

        <label>Last Name:</label>
        <input type="text" required>

        <label>First Name:</label>
        <input type="text" required>

        <label>Email:</label>
        <input type="email" required>

        <button type="submit">Submit</button>
    </form>

</body>
</html>
