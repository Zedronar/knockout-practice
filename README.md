knockout-practice
=================

Just a repository that holds small ko projects in it. For fun and practicing purposes.


Boilerplate for new projects:

------------------------------------------------------------------------------------------
```html
<html>
    <head>
        <title>Axel Practice Project</title>
        <meta name="Description" content="My JavaScript Playground">
        <script src="../JS Libraries/jquery-2.1.0.min.js"></script>
        <script src="../JS Libraries/knockout-3.1.0.js"></script>       
    </head>
    <body>
      
    </body>
    <script type="text/javascript">
      $(document).ready(function() {
		  
        ko.applyBindings(new myViewModel());
	  });

      function myViewModel(){
        var self = this;
        
      }
    </script>
</html>
```


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/Zedronar/knockout-practice/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

