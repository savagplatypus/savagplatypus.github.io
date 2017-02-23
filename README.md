## Hows it going!

First just wanted to say thanks for stopping by! I hope you enjoy your time in my repo!

### Helpdesk/Technical Support Command Library

A quick access view for any commands you may need

```markdown
Common Commands used in a helpdesk environment

- gpupdate /force
- gpresult /R
- ipconfig (all,release,renew,flushdns)
- sfc /scannow
- sigverif
- driverquery
- driverquery -v
- driverquery -si
- nslookup hosthere
- ping ipaddresshere
- pathping ipaddresshere

```

### Common Problems when working with developers and how to resolve them!

```markdown
PROBLEM: If for whatever reason you are waiting for a msdn or 
visual studio license to issue and the trial runs out you can
follow the steps below to sign into a different account without
having to uninstall/reinstall visual studio(x)

- From MSDN forums - since I had to hunt around far too much to 
- find the solution to this:

- Close Visual Studio
- Start the Developer Command prompt installed with Visual 
- Studio as an administrator.
- type devenv /resetuserdata
- Start Visual Studio Normally.

- This is the registry link for in this case Visual Studio 
- 2013s profile location
hkey_current_user\software\Microsoft\VSCommon\12.0\clientservices\
tokenstorage\visualstudio\ideuser
```
<html>
<head>
<title>HTML Calculator</title>
</head>
<body bgcolor= "#000000" text= "gold">
<form name="calculator" >
<input type="button" value="1" onClick="document.calculator.ans.value+='1'">
<input type="button" value="2" onClick="document.calculator.ans.value+='2'">
<input type="button" value="3" onClick="document.calculator.ans.value+='3'">
<input type="button" value="+" onClick="document.calculator.ans.value+='+'">
 
<input type="button" value="4" onClick="document.calculator.ans.value+='4'">
<input type="button" value="5" onClick="document.calculator.ans.value+='5'">
<input type="button" value="6" onClick="document.calculator.ans.value+='6'">
<input type="button" value="-" onClick="document.calculator.ans.value+='-'">
 
<input type="button" value="7" onClick="document.calculator.ans.value+='7'">
<input type="button" value="8" onClick="document.calculator.ans.value+='8'">
<input type="button" value="9" onClick="document.calculator.ans.value+='9'">
<input type="button" value="*" onClick="document.calculator.ans.value+='*'">
<input type="button" value="/" onClick="document.calculator.ans.value+='/'">
 
<input type="button" value="0" onClick="document.calculator.ans.value+='0'">
<input type="reset" value="Reset">
<input type="button" value="=" onClick="document.calculator.ans.value=eval(document.calculator.ans.value)">
<br>Solution is <input type="textfield" name="ans" value="">
</form>
</body>
</html>
