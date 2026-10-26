# <!DOCTYPE html>
<html lang="es">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Estudio de Mercado B2B · Licor Artesanal de Cacao</title>
<style>
:root{box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px);
--bg:#f7f3ee;--card:#fff;--tx:#2a1f1a;--mut:#6f6058;--ac:#6b3f2a;--acx:#fff;--bd:#dccfc4;--ok:#2e7d4f}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){color-scheme:dark;--bg:#1b1512;--card:#261d19;--tx:#f2e9e2;--mut:#b5a69b;--ac:#d29a76;--acx:#1b1512;--bd:#4a3b33;--ok:#6fcf97}}
:root[data-theme="dark"]{color-scheme:dark;--bg:#1b1512;--card:#261d19;--tx:#f2e9e2;--mut:#b5a69b;--ac:#d29a76;--acx:#1b1512;--bd:#4a3b33;--ok:#6fcf97}
*,*:before,*:after{box-sizing:inherit}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
body{margin:0;background:var(--bg);color:var(--tx);font:16px/1.5 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif}
main{max-width:720px;margin:0 auto;padding:20px 16px 48px}
header{text-align:center;margin-bottom:18px}
header small{color:var(--mut);display:block}
h1{font-size:1.3rem;margin:6px 0 4px;color:var(--ac)}
.obj{background:var(--card);border:1px solid var(--bd);border-radius:12px;padding:12px 14px;color:var(--mut);font-size:.92rem;margin-bottom:16px}
section{background:var(--card);border:1px solid var(--bd);border-radius:12px;padding:14px;margin-bottom:14px}
h2{font-size:1.05rem;margin:0 0 10px;color:var(--ac)}
.q{margin:14px 0 6px;font-weight:600}
label.o{display:flex;gap:10px;align-items:flex-start;padding:9px 10px;border:1px solid var(--bd);border-radius:10px;margin:6px 0;cursor:pointer}
label.o input{margin-top:4px;accent-color:var(--ac)}
input[type=text],input[type=date],textarea{width:100%;font:inherit;padding:10px;border:1px solid var(--bd);border-radius:10px;background:var(--bg);color:var(--tx)}
textarea{min-height:100px;resize:vertical}
.row{display:grid;gap:10px}
.fac{margin:10px 0;padding-bottom:10px;border-bottom:1px dashed var(--bd)}
.fac:last-child{border:0}
.scale{display:grid;grid-template-columns:repeat(5,1fr);gap:6px;margin-top:6px}
.scale label{display:flex;flex-direction:column;align-items:center;gap:2px;padding:8px 0;border:1px solid var(--bd);border-radius:10px;cursor:pointer;font-weight:600}
.scale input{accent-color:var(--ac)}
.hint{color:var(--mut);font-size:.85rem}
button{font:inherit;font-weight:700;background:var(--ac);color:var(--acx);border:0;border-radius:12px;padding:14px;width:100%;cursor:pointer}
button:disabled{opacity:.6}
.msg{margin-top:10px;font-weight:600}
.err{color:#c0392b}.ok{color:var(--ok)}
.adm{border-style:dashed}
.adm button{width:auto;padding:10px 16px;margin-top:8px}
.foot{text-align:center;color:var(--mut);font-size:.8rem;margin-top:16px}
</style>
</head>
<body>
<main>
<header>
<small>UNIVERSIDAD NACIONAL DE SAN ANTONIO ABAD DEL CUSCO</small>
<small>Escuela Profesional de Ingeniería Agroindustrial</small>
<h1>Estudio de Mercado (B2B): Clientes Minoristas y Distribuidores</h1>
</header>
<div class="obj"><b>Objetivo:</b> evaluar la viabilidad comercial y los requisitos de distribución para introducir un nuevo Licor Artesanal a base de Pasta Pura de Cacao en el mercado minorista. Sus respuestas nos ayudarán a definir precios, presentaciones y estrategias de venta al por mayor.</div>


<form id="f" onsubmit="return false">
<section>
<h2>Datos del establecimiento</h2>
<div class="row">
<div><div class="q">Nombre del establecimiento / razón social</div><input type="text" name="establecimiento"></div>
<div><div class="q">Ciudad / distrito (ej. Sicuani, Cusco)</div><input type="text" name="ciudad"></div>
<div><div class="q">Cargo del encuestado</div>
<label class="o"><input type="radio" name="cargo" value="Dueño/Gerente">Dueño/Gerente</label>
<label class="o"><input type="radio" name="cargo" value="Administrador">Administrador</label>
<label class="o"><input type="radio" name="cargo" value="Otro">Otro</label>
<input type="text" name="cargo_otro" placeholder="Si es otro, indique cuál"></div>
<div><div class="q">Fecha</div><input type="date" name="fecha"></div>
</div>
</section>

<section>
<h2>1. Perfil del negocio</h2>
<div class="q">1.1. ¿Cuál es el giro principal de su negocio?</div>
<label class="o"><input type="radio" name="p11" value="Licorería especializada">Licorería especializada</label>
<label class="o"><input type="radio" name="p11" value="Bodega / Minimarket">Bodega / Minimarket</label>
<label class="o"><input type="radio" name="p11" value="Tienda de productos turísticos/regionales">Tienda de productos turísticos/regionales</label>
<label class="o"><input type="radio" name="p11" value="Restaurante / Restobar">Restaurante / Restobar</label>
<label class="o"><input type="radio" name="p11" value="Discoteca / Bar">Discoteca / Bar</label>
<label class="o"><input type="radio" name="p11" value="Otro">Otro</label>
<input type="text" name="p11_otro" placeholder="Si es otro, indique cuál">
<div class="q">1.2. Actualmente, ¿comercializa licores artesanales o regionales de cacao/café/muña?</div>
<label class="o"><input type="radio" name="p12" value="Sí, tienen alta rotación">Sí, tienen alta rotación</label>
<label class="o"><input type="radio" name="p12" value="Sí, pero de rotación lenta">Sí, pero de rotación lenta</label>
<label class="o"><input type="radio" name="p12" value="No, pero me interesa">No, pero me interesa</label>
<label class="o"><input type="radio" name="p12" value="No, no son mi rubro">No, no son mi rubro</label>
</section>

<section>
<h2>2. Condiciones comerciales y distribución</h2>
<div class="q">2.1. ¿Qué volumen de compra inicial consideraría para un producto nuevo como este (licor de cacao)?</div>
<label class="o"><input type="radio" name="p21" value="Muestra / prueba (1 a 3 botellas)">Muestra / prueba (1 a 3 botellas)</label>
<label class="o"><input type="radio" name="p21" value="Media caja (6 botellas)">Media caja (6 botellas)</label>
<label class="o"><input type="radio" name="p21" value="Una caja o más (12+ botellas)">Una caja o más (12+ botellas)</label>
<div class="q">2.2. ¿Qué margen de ganancia neto espera obtener al vender licores artesanales?</div>
<label class="o"><input type="radio" name="p22" value="15% - 20%">15% - 20%</label>
<label class="o"><input type="radio" name="p22" value="20% - 30%">20% - 30%</label>
<label class="o"><input type="radio" name="p22" value="30% - 40%">30% - 40%</label>
<label class="o"><input type="radio" name="p22" value="Más del 40%">Más del 40%</label>
<div class="q">2.3. Pensando en una botella estándar de 500 ml, ¿cuál es el precio MAYORISTA máximo que estaría dispuesto a pagar por unidad para poder revenderla con buen margen?</div>
<label class="o"><input type="radio" name="p23" value="Hasta S/ 18.00">Hasta S/ 18.00</label>
<label class="o"><input type="radio" name="p23" value="De S/ 18.00 a S/ 25.00">De S/ 18.00 a S/ 25.00</label>
<label class="o"><input type="radio" name="p23" value="De S/ 25.00 a S/ 32.00">De S/ 25.00 a S/ 32.00</label>
<label class="o"><input type="radio" name="p23" value="Más de S/ 32.00">Más de S/ 32.00</label>
</section>

<section>
<h2>3. Presentación y atributos de decisión</h2>
<div class="q">3.1. Según la preferencia de sus clientes, ¿qué tipo de envase se vende más rápido?</div>
<label class="o"><input type="radio" name="p31" value="Botella clásica de 750 ml (familiar/eventos)">Botella clásica de 750 ml (familiar/eventos)</label>
<label class="o"><input type="radio" name="p31" value="Botella mediana de 500 ml (consumo estándar)">Botella mediana de 500 ml (consumo estándar)</label>
<label class="o"><input type="radio" name="p31" value="Botella pequeña/petaca de 250 ml (regalo/souvenir)">Botella pequeña/petaca de 250 ml (regalo/souvenir)</label>
<label class="o"><input type="radio" name="p31" value="Botellas miniatura (colección/muestras)">Botellas miniatura (colección/muestras)</label>
<div class="q">3.2. Califique la importancia de los siguientes factores al decidir incluir nuestro licor de cacao en sus vitrinas</div>
<div class="hint">1 = Nada importante · 2 = Poco importante · 3 = Neutral · 4 = Importante · 5 = Muy importante</div>
<div id="fac"></div>
</section>

<section>
<h2>4. Intención comercial y feedback</h2>
<div class="q">4.1. Si le proporcionamos material promocional (volantes/exhibidores) y un lote inicial a consignación, ¿estaría dispuesto a exhibir y vender el producto?</div>
<label class="o"><input type="radio" name="p41" value="Sí, definitivamente">Sí, definitivamente</label>
<label class="o"><input type="radio" name="p41" value="Probablemente sí">Probablemente sí</label>
<label class="o"><input type="radio" name="p41" value="Dependería de la presentación física">Dependería de la presentación física</label>
<label class="o"><input type="radio" name="p41" value="No por el momento">No por el momento</label>
<div class="q">4.2. ¿Qué recomendación nos daría como productores agroindustriales para que este producto sea un éxito de ventas en su negocio?</div>
<textarea name="p42"></textarea>
</section>

<button id="send" type="button">Enviar respuestas</button>
<div id="msg" class="msg" role="status"></div>
</form>
<p class="foot">¡Agradecemos sinceramente su tiempo y experiencia comercial! Esta información es estrictamente confidencial y con fines de investigación agroindustrial.</p>
</main>

<script>
const FACT=[["f_etiqueta","Diseño de la etiqueta y presentación visual"],["f_margen","Margen de ganancia ofrecido"],["f_sabor","Sabor y calidad del producto (degustación)"],["f_marketing","Apoyo en marketing (material POP, impulsadoras)"],["f_registro","Registro sanitario y legalidad"]];
const fac=document.getElementById("fac");
FACT.forEach(([k,t])=>{
  const d=document.createElement("div");d.className="fac";
  const l=document.createElement("div");l.textContent=t;d.appendChild(l);
  const s=document.createElement("div");s.className="scale";
  for(let i=1;i<=5;i++){
    const lb=document.createElement("label");
    const inp=document.createElement("input");inp.type="radio";inp.name=k;inp.value=String(i);
    lb.appendChild(inp);lb.appendChild(document.createTextNode(String(i)));s.appendChild(lb);
  }
  d.appendChild(s);fac.appendChild(d);
});

const f=document.getElementById("f"),msg=document.getElementById("msg"),send=document.getElementById("send");
function val(n){const e=f.elements[n];if(!e)return"";if(e.length&&e[0]&&e[0].type==="radio"){const c=[...e].find(x=>x.checked);return c?c.value:""}return(e.value||"").trim()}
const FIELDS=["establecimiento","ciudad","cargo","cargo_otro","fecha","p11","p11_otro","p12","p21","p22","p23","p31",...FACT.map(x=>x[0]),"p41","p42"];

function setMsg(t,c){msg.textContent=t;msg.className="msg "+(c||"")}

send.addEventListener("click",()=>{
  f.style.display="none";
  setMsg("¡Gracias por su tiempo y experiencia comercial!","ok");
  window.scrollTo(0,0);
});
</script>
</body>
</html>
