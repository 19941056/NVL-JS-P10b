# NVL-JS-P10b
números aleatorios

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Números aleatorios</title>
</head>
<body>
    <script>
        var impares=[], pares=[];
        for(var i= 0; i<50;i++){
            var numero= Math.floor(Math.random() *100);
            if (numero%2==0)
            pares.push(numero);
            else
            impares.push(numero);
            console.log(numero);

        }
        
    </script>
    
</body>
</html>
