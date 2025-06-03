<!DOCTYPE html>

<html lang="en">

<head>

  <meta charset="UTF-8" />

  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <title>Volunteer in Israel - Program Overview & Application</title>

  <style>

    body {

      font-family: Arial, sans-serif;

      background-color: #f3f3f3;

      margin: 0;

      padding: 0;

    }

    .container {

      max-width: 800px;

      margin: 50px auto;

      padding: 30px;

      background-color: white;

      border-radius: 10px;

      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);

    }

    h1, h2 {

      text-align: center;

      color: #00529B;

    }

    p {

      line-height: 1.6;

    }

    label {

      display: block;

      margin: 15px 0 5px;

      font-weight: bold;

    }

    input, textarea, select {

      width: 100%;

      padding: 10px;

      border: 1px solid #ccc;

      border-radius: 5px;

    }

    button {

      margin-top: 20px;

      padding: 10px 20px;

      background-color: #00529B;

      color: white;

      border: none;

      border-radius: 5px;

      font-size: 16px;

      cursor: pointer;

    }

    button:hover {

      background-color: #003f7d;

    }

  </style>

</head>

<body>

  <div class="container">

    <h1>Volunteer in Israel</h1>

    <p>

      Join our meaningful volunteer programs in Israel, serving in institutions such as centers for individuals with autism, guest houses, churches, hospitals, social aid programs, and elderly care homes.

    </p>

 

    <h2>Program Options</h2>

    <ul>

      <li><strong>3-Month Program:</strong> Includes accommodation. All other expenses are the volunteer's responsibility.</li>

      <li><strong>9, 12, 16, or 24-Month Programs:</strong> Include accommodation, meals, and a monthly stipend. Other expenses are the volunteer's responsibility.</li>

    </ul>

 

    <p>

      This is a unique opportunity to contribute to meaningful causes and experience life in Israel. Volunteers should be adaptable, compassionate, and committed.

    </p>

 

    <h2>Application Form</h2>

    <form name="volunteer-form" method="POST" data-netlify="true">

      <input type="hidden" name="form-name" value="volunteer-form" />

 

      <label for="name">Full Name</label>

      <input type="text" id="name" name="name" required />

 

      <label for="email">Email Address</label>

      <input type="email" id="email" name="email" required />

 

      <label for="age">Age</label>

      <input type="number" id="age" name="age" required />

 

      <label for="nationality">Nationality</label>

      <input type="text" id="nationality" name="nationality" required />

 

      <label for="program_length">Desired Program Duration</label>

      <select id="program_length" name="program_length">

        <option value="3 months">3 months</option>

        <option value="9 months">9 months</option>

        <option value="12 months">12 months</option>

        <option value="16 months">16 months</option>

        <option value="24 months">24 months</option>

      </select>

 

      <label for="start-date">Preferred Start Date</label>

      <input type="date" id="start-date" name="start_date" required />

 

      <label for="skills">Relevant Skills or Experience</label>

      <textarea id="skills" name="skills" rows="4" placeholder="Tell us about your background..." required></textarea>

 

      <label for="motivation">Why do you want to volunteer in Israel?</label>

      <textarea id="motivation" name="motivation" rows="4" required></textarea>

 

      <label for="language">Do you speak Hebrew?</label>

      <select id="language" name="hebrew">

        <option value="yes">Yes</option>

        <option value="no">No</option>

        <option value="learning">Currently learning</option>

      </select>

 

      <button type="submit">Submit Application</button>

    </form>

  </div>

</body>

</html>
