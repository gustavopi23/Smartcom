# Smartcom
Smartcom 
<!DOCTYPE html>
<html lang="pt-BR">


<head>


<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">


<title>SMARTCOM | Gestão Inteligente</title>


<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>


<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">


<style>


*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}


body{
background:#07172d;
color:#fff;
overflow-x:hidden;
}


body::before{


content:'';
position:fixed;
width:800px;
height:800px;
background:#00c48c30;
filter:blur(180px);
top:-250px;
right:-250px;
z-index:-1;


}


body::after{


content:'';
position:fixed;
width:700px;
height:700px;
background:#0f5eff20;
filter:blur(180px);
bottom:-250px;
left:-250px;
z-index:-1;


}


header{


position:fixed;
width:100%;
top:0;
left:0;
background:rgba(6,16,32,.85);
backdrop-filter:blur(15px);
padding:18px 10%;
display:flex;
justify-content:space-between;
align-items:center;
z-index:999;


}


.logo{


font-size:32px;
font-weight:800;
color:#fff;


}


.logo span{


color:#00c48c;


}


nav a{


text-decoration:none;
color:white;
margin-left:35px;
transition:.4s;


}


nav a:hover{


color:#00c48c;


}


.hero{


min-height:100vh;
display:flex;
justify-content:space-between;
align-items:center;
padding:120px 10%;


}


.left{


width:50%;


}


.left h1{


font-size:64px;
line-height:72px;
margin-bottom:25px;


}


.left h1 span{


color:#00c48c;


}


.left p{


font-size:20px;
line-height:35px;
color:#d0d0d0;
margin-bottom:40px;


}


.buttons{


display:flex;
gap:20px;


}


.btn{


padding:18px 40px;
border-radius:50px;
text-decoration:none;
font-weight:600;
transition:.4s;


}


.primary{


background:#00c48c;
color:white;


}


.primary:hover{


transform:translateY(-5px);


}


.secondary{


border:2px solid white;
color:white;


}


.secondary:hover{


background:white;
color:#07172d;


}


.right{


width:45%;
display:flex;
justify-content:center;


}


.card{


width:430px;
height:430px;


background:rgba(255,255,255,.06);


backdrop-filter:blur(25px);


border-radius:30px;


padding:45px;


border:1px solid rgba(255,255,255,.1);


box-shadow:0 20px 60px rgba(0,0,0,.4);


animation:float 4s ease-in-out infinite;


}


@keyframes float{


50%{


transform:translateY(-20px);


}


}


.card h2{


font-size:30px;
margin-bottom:30px;


}


.info{


display:flex;
justify-content:space-between;
margin-bottom:25px;
padding-bottom:15px;
border-bottom:1px solid rgba(255,255,255,.1);


}


.info span{


color:#00c48c;
font-weight:700;


}


section{


padding:100px 10%;


}


.title{


text-align:center;
font-size:42px;
margin-bottom:70px;


}


.cards{


display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:35px;


}


.box{


background:rgba(255,255,255,.05);
padding:40px;
border-radius:25px;
transition:.5s;


}


.box:hover{


transform:translateY(-12px);


background:#00c48c;


}


.box h3{


margin-bottom:20px;
font-size:26px;


}


.box p{


line-height:30px;


}


footer{


padding:60px;
text-align:center;
background:#05101f;
color:#bbb;


}


@media(max-width:900px){


.hero{


flex-direction:column;
text-align:center;


}


.left,.right{


width:100%;


}


.left h1{


font-size:45px;
line-height:55px;


}


.right{


margin-top:60px;


}


nav{


display:none;


}


}


</style>


</head>


<body>


<header>


<div class="logo">
SMART<span>COM</span>
</div>


<nav>


<a href="#sobre">Sobre</a>


<a href="#servicos">Serviços</a>


<a href="#diferenciais">Diferenciais</a>


<a href="#contato">Contato</a>


</nav>


</header>


<section class="hero">


<div class="left">


<h1>


Gestão Inteligente para
<span>Empresas e Condomínios</span>


</h1>


<p>


Transformamos processos administrativos em resultados,
com organização, transparência e tecnologia.


</p>


<div class="buttons">


<a href="#" class="btn primary">


