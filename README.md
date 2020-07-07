# examplePivotGrid
Example dxPivotGrid by DevExpress

### Basic การสร้าง Pivot Table ด้วย DevExpress

#### Example code (index.html)
```sh
<!DOCTYPE html>
<head>
    <title>DevExtreme Demo</title>
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0" />
	
	<!-- JavaScripts -->
	<script type="text/javascript" src="js/jquery.min.js"></script>
  <script src="js/cldr.min.js"></script>
  <script src="js/cldr/event.min.js"></script>
  <script src="js/cldr/supplemental.min.js"></script>
  <script src="js/cldr/unresolved.min.js"></script>
  <script type="text/javascript" src="js/globalize.min.js"></script>
  <script type="text/javascript" src="js/globalize/message.min.js"></script>
  <script type="text/javascript" src="js/globalize/number.min.js"></script>
  <script type="text/javascript" src="js/globalize/currency.min.js"></script>
  <script type="text/javascript" src="js/globalize/date.min.js"></script>
	<script type="text/javascript" src="js/dx.all.js"></script>
	
	<!-- CSS -->
  <link rel="stylesheet" type="text/css" href="css/dx.common.css" />
  <link rel="stylesheet" type="text/css" href="css/dx.light.css" />
	
	<!-- In Page -->
  <script src="data/data.js"></script>
	
	<script type="text/javascript">
		$(function(){
			$('#pivotgrid-container').dxPivotGrid({
				dataSource: {
					store: sales
				}
			});
		});
	</script>
	
</head>
<body class="form">
    <div id="pivotgrid-container"> </div>
</body>
</html>
```
