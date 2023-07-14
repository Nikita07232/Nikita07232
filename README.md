<!DOCTYPE html>
<html>
<head>
  <title>User Management System</title>
  <style>
    /* CSS Styles */
    body {
      font-family: Arial, sans-serif;
    }

    h1 {
      color: #333;
      text-align: center;
    }

    form {
      max-width: 400px;
      margin: 0 auto;
    }

    label {
      display: block;
      margin-top: 10px;
      font-weight: bold;
    }

    input[type="text"],
    select {
      width: 100%;
      padding: 5px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }

    input[type="submit"] {
      background-color: #4CAF50;
      color: white;
      padding: 10px 15px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      margin-top: 20px;
    }

    table {
      width: 100%;
      border-collapse: collapse;
    }

    th, td {
      padding: 8px;
      text-align: left;
      border-bottom: 1px solid #ddd;
    }

    th {
      background-color: #4CAF50;
      color: white;
    }
  </style>
</head>
<body>
  <h1>User Management System</h1>
  <h2>Add User</h2>
  <form action="/add-user" method="post">
    <label for="username">Username</label>
    <input type="text" id="username" name="username" required>

    <label for="department">Department</label>
    <select id="department" name="department">
      <option value="Theatre Artist">Theatre Artist</option>
      <option value="Technology">Technology</option>
      <option value="Pianist">Pianist</option>
      <option value="Violinist">Violinist</option>
      <option value="Playback singer">Playback singer</option>
    </select>

    <input type="submit" value="Add User">
  </form>
