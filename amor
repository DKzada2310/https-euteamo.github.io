<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<title>Para Raiany ❤️</title>
<style>
    body {
        margin: 0;
        font-family: "Verdana", sans-serif;
        background: linear-gradient(135deg, #ff7eb9, #ff65a3, #ff9dcb);
        color: white;
        text-align: center;
    }

    .container {
        display: none;
        padding: 40px;
        animation: fade 0.6s ease;
    }

    @keyframes fade {
        from { opacity: 0; }
        to { opacity: 1; }
    }

    h1 {
        font-size: 48px;
        margin-bottom: 10px;
        text-shadow: 0 0 10px #fff;
    }

    h2 {
        font-size: 30px;
    }

    button {
        background: #ff4f8b;
        border: none;
        padding: 12px 30px;
        margin-top: 20px;
        border-radius: 20px;
        font-size: 22px;
        color: white;
        cursor: pointer;
        transition: 0.3s;
    }

    button:hover {
        transform: scale(1.1);
        background: #ff2c75;
    }

    .option {
        background: #ff82b4;
        padding: 10px 20px;
        font-size: 20px;
        border-radius: 15px;
        cursor: pointer;
        margin: 10px auto;
        max-width: 250px;
        transition: 0.2s;
    }

    .option:hover {
        background: #ff5f9e;
        transform: scale(1.05);
    }

    .hidden {
        display: none;
    }

    input {
        padding: 10px;
        border-radius: 10px;
        border: none;
        margin-top: 10px;
        font-size: 18px;
        text-align: center;
    }

</style>
</head>
<body>

<!-- INTRODUÇÃO -->
<div class="container" id="topico1" style="display:block;">
    <img src="https://media.tenor.com/1n32dMF_SJMAAAAi/pink-heart.gif" width="200">
    <h1>RAIANY ❤️</h1>
    <h2>Responda com carinho e leia tudo o que tenho para dizer.</h2>

    <br><br>

    <p>🔒 Digite a senha para visualizar as respostas (apenas você):</p>
    <input type="password" id="senha" placeholder="Senha">
    <button onclick="verRespostas()">Ver respostas</button>

    <br><br>

    <button onclick="irPara('topico2')">&lt;3</button>
</div>


<!-- TÓPICO 2 -->
<div class="container" id="topico2">
    <img src="https://media.tenor.com/pkQ6f0GO6V0AAAAC/cat-smile.gif" width="200">
    <h2>Vamos começar pela pergunta mais simples</h2>
    <h3>Você ainda me tem em seu coração?</h3>

    <div class="option" onclick="salvarResposta('Você ainda me tem em seu coração?', 'Sim', 'btn2')">Sim</div>
    <div class="option" onclick="salvarResposta('Você ainda me tem em seu coração?', 'Não', 'btn2')">Não</div>
    <div class="option" onclick="salvarResposta('Você ainda me tem em seu coração?', 'Talvez', 'btn2')">Talvez</div>

    <button id="btn2" class="hidden" onclick="irPara('topico3')">Continuar</button>
</div>


<!-- TÓPICO 3 -->
<div class="container" id="topico3">
    <img src="https://media.tenor.com/5zxubUANe0sAAAAC/cat-thinking.gif" width="200">
    <h2>Você acha que não tenho possibilidades de melhorar?</h2>

    <div class="option" onclick="salvarResposta('Posso melhorar?', 'Sim', 'btn3')">Sim</div>
    <div class="option" onclick="salvarResposta('Posso melhorar?', 'Não', 'btn3')">Não</div>
    <div class="option" onclick="salvarResposta('Posso melhorar?', 'Não sei', 'btn3')">Não sei</div>

    <button id="btn3" class="hidden" onclick="irPara('topico4')">Continuar</button>
</div>


<!-- TÓPICO 4 -->
<div class="container" id="topico4">
    <img src="https://media.tenor.com/v5E9OQj1v1oAAAAC/cat-sad.gif" width="200">
    <h2>
        Sei que parece bobo tudo isso, mas quero mostrar que estou arrependido de verdade Raiany,
        não tem outro alguém no mundo que está mais envergonhado do que eu por tudo que disse a você.
        Eu falei a coisa mais absurda para mulher que amo e sei o quão difícil é acreditar em mim.
    </h2>

    <button onclick="irPara('topico5')">Continuar</button>
</div>


<!-- TÓPICO 5 -->
<div class="container" id="topico5">
    <img src="https://media.tenor.com/XpR2ymlk4nEAAAAC/dance-cat.gif" width="200">
    <h2>Acha que nunca poderá pensar mais em nós?</h2>

    <div class="option" onclick="salvarResposta('Pensar em nós?', 'Sim', 'btn5')">Sim</div>
    <div class="option" onclick="salvarResposta('Pensar em nós?', 'Não', 'btn5')">Não</div>
    <div class="option" onclick="salvarResposta('Pensar em nós?', 'Não sei', 'btn5')">Não sei</div>
    <div class="option" onclick="salvarResposta('Pensar em nós?', 'Talvez', 'btn5')">Talvez</div>

    <button id="btn5" class="hidden" onclick="irPara('topico6')">Continuar</button>
</div>


<!-- TÓPICO FINAL -->
<div class="container" id="topico6">
    <img src="https://media.tenor.com/7XjH9Muqux4AAAAC/love-cat.gif" width="200">
    <h2>
        Fiz isso apenas para descontrair, você precisa saber que além de mim, tem pessoas que te amam muito
        e querem seu bem. Você é uma mulher incrível e você sabe disso. Não quero desistir de você Raiany
        e como te falei, vou fazer de tudo, até você dizer na minha cara que não me ama mais e que não quer
        mais me ver. Nesse momento eu irei me retirar e com certeza ficarei triste, mas não pense na minha
        tristeza: é seu dever seguir sua vida, assim como eu. Mas pense com a razão, mas não esqueça o coração.
    </h2>
</div>


<!-- SISTEMA DE RESPOSTAS -->
<div class="container" id="respostas">
    <h1>Respostas da Raiany 💖</h1>
    <p id="lista"></p>
</div>


<script>
// Trocar de tópico
function irPara(id) {
    document.querySelectorAll('.container').forEach(c => c.style.display = 'none');
    document.getElementById(id).style.display = 'block';
}

// Salvar respostas no LocalStorage
function salvarResposta(pergunta, resposta, botaoID) {
    let dados = JSON.parse(localStorage.getItem("respostasRaiany") || "[]");

    dados.push({ pergunta, resposta });

    localStorage.setItem("respostasRaiany", JSON.stringify(dados));

    document.getElementById(botaoID).classList.remove("hidden");
}

// Ver respostas (senha: Vida)
function verRespostas() {
    const senha = document.getElementById("senha").value;

    if (senha !== "Vida") {
        alert("Senha incorreta!");
        return;
    }

    let dados = JSON.parse(localStorage.getItem("respostasRaiany") || "[]");

    let html = "";
    dados.forEach(r => {
        html += `<p><b>${r.pergunta}</b><br>Resposta: ${r.resposta}</p><hr>`;
    });

    document.getElementById("lista").innerHTML = html || "Nenhuma resposta ainda.";

    irPara("respostas");
}
</script>

</body>
</html>
