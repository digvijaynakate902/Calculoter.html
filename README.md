<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
<title>Calculater</title>
</head>
<center>
<b> Calculator </b><hr>

    <body>
<h1><form name="Calc">
<table border=5>
<tr>
<td>
<input type="text" name="Numbers" size=15 />
</td>
</tr>
<tr>
<td>
<input type="button" value=" 7 " onClick="document.Calc.Numbers.value += '7'"/>
<input type="button" value=" 8 " onClick="document.Calc.Numbers.value += '8'"/>
<input type="button" value=" 9 " onClick="document.Calc.Numbers.value += '9'"/>
<input type="button" value=" / " onClick="document.Calc.Numbers.value += '%'"/>
<input type="button" value="AC" onClick="document.Calc.Numbers.value = ' '"/>

<br/>
<input type="button" value=" 4 " onClick="document.Calc.Numbers.value += '4'"/>
<input type="button" value=" 5 " onClick="document.Calc.Numbers.value += '5'"/>
<input type="button" value=" 6 " onClick="document.Calc.Numbers.value += '6'"/>
<input type="button" value=" * " onClick="document.Calc.Numbers.value += '*'"/>
<input type="button" value=" %" onClick="document.Calc.Numbers.value = eval(Calc.Numbers.value)"/>

<br/>
<input type="button" value=" 1 " onClick="document.Calc.Numbers.value += '1'"/>
<input type="button" value=" 2 " onClick="document.Calc.Numbers.value += '2'"/>
<input type="button" value=" 3 " onClick="document.Calc.Numbers.value += '3'"/>
<input type="button" value=" +" onClick="document.Calc.Numbers.value += '+'"/>
<input type="button" value="  - " onClick="document.Calc.Numbers.value += '-'"/>

<br/>
<input type="button" value="CE"onClick="document.Calc.Numbers.value = ' '"/>
<input type="button" value="0 " onClick="document.Calc.Numbers.value += '0'"/>
<input type="button" value="00" onClick="document.Calc.Numbers.value += '00'"/>
<input type="button" value=" . " onClick="document.Calc.Numbers.value += '.'"/>
<input type="button" value=" = " onClick="document.Calc.Numbers.value = eval(Calc.Numbers.value)"/>

<br/>
</td>
</tr>
</table>
</center>
</h1>
<hr><center><h5><a href="https://www.sololearn.com/Profile/24121633/?ref=app">
 &copy; digvijay_nakate_902</a></h5></center><hr>
</body>
</html>
