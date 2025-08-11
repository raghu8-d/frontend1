# frontend1
<!DOCTYPE html>
<html>
<head>
  <title>Student Application Form</title>
</head>
<body>
  <h2>Student Application Form</h2>
  <form action="/submit" method="post">
    <label for="name">Full Name:</label><br>
    <input type="text" id="name" name="name" required><br><br>

    <label for="email">Email:</label><br>
    <input type="email" id="email" name="email" required><br><br>

    <label for="dob">Date of Birth:</label><br>
    <input type="date" id="dob" name="dob" required><br><br>

    <label for="course">Course Applied:</label><br>
    <input type="text" id="course" name="course" required><br><br>

    <label for="gender">Gender:</label><br>
    <select id="gender" name="gender">
      <option value="">Select</option>
      <option value="male">Male</option>
      <option value="female">Female</option>
      <option value="other">Other</option>
    </select><br><br>

    <input type="submit" value="Submit">
  </form>
</body>
</html>

