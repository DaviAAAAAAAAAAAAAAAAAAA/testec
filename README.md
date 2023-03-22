# testec
me da doi real ae parça

<!DOCTYPE html>
<html lang="pt-BR">
    <head>
        <meta charset="utf-8">
        <title>Página com cálculos</title>
        <script>
            var num1 = 50;
            var num2 = 30;

            if (num1 == num2){
                alert("Os números são iguais");
            }else{
                alert("Os números são diferentes");
            }

            function escreveNome(){
                console.log("Técnico em Informática");
            }
            escreveNome();

            function converterTemp(celsius){
                var fah = (celsius * 1.8) + 32;
                return fah;
            }

            var fahreinheit = converterTemp(30);
            console.log(fahreinheit);

            function calcular(){
                return Math.round(200/30);
            }
            var diaria = calcular();
            alert(diaria);

            function calcular2(salario){
                return Math.round(salario/30);
            }
            var diaria = calcular2(8000);
            alert(diaria);

            function calcular3(salario,dias){
                return Math.round(salario/dias);
            }
            var diaria = calcular3(8000/22);
            alert(diaria);
           
       </script>

    </head>
    <body>
        
    </body>
</html>
