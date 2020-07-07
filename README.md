# examplePivotGrid
Example dxPivotGrid by DevExpress

### Basic Create PivotTable with [DevExpress](https://js.devexpress.com/Documentation/Guide/jQuery_Components/Add_DevExtreme_to_a_jQuery_Application/)

#### Example code (index.html)
```sh

...
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
<body class="form">
    <div id="pivotgrid-container"> </div>
</body>
...
```
