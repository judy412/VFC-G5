# VFC-G5
demo1
REGISTER:
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>Add user</title>
<style type="text/css">
body {
	background-color: #E4E5EA;
}
</style>
</head>

<body bgcolor="#99FFFF">
<form action="userAction_add" method="post">
<table width="328" border="1" align="center">
  <tr> <td colspan="2" align="center">    <strong>Register</strong>  </tr>
  <tr>
    <td width="114"><strong>ID：</strong>     <td width="198" ="center">  <input type="text" name="username" /></td>
  </tr>
  <tr>
    <td><strong>Password：
    </strong>       <td ="center"><input type="password" name="password"  /></td>
  </tr>
  <tr>
    <td><strong>Username：</strong>    <td ="center">   <input type="text" name="realname"  /></td>
  </tr>
  <tr>
    <td><strong>VeriflactionCode：</strong>    <td ="center">   <input type="text" name="realname"  /></td>
  </tr>
  <tr> <td colspan="2" align="center">
    <input type="submit" name="button" id="button" value="Subimit" />
  </tr>
</table>
</form>
</body>
</html>




LOGIN：
<form action="/exam01/login.action" method="post">
		<table>
			<tr>
				<td><label style="text-align: center;">ID:</label></td>
				<td><input type="text" name="username"></td>
			</tr>
			<tr>
				<td height="70"><label style="text-align: right;">Password:</label></td>
			  <td><input type="password" name="password"></td>
			</tr>
			<tr>
				<td height="43" colspan="2" align="center"><input type="submit" value="Login"></td>
                
		  <tr onmouseover="this.style.background='#666'"
  onmouseout="this.style.background=''">
   </tr>    <td height="27" align="center"colspan="2"><h3><a href="adduser.html">Register</strong></a></h3></td>
			</tr>
		</table>
	</form>
