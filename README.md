<!DOCTYPE html>
<html>
<head>
  <title>FedEx Express Delivery Company - Admin Add Package</title>
</head>
<body>
  <h1>Package Tracking Code</h1>
  <h2>Add New Package</h2>
  <form method="POST">
    <input name="sender" placeholder="Sender Name" required><br>
    <input name="receiver" placeholder="Receiver Name" required><br>
    <input name="code" placeholder="Tracking Code" required><br>
    <input name="departure" type="date" placeholder="Departure Date" required><br>
    <input name="arrival" type="date" placeholder="Arrival Date" required><br>
    <input name="location" placeholder="Current Location" required><br>
    <textarea name="status" placeholder="Package Status/Details" required></textarea><br>
    <button type="submit">Add Package</button>
  </form>
</body>
</html>
