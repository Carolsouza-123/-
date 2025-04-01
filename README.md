
border-radius: 5px;
cursor: pointer;
font-size: 16px;
}
button:hover {
background: #b82c6d;
}
</style>
</head>
<body>
<div class="container">
<h2>Digite a senha para ver a mensagem</h2>
<input type="text" id="password" placeholder="DD/MM/AAAA">
<button onclick="checkPassword()">Entrar</button>
<div id="message">
<h3>Feliz aniversário, <span style="font-size: 24px; font-weight: bold;">[Nome]</span>!</h3>
<p>Hoje é um dia especial, e, mesmo com tudo o que aconteceu, eu queria te lembrar o quanto você significa pra mim. Que você tenha um ano cheio de alegrias, conquistas e, acima de tudo, felicidade. Eu sempre vou guardar com carinho os momentos que passamos juntos.</p>
<p style="font-style: italic;">Com todo o meu afeto e gratidão por tudo o que vivemos. ❤️</p>
</div>
</div>

<script>
function checkPassword() {
var input = document.getElementById("password").value;
if (input === "16/03/2024") {
document.getElementById("message").style.display = "block";
setTimeout(function() {
document.getElementById("message").style.opacity = "1";
document.getElementById("message").style.transform = "translateY(0)";
}, 200);
} else {
alert("Senha incorreta. Tente novamente!");
}
}
</script>
</body>
</html>
} else {
alert("Senha incorreta. Tente novamente!");
}
}
</script>
</body>
</html>
