DESCRIPTION

Firefox, Safari and Opera 9 support the canvas tag to allow 2D command-based 
drawing operations. ExplorerCanvas brings the same functionality to Internet 
Explorer; web developers only need to include a single script tag in their 
existing canvas webpages to enable this support.


-------------------------------------------------------------------------------
INSTALLATION

Include the ExplorerCanvas tag in the same directory as your HTML files, and 
add the following code to your page, preferably in the <head> tag.

<pre>&lt;!--[if IE]>&lt;script type="text/javascript" src="excanvas.js"&gt;&lt;/script&gt;&lt;![endif]--&gt;</pre>

If you run into trouble, please look at the included example code to see how
to best implement this

--------------------------------------------------------------------------------

canvas 兼容ie9以下

```
<!--[if lt IE 9]>  
  <script src="js/html5shiv.js"></script>  
  <script src="js/excanvas.min.js"></script>
<![endif]-->
```
