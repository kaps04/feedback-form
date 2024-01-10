# feedback-form

**this is me while learning responsive web design.<br>
author:Kalpana Acharya
git stat **

<!DOCTYPE html>

<html>
<head> 
<title>
 <h1> Store Feedback Form
   <p>please feel free to fill to provide the feedback based on your experience.</p>
 </h1>
</title>
</head>
<body>
<div class="container">
  <header class="header">
    <h1 id="title" class="text-center">
      Feedback Survey form</h1>
      <p id="description"> Thankyou for your time and feedback</p>
      </header>
      <form id="survey-form">
        <div class="form-group">
          <label id="name-label" for="name">Name</label>
          <input type="text" id="name" name="name" class="form- control" placeholder="Enter your name" required>
          </div>
  <div class="form-group">
    <label id="email-label" for="email">Email</label>
    <input type="email"
    id="email" class="form-control"
    placeholder="Enter your email" required>
    </div>
    <div class="form-group">
      <label id="number-label" for="number">Number</label>
      <input type="number"
      id="number" min="5" max=65
      placeholder="Enter your age" class="form control"
      required></div><div class="form-group">
        <p>How often have you visited our cafe?</p>
<select id="dropdown" name="frequency" class="form-control" required>
  <option disabled selected value>Select how many times you've been here</option>
  <option value="once">Once</option>
 <option value="Twice">Twice</option>
 <option value="Many times">Many times</option>
 <option value="prefer not to say">Prefer not to say</option></select>
 </div>
 <div class="form-group"><p>
 Would you recommened our cafe to your friend?</p>
 <label>
   <input name="user recommended" value="definitely" type='radio' class="input-radio" checked>
   Definitely</label>
   <label>
   <input name="user recommended" value="Maybe" type='radio' class="input-radio" checked>
   Maybe</label>
   <label>
   <input name="user recommended" value="not sure" type='radio' class="input-radio" checked>
   Not sure</label></div>
   <div class="form-group">
     </p>What food items do you like the most from our menu?</p> <select id='feedback' name='feedback' required> <option disabled selected value>Select any option</option>
     <option value="beverages">Beverages</option>
      <option value="Cheesecakes">Cheesecakes</option>
 <option value="Pastries">Pastries</option>
 <option value="Brownies">Brownies</option></select></div>
 <div class="form-group">
   <p>What would you like to see improved?</p><label>Ambience
   <input name="prefer" type="checkbox" value="Ambience"class="input-checkbox"></label>

<label>Service time
<input name="prefer" type="checkbox" value="service time"class="input-checkbox"></label>
<label>Staff Behaviour
<input name="prefer" type="checkbox" value="staff behaviour"class="input-checkbox"></label>
<label>Sanitation
<input name="prefer" type="checkbox" value="sanitation"class="input-checkbox"></label>
<label>Food portion
<input name="prefer" type="checkbox" value="Food Portion"class="input-checkbox"></label>
<label>Flavouring
<input name="prefer" type="checkbox" value="Flavouring"class="input-checkbox"></label></div>

   <div class="form-group">
     <p>Any comments or suggestion?</p>
     <textarea id="comments" class="input-textarea" name="comment" placeholder="enter your comment here.."></textarea></div>
     <div class="form-group">
       <button type="submit" id="submit" class="submit-button">Submit</button></div>

     </form>
     </div>

</body>
</html>
