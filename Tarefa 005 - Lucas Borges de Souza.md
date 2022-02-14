**Tarefa 005 - 08/02/2022 - Grafo de Causa e Efeito / Tabela de Decisão**

**Aluno:** Lucas Borges de Souza

**Matrícula:** 201802776

1.Considere o seguinte cenário: Uma corretora de seguros concede desconto sobre o prêmio anual de seguro de automóvel, aos seus segurados conforme as regras a seguir:
|Sexo|Idade (anos)|Estado Civil|Desconto (%)|
|---|---|---|---|
|Masculino|< 25|Solteiro|0|0
|Masculino|< 25|Casado|5|
|Masculino|> 25|Solteiro|10|
|Masculino|> 25|Casado|15|
|Feminino|< 25|Solteira|5|
|Feminino|< 25|Casada|10|
|Feminino|> 25|Solteira|15|
|Feminino|> 25|Casada|20|

2. Solicita-se:
   1. Geração do grafo de causa e efeito para representar este cenário.
      
<p align="center">
  <img src="https://imgur.com/IYnxEH4" width="70%"/>
</p>

   2. Geração da tabela de decisão para representar o cenário:
      
|Causa|R1|R2|R3|R4|R5|R6|R7|R8|
|--|--|--|--|--|--|--|--|--|
|Sexo| Masculino| Masculino| Masculino| Masculino| Feminino| Feminino| Feminino| Feminino|
|Idade|<25|<25|>25|>25|<25|<25|>25|>25|
|Estado Civil|Solteiro|Casado|Solteiro|Casado|Solteira|Casada|Solteira|Casada|

|Efeito|R1|R2|R3|R4|R5|R6|R7|R8|
|-|-|-|-|-|-|-|-|-|
|Valor do Desconto(%)|0|5|10|15|5|10|15|20|
   3. Geração do conjunto de casos de teste suficientes para cobrir todos os cenários, constantes do grafo e da tabela de decisão: 
 
|CT|Valores de Entrada|Resultado Esperado|
|--|--|--|
|CT01|**Sexo)** Masculino **Idade)** 19 **Estado Civil)** Solteiro |**Valor Líquido)** R$ 2000,00|
|CT02|**Sexo)** Masculino **Idade)** 20 **Estado Civil)** Casado |**Valor Líquido)** R$ 1900,00|
|CT03|**Sexo)** Masculino **Idade)** 26 **Estado Civil)** Solteiro |**Valor Líquido)** R$ 1800,00|
|CT04|**Sexo)** Masculino **Idade)** 30 **Estado Civil)** Casado |**Valor Líquido)** R$ 1700,00|
|CT05|**Sexo)** Feminino **Idade)** 18 **Estado Civil)** Solteira |**Valor Líquido)** R$ 1900,00|
|CT06|**Sexo)** Feminino **Idade)** 20 **Estado Civil)** Casada |**Valor Líquido)** R$ 1800,00|
|CT07|**Sexo)** Feminino **Idade)** 32 **Estado Civil)** Solteira |**Valor Líquido)** R$ 1700,00|
|CT08|**Sexo)** Feminino **Idade)** 29 **Estado Civil)** Casada |**Valor Líquido)** R$ 1600,00|

   4. Em relação aos casos de teste, considere o valor do seguro de R$ 2.000,00 (Dois mil reais). Desta forma, o valor esperado, do resultado do caso de teste, deve ser o valor líquido a ser pago. Ou seja, o prêmio deduzido do valor correspondente ao percentual do desconto obtido pelo cliente.
   