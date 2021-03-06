<!DOCTYPE html>
<html lang='en-us'>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta http-equiv="x-UA-Compatible", content="ie=edge"
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <link rel="stylesheet" href="assets/css/styles.css" media="screen">
</head>

<body>
  <nav class="navbar navbar-default">
    <div class="container-fluid navbar-custom">
      <div class="row">
        <div class="navbar-header">
          <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1" aria-expanded="false">
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <div class="col-xs-9 phone-nav">
          </div>
        </div>
        <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
          <ul class="nav navbar-nav navbar-right navbar-right-custom">
            <li class="dropdown">
              <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Plots <span class="caret"></span></a>
              <ul class="dropdown-menu">
               <li><a href="temp.html">Temperature</a></li>
                <li><a href="humidity.html">Humidity</a></li>
                <li><a href="cloudiness.html">Cloudiness</a></li>
                <li><a href="wind.html">Wind Speed</a></li>
              </ul>
            </li>
            <li><a href="comparisons.html">Comparisons</a></li>
            <li><a href="data.html">Data</a></li>
          </ul>
        </div>
      </div>
    </div>
  </nav>
  <div class="container">
    <section class="row">
      <div class="col-md-8">
        <article class="description-content">
          <h1 class="description-header">Summary: Latitude vs. X</h1>
          <hr class="description-hr"/>
          <img src="assets/images/tempreg.png" alt="" id="description-image"/>
          <p>The purpose of this project was to analyze how weather changes as you get closer to the equator. To accomplish this analysis, we first pulled data from the OpenWeatherMap API to assemble a dataset on over 500 cities.</p>
          <p>After assembling the dataset, we used Matplotlib to plot various aspects of the weather vs. latitude. Factors we looked at included: temperature, cloudiness, wind speed, and humidity. This site provides the source data and visualizations created as part of the analysis, as well as explanations and descriptions of any trends and correlations witnessed.</p>
        </article>
      </div>
      <div class="col-md-4">
        <section id="imageNav-area">
          <div class="imageNav-content">
            <h2 class="imageNav-header">Visualizations</h2>
            <hr />
            <div id="images">
              <a href="temp.html"><img src="assets/images/temp.png" alt="Latitude vs. Temperature" class="imageNav-photo"></a>
              <a href="humidity.html"><img src="assets/images/humidity.png" alt="Latitude vs. Humidity" class="imageNav-photo"></a>
              <a href="cloudiness.html"><img src="assets/images/cloud.png" alt="Latitude vs. Cloudiness" class="imageNav-photo"></a>
              <a href="wind.html"><img src="assets/images/wind.png" alt="Latitude vs. Wind Speed" class="imageNav-photo"></a>
            </div>
          </div>
        </section>
      </div>
    </section>
  </div>                 
