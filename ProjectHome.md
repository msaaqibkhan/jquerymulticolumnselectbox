## Jquery Multi Column Selectbox ##
A jquery plugin that creates a multiple column selectbox
2 column dropdown box

Try demo http://itlivewire.com/jquerymulticolumnselectbox

Directions for Use:

1. Include of course jquery.js and jquery.multicolselect.js
```
<script type="text/javascript" src="jquery.js"></script>
<script type="text/javascript" src="jquery.multicolselect.js"></script>
```

2. Create a div with a table name the identify the div with a class "ex. datatable"
```
<div id="datatable">
<table cellspacing="0" width="100%">
<tr>
<th>ID</th><th>Key</th><th>Fruit</th>
</tr>
<tr>
<td>1</td><td>1234</td><td>Apple</td>
</tr>
<tr>
<td>2</td><td>1111</td><td>Cat</td>
</tr>
<tr>
<td>3</td><td>5555</td><td>Dog</td>
</tr>
</table>
</div>
```

3. Run the plugin using this command
```
$("#datatable").multicolselect({
	   		buttonImage:"selectbutton.gif",
			valueCol:1,                  
	  		hideCol:0
	   });
```

4 . Note you need the "selectbutton.gif" so save it.

5. Then your done.

Options
| **Option** | **Description** |
|:-----------|:----------------|
| buttonImage | The source of your button image  |
| valueCol   | The column index to be used to display value for the textbox |
| hideCol    | The column index to hide this is usually an id column |

For issues and concern contact Gerard Banasig actuate@gmail.com



