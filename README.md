1. tengo 2 clases Calculadora y CarroCompra
   Calculadora es una clase simple cuyo proposito es realizar operaciones aritmeticas basicas (sumas y multiplicaciones)
   CarroCompra como us nombre indica esta clase hace referencia a un carro de compras doonde llevas productos ves la cantidad y precvios y calcula el valor de la compra
   El contexto es calcular un costo total de un carro de compras y usamos 2 clases por la responsabilidad unica de clase

2. atributos Calculadora
   n1 y n2 ambos son privados y enteros
   metodos Calculadora
   Calculadora() constructor vacio inicia con los valores en 0
   Calculadora(int num1, int num2) constructor que inicia con valores dados
   Sumar() devuelve la suma de 2 enteros
   multiplicar() devuelve la multiplicacion de 2 enteros
   setN1(int num1) setea el n1 le da un valor
   setN2(int num2) setea el n2 le da un valor

   atributos CarroCompra
   productos que es privado y entero [][]
   metodos CarroCompra
   CarroCompra() es un array predefinido donde el primer valor es cantidad y el segundo precio y definimos cantidad como 1 y precio como mil de 5 preoductos
   calcularTotal() itera los productos usando el metodo de subTotal
   subTotal() llama la clase calculadora para calcular precio*cantidad
   mostrarTotal() imprime un texto y nos da el resultado de calcularTotal

    y estas tienen una relacion de dependencia nunidireccional donde la clase CarroCompra depende directamente de Calculadora
   
<img width="1449" height="480" alt="image" src="https://github.com/user-attachments/assets/d5fb6559-4043-4c8e-aeb9-4692b034b536" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5f786c64-5370-47fa-8dd6-2aa67961df95" />
