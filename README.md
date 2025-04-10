<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Employee Management</title>
    <link rel="stylesheet" href="style.css"> <!-- For Styling (Optional) -->
</head>
<body>
    <h1>JR GROUPS OF COMPANY</h1>
    <h2>Employee Management System</h2>

    <!-- Form for Employee Input -->
    <div id="form-container">
        <input type="text" id="nameInput" placeholder="Enter employee name">
        <input type="text" id="idInput" placeholder="Enter employee ID">
        <input type="text" id="phoneInput" placeholder="Enter phone number">
        <input type="email" id="emailInput" placeholder="Enter email ID">
        <input type="text" id="addressInput" placeholder="Enter address">
        <button id="addEmployeeBtn">Add Employee</button>
    </div>

    <!-- Table to Display Employees -->
    <table>
        <thead>
            <tr>
                <th>Name</th>
                <th>ID</th>
                <th>Phone Number</th>
                <th>Email ID</th>
                <th>Address</th>
                <th>Actions</th>
            </tr>
        </thead>
        <tbody id="employeeTable">
            <!-- Table rows will be dynamically added here -->
        </tbody>
    </table>

    <script src="script.js"></script> <!-- JavaScript File -->
</body>
</html>
