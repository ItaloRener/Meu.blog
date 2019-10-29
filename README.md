# Meu.blog
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <link rel="stylesheet" href="stylo/estilo.css">
</head>

<body>
    <div id="navegacao">
        <div class="container">
            <div class="logo">
                <span class="verde">My</span>Blog</div>
            <div class="menu">
                <a href="">Home</a>
                <a href="">Games</a>
                <a href="">Apps</a>
                <a href="">Eletronicos</a>
            </div>
        </div>
    </div>
    <div id="conteudo">
        <div class="noticia">
            <div>
                <h2 class="verde">Titulo da Postagem</h2>
                <span class="data-postagem">Postado em 20/20/2019</span>
            </div>
            <div>
                <img src="img/imagem1.png" class="imagem">
                <p class="texto">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio ut similique hic in error dignissimos
                    perspiciatis, illo, corporis facere magnam eum, totam qui repellat culpa dolore facilis neque
                    deleniti sed.
                    Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nulla, odit autem iure dicta nobis, vitae
                    minus natus veritatis nam iusto assumenda, voluptate saepe nostrum dolore sequi cumque? Placeat,
                    provident non.
                </p>
            </div>
            <div class="autor">
                Postado por Abraão Brito
            </div>
        </div>
        <div class="noticia">
            <div>
                <h2 class="verde">Titulo da Postagem</h2>
                <span class="data-postagem">Postado em 20/20/2019</span>
            </div>
            <div>
                <img src="img/imagem1.png" class="imagem">
                <p class="texto">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio ut similique hic in error dignissimos
                    perspiciatis, illo, corporis facere magnam eum, totam qui repellat culpa dolore facilis neque
                    deleniti sed.
                    Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nulla, odit autem iure dicta nobis, vitae
                    minus natus veritatis nam iusto assumenda, voluptate saepe nostrum dolore sequi cumque? Placeat,
                    provident non.
                </p>
            </div>
            <div class="autor">
                Postado por Autor Desconhecido
            </div>
        </div>
        <div class="noticia">
            <div>
                <h2 class="verde">Titulo da Postagem</h2>
                <span class="data-postagem">Postado em 20/20/2019</span>
            </div>
            <div>
                <img src="img/imagem2.png" class="imagem">
                <p class="texto">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio ut similique hic in error dignissimos
                    perspiciatis, illo, corporis facere magnam eum, totam qui repellat culpa dolore facilis neque
                    deleniti sed.
                    Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nulla, odit autem iure dicta nobis, vitae
                    minus natus veritatis nam iusto assumenda, voluptate saepe nostrum dolore sequi cumque? Placeat,
                    provident non.
                </p>
            </div>
            <div class="autor">
                Postado por Autor Desconhecido
            </div>
        </div>
        <div class="noticia">
            <div>
                <h2 class="verde">Titulo da Postagem</h2>
                <span class="data-postagem">Postado em 20/20/2019</span>
            </div>
            <div>
                <img src="img/imagem3.png" class="imagem">
                <p class="texto">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio ut similique hic in error dignissimos
                    perspiciatis, illo, corporis facere magnam eum, totam qui repellat culpa dolore facilis neque
                    deleniti sed.
                    Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nulla, odit autem iure dicta nobis, vitae
                    minus natus veritatis nam iusto assumenda, voluptate saepe nostrum dolore sequi cumque? Placeat,
                    provident non.
                </p>
            </div>
            <div class="autor">
                Postado por Autor Desconhecido
            </div>
        </div>
        <div class="noticia">
            <div>
                <h2 class="verde">Titulo da Postagem</h2>
                <span class="data-postagem">Postado em 20/20/2019</span>
            </div>
            <div>
                <img src="img/imagem4.png" class="imagem">
                <p class="texto">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio ut similique hic in error dignissimos
                    perspiciatis, illo, corporis facere magnam eum, totam qui repellat culpa dolore facilis neque
                    deleniti sed.
                    Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nulla, odit autem iure dicta nobis, vitae
                    minus natus veritatis nam iusto assumenda, voluptate saepe nostrum dolore sequi cumque? Placeat,
                    provident non.
                </p>
            </div>
            <div class="autor">
                Postado por Autor Desconhecido
            </div>
        </div>
    </div>
</body>

</html> 


##CSS
*{
    margin: 0px;
    padding: 0px;
    font-family:'Courier New', Courier, monospace;
}
body{
    background: rgb(214, 214, 214);
}
a{
    text-decoration: none;
    
    padding: 10px;
    border-radius: 9px;
    border: solid 1px;
    transition: 1s;
}
a:visited{
    background: white;
    color: black;
}
a:link{
    color: white;
    background: black;
}
a:hover{
    color: white;
    background:black;
}
#navegacao{
    background: white;
    width: 100%;
    border-bottom: 1px solid grey;
    position: fixed;
    top: 0px;
    left: 0px;
}
#conteudo{
    width: 100%;
    margin-top: 80px;
}
.noticia{
    width: 80%;
    background: white;
    margin: auto;
    margin-bottom: 10px;
}
.data-postagem{
    font-size: 13px;
}
.imagem{
    float: left;
    margin: 10px;
}
.autor{
    margin: 5px 3px 3px 3px;
    padding: 2px;
    font-size: 13px;
    border-left: 3px solid grey;
}
.container{
    width: 90%;
    height: 60px;
    line-height: 60px;
    margin: auto;
}
.texto{
    text-align: justify;
    margin-right: 10px;
    margin-left: 10px;
    
}
.logo{
    float: left;
    font-size: 30px;
    font-weight: bold;
    transition: 1s;
}
.menu{
    float: right;
}
.verde{
    color:rgb(120, 180, 29);
}