Solicitar Proposta


</a>


<a href="#" class="btn secondary">


WhatsApp


</a>


</div>


</div>


<div class="right">


<div class="card">


<h2>SMARTCOM</h2>


<div class="info">


<p>BPO Empresarial</p>


<span>✓</span>


</div>


<div class="info">


<p>Administração Condominial</p>


<span>✓</span>


</div>


<div class="info">


<p>Atendimento Personalizado</p>


<span>✓</span>


</div>


<div class="info">


<p>Gestão Financeira</p>


<span>✓</span>


</div>


<div class="info">


<p>Prestação de Contas</p>


<span>✓</span>


</div>


</div>


</div>


</section>


<!-- SOBRE -->


<section id="sobre">


    <h2 class="title">Quem Somos</h2>


    <div class="cards">


        <div class="box">


            <h3>Missão</h3>


            <p>
                A SMARTCOM nasceu com o propósito de transformar a gestão
                administrativa e financeira de empresas e condomínios,
                oferecendo soluções inteligentes, transparentes e eficientes.
                Trabalhamos para reduzir burocracias e proporcionar mais
                tranquilidade aos nossos clientes.
            </p>


        </div>


        <div class="box">


            <h3>Visão</h3>


            <p>
                Ser referência em BPO Empresarial e Administração
                Condominial, reconhecida pela excelência no atendimento,
                inovação tecnológica e compromisso com resultados.
            </p>


        </div>


        <div class="box">


            <h3>Valores</h3>


            <p>


                ✔ Transparência<br>
                ✔ Ética<br>
                ✔ Compromisso<br>
                ✔ Organização<br>
                ✔ Tecnologia<br>
                ✔ Atendimento Humanizado


            </p>


        </div>


    </div>


</section>


<!-- SERVIÇOS -->


<section id="servicos">


<h2 class="title">Nossos Serviços</h2>


<div class="cards">


<div class="box">


<h3>🏢 BPO Empresarial</h3>


<p>


• Gestão Financeira<br><br>


• Contas a Pagar e Receber<br><br>


• Fluxo de Caixa<br><br>


• Conciliação Bancária<br><br>


• Emissão de Notas Fiscais<br><br>


• Relatórios Gerenciais


</p>


</div>


<div class="box">


<h3>🏘 Administração Condominial</h3>


<p>


• Prestação de Contas<br><br>


• Gestão Financeira<br><br>


• Emissão de Boletos<br><br>


• Atendimento ao Síndico<br><br>


• Gestão de Assembleias<br><br>


• Gestão de Fornecedores


</p>


</div>


<div class="box">


<h3>🚀 Nosso Diferencial</h3>


<p>


Atendimento personalizado.


<br><br>


Tecnologia aplicada à gestão.


<br><br>


Relatórios claros.


<br><br>


Segurança das informações.


<br><br>


Processos eficientes.


<br><br>


Total transparência.


</p>


</div>


</div>


</section>


<!-- DIFERENCIAIS -->


<section id="diferenciais">


<h2 class="title">
Por que escolher a SMARTCOM?
</h2>


<div class="cards">


<div class="box">


<h3>💼 Gestão Inteligente</h3>


<p>


Utilizamos processos modernos para simplificar a rotina administrativa,
reduzir custos e aumentar a eficiência operacional.


</p>


</div>


<div class="box">


<h3>📈 Transparência</h3>


<p>


Todas as informações financeiras ficam organizadas,
com prestação de contas clara e acompanhamento constante.


</p>


</div>


<div class="box">


<h3>🤝 Atendimento Personalizado</h3>


<p>


Cada cliente possui necessidades diferentes.
Nosso atendimento é próximo, rápido e focado em soluções.


</p>


</div>


<div class="box">


<h3>🔒 Segurança</h3>


<p>


Processos seguros,
controle documental,
confidencialidade
e responsabilidade em todas as operações.


</p>


</div>


<div class="box">


<h3>⚙ Eficiência</h3>


<p>


Automatizamos tarefas administrativas para que empresas e condomínios
tenham mais tempo para focar no que realmente importa.


</p>


</div>


<div class="box">


<h3>📊 Resultados</h3>


<p>


