<!doctype html>
<html lang="en">
 <head>
  <meta charset="UTF-8">
  <meta name="Generator" content="EditPlus®">
  <meta name="Author" content="">
  <meta name="Keywords" content="">
  <meta name="Description" content="">
  <title>Document</title>
 </head>
 <body>
  <script>
  
	for (var i=1;i<=5 ;i++ )
	{
		for (var j=0;j<(5-i);j++ )
		{
			
			document.write("&nbsp")
		}

		for (var k=0;k<(2*i-1);k++ )
		{
			document.write("* ")
		}
	document.write("<br/>")

	}

	for (var i=0;i<=5;i++ )
	{
		for (var j=0;j<=i;j++ )
		{
			
			document.write("&nbsp")
		}

		for (var k=5;k>=(2*i-1);k-- )
		{
			document.write("* ")
		}
	document.write("<br/>")

	}
  
  </script>
 </body>
</html>
