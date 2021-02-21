# Intervalo Tempo Algoritmo


*******
### Links De Trabalhos Similares  

 [USP - Sobre Algoritmos Disjuntos](https://www.ime.usp.br/~pf/analise_de_algoritmos/aulas/intervalos.html)

*******

  >*“O usuário tem uma lista de cadastro de ativadores com datas, seus ativadores devem se ativar respectivamente nas datas em que estão marcados, através da seguinte lógica, a data do respectivo modulo só irá se ativar por manifestação do usuário e caso seu intervalo de tempo não esteja conflitando com nenhum outro, do contrário ela irá desativar o modulo que estiver conflitando com sua data, partindo do seguinte principio lógico, que ela deve desativar tudo que estiver dentro de seu intervalo de tempo (intervalo Y) > (começo do intervalo_local) && (fim do intervalo_local) < (intervalo X) { desativar XY },  o problema é que tudo que for maior que o intervalo de Y será desativado, inclusivo o próprio intervalo X e o intervalo de Y também será desativado pela condição de X, pois a regra imposta é que tudo que for menor ou maior que estes intervalos vão ser desativados, mas vamos basear no principio hipotético e fantasioso de que o intervalo sabe que deve respeito XY, devemos manter ativos tudo que estiver foram do intervalo de X e Y, o único problema é que o tempo é uma variável que tende ao infinito em ambas extremidades do seu intervalo, com apenas um ponto de referência extremamente oscilante, então de forma básica para manter ativadas outras dependências locais do intervalo_local, por exemplo o intervalo_local2, devemos considerar que todos os demais intervalos que foram maiores que (intervalo Y) < (começo do intervalo_local) && (fim do intervalo_local) > (intervalo X) {ativar XY}, se a condição trabalha-se com apenas duas variáveis de intervalo_local, séria relativamente fácil resolver o problema, o problema dela lidar com mais duas variáveis é que a variável de intervalo XY são genéricas, podendo estas receber absolutamente qualquer valor imposto pelo usuário, e pelo fato delas serem genéricas e trabalharem com valores definidos de tempo, mas com a inserção de valores indefinidos pelo usuário, ela poderá ou não respeitar a condição, você possuem  quatro condições apenas para estabelecer um intervalo, em uma fração que podem trabalhar com inúmeras condições de intervalo, por exemplo, você pode terminar um intervalo do dia 20 ao dia 25 e do dia 26 ao dia 28, para isso teria que ter módulos para separar estes intervalos como por exemplo (D1 >< D2) (D3 >< D4), esta é sua para determinar um intervalo com números conhecidos, mas agora vamos tratar do problema com as mesmas variáveis, é uma infinidade de possibilidades, D1 >< D2 && D3 >< D4 , temos aqui uma nova condição, porque está também poderia ser D1 > D3 && D1 < D4, assim como D2 < D3 e D2>4, quando temos condições determinadas e predeterminadas, podemos ditar as normas que vão ser atribuídas as condições especificas, agora quando não temos a condição, mas temos a determinação genérica e autoadaptação as diferentes circunstancias, teremos inúmeras possibilidades, provavelmente tão infinitas que podem ser impossíveis de determinar em uma expressão .”*  


![](https://github.com/joomoraes/Intervalo_Tempo_Algoritmo-/blob/main/Iinterval.jpg?raw=true)  
