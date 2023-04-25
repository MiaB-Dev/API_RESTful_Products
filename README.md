<h1>Projeto de uma API RESTful de um sistema de produtos usando Spring Data JPA </h1>
<p> Repositório contendo uma API RESTful de nível 3 da maturidade de Richardson. A API permite ler, inserir, atualizar e deletar produtos (cada produto tem um nome e um valor) de um banco de dados PostgreSQL.<br>





<h2>🛠 Tecnologias Utilizadas</h2>

<ul>
    <li>VS Code</li>
    <li>Java 11</li>
    <li>Maven</li>
    <li><strong>Spring Web</strong></li>
    <li><strong>Spring Data JPA</strong></li>
    <li><strong>PostgreSQL Driver</strong></li>
    <li><strong>Hibernate Validator</strong></li>
    <li>Lombok</li>
    <li>Postman</li>
</ul>

<h2>Rotas</h2>
<h3>/products</h3>
<ul>
<li>via GET: lista todos os produtos cadastrados</li>
<li>via POST: cadastra um novo produto </li>
</ul>
<h3>/products/{id}</h3>
<ul>
<li>via GET: lista o produto com id {id}</li>
<li>via PUT: atualiza os dados do produto com id {id}</li>
<li>via DELETE: deleta o produto com id {id}</li>
</ul>




