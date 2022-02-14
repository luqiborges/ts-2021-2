**Tarefa 005 - 08/02/2022 - Grafo de Causa e Efeito / Tabela de Decisão**

**Aluno:** Lucas Borges de Souza

**Matrícula:** 201802776

**1. Grafo de causa e efeito**

<p align="center">
  <img src="https://i.imgur.com/IYnxEH4.png" width="68%">
</p>

**2. Tabela de Decisão**
      
|Causa|R1|R2|R3|R4|R5|R6|R7|R8|
|--|--|--|--|--|--|--|--|--|
|Sexo| Masculino| Masculino| Masculino| Masculino| Feminino| Feminino| Feminino| Feminino|
|Idade|<25|<25|>25|>25|<25|<25|>25|>25|
|Estado Civil|Solteiro|Casado|Solteiro|Casado|Solteira|Casada|Solteira|Casada|

|Efeito|R1|R2|R3|R4|R5|R6|R7|R8|
|-|-|-|-|-|-|-|-|-|
|Valor do Desconto(%)|0|5|10|15|5|10|15|20|

**3. Casos de teste**
 
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
