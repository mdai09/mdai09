- 👋 Hi, I’m @mdai09
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
mdai09/mdai09 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" type="text/css" href="form.css"/>
  <title>Document</title>
</head>
<body>
  <div class="container">
    <h1 style="text-align: center;">Application Form(Applicatnt's copy)</h1>
    <div class="row">
      <div class="col-25 col-10">
        <Label for="fname">First Name</Label>
      </div>
      <div class="col-75">
        <input type="text" name="fname" id="fname" placeholder="Your fisrt Name.."/>
      </div>
    </div>

    <div class="row">
      <div class="col-25 col-10">
        <Label for="lname">Last Name</Label>
      </div>
      <div class="col-75">
        <input type="text" name="lname" id="lname" placeholder="Your last Name..">
      </div>
    </div>

    <div class="row">
      <div class="col-25 col-10">
        <Label for="department">Department</Label>
      </div>
      <div class="col-75">
        <select name="department"  id="department">
          <option value="CSE">CSE</option>
          <option value="EEE">EEE</option>
          <option value="ICE">ICE</option>
        </select>
      </div>
    </div>

    <div class="row">
      <div class="col-25 col-10">
        <Label for="gender">Gender</Label>
      </div>
      <div class="col-75">
        <input type="radio" name="gender" value="Male">
        <label for="gender" >Male</label>
        <input type="radio" name="gender" value="female">
        <label for="gender">Female</label>
        <div class="dob">
        <label  for="dob" >Date of Birth: </label>
        <input type="date" name="dob" id="dob">
        </div>
      </div>
    </div>
    
    <div class="row">
      <div class="col-25 col-10">
        <Label for="session">Session</Label>
      </div>
      <div class="col-75">
        <input type="checkbox" name="session" value="summer">
        <label for="summer" >Summer</label>
        <input type="checkbox" name="session" value="winter">
        <label for="wimter" >Winter</label>
        <input type="checkbox" name="session" value="Autumn">
        <label for="autumn" >Autumn</label>
      </div>
    </div>

    <div class="row">
      <div class="col-25 col-10">
        <Label for="Description">Description</Label>
      </div>
      <div class="col-75">
        <textarea name="description" id="description" placeholder ="Write about you.." style="height: 150px;"></textarea>
      </div>
    </div>

    <div class="row">
      <button type="submit"id="submit" >Submit</button>
    </div>

  </div>
</body>
</html>
