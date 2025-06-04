<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Favoritos</title>
</head>
<body>
    <center>
        <h1>Seleção de cantores</h1>
        <script>
            //criar uma variavel
            var opcao = parseInt(prompt(`Seu componente escolhido é: 
            1 - Lana del Rey
            2 - The Wekeend
            3 - Kali Uchis 
            4 - Doja Cat
            5 - Marina 
            6 - Gwen Stefanie`))
        switch(opcao) {
            case 1:
            document.write("Seu cantor escolhido é: Lana del Rey")
            break;
            case 2:
            document.write("Seu cantor escolhido é: The wekeend")
            break;
            case 3:
            document.write("Seu cantor escolhido é: Kali Uchis")
            break;
            case 4:
            document.write("Seu cantor escolhido é: Doja Cat")
            break;
            case 5:
            document.write("Seu cantor escolhido é: Marina")
            break;
            case 6:
            document.write("Seu cantor escolhido é: Gwen Stefanie")
            break;
            default:
            document.write("Opção inválida")
        }
        </script>
    </center>
</body>
</html>
