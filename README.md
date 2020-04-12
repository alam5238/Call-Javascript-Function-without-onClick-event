# Call-Javascript-Function-without-onClick-event
Automatically execute any java-script function in HTML page. 

```
<!Doctype HTML>
<html>
<head>
<head>
<body>

<script>
window.onLoad = function(){     <!-- window.onLoad run the javascript function autometically when page load -->
  function(0);
}
</script>

<div id="myPic"><img src="pic.jpg"></div>

<script>

function test(x==1){
  document.getElementById('myPic').style.display='none';
}else{

  document.getElementById('myPic').style.display='block';

}

<script>
</body>
</html>
```
