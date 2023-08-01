<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    * {
        margin: 0px;
        padding: 0px;
    }
    main {
        margin: auto;
        background-color: rgba(109, 109, 238, 0.61);
        width: 700px;
        height: 400px;
        position: relative;
    }
    div#div-main{
        position: absolute;
        background-color: rgba(0, 0, 0, 0.267);
        width: 650px;
        height: 350px;
        bottom:26px;
        left: 26px;
    }
    h1 {
        margin-top: 10px;
        text-align: center;
        font-family: Arial, Helvetica, sans-serif;
        font-size: 3em;
    }
    h2 {
        padding: 10px 0px 5px 0px;
        color: white;
        box-shadow: 1px 1px 5px rgba(0, 0, 0, 0.404);
        text-shadow: 1px 1px 5px rgba(0, 0, 0, 0.363);
        text-align: center;
        background-color: red;
    }
    div#links {
        text-align: center;
        margin-top: 90px;
    }
    a{
        font-size: 1.2em;
        text-decoration: none;
        color: black;
        text-shadow: 1px 1px 5px rgba(0, 0, 0, 0.116);
    }
    a:hover {
        background-color: rgba(255, 0, 0, 0.342);
        padding: 5px;
        border-top-left-radius: 10px;
        border-top-right-radius: 10px;
        text-decoration: underline;
        color: white;
    }

</style>
<body>
    <main>
        <div id="div-main">
            <h1>Seja Bem vindo !!!</h1>
            <h2>Meus Projetos em HTML5</h2>
            <div id="links">
                <a href="https://github.com/GustavOnX/Projetos/tree/main/Android" target="_blank">Android</a>
                <a href="">|</a>
                <a href="https://github.com/GustavOnX/Projetos/tree/main/Projeto-cordel">Cordel</a>
                <a href="">|</a>
                <a href="https://github.com/GustavOnX/Projetos/tree/main/Redes%20sociais">Redes Socias</a>
            </div>
        </div>
    </main>
</body>
</html>
