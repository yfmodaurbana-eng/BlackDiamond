<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Panel Admin Productos</title>

<style>
body{
  background:#0f0f0f;
  font-family:Arial;
  padding:20px;
  color:white;
}

.admin-box{
  max-width:700px;
  margin:auto;
  background:#171616;
  padding:20px;
  border-radius:14px;
  box-shadow:0 0 15px rgba(255,255,255,0.05);
}

h1{
  text-align:center;
  color:#ABAA57;
  margin-bottom:20px;
  font-size:22px;
}

input, select, textarea{
  width:100%;
  margin-top:8px;
  padding:12px;
  border:none;
  border-radius:8px;
  background:#2a2a2a;
  color:white;
}

button{
  width:100%;
  margin-top:12px;
  background:#ABAA57;
  color:black;
  padding:12px;
  border:none;
  border-radius:8px;
  font-weight:bold;
  cursor:pointer;
}

textarea{
  min-height:280px;
  resize:vertical;
}

small{
  color:#bcbcbc;
}
</style>
</head>
<body>

<div class="admin-box">
  <h1>Panel Admin Productos</h1>

  <input id="titulo" placeholder="Nombre del producto">
  <input id="precio" placeholder="Precio (ej: 15€)">
  <input id="referencia" placeholder="Referencia (ej: CD002)">

  <input id="imgBlanco" placeholder="URL imagen Blanco">
  <input id="imgNegro" placeholder="URL imagen Negro">
  <input id="imgGris" placeholder="URL imagen Gris">
  <input id="imgRojo" placeholder="URL imagen Rojo">
  <input id="imgAzul" placeholder="URL imagen Azul">
  <input id="imgVerde" placeholder="URL imagen Verde">
  <input id="imgBeige" placeholder="URL imagen Beige">
  <input id="imgRosa" placeholder="URL imagen Rosa">
  <input id="imgMarron" placeholder="URL imagen Marrón">
  <input id="imgAmarillo" placeholder="URL imagen Amarillo">

  <input id="telefono" placeholder="WhatsApp de pedidos (ej: 34600000000)">

  <button onclick="generarCodigo()">Generar código HTML</button>

  <small>Este bloque lo copias y lo pegas dentro de tu catálogo de productos.</small>

  <textarea id="resultado" placeholder="Aquí aparecerá el código listo para copiar"></textarea>
</div>

<script>
function generarCodigo(){
  const titulo = document.getElementById('titulo').value;
  const precio = document.getElementById('precio').value;
  const referencia = document.getElementById('referencia').value;
  const telefono = document.getElementById('telefono').value;

  const colores = [
    ['Blanco', document.getElementById('imgBlanco').value],
    ['Negro', document.getElementById('imgNegro').value],
    ['Gris', document.getElementById('imgGris').value],
    ['Rojo', document.getElementById('imgRojo').value],
    ['Azul', document.getElementById('imgAzul').value],
    ['Verde', document.getElementById('imgVerde').value],
    ['Beige', document.getElementById('imgBeige').value],
    ['Rosa', document.getElementById('imgRosa').value],
    ['Marrón', document.getElementById('imgMarron').value],
    ['Amarillo', document.getElementById('imgAmarillo').value]
  ].filter(item => item[1] !== '');

  let opcionesColor = '<option value="" selected>🎨 Color</option>';
  let arrayProductos = '';

  colores.forEach((item, index) => {
    opcionesColor += `\n<option value="${item[0]}">${item[0]}</option>`;
    arrayProductos += `${index > 0 ? ',' : ''}\n{color:"${item[0]}",imagen:"${item[1]}"}`;
  });

  const primeraImagen = colores.length ? colores[0][1] : '';

  const codigo = `<iframe srcdoc='\n<div style="max-width:240px;font-family:Arial;padding:10px;position:relative;background:#171616;border-radius:12px;">\n\n<img id="img" src="${primeraImagen}" style="width:100%;height:160px;object-fit:cover;border-radius:10px;">\n\n<button onclick="prev()" style="position:absolute;top:70px;left:5px;background:#3D3D3D;color:white;border:none;border-radius:50%;width:25px;height:25px;">‹</button>\n<button onclick="next()" style="position:absolute;top:70px;right:5px;background:#3D3D3D;color:white;border:none;border-radius:50%;width:25px;height:25px;">›</button>\n\n<h3 style="margin:8px 0 2px;font-size:14px;color:#ABAA57;">💎${titulo} ${precio}</h3>\n<p style="font-size:10px;color:#BABABA;margin:2px 0;">Ref: ${referencia}</p>\n\n<select id="color" onchange="cambiarColor()" style="width:100%;margin-top:6px;">${opcionesColor}\n</select>\n\n<select id="talla" style="width:100%;margin-top:5px;">\n<option value="" selected>🏷️ Talla</option>\n<option>S</option>\n<option>M</option>\n<option>L</option>\n</select>\n\n<button onclick="enviar()" style="width:100%;margin-top:8px;background:#ABAA57;color:black;padding:10px;border:none;border-radius:8px;font-weight:bold;">💳 Compra</button>\n\n</div>\n\n<script>\nvar i=0;\nvar productos=[${arrayProductos}\n];\nfunction actualizarImagen(){document.getElementById("img").src=productos[i].imagen;}\nfunction next(){i=(i+1)%productos.length;actualizarImagen();document.getElementById("color").value=productos[i].color;}\nfunction prev(){i=(i-1+productos.length)%productos.length;actualizarImagen();document.getElementById("color").value=productos[i].color;}\nfunction cambiarColor(){var c=document.getElementById("color").value;for(var x=0;x<productos.length;x++){if(productos[x].color===c){i=x;actualizarImagen();break;}}}\nfunction enviar(){window.open("https://wa.me/${telefono}");}\nactualizarImagen();\n<\/script>' style="width:100%;height:420px;border:none;"></iframe>`;

  document.getElementById('resultado').value = codigo;
}
</script>

</body>
</html>
