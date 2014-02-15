misproyectosyarelym1
==============
html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>formulario sumar</title>

<script language="javascript1.5">
function sumar(){
	var a, b, r;
	a = parseFloat(document.f1.t1.value);
	b = parseFloat(document.f1.t2.value);
	r = a+ b;
	document.f1.t3.value = r;
}

function limpiar(){
	document.f1.t1.value = "";
	document.f1.t2.value = "";
	document.f1.t3.value = "";
	document.f1.t1.value = focus();
	document.f1.t1.value = "";
	document.f1.t2.value = "";
	document.f1.t3.value = "";
}
</script>
</head>
<body>
DATOS DEL USUARIO
<input type="text" name="textfield" id="textfield" />
<form id="form1" name="form1" method="post" action="">
  <label for="textfield"></label>
</form>
<p>
<form name="f1" action="" method="post">

INGRESE EL PRIMER VALOR: 
<input type="text" name="textfield2" id="textfield2" />
<p>
<form type="text" name="t1" size="30"/><p>

INGRESE EL SEGUNDO VALOR: 
  <input type="text" name="textfield3" id="textfield3" />
<p>
<form type="text" name="t2" size="30"/><p>

RESULTADO DE LA SUMA:
  
<form type="text" name="t3" size="30"/>
  <input type="text" name="textfield4" id="textfield4" />
<p>
<input type="button" value="SUMAR" onmouseover="sumar()" >
<input type="button" value="LIMPIAR" onmouseover="limpiar()" >
</form>
</body>
</html>
