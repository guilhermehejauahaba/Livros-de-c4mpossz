# Livros-de-c4mpossz
Site Sobre livres
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Livraria Digital</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>📚 Livraria Digital</h1>
    <p>Livros físicos e e-books</p>
</header>

<main class="produtos">

    <div class="produto">
        <h2>O Poder do Hábito</h2>
        <p>Tipo: Livro físico</p>
        <span>R$ 49,90</span>
        <button onclick="adicionarCarrinho('O Poder do Hábito', 49.90)">Comprar</button>
    </div>

    <div class="produto">
        <h2>Harry Potter (E-book)</h2>
        <p>Tipo: E-book</p>
        <span>R$ 29,90</span>
        <button onclick="adicionarCarrinho('Harry Potter E-book', 29.90)">Comprar</button>
    </div>

    <div class="produto">
        <h2>Manual de Logística</h2>
        <p>Tipo: Livro físico</p>
        <span>R$ 59,90</span>
        <button onclick="adicionarCarrinho('Manual de Logística', 59.90)">Comprar</button>
    </div>

</main>

<section class="carrinho">
    <h2>🛒 Carrinho</h2>
    <ul id="listaCarrinho"></ul>
    <p>Total: R$ <span id="total">0.00</span></p>
</section>

<script src="script.js"></script>
</body>
</html>
