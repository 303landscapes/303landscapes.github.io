  #Maintence form
<body>
  <form action="data/results.html method="POST">
      <div>
          <label for="name">Name:</label>
          <input type="text" name ="name" id="name" placeholder="username">
      </div>
      <div>
        <label>
          Password
          <input type="password" name="password">
        </label>
      </div>
      <button type="reset">Clear</button>
      <button type="submit">Submit</button>
    </form>
</body>


<form>
  <label for="date">Date:</label><br>
  <input type="date" id="date" name="date"><br>

  <label for="employeeName">Employee Name:</label><br>
  <input type="text" id="employeeName" name="employeeName"><br>

  <label for="clientName">Client Name:</label><br>
  <input type="text" id="clientName" name="clientName"<br>

  <label for="clientName">Client:</label><br>
  <input list="clients" name="clients"><br>
  <datalist id="clients">
    <option value="Jenny">
    <option value="Amy">
    <option value="Suzie">
    <option value="Dry Creek">
    <option value="Patty">
  </datalist>


</form>
