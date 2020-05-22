<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css" />
    <link href="https://fonts.googleapis.com/css2?family=Bree+Serif&family=Shadows+Into+Light&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap" rel="stylesheet">

    <title> Survey Form</title>
</head>
<body>
    <div class="container"></div>
<header class="header">
    <h1 id="title" class="centered-text"> Favorite Book Genre Survey</h1>
    <p id="description" class="centered-text"> <em> Thank you for helping us provide your preference </em></p>
</header>

<form id="survey-form">
<div id="form-group">
    <label name="label" for="name" id="name-label"> Name </label>
    <input type="text" name="name" id="name" class="form-control" placeholder="Enter your name" required> </input>
</div>
<div id="form-group">
    <label name="label" for="email" id="email-label"> Email </label>
    <input type="email" email="email" id="email" class="form-control" placeholder="Enter your email" required> </input>
</div>
<div id="form-group">
    <label name="label" for="Age" id="number-label"> Age (optional) </label>
    <input type="number" min="10" max="90"  id="number" class="form-control" placeholder="Enter your Age"> </input>
</div>
<div id="form-group">
    <label name="label" for="genre" id="genre-label"> What is your favorite genre? </label>
   <select name="role" id="dropdown"> 
       <option disabled hidden selected> Select a genre </option>
       <option id="fantasy" class="dropdown-option"> Fantasy </option>
       <option id="Sci-Fi" class="dropdown-option"> Sci-Fi </option>
       <option id="Mystery" class="dropdown-option"> Mystery </option>
       <option id="Thriller" class="dropdown-option"> Thriller </option>
       <option id="Romance" class="dropdown-option"> Romance </option>
       <option id="Westerns" class="dropdown-option"> Westerns </option>
       <option id="Dystopian" class="dropdown-option"> Dystopian </option>
       <option id="Comtemporary" class="dropdown-option"> Comtemporary </option>
   </select>
</div>
<div id="form-group">
    <p id="genre-label"> How often do you read? </p>
<label>
    <input name="user-recommend" value="everyday"  type="radio"  class="radio-input" checked> Everyday  
</label>
<label>
    <input name="user-recommend" value="Sometimes"  type="radio"  class="radio-input"> Sometimes  
</label>
<label>
    <input name="user-recommend" value="Once in a while"  type="radio"  class="radio-input"> Once in a while  
</label>
<label>
    <input name="user-recommend" value="Not at all"  type="radio"  class="radio-input"> Not at all  
</label>
</div>
<div id="form-group">
    <p id="genre-label" name="label" for="genre" id="genre-label"> Where do you prefer to read? </p>
   <select name="role" id="dropdown"> 
       <option disabled hidden selected> Select a genre </option>
       <option id="Library" class="dropdown-option"> Library </option>
       <option id="Home" class="dropdown-option"> Home </option>
       <option id="Cafè" class="dropdown-option"> Cafè </option>
       <option id="Outside" class="dropdown-option"> Outside </option>
   </select>
</div>
<div id="form-group">
    <p id="genre-label"> What's your favorite drink?  </p>
<label>
    <input name="user-recommend" value="everyday"  type="checkbox"  class="radio-input" checked> Tea 
</label>
<label>
    <input name="user-recommend" value="Sometimes"  type="checkbox"  class="radio-input"> Coffee  
</label>
<label>
    <input name="user-recommend" value="Once in a while"  type="checkbox"  class="radio-input"> Juice  
</label>
<label>
    <input name="user-recommend" value="Not at all"  type="checkbox"  class="radio-input"> Water  
</label>
</div>
<div id="form-group">
    <p id="genre-label"> Additional comments: </p>
   <textarea id="text-area" placeholder="Write any additional comments here..."></textarea>
</div>
<div id="form-group">
    <button id="submit"> Submit </button>
</div>
</form>
</div>
</body>
<script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>
</html>