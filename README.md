<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JobFinder</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.4/css/all.css" integrity="sha384-DyZ88mC6Up2uqS4h/KRgHuoeGwBcD4Ng9SiP4dIRy0EXTlnuz47vAwmeGwVChigm" crossorigin="anonymous"/>

</head>
<body>
    <div class="container"><!-- definicao de largura máxima -->
        <header><!-- cabecalho -->
            <nav class="nav-container"><!-- barra de navegação -->
                <img id = logo src="img/logo.png" alt="JobFinder"><!-- imagem da logo -->
                <ul><!-- menu da barra de navegação -->
                    <li><a href="#">Encontrar vaga</a></li>
                    <li><a href="#">Enviar vaga</a></li>
                    <li><a href="#">Contato</a></li>
            <div id="main-banenr"><!-- inclução de CSS -->
                <div id="search-form"><!-- Formulario pesquisa de vaga -->
                     <h1>A maneira mais fácil de encontrar seu novo emprego</h1>
                     <p>Conecte -se de forma gratuita as melhores empresas e consigo o emprego dos seus sonhos</p>
                    <form><!-- formulario sem action pois falta back-end -->
                        <input type="text" name="job" placeholder="Digite o cargo"><!-- inputar o  cargo-->
                        <select name="region" id=""><!-- escolher o estado -->
                            <option value="">Todos os estados</option><!-- caso ele queira pesquisar em todos os estados -->
                        </select>
                        <select name="category" id="">
                            <option value="">Categoria</option><!-- Para servir de estilização -->
                            <input type="submit" value="pesquisar"> 
                        </select>
                    </form>
                </div>
            </div>
        </header>
        
    </div>
</body>
</html>
