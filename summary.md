<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
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
    }

    .container {
      max-width: 1000px;
      margin: 2rem auto;
      padding: 0 1rem;
    }

    h2 {
      font-size: 1.5rem;
      color: #005eb8;
      text-align: center;
      margin-bottom: 1rem;
    }

    .iframe-container {
      width: 100%;
      max-width: 1000px;
      margin: 0 auto 1.5rem auto;
      overflow: hidden;
      position: relative;
      padding-top: 56.25%; /* 16:9 ratio */
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }

    .iframe-container iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      border: none;
    }

    .source-note {
      font-size: 0.85rem;
      color: #555;
      text-align: center;
      margin-top: 1rem;
    }

    .source-note a {
      color: #005eb8;
      text-decoration: none;
    }

    .source-note a:hover {
      text-decoration: underline;
    }

    .footer {
      text-align: center;
      margin-top: 2rem;
    }

    .footer a {
      padding: 10px 18px;
      background-color: #007c9e;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      margin: 0 0.5rem;
      font-weight: 500;
      display: inline-block;
    }

    .footer a:hover {
      background-color: #005e7a;
    }
  </style>
</head>
<body>

  <div class="header">
    Healthify: Influenza Hospitalization Explorer
  </div>

  <div class="container">
    <h2>Median Confirmed Hospitalizations of Seasonal Flu Incidence per 100,000 Population</h2>

    <div class="iframe-container">
      <iframe title="Flu Incidence Trends" 
              aria-label="Interactive line chart" 
              id="datawrapper-chart-jPRTH" 
              src="https://datawrapper.dwcdn.net/jPRTH/1/" 
              scrolling="no" frameborder="0" 
              style="width: 0; min-width: 100% !important; border: none;" 
              height="383" data-external="1">
      </iframe>
    </div>

    <p class="source-note">
      Influenza Hospitalization Surveillance Network (FluSurv-NET) conducts population-based surveillance for laboratory-confirmed influenza-associated hospitalizations in children (persons younger than 18 years) and adults.
      <br>
      <a href="https://gis.cdc.gov/GRASP/Fluview/" target="_blank">Source: CDC FluSurv-NET</a>
    </p>
  </div>

  <div class="footer">
    <a href="index.html">Home</a>
    <a href="documentation.html">Documentation</a>
  </div>

  <script type="text/javascript">
    !function() {
      "use strict";
      window.addEventListener("message", function(a) {
        if (void 0 !== a.data["datawrapper-height"]) {
          var e = document.querySelectorAll("iframe");
          for (var t in a.data["datawrapper-height"])
            for (var r = 0; r < e.length; r++)
              if (e[r].contentWindow === a.source) {
                var i = a.data["datawrapper-height"][t] + "px";
                e[r].style.height = i;
              }
        }
      });
    }();
  </script>

</body>
</html>
