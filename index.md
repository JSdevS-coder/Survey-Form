<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
  <link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Do+Hyeon&display=swap" rel="stylesheet">
  <title>Survey Form</title>
</head>

<body>
  <div id="color">
    <header>
      <h1 id="title">Training program survey form</h1>
      <p id="description">
        Thank you for taking a few minutes of your time and letting us know how satisfied are you with our training
        programs
      </p>
    </header>
    <main>
      <form action="#" id="survey-form">
        <div class="form-items">
          <label for="name" id="name-label">Name </label>
          <br>
          <input name="name" type="text" id="name" class="input-field" placeholder="Write your name here" required>
        </div>
        <div class="form-items">
          <label for="email" id="email-label">Email </label>
          <br>
          <input name="email" type="email" id="email" placeholder="example@gmail.com" class="input-field" required>
        </div>
        <div class="form-items">
          <label for="number" id="number-label">Age </label>
          <br>
          <input name="number" type="number" id="number" class="input-field" min="18" max="90"
            placeholder="How old are you?">
        </div>
        <div class="form-items">
          <p>How often do you exercise?</p>
          <select name="frequency" id="dropdown" class="input-field">
            <option value="daily" selected> Every day</option>
            <option value="often"> Every second day</option>
            <option value="ocasionally"> Whenever I feel like it</option>
            <option value="never"> Never</option>
          </select>
        </div>
        <div class="form-items">
          <p>Do you like trainings that include equipment like dumbells and bands?</p>
          <label>
            <input type="radio" name="preference" value="definetely" checked> Definetely
          </label>
          <br>
          <label>
            <input type="radio" name="preference" value="mosty-yes"> Most of the time yes
          </label>
          <br>
          <label>
            <input type="radio" value="sometimes" name="preference"> Sometimes yes sometimes no
          </label>
          <br>
          <label>
            <input type="radio" name="preference" value="mosty-no"> Most of the time no
          </label>
          <br>
          <label>
            <input type="radio" name="preference" value="no"> Not at all
          </label>
        </div>
        <div class="form-items">
          <p>What training video lenght you usually follow?</p>
          <select name="training-type" id="dropdown" class="input-field">
            <option value="short"> Less than 10 minutes</option>
            <option value="medium"> Around 30 minutes</option>
            <option value="long" selected> Around 1 hour</option>
            <option value="longer"> More than 1 hour</option>
          </select>
        </div>
        <div class="form-items">
          <p>What kind of trainings you usually follow?</p>
          <label>
            <input value="hilit" type="checkbox" checked> 
            Full body HILIT trainings
          </label>
          <br>
          <label>
            <input value="cardio" type="checkbox"> 
            Cardio full body trainings
          </label>
          <br>
          <label>
            <input value="targeted-hilit" type="checkbox"> 
            Targeted HILIT trainings
          </label>
          <br>
          <label>
            <input value="targeted-cardio" type="checkbox"> 
            Targeted cardio trainings
          </label>
          <br>
          <label>
            <input value="pilates" type="checkbox"> 
            Pilates training
          </label>
        </div>
        <div class="form-items">
          <p>If you have any other comments, feel free to write them down.</p>
          <textarea name="comments" id="user-comment" cols="30" rows="10"
            placeholder="Please write your comments, sugestions or just opinion about our trainings"
            class="input-field"></textarea>
        </div>
        <div class="form-items">
          <button id="submit" type="submit">Submit your opinion</button>
        </div>


      </form>
    </main>
  </div>
</body>

</html>
