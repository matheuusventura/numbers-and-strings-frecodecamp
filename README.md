# 🌎🖥 Criando um algoritmo de validação de Luhn (Fórmula de Luhn) em Python

Aprendendo a trabalhar com numbers e strings em Python criando um algoritmo de validação conhecido como 'Luhn algorithm', durante o curso Scientific Computing with Python da freecodecamp.org.
<br>
<br>
🗣️ [portuguese](https://web.whatsapp.com/) - [english](https://github.com/matheuusventura/numbers-and-strings-freecodecamp/blob/master/README-english.md) - [spanish](https://web.whatsapp.com/)
<h3>O que é Algoritmo de Luhn?</h3>
Algoritmo de Luhn (ou Fórmula de Luhn) é um método simples utilizado para verificar a validade de números de identificação tais como como números de cartões de crédito, números de IMEI de celulares, números de segurança social (em alguns países), entre outros.
<br>
<h3>Como funciona?</h3>
<ol>
  <li>O algoritmo começa invertendo a ordem dos dígitos do número original.<br></li>
  <li>Então os dígitos em posições ímpares (considerando a nova ordem) são somados diretamente enquanto os dígitos em posições pares são multiplicados por 2. Se a multiplicação resultar em um número maior ou igual a 10, os dígitos do resultado são somados individualmente (por exemplo, 12 se torna 1 + 2 = 3).<br></li>
  <li>O algoritmo verifica se a soma total dos dígitos (após as operações acima) é um múltiplo de 10.</li>
</ol>
<br>
Caso o número não seja múltiplo de 10, o algoritmo nos retorna ´INVÁLIDO!´, caso contrário temos ´VÁLIDO!´ como retorno.
<hr>
<h4>👋😆 Essa foi minha segunda etapa do curso da freecodecamp, estarei publicando e explicando todos os projetos e minha progressão durante o andamento.</h4>
