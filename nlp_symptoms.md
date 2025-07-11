<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Healthify | NLP Symptom Analysis</title>
  <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Open Sans', sans-serif;
      background-color: #f9fafa;
      color: #333;
      margin: 0;
      padding: 0;
    }

    .header {
      background: linear-gradient(to right, #005eb8, #007c9e);
      color: white;
      padding: 1.5rem 2rem;
      font-size: 1.6rem;
      font-weight: 600;
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
      z-index: 1000;
    }

    .container {
      max-width: 1000px;
      margin: 100px auto 2rem auto;
      padding: 0 1rem;
    }

    .iframe-container {
      width: 100%;
      overflow: hidden;
      position: relative;
      padding-top: 56.25%; /* Maintain 16:9 ratio */
    }

    .iframe-container iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      border: none;
      border-radius: 8px;
    }
  </style>
</head>
<body>

  <div class="header">
    Healthify: NLP Symptom Analysis
  </div>

  <div class="container">
    <div class="iframe-container">
      <iframe 
        title="Flu NLP Symptoms Shiny App" 
        src="https://healthifywebapp.shinyapps.io/app_nlp_symptoms/" 
        allowfullscreen>
      </iframe>
    </div>
  </div>

</body>
</html>
