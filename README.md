<!DOCTYPE html>
<html>
<head>
  <title>Dashboard</title>
</head>

<body>

  <h1>Dashboard</h1>

  <h3>Total Users: 0</h3>
  <h3>Total Posts: 0</h3>

  <button onclick="logout()">Logout</button>

  <script>
    function logout() {
      alert("Logged out");
      window.location.href = "index.html";
    }
  </script>

</body>
</html>
