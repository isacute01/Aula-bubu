<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Isa Fashion - Loja Online</title>
<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        background-color: #fdf2f8;
    }
   
    header {
        background-color: #d63384;
        color: white;
        padding: 20px;
    text-align: center;
}
 
nav {
    background-color: #ff85c1;
    padding: 10px;
    text-align: center;
}
nav a {
    color: white;
    text-decoration: none;
    margin: 15px;
    font-weight: bold;
}
.banner {
    text-align: center;
    padding: 40px;
    background-color: #ffe3f1;
}
 
.produtos {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    padding: 20px;
}
 
.card {
    background-color: white;
    width: 250px;
    margin: 15px;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    text-align: center;
    padding: 15px;
}
 
.card img {
    width: 100%;
    border-radius: 10px;
}
.preco {
    color: #d63384;
    font-size: 18px;
    font-weight: bold;
}
 
button {
    background-color: #d63384;
    color: white;
    border: none;
    padding: 10px 15px;
    margin-top: 10px;
    border-radius: 5px;
    cursor: pointer;
}
button:hover {
    background-color: #b0256c;
}
 
footer {
    background-color: #d63384;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 30px;
}
</style>
 
<script>
function comprar(produto) {
    alert("Você adicionou " + produto + " ao carrinho!");
}
</script>
 
</head>
 
<body>
 
<header>
    <h1> Isa Fashion</h1>
    <p>Sua loja online favorita</p>
</header>
<nav>
    <a href="#">Início</a>
    <a href="#">Feminino</a>
    <a href="#">Masculino</a>
    <a href="#">Contato</a>
</nav>
<section class="banner">
    <h2>Nova Coleção 2026</h2>
    <p>Peças modernas e estilosas para você arrasar ✨</p>
</section>
 
<section class="produtos">
    <div class="card">
        <img src="https://via.placeholder.com/250x300" alt="Vestido Rosa">
        <h3>Vestido Rosa</h3>
        <p class="preco">R$ 129,90</p>
        <button onclick="comprar('Vestido Rosa')">Comprar</button>
    </div>
    <div class="card">
        <img src="https://via.placeholder.com/250x300" alt="Jaqueta Jeans">
        <h3>Jaqueta Jeans</h3>
        <p class="preco">R$ 199,90</p>
        <button onclick="comprar('Jaqueta Jeans')">Comprar</button>
    </div>
    <div class="card">
        <img src="https://via.placeholder.com/250x300" alt="Conjunto Moletom">
        <h3>Conjunto Moletom</h3>
        <p class="preco">R$ 159,90</p>
        <button onclick="comprar('Conjunto Moletom')">Comprar</button>
    </div>
 
</section>
 
<footer>
    2026 Isa Fashion - Todos os direitos reservados
</footer>
 
</body>
</html>
