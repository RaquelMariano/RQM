<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">

<iframe width="500" height="300" scrolling="no" frameborder="no" src="https://fusiontables.google.com/embedviz?q=select+col2+from+13IhnuBzX0CHkluSJUjBtfhWsrllB0nSgbzbmcSb7&amp;viz=MAP&amp;h=false&amp;lat=-34.55462600794174&amp;lng=-126.93999794999996&amp;t=1&amp;z=0&amp;l=col2&amp;y=2&amp;tmplt=2&amp;hml=GEOCODABLE"></iframe>

<html xmlns="http://www.w3.org/1999/xhtml"><head>
  <meta http-equiv="content-type" content="text/html; charset=utf-8" />
  <title>Google Visualization API Sample</title>
  <script type="text/javascript" src="https://www.gstatic.com/charts/loader.js"></script>
  <script type="text/javascript">
    google.charts.load("current", {packages:['table']});
    google.charts.setOnLoadCallback(drawVisualization);
    function drawVisualization() {
      google.visualization.drawChart({
        "containerId": "visualization_div",
        "dataSourceUrl": "//www.google.com/fusiontables/gvizdata?tq=",
        "query":"SELECT 'Picture', 'Building Name', 'Country' FROM " +
                "13IhnuBzX0CHkluSJUjBtfhWsrllB0nSgbzbmcSb7" +
                " WHERE Country LIKE 'Canada' ",
        "refreshInterval": 5,
        "chartType": "Table",
        "options": {}
     });
    }
  </script>
</head>
<body style="font-family: Arial;border: 0 none;">
  <div id="visualization_div" style="width: 600px; height: 400px;"></div>
</body>
</html>
