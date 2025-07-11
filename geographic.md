<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Geographic Flu Incidence Analysis</title>
  <style>
    body {
      font-family: 'Open Sans', sans-serif;
      background-color: #f9fafa;
      color: #333;
      margin: 0;
      padding: 0;
      text-align: center;
    }

    .healthify-banner {
      display: block;
      width: 100%;
      padding: 20px;
      font-size: 28px;
      font-weight: bold;
      color: white;
      background-color: #0047ab;
      text-decoration: none;
      text-align: center;
      position: fixed;
      top: 0;
      left: 0;
      z-index: 1000;
    }

    .healthify-banner:hover {
      background-color: #003580;
      transform: scale(1.03);
    }

    .container {
      max-width: 1000px;
      margin: 100px auto 40px auto;
      padding: 20px;
    }

    h2 {
      color: #005eb8;
      margin-bottom: 1rem;
    }

    p {
      font-size: 1rem;
      line-height: 1.6;
      color: #444;
      margin-bottom: 2rem;
    }

    iframe {
      width: 100%;
      height: 650px;
      border: 1px solid #ddd;
      border-radius: 8px;
    }
  </style>
</head>
<body>

  <a href="index.html" class="healthify-banner">Healthify</a>

  <div class="container">
    <h2>Geographic Flu Incidence Analysis</h2>

    <p>
      Explore geographic trends in laboratory-confirmed influenza hospitalizations using an interactive map-based visualization.
      This tool helps identify regional hotspots and state-level disparities.
    </p>

    <iframe 
      title="Geographic Flu Incidence Map" 
      src="https://healthifywebapp.shinyapps.io/app_geographic/" 
      allowfullscreen>
    </iframe>
  </div>

</body>
</html>
