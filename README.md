Html=
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!--GOOGLE FONTS-->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">family=Poppins:ital,wght@1,900&display=swap" rel="stylesheet">


    <!--FIM GOOGLE FONTS-->
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="" class="css">
    <!-- GOOGLE FONTS-->
    <title>Agencia BRN</title>
</head>
<body>


    <header>
        <div class="interface">
            <div class="logo">
                <a href="#">
                    <img src="https://img.freepik.com/fotos-premium/fundo-vibrante-de-ilustracao-de-abobora_905683-137538.jpg" width="100px" alt="">
                </a>


            </div><!--logo-->


            <nav class="menu-desktop">
                <ul>
                    <li><a href="#">Inicio</a></li>
                    <li><a href="#">Especialidade</a></li>
                    <li><a href="#">Sobre</a></li>
                    <li><a href="#">projetos</a></li>
                </ul>
            </nav>


            <div class="btn-contato">
                <a href="#">
                    <button>Contato</button>
                </a>


            </div><!--btn-contato-->
        </div><!--interface-->
    </header>
    <main>
        <selection class="topo-do-site">
            <div class="interface">
                <div class="flex">
                    <div class="txt-topo-site">
                        <h1>JUCIVALDO VALE<span>.</span></h1>
                        <p>Sejam Bem-vindos, Destaco minha expertise em meu rapido aprendizado, nos quais desenvolvi competências sólidas e obtive resultados significativos. Ao longo do tempo, também aprimorei minhas habilidades de comunicação e trabalho em equipe, reconhecendo a importância da colaboração para o alcance de resultados excepcionais.</p>
                        <div class="btn-contato">
                            <a href="#">
                                <button>Entre em contato</button>
                            </a>
                        </div>
                    </div><!--txt-topo-site-->


                    <div class="img-topo-site">
                        <img src="https://img.freepik.com/vetores-premium/ilustracao-de-abobora-bruxa_101717-201.jpg?size=626&ext=jpg" alt="">


                </div>
            </div><!--interface-->
        </selection>
    </main>
</body>
</html>




style.css=
/*ESTILO GERAL*/
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Poppins", sans-serif;
}


body{
    background-color: black;
    height: 100vh;
}


.interface{
    max-width: 1280px;
    margin: 0 auto;
}
.flex{
    display: flex;
}


/* ESTILO DO CABEÇALHO*/
header{
    padding: 40px 4%;
}
header > .interface{
    display: flex;
    align-items: center;
    justify-content: space-between;
}


header a{
    color:#5c5c5c;
    text-decoration: none;
    display: inline-block;
    transition: .6s;
}
header a:hover{
    color:#fff;
    transform: scale(1.5);
}
header nav ul{
    list-style-type: none;
}


header nav ul li{
    display: inline-block;
    padding: 0 40px;
}
.btn-contato button{
    padding: 10px 40px;
    font-size: 18px;
    font-weight: 600;
    background-color: #00ff08;
    border: 0;
    border-radius: 30px;
    cursor: pointer;
    transition: .6s;


}
.btn-contato button:hover{
    box-shadow: 0px 0px 8px #00ff08;
    transform:scale(1.05);
}


/*ESTILO DO TOPO DO SITE*/


section.topo-do-site{
    padding:40px 4%;
}


section.topo-do-site.flex{
    align-content: center;
    justify-content: center;
    gap: 90px;
}


.topo-do-site h1{
    color:#fff;
    font-size: 42px;
    line-height: 40px;
}


.topo-do-site .txt-do-site h1 span{
    color:#00ff08;
    font-size: 60;
}


.topo-do-site .txt-do-site p{
    color: #fff;
    margin: 40px 0;
}




.topo-do-site .img-topo-site


@keyframes flutuar{
    0%{
        top: 0;
    }
    100%{
        top: 30px;
    }
}



