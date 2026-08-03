[Uploading La Catalina_Onboarding_Interactivo.html…]()
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>La Catalina · Onboarding de marca · BBPR</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Marcellus&family=Jost:wght@300;400;500;600&display=swap');
:root{
 --marfil:#FAF4F0; --marfil2:#F3EAE1; --arena:#E4D1BA; --arena-soft:#EFE3D2;
 --salvia:#6B745F; --salvia-deep:#26342C; --salvia-mid:#4A5544;
 --terracota:#854A30; --terracota-soft:#A96545;
 --ink:#2C2A26; --body:#4A453E; --muted:#8B8177;
 --line:rgba(38,52,44,0.12);
 --herring:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='56' height='56' viewBox='0 0 56 56'%3E%3Cg fill='none' stroke='%2326342C' stroke-opacity='0.05' stroke-width='1.4'%3E%3Cpath d='M0 14 L14 0 M14 28 L28 14 M28 14 L14 0'/%3E%3Cpath d='M28 14 L42 0 M42 28 L56 14 M56 14 L42 0'/%3E%3Cpath d='M0 42 L14 28 M14 56 L28 42 M28 42 L14 28'/%3E%3Cpath d='M28 42 L42 28 M42 56 L56 42 M56 42 L42 28'/%3E%3C/g%3E%3C/svg%3E");
}
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
body{background:var(--marfil);color:var(--body);font-family:'Jost',sans-serif;font-weight:300;font-size:16px;line-height:1.75;-webkit-font-smoothing:antialiased}
h1,h2,h3,h4{font-family:'Marcellus',serif;font-weight:400;color:var(--salvia-deep)}
section{max-width:1180px;margin:0 auto;padding:96px 56px;position:relative}
.eyebrow{font-family:'Jost',sans-serif;font-weight:500;font-size:12px;letter-spacing:.34em;text-transform:uppercase;color:var(--terracota);margin-bottom:20px;display:flex;align-items:center;gap:14px}
.eyebrow::before{content:'';width:30px;height:1px;background:var(--terracota)}
.s-title{font-size:clamp(30px,4.4vw,50px);line-height:1.08;letter-spacing:.01em;margin-bottom:22px}
.s-title em{font-style:italic;color:var(--salvia)}
.s-lead{font-size:17px;color:var(--body);max-width:760px;line-height:1.8;margin-bottom:50px}

/* cover */
.cover{min-height:100vh;display:flex;flex-direction:column;justify-content:center;align-items:center;text-align:center;padding:60px 40px;background:var(--salvia-deep);position:relative;overflow:hidden}
.cover::before{content:'';position:absolute;inset:0;background-image:var(--herring);opacity:1;mix-blend-mode:overlay}
.cover::after{content:'';position:absolute;inset:0;background:radial-gradient(ellipse at 50% 30%,rgba(107,116,95,.35),transparent 70%)}
.cover>*{position:relative;z-index:2}
.cover-logo{width:min(560px,72vw);margin-bottom:38px;filter:drop-shadow(0 10px 30px rgba(0,0,0,.25))}
.cover-tag{font-family:'Marcellus',serif;font-size:clamp(17px,2.4vw,25px);font-style:italic;color:var(--arena);margin-bottom:30px;letter-spacing:.02em}
.cover-rule{width:54px;height:1px;background:var(--arena);opacity:.6;margin:0 auto 30px}
.cover-meta{font-family:'Jost',sans-serif;font-weight:400;font-size:12.5px;letter-spacing:.24em;text-transform:uppercase;color:rgba(250,244,240,.62);line-height:2}
.cover-q{margin-top:44px;max-width:640px;font-family:'Marcellus',serif;font-size:clamp(18px,2.3vw,23px);color:var(--marfil);line-height:1.55;font-style:italic}
.cover-badge{position:absolute;bottom:30px;left:0;right:0;font-family:'Jost',sans-serif;font-size:11px;letter-spacing:.28em;text-transform:uppercase;color:rgba(228,209,186,.55);z-index:2}

/* nav */
nav{position:sticky;top:0;z-index:100;background:rgba(250,244,240,.92);backdrop-filter:blur(16px);border-bottom:1px solid var(--line);padding:0 28px;display:flex;align-items:center;justify-content:space-between;height:58px}
.nav-brand{font-family:'Marcellus',serif;font-size:16px;color:var(--salvia);letter-spacing:.14em;text-transform:uppercase;white-space:nowrap}
.nav-brand b{color:var(--terracota);font-weight:400}
.nav-links{display:flex;gap:15px;list-style:none;flex-wrap:wrap;justify-content:flex-end}
.nav-links a{font-family:'Jost',sans-serif;font-weight:400;font-size:11.5px;letter-spacing:.12em;text-transform:uppercase;color:var(--muted);text-decoration:none;transition:color .2s;white-space:nowrap}
.nav-links a:hover{color:var(--terracota)}

/* section tinting */
.tint{background:var(--marfil2)}
.tint-arena{background:linear-gradient(180deg,var(--arena-soft),var(--marfil))}
.sec-wrap{position:relative}

