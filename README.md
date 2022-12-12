- 👋 Hi, I’m @PRANJUL-MISHRA
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
PRANJUL-MISHRA/PRANJUL-MISHRA is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<html>
<head>
<script type="text/javascript">
function one()
{
document.getElementById("t1").value = document.getElementById("t1").value+"1"
}
function two()
{
document.getElementById("t1").value = document.getElementById("t1").value+"2"
}
function three()
{
document.getElementById("t1").value = document.getElementById("t1").value+"3"
}
function four()
{
document.getElementById("t1").value = document.getElementById("t1").value+"4"
}
function five()
{
document.getElementById("t1").value = document.getElementById("t1").value+"5"
}
function six()
{
document.getElementById("t1").value = document.getElementById("t1").value+"6"
}
function seven()
{
document.getElementById("t1").value = document.getElementById("t1").value+"7"
}
function eight()
{
document.getElementById("t1").value = document.getElementById("t1").value+"8"
}
function nine()
{
document.getElementById("t1").value = document.getElementById("t1").value+"9"
}
function zero()
{
document.getElementById("t1").value = document.getElementById("t1").value+"0"
}
function clear1()
{
document.getElementById("t1").value=""
}
function plus()
{
document.getElementById("t1").value = document.getElementById("t1").value+"+"
}
function minus()
{
document.getElementById("t1").value = document.getElementById("t1").value+"-"
}
function multi()
{
document.getElementById("t1").value = document.getElementById("t1").value+"*"
}
function divide()
{
document.getElementById("t1").value = document.getElementById("t1").value+"/"
}
function equal()
{
document.getElementById("t1").value = eval(document.getElementById("t1").value)
}
function sqrt()
{
var a=document.getElementById("t1").value
var b=Math.sqrt(a)
document.getElementById("t1").value=b
}
function open()
{
document.getElementById("t1").value=document.getElementById("t1").value+"("
}
function close()
{
document.getElementById("t1").value=document.getElementById("t1").value+")"
}
 
 
 
</script>
 
<title>Scientific Calculator
</title>
<body>
<form>
<table border="1" cellspacing="0" width="300" height="300">
<tr><input type="text" id="t1" value="" size="40">
</tr>
<tr>
<td><input type="Button" name="b1" value=" 2^nd "></td>
<td><input type="Button" name="b2" value="  pi  "></td>
<td><input type="Button" name="b3" value="  e  "></td>
<td><input type="Button" name="b4" value="  C "></td>
<td><input type="Button" name="b5" value="clear" onclick="clear1()"></td>
</tr>
<tr>
<td><input type="Button" name="b6" value="  x^2  "></td>
<td><input type="Button" name="b7" value=" 1/x "></td>
<td><input type="Button" name="b8" value=" |x| "></td>
<td><input type="Button" name="b9" value="exp"></td>
<td><input type="Button" name="b10" value=" mod"></td>
</tr>
<tr>
<td><input type="Button" name="b11" value="sqrt(x)" onclick="sqrt()"></td>
<td><input type="Button" name="b12" value="  (   " onclick="open()"></td>
<td><input type="Button" name="b13" value="  )  " onclick="close()"></td>
<td><input type="Button" name="b14" value="  n! "></td>
<td><input type="Button" name="b15" value="    /  " onclick="divide()"></td>
</tr>
<tr>
<td><input type="Button" name="b16" value="  x^y  "></td>
<td><input type="Button" name="b17" value="  7  " onclick="seven()"></td>
<td><input type="Button" name="b18" value="  8  " onclick="eight()"></td>
<td><input type="Button" name="b19" value="  9  " onclick="nine()"></td>
<td><input type="Button" name="b20" value="   *   " onclick="multi()"></td>
</tr>
<tr>
<td><input type="Button" name="b21" value=" 10^x "></td>
<td><input type="Button" name="b22" value="  4  " onclick="four()"></td>
<td><input type="Button" name="b23" value="  5  " onclick="five()"></td>
<td><input type="Button" name="b24" value="  6  " onclick="six()"></td>
<td><input type="Button" name="b25" value="   -   " onclick="minus()"></td>
</tr>
<tr>
<td><input type="Button" name="b26" value="  log  "></td>
<td><input type="Button" name="b27" value="  1  " onclick="one()"></td>
<td><input type="Button" name="b28" value="  2  " onclick="two()"></td>
<td><input type="Button" name="b29" value="  3  " onclick="three()"></td>
<td><input type="Button" name="b30" value="  +   " onclick="plus()"></td>
</tr>
<tr>
<td><input type="Button" name="b31" value="   ln   "></td>
<td><input type="Button" name="b32" value=" +/- "></td>
<td><input type="Button" name="b33" value="  0  " onclick="zero()"></td>
<td><input type="Button" name="b34" value="  .   "></td>
<td><input type="Button" name="b35" value="  =   " onclick="equal()"></td>
</tr>
</table>
</form>
</body>
</head>
</html>
