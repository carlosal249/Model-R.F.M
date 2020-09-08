<h1 align='center'>Modelo-R.F.M</h1>
<h2>A ideia principal do projeto e promover um mapeamento detalhado da nossa base de clientes</h2>

<p>Mas porque isso importa?, Porque gastar tempo com isso?</p>
<p>
Uma analise detalhada da nossa carteira de dados revela quais sao os clientes mais importantes e quais clientes sao mais 
ativos e evitar perdelos e essencial para manter o negocio forte assim como entender se temos clientes com potenciais Expansões
</p>
<p>
Realizei uma analise RFM, Recencia, Frequencia e Valor monetario,com a ajuda de machine learning para agrupar os clientes e atribuir uma nota final que 
chamei de 'Pontuacao', e os valores variam com base nos tres fatores que estamos analisando</p>
<br>
<ul>
  <li>0-3 para recencia, onde quanto menor a recencia, maior a nota!</li>
  <li>0-3 para a frequencia, onde quanto maior a frequencia de compras, maior a nota</li> 
  <li>0-3 valor de gasto, onde quanto maior o gasto em produtos, maior a nota</li>
</ul>

<br>
<p>
e ao final da analise a base foi dividida em 4 grupos:
</p>
<ul> 
  <li>pontuacao = 0  Inativo</li>
  <li>pontuacao >= 1 Bussines</li>
  <li>Pontuacao >= 3 Master</li>
  <li>Pontuacao >= 5 Premium</li>
</ul>
<br>

![Main](https://github.com/carlosal249/Model-R.F.M/blob/master/analise_segmentos.png)

<p> E podemos concluir que o modelo funcionou bem, após plotarmos os grupos X Compras(media) fica clara a diferença entre os grupos!<p>

![Main](https://github.com/carlosal249/Model-R.F.M/blob/master/analise_anual_premium.png)

<p></p>

![Main](https://github.com/carlosal249/Model-R.F.M/blob/master/analise_anual_bussines.png)

<p>Conseguimos tabem quantificar o valor de cada grupo ao  nosso negocio: </p>

|       | Receita | Recencia | Frequencia |
| ---   |     ---   |    ---  |  ---   |
| Inativo	|202.075 | 490.10 |	1.28    |
| Bussines|265.552 | 260.83 |	1.63    |
| Master  |486.284 | 80.904 |  2.25   |
| Premium	|11374.9 |	112.45 |	12.00 |

<sub>Valores agrupados pela media</sub>

