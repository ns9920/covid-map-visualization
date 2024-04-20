<body>
<div>
    <h1>COVID-19 Map Visualization</h1>
    <p>This is a web application that visualizes COVID-19 cases around the world using Mapbox GL JS. The application fetches real-time data from a JSON file and updates the map accordingly, displaying markers with varying colors based on the number of cases in each location.</p>

    <h2>Features</h2>
    <ul>
        <li>Real-time data updates every 20 seconds</li>
        <li>Interactive map with zoom, pan, and hover capabilities</li>
        <li>Color-coded markers based on the number of cases</li>
        <li>Dark map style for better visibility</li>
    </ul>

    <h2>Technologies Used</h2>
    <ul>
        <li><strong>HTML</strong>: Markup language for creating the structure of the web page.</li>
        <li><strong>CSS</strong>: Stylesheet language for styling the web page.</li>
        <li><strong>JavaScript</strong>: Programming language for adding interactivity and functionality to the web page.</li>
        <li><strong>Mapbox GL JS</strong>: A JavaScript library for rendering interactive maps from vector tiles and Mapbox styles.</li>
    </ul>

    <h2>Getting Started</h2>
    <p>To run this application locally, follow these steps:</p>
    <ol>
        <li>Clone the repository: <code>git clone https://github.com/ns9920/covid-map-visualization.git</code></li>
        <li>Navigate to the project directory: <code>cd covid-map-visualization</code></li>
        <li>Open the <code>index.html</code> file in a web browser.</li>
    </ol>
    <p>Note: You need to replace <code>'token'</code> in the <code>mapboxgl.accessToken</code> line with your own Mapbox access token. You can obtain a token by signing up for a free account on <a href="https://www.mapbox.com/">Mapbox</a>.</p>

    <h2>Usage</h2>
    <ol>
        <li>Zoom in and out using the +/- buttons or scroll wheel to navigate the map.</li>
        <li>Click and drag to pan the map in any direction.</li>
        <li>Hover over the markers to see the number of cases in that location.</li>
    </ol>

    <h2>Contributing</h2>
    <p>Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.</p>

</div>
</body>