Mais organização.


<br><br>


Mais controle financeiro.


<br><br>


Mais economia.


<br><br>


Mais tranquilidade.


</p>


</div>


</div>


</section>


<!-- ========================= -->
<!-- COMO TRABALHAMOS -->
<!-- ========================= -->


<section id="processo">


    <h2 class="title">Como Trabalhamos</h2>


    <div class="cards">


        <div class="box">
            <h3>1️⃣ Diagnóstico</h3>
            <p>
                Entendemos as necessidades do cliente para oferecer a melhor solução.
            </p>
        </div>


        <div class="box">
            <h3>2️⃣ Planejamento</h3>
            <p>
                Organizamos processos administrativos e financeiros de forma estratégica.
            </p>
        </div>


        <div class="box">
            <h3>3️⃣ Implantação</h3>
            <p>
                Colocamos toda a estrutura em funcionamento com acompanhamento especializado.
            </p>
        </div>


        <div class="box">
            <h3>4️⃣ Gestão Contínua</h3>
            <p>
                Monitoramos resultados e buscamos melhorias constantes para sua empresa ou condomínio.
            </p>
        </div>


    </div>


</section>


<!-- ========================= -->
<!-- NÚMEROS -->
<!-- ========================= -->


<section>


<h2 class="title">
SMARTCOM em Números
</h2>


<div class="cards">


<div class="box" style="text-align:center;">


<h1 class="counter" data-target="100">0</h1>


<p>Clientes Satisfeitos</p>


</div>


<div class="box" style="text-align:center;">


<h1 class="counter" data-target="250">0</h1>


<p>Projetos Concluídos</p>


</div>


<div class="box" style="text-align:center;">


<h1 class="counter" data-target="99">0</h1>


<p>% de Satisfação</p>


</div>


<div class="box" style="text-align:center;">


<h1 class="counter" data-target="24">0</h1>


<p>Suporte Especializado</p>


</div>


</div>


</section>


<!-- ========================= -->
<!-- CHAMADA -->
<!-- ========================= -->


<section>


<div class="box" style="text-align:center;">


<h2 style="font-size:42px;margin-bottom:20px;">


Sua gestão pode ser muito mais eficiente.


</h2>


<p style="font-size:20px;margin-bottom:40px;">


Solicite uma proposta personalizada e descubra como a SMARTCOM
pode transformar a administração do seu negócio ou condomínio.


</p>


<a href="#contato" class="btn primary">


Solicitar Proposta


</a>


</div>


</section>


<!-- ========================= -->
<!-- CONTATO -->
<!-- ========================= -->


<section id="contato">


<h2 class="title">


Entre em Contato


</h2>


<div class="box">


<form>


<input
type="text"
placeholder="Nome"
style="
width:100%;
padding:18px;
margin-bottom:20px;
border:none;
border-radius:10px;
">


<input
type="email"
placeholder="E-mail"
style="
width:100%;
padding:18px;
margin-bottom:20px;
border:none;
border-radius:10px;
">


<input
type="text"
placeholder="Telefone"
style="
width:100%;
padding:18px;
margin-bottom:20px;
border:none;
border-radius:10px;
">


<textarea
placeholder="Como podemos ajudar?"
style="
width:100%;
height:180px;
padding:18px;
border:none;
border-radius:10px;
margin-bottom:25px;
"></textarea>


<button
class="btn primary"
style="
border:none;
cursor:pointer;
">


Enviar Solicitação


</button>


</form>


</div>


</section>


<footer>


<h2 style="margin-bottom:15px;">
SMART<span style="color:#00c48c;">COM</span>
</h2>


<p>


Gestão Inteligente para Empresas e Condomínios


</p>


<br>


<p>


© 2026 SMARTCOM - Todos os direitos reservados.


</p>


</footer>


<script>


const counters=document.querySelectorAll(".counter");


counters.forEach(counter=>{


const update=()=>{


const target=+counter.getAttribute("data-target");


const c=+counter.innerText;


const increment=target/100;


if(c<target){


counter.innerText=Math.ceil(c+increment);


setTimeout(update,20);


}else{


counter.innerText=target;


}


}


update();


});


</script>


</body>


</html>