/* identity fields */
.idcard{background:#fff;border:1px solid var(--line);border-radius:14px;padding:34px 38px;margin-bottom:26px;box-shadow:0 12px 34px rgba(38,52,44,.05)}
.idcard h3{font-size:24px;letter-spacing:.16em;text-transform:uppercase;color:var(--salvia);margin-bottom:22px}
.idrows{display:grid;grid-template-columns:1fr 1fr;gap:2px 40px}
.idrow{display:flex;gap:14px;padding:11px 0;border-bottom:1px solid var(--line);align-items:baseline}
.idrow .k{font-family:'Jost',sans-serif;font-weight:500;font-size:12px;letter-spacing:.12em;text-transform:uppercase;color:var(--terracota);min-width:96px}
.idrow .v{font-size:15.5px;color:var(--ink);flex:1}

/* stat callouts */
.stats{display:grid;grid-template-columns:repeat(auto-fit,minmax(170px,1fr));gap:18px;margin:6px 0}
.stat{background:#fff;border:1px solid var(--line);border-radius:14px;padding:30px 26px;text-align:left;box-shadow:0 12px 30px rgba(38,52,44,.05)}
.stat b{font-family:'Marcellus',serif;font-size:clamp(34px,4vw,44px);color:var(--terracota);line-height:1;display:block;margin-bottom:12px}
.stat span{font-family:'Jost',sans-serif;font-weight:400;font-size:12.5px;color:var(--muted);line-height:1.5;letter-spacing:.02em}
.stat.green b{color:var(--salvia)}

/* generic field grid */
.grid2{display:grid;grid-template-columns:1fr 1fr;gap:16px}
.grid3{display:grid;grid-template-columns:1fr 1fr 1fr;gap:16px}
.f{background:#fff;border:1px solid var(--line);border-radius:12px;padding:20px 24px}
.f .k{font-family:'Jost',sans-serif;font-weight:500;font-size:11.5px;letter-spacing:.1em;text-transform:uppercase;color:var(--terracota);margin-bottom:7px}
.f .v{font-size:15.5px;color:var(--ink);line-height:1.55}
.f .v.no{color:var(--terracota-soft)}
.full{grid-column:1/-1}

/* lists */
.starlist{list-style:none;display:flex;flex-wrap:wrap;gap:12px;margin-top:4px}
.starlist li{background:var(--arena-soft);color:var(--salvia-deep);font-family:'Marcellus',serif;font-size:17px;padding:12px 22px;border-radius:40px;border:1px solid rgba(133,74,48,.16)}

/* tags */
.tags{display:flex;flex-wrap:wrap;gap:10px;margin-top:6px}
.tag{font-family:'Jost',sans-serif;font-weight:400;font-size:13.5px;padding:8px 16px;border-radius:40px;background:#fff;border:1px solid var(--line);color:var(--salvia-deep)}
.tag.green{background:var(--salvia);color:var(--marfil);border-color:var(--salvia)}
.tag.terra{background:var(--terracota);color:var(--marfil);border-color:var(--terracota)}
.tag.arena{background:var(--arena);color:var(--salvia-deep);border-color:var(--arena)}

/* BBPR callout */
.bbpr{background:var(--salvia-deep);color:var(--marfil);border-radius:16px;padding:38px 42px;margin-top:34px;position:relative;overflow:hidden;box-shadow:0 20px 50px rgba(38,52,44,.18)}
.bbpr::before{content:'';position:absolute;inset:0;background-image:var(--herring);opacity:.7;mix-blend-mode:overlay}
.bbpr>*{position:relative;z-index:2}
.bbpr .badge{font-family:'Jost',sans-serif;font-weight:500;font-size:11px;letter-spacing:.26em;text-transform:uppercase;color:var(--arena);margin-bottom:15px;display:flex;align-items:center;gap:10px}
.bbpr .badge::before{content:'◆';color:var(--terracota-soft)}
.bbpr h4{color:var(--marfil);font-size:22px;margin-bottom:13px;line-height:1.25}
.bbpr p{color:rgba(250,244,240,.86);font-size:15.5px;line-height:1.78;margin-bottom:11px}
.bbpr p:last-child{margin-bottom:0}
.bbpr strong{color:var(--arena);font-weight:500}
.bbpr ul{list-style:none;display:flex;flex-direction:column;gap:11px;margin-top:4px}
.bbpr li{padding-left:22px;position:relative;color:rgba(250,244,240,.86);font-size:15.5px;line-height:1.65}
.bbpr li::before{content:'→';position:absolute;left:0;color:var(--terracota-soft)}
.bbpr.soft{background:#fff;color:var(--body);box-shadow:0 14px 34px rgba(38,52,44,.07);border:1px solid var(--line)}
.bbpr.soft::before{display:none}
.bbpr.soft .badge{color:var(--terracota)}
.bbpr.soft h4{color:var(--salvia-deep)}
.bbpr.soft p{color:var(--body)}
.bbpr.soft strong{color:var(--terracota)}
.bbpr.soft li{color:var(--body)}

/* quote */
.pull{background:var(--arena-soft);border-radius:14px;padding:32px 38px;margin:6px 0;border:1px solid rgba(133,74,48,.14)}
.pull .q{font-family:'Marcellus',serif;font-style:italic;font-size:24px;color:var(--salvia-deep);line-height:1.4}
.pull .cite{font-family:'Jost',sans-serif;font-size:12px;letter-spacing:.14em;text-transform:uppercase;color:var(--terracota);margin-top:12px}

/* compare want/avoid */
.cmp{display:grid;grid-template-columns:1fr 1fr;gap:18px;margin-top:6px}
.cmp .c{background:#fff;border:1px solid var(--line);border-radius:14px;padding:28px 30px}
.cmp .c h4{font-size:15px;letter-spacing:.1em;text-transform:uppercase;margin-bottom:12px}
.cmp .want h4{color:var(--salvia)}
.cmp .avoid h4{color:var(--terracota)}
.cmp .c p{font-size:15px;color:var(--ink);line-height:1.6}

/* palette swatches */
.pal{display:grid;grid-template-columns:repeat(4,1fr);gap:16px;margin-bottom:12px}
.sw{border-radius:14px;overflow:hidden;border:1px solid var(--line);box-shadow:0 10px 26px rgba(38,52,44,.06)}
.sw .chip{height:120px}
.sw .lbl{padding:16px 18px;background:#fff}
.sw .lbl b{font-family:'Marcellus',serif;font-size:19px;color:var(--salvia-deep);display:block;letter-spacing:.06em}
.sw .lbl span{font-family:'Jost',sans-serif;font-size:12.5px;color:var(--muted);letter-spacing:.08em}
.typo{display:grid;grid-template-columns:1fr 1fr;gap:16px;margin-top:8px}
.typo .t{background:#fff;border:1px solid var(--line);border-radius:14px;padding:26px 30px}
.typo .t .big{font-family:'Marcellus',serif;font-size:34px;color:var(--salvia-deep);margin-bottom:6px}
.typo .t .role{font-family:'Jost',sans-serif;font-size:12px;letter-spacing:.14em;text-transform:uppercase;color:var(--terracota);margin-bottom:14px}
.typo .t .note{font-size:14px;color:var(--muted)}
.typo .t.body .big{font-family:'Jost',sans-serif;font-weight:300;font-size:30px}

/* tables */
.tbl{width:100%;border-collapse:collapse;margin-top:6px;background:#fff;border:1px solid var(--line);border-radius:14px;overflow:hidden}
.tbl th{font-family:'Jost',sans-serif;font-weight:500;font-size:11.5px;letter-spacing:.12em;text-transform:uppercase;color:var(--marfil);background:var(--salvia);padding:15px 20px;text-align:left}
.tbl td{padding:15px 20px;border-top:1px solid var(--line);font-size:15px;color:var(--ink);vertical-align:middle}
.tbl td strong{color:var(--salvia-deep);font-weight:500}
.tbl tr:nth-child(even) td{background:var(--marfil2)}
.pri{font-family:'Jost',sans-serif;font-weight:600;font-size:11px;letter-spacing:.08em;padding:5px 12px;border-radius:30px;display:inline-block}
.pri.alta{background:var(--terracota);color:var(--marfil)}
.pri.media{background:var(--arena);color:var(--salvia-deep)}
.pri.baja{background:var(--marfil2);color:var(--muted);border:1px solid var(--line)}
.tbl .imp{font-family:'Marcellus',serif;color:var(--terracota);white-space:nowrap}
.tnote{font-size:13px;color:var(--muted);margin-top:14px;font-style:italic}

/* footer */
footer{background:var(--salvia-deep);text-align:center;padding:90px 40px;position:relative;overflow:hidden}
footer::before{content:'';position:absolute;inset:0;background-image:var(--herring);opacity:.7;mix-blend-mode:overlay}
footer>*{position:relative;z-index:2}
footer .flogo{width:min(360px,64vw);margin:0 auto 26px;display:block}
footer .fq{font-family:'Marcellus',serif;font-style:italic;font-size:22px;color:var(--arena);margin-bottom:22px}
footer .fm{font-family:'Jost',sans-serif;font-size:11.5px;letter-spacing:.24em;text-transform:uppercase;color:rgba(250,244,240,.5)}

@media(max-width:820px){
 section{padding:64px 24px}
 .idrows,.grid2,.grid3,.cmp,.typo{grid-template-columns:1fr}
 .pal{grid-template-columns:1fr 1fr}
 .nav-links{display:none}
 .tbl{display:block;overflow-x:auto;white-space:nowrap}
}
</style>
</head>
<body>

<!-- COVER -->
<header class="cover">
 <img class="cover-logo" src="data:image/png;base64,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AAAAAAAAALCEgBoAAAAAAAAAAABLCKgBAAAAAAAAAACwhIAaAAAAAAAAAAAASwioAQAAAAAAAAAAsISAGgAAAAAAAAAAAEsIqAEAAAAAAAAAALCEgBoAAAAAAAAAAABLCKgBAAAAAAAAAACwhIAaAAAAAAAAAAAASwioAQAAAAAAAAAAsISAGgAAAAAAAAAAAEsIqAEAAAAAAAAAALCEgBoAAAAAAAAAAABLCKgBAAAAAAAAAACwhIAaAAAAAAAAAAAASwioAQAAAAAAAAAAsISAGgAAAAAAAAAAAEsIqAEAAAAAAAAAALCEgBoAAAAAAAAAAABLCKgBAAAAAAAAAACwhIAaAAAAAAAAAAAASwioAQAAAAAAAAAAsISAGgAAAAAAAAAAAEsIqAEAAAAAAAAAALCEgBoAAAAAAAAAAABLCKgBAAAAAAAAAACwhIAaAAAAAAAAAAAASwioAQAAAAAAAAAAsISAGgAAAAAAAAAAAEsIqAEAAAAAAAAAALCEgBoAAAAAAAAAAABLCKgBAAAAAAAAAACwhIAaAAAAAAAAAAAASwioAQAAAAAAAAAAsISAGgAAAAAAAAAAAEsIqAEAAAAAAAAAALCEgBoAAAAAAAAAAABLCKgBAAAAAAAAAACwhIAaAAAAAAAAAAAASwioAQAAAAAAAAAAsISAGgAAAAAAAAAAAEsIqAEAAAAAAAAAALCEgBoAAAAAAAAAAABLCKgBAAAAAAAAAACwhIAaAAAAAAAAAAAASwioAQAAAAAAAAAAsISAGgAAAAAAAAAAAEsIqAEAAAAAAAAAALCEgBoAAAAAAAAAAABLCKgBAAAAAAAAAACwhIAaAAAAAAAAAAAASwioAQAAAAAAAAAAsISAGgAAAAAAAAAAAEsIqAEAAAAAAAAAALCEgBoAAAAAAAAAAABLCKgBAAAAAAAAAACwhIAaAAAAAAAAAAAASwioAQAAAAAAAAAAsISAGgAAAAAAAAAAAEsIqAEAAAAAAAAAALCEgBoAAAAAAAAAAABLCKgBAAAAAAAAAACwhIAaAAAAAAAAAAAASwioAQAAAAAAAAAAsISAGgAAAAAAAAAAAEsIqAEAAAAAAAAAALCEgBoAAAAAAAAAAABLCKgBAAAAAAAAAACwhIAaAAAAAAAAAAAASwioAQAAAAAAAAAAsISAGgAAAAAAAAAAAEsIqAEA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" alt="La Catalina">
 <div class="cover-tag">Cocina &amp; encuentros</div>
 <div class="cover-rule"></div>
 <div class="cover-meta">Onboarding de marca · Documento interno para el equipo · BBPR Agency</div>
 <div class="cover-q">"Que se sienta como en su casa y nos vuelva a elegir."</div>
 <div class="cover-badge">La Catalina · Mataderos · Desde 2015</div>
</header>

<!-- NAV -->
<nav>
 <div class="nav-brand">La Catalina · <b>BBPR</b></div>
 <ul class="nav-links">
  <li><a href="#negocio">Negocio</a></li>
  <li><a href="#operacion">Operación</a></li>
  <li><a href="#carta">Carta</a></li>
  <li><a href="#numeros">Números</a></li>
  <li><a href="#digital">Digital</a></li>
  <li><a href="#vision">Visión</a></li>
  <li><a href="#marca">Marca &amp; tono</a></li>
  <li><a href="#identidad">Identidad</a></li>
  <li><a href="#lectura">Lectura BBPR</a></li>
  <li><a href="#resumen">Resumen</a></li>
 </ul>
</nav>

<!-- 01 NEGOCIO -->
<div class="sec-wrap"><section id="negocio">
 <div class="eyebrow">01 · El negocio</div>
 <h2 class="s-title">Identidad y <em>propuesta</em></h2>
 <p class="s-lead">La Catalina es un clásico de barrio: casi una década en Mataderos, cocina tradicional reversionada y una marca que la gente ya conoce y quiere. Todo lo que comunicamos parte de ahí.</p>
 <div class="idcard">
  <h3>La Catalina</h3>
  <div class="idrows">
   <div class="idrow"><span class="k">Cocina</span><span class="v">Tradicional reversionada · menú ejecutivo distinto cada día</span></div>
   <div class="idrow"><span class="k">Zona</span><span class="v">Av. Emilio Castro 7502, Barrio Naón — Mataderos</span></div>
   <div class="idrow"><span class="k">Apertura</span><span class="v">2015 · casi 9 años de marca instalada</span></div>
   <div class="idrow"><span class="k">Concepto</span><span class="v">"Cocina &amp; encuentros" · como en casa</span></div>
   <div class="idrow"><span class="k">Horarios</span><span class="v">Mar a dom 8–00 h · Lun 11–20 h</span></div>
   <div class="idrow"><span class="k">Reputación</span><span class="v">6.2K reseñas en Google · 4.3★</span></div>
  </div>
 </div>
 <div class="stats">
  <div class="stat"><b>164</b><span>aforo total · ~23 mesas operativas por turno</span></div>
  <div class="stat green"><b>2015</b><span>año de apertura</span></div>
  <div class="stat"><b>$32.500</b><span>ticket promedio por comensal</span></div>
  <div class="stat green"><b>2</b><span>turnos por día · almuerzo y cena</span></div>
 </div>
 <div class="bbpr">
  <div class="badge">Lo primero que tiene que entender el equipo</div>
  <h4>Marca instalada, ocupación con techo</h4>
  <p>La Catalina no se construye de cero: <strong>ya existe y es querida</strong>. Casi 9 años y +6.000 reseñas con 4.3★ son un activo de reputación que pocos competidores de zona tienen. El problema no es awareness — es <strong>reactivar y monetizar mejor lo que ya está</strong>.</p>
  <p>Con 164 de aforo y 40% de ocupación semanal hay <strong>capacidad ociosa instalada</strong>. Cada punto de ocupación que recuperemos cae casi entero a margen, sin sumar costo fijo. Ahí está el primer pozo de plata.</p>
 </div>
</section></div>

<!-- 02 OPERACIÓN -->
<div class="sec-wrap tint"><section id="operacion">
 <div class="eyebrow">02 · Operación</div>
 <h2 class="s-title">Cómo funciona <em>el día a día</em></h2>
 <p class="s-lead">Restricciones y oportunidades reales del servicio. Definen dónde está la capacidad libre y qué podemos prometer en comunicación.</p>
 <div class="stats" style="margin-bottom:16px">
  <div class="stat"><b>40%</b><span>ocupación promedio semanal</span></div>
  <div class="stat green"><b>60%</b><span>ocupación fines de semana</span></div>
  <div class="stat"><b>50</b><span>capacidad máx. eventos privados</span></div>
  <div class="stat green"><b>0%</b><span>delivery · hoy no operan</span></div>
 </div>
 <div class="grid3">
  <div class="f"><div class="k">Temporada alta</div><div class="v">Junio · Julio · Agosto · Diciembre</div></div>
  <div class="f"><div class="k">Temporada baja</div><div class="v">Enero · Febrero · Marzo · Abril</div></div>
  <div class="f"><div class="k">Reservas</div><div class="v">Sí — WhatsApp y teléfono fijo</div></div>
  <div class="f"><div class="k">Lista de espera</div><div class="v no">No estructurada</div></div>
  <div class="f"><div class="k">Take away</div><div class="v">Sí</div></div>
  <div class="f"><div class="k">Eventos privados</div><div class="v">Sí — hasta 50 personas</div></div>
 </div>
 <div class="bbpr">
  <div class="badge">Dato clave para pauta y contenido</div>
  <h4>El calendario juega a favor: arrancamos en temporada alta</h4>
  <ul>
   <li>Entramos en <strong>junio–agosto (alta)</strong>: timing ideal para resultados rápidos y para construir base de datos con flujo. En paralelo hay que preparar ya el <strong>plan anti-baja de enero–abril</strong>, que es donde se sufre.</li>
   <li>Las reservas entran por WhatsApp y fijo, <strong>sin lista de espera ni señas</strong>: se pierde demanda y se comen no-shows. Oportunidad directa de CRM.</li>
   <li>El crecimiento no está el sábado a la noche (ya al 60%): está en <strong>los mediodías de semana y la temporada baja</strong>. Antes de pensar delivery, primero llenar el salón.</li>
  </ul>
 </div>
</section></div>

<!-- 03 CARTA -->
<div class="sec-wrap"><section id="carta">
 <div class="eyebrow">03 · Carta &amp; cocina</div>
 <h2 class="s-title">Lo que sale <em>de la cocina</em></h2>
 <p class="s-lead">Qué se vende, qué deja margen y qué no. La pasta manda; la carne tracciona pero rinde poco. El menú ejecutivo cambia todos los días — eso es contenido, no un problema logístico.</p>
 <div class="f full" style="margin-bottom:20px">
  <div class="k">Platos estrella · Top 5 en ventas</div>
  <ul class="starlist">
   <li>Risotto La Catalina</li><li>Ñoquis La Catalina</li><li>Gran Bife Porteño</li><li>La Milanga</li><li>Sorrentinos de ternera</li>
  </ul>
 </div>
 <div class="grid3">
  <div class="f"><div class="k">Más rentables</div><div class="v">Las pastas</div></div>
  <div class="f"><div class="k">Menos rentables</div><div class="v no">La carne</div></div>
  <div class="f"><div class="k">Menú ejecutivo</div><div class="v">Sí — distinto todos los días</div></div>
  <div class="f"><div class="k">Menú degustación</div><div class="v no">No</div></div>
  <div class="f"><div class="k">Opciones</div><div class="v">Gluten free</div></div>
  <div class="f"><div class="k">Carta por temporada</div><div class="v">Sí, cambia</div></div>
 </div>
 <div class="bbpr">
  <div class="badge">La palanca que el propio producto marca</div>
  <h4>La pasta es el héroe rentable — hay que volverla protagonista de marca</h4>
  <ul>
   <li>Las pastas son <strong>lo más vendido Y lo más rentable</strong>: alineación perfecta. Risotto y Ñoquis "La Catalina" son platos firma con nombre propio — oro para storytelling y para pauta.</li>
   <li>La carne vende pero rinde poco: revisar <strong>ingeniería de menú</strong> (repricing, guarniciones de mayor margen, reposicionar el Gran Bife como producto aspiracional).</li>
   <li>El <strong>menú ejecutivo distinto cada día</strong> es un diferencial enorme y subexplotado: da contenido diario nativo (el plato del día), justifica recurrencia y ataca el mediodía de semana flojo. Hoy nadie se entera.</li>
  </ul>
 </div>
</section></div>

<!-- 04 NÚMEROS -->
<div class="sec-wrap tint"><section id="numeros">
 <div class="eyebrow">04 · Números &amp; gestión</div>
 <h2 class="s-title">Estado <em>económico</em></h2>
 <p class="s-lead">Información sensible: uso interno del equipo, nunca en piezas ni en reuniones abiertas. Hay volumen, pero la rentabilidad es la preocupación central del cliente.</p>
 <div class="stats">
  <div class="stat"><b>$124M</b><span>facturación mensual promedio (2026)</span></div>
  <div class="stat green"><b>$159M</b><span>mejor mes · julio 2025</span></div>
  <div class="stat"><b>$108M</b><span>peor mes · enero 2025</span></div>
  <div class="stat green"><b>$62M</b><span>costos fijos mensuales</span></div>
 </div>
 <div class="bbpr soft" style="margin-top:30px">
  <div class="badge">A tener en cuenta</div>
  <ul>
   <li>Los <strong>costos fijos (~$62M) representan la mitad de la facturación promedio (~$124M)</strong>. La estructura es pesada: cada mesa adicional rinde muchísimo y cada mesa vacía duele. Esto confirma la intuición del cliente ("perdemos en la rentabilidad").</li>
   <li>La distancia entre el mejor y el peor mes es de <strong>~$51M (≈32%)</strong>: estacionalidad fuerte (alta jun–ago y diciembre / baja ene–abr). Sin comunicación, ene–abr seguirá siendo un agujero.</li>
   <li><strong>No hay control de stock profesional</strong> — punto ciego de margen a señalar al cliente. Sí usan sistema de gestión.</li>
   <li>Reservas <strong>sin señas</strong>: con esta estructura, cada no-show en fin de semana es plata que no vuelve.</li>
  </ul>
 </div>
</section></div>

<!-- 05 DIGITAL -->
<div class="sec-wrap"><section id="digital">
 <div class="eyebrow">05 · Presencia digital &amp; marketing</div>
 <h2 class="s-title">Punto de partida <em>en comunicación</em></h2>
 <p class="s-lead">El estado en el que recibimos la marca. Es la línea de base contra la que vamos a medir todo: reputación fuerte, comunicación pobre. Publican a diario pero dicen poco.</p>
 <div class="grid3">
  <div class="f"><div class="k">Instagram</div><div class="v">@lacatalinabar · clave ••••••</div></div>
  <div class="f"><div class="k">TikTok</div><div class="v">lacatalina.mkt · clave ••••••</div></div>
  <div class="f"><div class="k">Web propia</div><div class="v">Sí</div></div>
  <div class="f"><div class="k">Google My Business</div><div class="v">Optimizado parcialmente</div></div>
  <div class="f"><div class="k">Reseñas Google</div><div class="v">6.2K · 4.3★ · responden algunas</div></div>
  <div class="f"><div class="k">Frecuencia IG</div><div class="v">Diaria</div></div>
  <div class="f"><div class="k">Lineamiento estético</div><div class="v no">No</div></div>
  <div class="f"><div class="k">Manual de marca</div><div class="v no">No formal</div></div>
  <div class="f"><div class="k">Pauta mensual</div><div class="v">~$250 · promos ocasionales</div></div>
  <div class="f"><div class="k">Performance</div><div class="v no">No — solo promos sueltas</div></div>
  <div class="f"><div class="k">Base de datos</div><div class="v">Sí (email / WhatsApp)</div></div>
  <div class="f"><div class="k">Email / Automatizaciones</div><div class="v no">No (base sin usar)</div></div>
 </div>
 <div class="pull" style="margin-top:22px">
  <div class="q">"Solo platos, no experiencias."</div>
  <div class="cite">Lo que el propio cliente cree que comunica su marca hoy · autoevaluación de marketing: 5/10</div>
 </div>
 <div class="bbpr">
  <div class="badge">Oportunidad clave</div>
  <h4>Mucho esfuerzo diario sin sistema: alcance desperdiciado</h4>
  <ul>
   <li>El diagnóstico del cliente es el brief: comunican "solo platos". <strong>Norte creativo: vender la experiencia La Catalina</strong> — el lugar, la historia, la mesa, el ritual de barrio.</li>
   <li>Frecuencia diaria <strong>sin guía estética ni manual de marca</strong> = esfuerzo que no capitaliza. Primer entregable: identidad + pilares de contenido.</li>
   <li>Tienen <strong>base de datos pero no la usan</strong> (sin email, sin automatizaciones): plata dormida. Cumpleaños, recordatorios y reactivación son quick wins de CRM.</li>
   <li>Pauta de ~$250 sin funnel y GMB solo parcial: <strong>el canal más barato y escalable está casi sin usar</strong>, y el cliente identifica la comunicación como lo que frena el crecimiento.</li>
  </ul>
 </div>
</section></div>

<!-- 06 VISIÓN -->
<div class="sec-wrap tint-arena"><section id="vision">
 <div class="eyebrow">06 · Visión &amp; objetivos</div>
 <h2 class="s-title">Hacia dónde <em>quieren ir</em></h2>
 <p class="s-lead">Las ambiciones declaradas por el cliente. Quieren escalar fuerte y verse como marca referente, con apertura a sucursales y franquicia a futuro.</p>
 <div class="stats">
  <div class="stat green"><b>$160M</b><span>facturación actual declarada</span></div>
  <div class="stat"><b>$200M</b><span>meta a 12 meses · ≈ +25%</span></div>
  <div class="stat green"><b>$400M</b><span>meta ideal a 3 años · ≈ ×2,5</span></div>
  <div class="stat"><b>Sí</b><span>abrir sucursales · franquiciar · ser referente</span></div>
 </div>
 <div class="bbpr">
  <div class="badge">Tensión central del proyecto</div>
  <h4>De $160M a $200M en 12 meses: alcanzable sin abrir un local nuevo</h4>
  <p>El salto de los próximos 12 meses (~25%) se puede sacar <strong>llenando el local actual</strong>, hoy al 40% de ocupación: no requiere capex de sucursal. La franquicia y las nuevas sucursales son visión a 3 años.</p>
  <p>El cliente pide <strong>"volumen Y exclusividad, no volumen a cualquier precio"</strong> y quiere "hacer cola como en otros años". El posicionamiento correcto es <strong>aspiracional accesible</strong>: llenar mesas por deseo y recurrencia, no canibalizando el ticket con promo barata.</p>
 </div>
</section></div>

<!-- 07 MARCA & TONO -->
<div class="sec-wrap"><section id="marca">
 <div class="eyebrow">07 · Marca, tono y audiencia</div>
 <h2 class="s-title">Cómo <em>hablamos</em></h2>
 <p class="s-lead">Autopercepción, cliente ideal, referentes y la experiencia que quieren transmitir. La base para definir el territorio de marca.</p>
 <div class="grid2" style="margin-bottom:16px">
  <div class="f"><div class="k">La marca en 3 palabras</div><div class="tags"><span class="tag arena">Familiar</span><span class="tag arena">Clásico</span><span class="tag arena">Moderno</span></div></div>
  <div class="f"><div class="k">Emoción buscada</div><div class="v">Que se sienta como en su casa y vuelva a elegirlos. Que recuerde un rato agradable, con detalles.</div></div>
 </div>
 <div class="f full" style="margin-bottom:16px"><div class="k">Diferencial real</div><div class="v">La atención · el menú ejecutivo distinto cada día · la presentación de los platos · la vajilla.</div></div>
 <div class="cmp">
  <div class="c want"><h4>Cliente que SÍ quieren</h4><p>El que valora la experiencia y "la gasta" — que vuelve a elegirlos y disfruta los detalles, no el precio.</p></div>
  <div class="c avoid"><h4>Cliente que NO quieren</h4><p>El cazador de promos, o el que cree que por estar en Mataderos un plato debe valer menos que en otros barrios.</p></div>
 </div>
 <div class="grid2" style="margin-top:16px">
  <div class="f"><div class="k">Sí o sí — innegociables</div><div class="tags"><span class="tag green">Buena atención</span><span class="tag green">Platos a tiempo</span><span class="tag green">Calidad de comida</span><span class="tag green">Presentación cuidada</span><span class="tag green">Sentirse como en casa</span></div></div>
  <div class="f"><div class="k">Don'ts — no negociable</div><div class="tags"><span class="tag terra">Mala atención</span><span class="tag terra">Demora en los platos</span><span class="tag terra">Mala calidad</span><span class="tag terra">Promo como mensaje de marca</span></div></div>
 </div>
 <div class="grid3" style="margin-top:16px">
  <div class="f"><div class="k">Referente a seguir</div><div class="v">Kansas — por los procesos y la atención</div></div>
  <div class="f"><div class="k">Comunica muy bien</div><div class="v">Mucho.arg — por la imagen</div></div>
  <div class="f"><div class="k">Efemérides ancla</div><div class="v">Aniversario La Catalina · findes XXL · Día del Amigo</div></div>
 </div>
 <div class="bbpr">
  <div class="badge">El problema de percepción a resolver</div>
  <h4>"De todo a toda hora" es su fuerza y su problema</h4>
  <p>Esa versatilidad los hace queridos pero <strong>diluye la identidad</strong>. El trabajo de marca es elegir un héroe —la pasta, el ritual del menú del día, la experiencia de barrio con detalle— sin perder la amplitud.</p>
  <p>Definen con claridad al cliente que NO quieren, pero a "¿a quién le hablamos?" responden <strong>"hoy no sabemos"</strong>. Definir el cliente ideal positivo es el primer entregable estratégico pendiente. El norte ya está en sus referentes: Kansas (operación/atención) + Mucho.arg (estética).</p>
 </div>
</section></div>

<!-- 08 IDENTIDAD VISUAL -->
<div class="sec-wrap tint"><section id="identidad">
 <div class="eyebrow">08 · Identidad visual</div>
 <h2 class="s-title">El sistema <em>gráfico</em></h2>
 <p class="s-lead">Manual de marca desarrollado por BBPR. Todo lo que producimos respeta este sistema: paleta cálida de barrio, verde salvia como firma y una tipografía elegante y sobria. Nada de esto se improvisa.</p>
 <div class="pal">
  <div class="sw"><div class="chip" style="background:#E4D1BA"></div><div class="lbl"><b>Arena</b><span>#E4D1BA</span></div></div>
  <div class="sw"><div class="chip" style="background:#6B745F"></div><div class="lbl"><b>Salvia</b><span>#26342C</span></div></div>
  <div class="sw"><div class="chip" style="background:#854A30"></div><div class="lbl"><b>Terracota</b><span>#854A30</span></div></div>
  <div class="sw"><div class="chip" style="background:#FAF4F0;border-bottom:1px solid var(--line)"></div><div class="lbl"><b>Marfil</b><span>#FAF4F0</span></div></div>
 </div>
 <div class="typo">
  <div class="t"><div class="role">Logotipo &amp; títulos</div><div class="big">La Catalina</div><div class="note">Fino Sans — Regular. Elegante, condensada, en mayúsculas. En web se aproxima con Marcellus.</div></div>
  <div class="t body"><div class="role">Párrafos</div><div class="big">Cocina &amp; encuentros</div><div class="note">Nohemi — Light. Geométrica y liviana para textos. En web se aproxima con Jost.</div></div>
 </div>
 <div class="bbpr soft">
  <div class="badge">Cómo lo usamos</div>
  <h4>Marfil de base, salvia de firma, terracota para acentuar</h4>
  <p>El <strong>marfil</strong> es el fondo neutro cálido; el <strong>verde salvia</strong> lleva el peso de marca (logo, títulos, bloques); la <strong>terracota</strong> es el acento que resalta datos y llamados; el <strong>arena</strong> aporta calidez en cards y superficies. El patrón geométrico de fondo (herringbone) es un recurso de textura, siempre sutil.</p>
 </div>
</section></div>

<!-- 09 LECTURA ESTRATÉGICA -->
<div class="sec-wrap"><section id="lectura">
 <div class="eyebrow">09 · Lectura estratégica</div>
 <h2 class="s-title">Cómo lo leemos <em>desde BBPR</em></h2>
 <p class="s-lead">De dónde salen los $40M que separan a La Catalina de su meta a 12 meses. Esto es lectura de agencia, no dato del cliente: priorizado por impacto.</p>
 <table class="tbl">
  <thead><tr><th>Palanca</th><th>Aporte estimado</th><th>Prioridad</th></tr></thead>
  <tbody>
   <tr><td><strong>Ocupación semanal</strong> — llenar mediodías de semana y temporada baja (hoy 40%)</td><td class="imp">+$15 a 20M</td><td><span class="pri alta">ALTA</span></td></tr>
   <tr><td><strong>CRM + automatizaciones</strong> — base de datos hoy sin usar: recompra, cumpleaños, señas</td><td class="imp">+$6 a 9M</td><td><span class="pri alta">ALTA</span></td></tr>
   <tr><td><strong>Pauta digital estructurada</strong> — hoy ~$250 sin funnel</td><td class="imp">habilitante</td><td><span class="pri alta">ALTA</span></td></tr>
   <tr><td><strong>Eventos privados</strong> (hasta 50 pax) — hoy sin comunicar</td><td class="imp">+$5 a 8M</td><td><span class="pri media">MEDIA</span></td></tr>
   <tr><td><strong>Reputación + SEO local</strong> — 6.2K reseñas y GMB solo parcial</td><td class="imp">+$3 a 5M</td><td><span class="pri media">MEDIA</span></td></tr>
   <tr><td><strong>Mediodía ejecutivo + take away</strong> — plato del día como producto</td><td class="imp">+$3 a 5M</td><td><span class="pri media">MEDIA</span></td></tr>
   <tr><td><strong>Sucursales / franquicia</strong> — visión a 3 años</td><td class="imp">techo del modelo</td><td><span class="pri baja">BAJA</span></td></tr>
  </tbody>
 </table>
 <p class="tnote">Estimaciones BBPR sobre la base declarada en el onboarding. A validar con datos del sistema de gestión.</p>
</section></div>

<!-- 10 RESUMEN -->
<div class="sec-wrap tint"><section id="resumen">
 <div class="eyebrow">En resumen</div>
 <h2 class="s-title">Una marca querida <em>que todavía no se cuenta</em></h2>
 <p class="s-lead">La Catalina no tiene un problema de producto ni de reputación: tiene capacidad ociosa y comunicación dormida. Salón al 40%, base de datos sin usar, reputación sólida sin capitalizar y un diferencial real que hoy no se muestra. Ahí está todo el trabajo.</p>
 <h3 style="font-size:22px;letter-spacing:.04em;margin-bottom:18px;color:var(--salvia)">Próximos pasos · primeros 90 días</h3>
 <table class="tbl">
  <thead><tr><th>Acción</th><th>Impacto esperado</th><th>Prioridad</th></tr></thead>
  <tbody>
   <tr><td><strong>Encender pauta</strong> con foco en mediodías de semana y temporada baja</td><td>Ocupación 40% → 60%</td><td><span class="pri alta">ALTA</span></td></tr>
   <tr><td><strong>Identidad + pilares de contenido</strong> — guía estética y manual de marca</td><td>Coherencia y relato de marca</td><td><span class="pri alta">ALTA</span></td></tr>
   <tr><td><strong>Optimizar Google My Business</strong> al 100% y responder todas las reseñas</td><td>Captura de búsqueda con intención</td><td><span class="pri alta">ALTA</span></td></tr>
   <tr><td><strong>Activar CRM</strong> — cumpleaños, recordatorios de reserva, reactivación</td><td>Recurrencia con inversión mínima</td><td><span class="pri alta">ALTA</span></td></tr>
   <tr><td><strong>Serie de contenido "el plato del día"</strong> — menú ejecutivo diario</td><td>Contenido nativo + mediodía de semana</td><td><span class="pri media">MEDIA</span></td></tr>
   <tr><td><strong>Activar señas</strong> en reservas</td><td>Reducción de no-shows</td><td><span class="pri media">MEDIA</span></td></tr>
   <tr><td><strong>Kit de eventos privados</strong> (hasta 50 pax)</td><td>Nueva fuente de facturación</td><td><span class="pri media">MEDIA</span></td></tr>
   <tr><td><strong>Campaña ancla Aniversario La Catalina</strong></td><td>Relato de marca + comunidad</td><td><span class="pri baja">BAJA</span></td></tr>
  </tbody>
 </table>
</section></div>

<!-- FOOTER -->
<footer>
 <img class="flogo" src="data:image/png;base64,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AAAAAAAAALCEgBoAAAAAAAAAAABLCKgBAAAAAAAAAACwhIAaAAAAAAAAAAAASwioAQAAAAAAAAAAsISAGgAAAAAAAAAAAEsIqAEAAAAAAAAAALCEgBoAAAAAAAAAAABLCKgBAAAAAAAAAACwhIAaAAAAAAAAAAAASwioAQAAAAAAAAAAsISAGgAAAAAAAAAAAEsIqAEAAAAAAAAAALCEgBoAAAAAAAAAAABLCKgBAAAAAAAAAACwhIAaAAAAAAAAAAAASwioAQAAAAAAAAAAsISAGgAAAAAAAAAAAEsIqAEAAAAAAAAAALCEgBoAAAAAAAAAAABLCKgBAAAAAAAAAACwhIAaAAAAAAAAAAAASwioAQAAAAAAAAAAsISAGgAAAAAAAAAAAEsIqAEAAAAAAAAAALCEgBoAAAAAAAAAAABLCKgBAAAAAAAAAACwhIAaAAAAAAAAAAAASwioAQAAAAAAAAAAsISAGgAAAAAAAAAAAEsIqAEAAAAAAAAAALCEgBoAAAAAAAAAAABLCKgBAAAAAAAAAACwhIAaAAAAAAAAAAAASwioAQAAAAAAAAAAsISAGgAAAAAAAAAAAEsIqAEAAAAAAAAAALCEgBoAAAAAAAAAAABLCKgBAAAAAAAAAACwhIAaAAAAAAAAAAAASwioAQAAAAAAAAAAsISAGgAAAAAAAAAAAEsIqAEAAAAAAAAAALCEgBoAAAAAAAAAAABLCKgBAAAAAAAAAACwhIAaAAAAAAAAAAAASwioAQAAAAAAAAAAsISAGgAAAAAAAAAAAEsIqAEAAAAAAAAAALCEgBoAAAAAAAAAAABLCKgBAAAAAAAAAACwhIAaAAAAAAAAAAAASwioAQAAAAAAAAAAsISAGgAAAAAAAAAAAEsIqAEAAAAAAAAAALCEgBoAAAAAAAAAAABLCKgBAAAAAAAAAACwhIAaAAAAAAAAAAAASwioAQAAAAAAAAAAsISAGgAAAAAAAAAAAEsIqAEAAAAAAAAAALCEgBoAAAAAAAAAAABLCKgBAAAAAAAAAACwhIAaAAAAAAAAAAAASwioAQAAAAAAAAAAsISAGgAAAAAAAAAAAEsIqAEAAAAAAAAAALCEgBoAAAAAAAAAAABLCKgBAAAAAAAAAACwhIAaAAAAAAAAAAAASwioAQAAAAAAAAAAsISAGgAAAAAAAAAAAEsIqAEA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" alt="La Catalina">
 <div class="fq">"Que se sienta como en su casa y nos vuelva a elegir."</div>
 <div class="fm">BBPR Agency · La Catalina — Onboarding de marca · Documento interno</div>
</footer>

</body>
</html>
