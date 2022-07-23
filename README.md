# TripCalc
<h3>See my updated version here! - https://trip-calculator-98654.web.app/home</h3>
Progressive Web App: Trip cost calculator using JS interacting with various APIs to collect accurate geographical and technical information in order to calculate the energy or fuel cost of a road trip in North America.
<br><br><b>Note: I excluded my google developer api key from the project at the end of my index.html file. If you want to try the App out you will have to get one from the google developer console. Also this was one of my first projects as I was learning JS, and web development and is not entirely finished so there are console logs and some rough calculations.</b>
<h2>App Demo</h2>
<ul>
  <li>On page startup, the script finds all vehicle info from fueleconomy.gov and populates the dropdown menus with possible selections.</li>
  <li>Once a year, make, model, and trim are chosen it is considered to be the currently selected vehicle (shown below the dropdown menus).</li>
  <li>Currently selected vehicles can optionally be stored locally in your garage, which is a feature that allows for quickly finding or managing vehicles you have already searched.</li>
  <li>The map and trip statistics will not show up until you have entered a valid starting and ending point, selected a vehicle, and then clicked go.</li>
  <li>Fuel and energy consumption is based on fueleconomy.gov XML API. For the purpose of this application I averaged between city and highway, but understood there are many ways to improve accuracy of the estimate.</li>
  <li>Location data is from google maps JavaScript APIs. Any location you could use in google maps would work in this application.</li>
  <li>If using a combustion car, the metric option toggles between cost per liter and cost per gallon.</li>
  <li>The application recognizes and converts between miles and kilometers for trips depending on your metric selection and if your trip is in US/Canada or both.</li>
</ul>
<p>Below is an example using my first car on a trip between two places I used to live.</p>
<img alt="main Screenshot" src="demoimages/demopage.png?raw=true" height="auto" width="100%" align="center">
<p>Below shows an example of the same trip using a popular EV model.</p>
<img alt="main Screenshot" src="demoimages/EVdemopage.png?raw=true" height="auto" width="100%" align="center">
