

<!DOCTYPE html>
<html lang="br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chamados</title>
    <link   rel="stylesheet" href="css/styles.css">
</head>
<body>
    <div class="box">
        <form action="">
            <fieldset>
                <legend> <B>ABERTURA DE CHAMADOS</B></legend> <BR>
    <div class="inputbox">
        <input type="text" name="nome" id="nome" class="inputuser" required>
    <label for="nome"> NOME COMPLETO</label>
    </div> <BR><BR>

    <div class="inputbox">
        <input type="text" name="secretaria" id="secretaria" class="inputuser" required>
         <label for="nome"> SECRETARIA</label>
    </div> <BR><BR>

    <div class="inputbox">
        <input type="text" name="setor" id="setor" class="inputuser" required>
        <label for="nome"> SETOR / SALA</label>
    </div> <BR><BR>
        <div class="inputbox">
        <input type="text" name="ramal" id="ramal" class="inputuser" required>
        <label for="nome"> RAMAL</label>
    </div> <BR><BR>
        <div class="inputbox">
        <input type="text" name="patrimonio" id="patrimonio" class="inputuser" required>
        <label for="nome"> PATRIMONIO DA MAQUINA</label>
    </div> <BR><BR>
    <div class="inputbox">
        <input type="text" name="ip" id="ip" class="inputuser" required>
        <label for="ip"> IP DO COMPUTADOR</label>
    </div> <BR><BR>

    <p> TIPO DE CHAMADO</p>
    <input type="radio" name="tipo" value="hardware" required>  
    <label for="hardware" > HARDWARE</label>
    <input type="radio" name="tipo" value="software" required>  
    <label for="software" >SOFTWARE</label>
    <input type="radio" name="tipo" value="outro" required>  
    <label for="outro" > OUTRO</label> <BR><BR>

        <div class="inputbox">
            <input type="text" name="motivo" id="motivo" class="inputuser" required>
            <label for="motivo"> MOTIVO DO CHAMADO</label>
        </div> <BR><BR>
        <input type="submit" name="submit" id="submit">




            </fieldset>
        </form>



    </div>
    
</body>
</html>
