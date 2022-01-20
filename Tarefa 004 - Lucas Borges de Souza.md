
**Tarefa 004 - 19/01/2022 - Análise do Valor Limte - Definição de casos de testes**

**Aluno:** Lucas Borges de Souza

**Matrícula:** 201802776

**Valores Limites para Quantidade de Faltas: 25% e 26%**
**Valores Limites para Média: 2.99, 3.00, 5.99 e 6.00**

**Casos de Teste**
|CT|Valor de Entrada|Resultado Esperado|Classe Equivalência|
|--|--|--|--|
|CT01|**n1)** 2.99 **n2)** 2.99 **cargaHorária)** 100h **faltas)** 25h|Reprovado por Média|CE02, CE03, CE07, CE13|
|CT02|**n1)** 3.00 **n2)** 3.00 **cargaHorária)** 100h **faltas)** 25h|Recuperação|CE02, CE04, CE10, CE14|
|CT03|**n1)** 5.99 **n2)** 5.99 **cargaHorária)** 100h **faltas)** 25h|Recuperação|CE02, CE04, CE10, CE14|
|CT04|**n1)** 6.00 **n2)** 6.00 **cargaHorária)** 100h **faltas)** 25h|Aprovado|CE02, CE05, CE11, CE15|
|CT05|**n1)** 2.99 **n2)** 2.99 **cargaHorária)** 100h **faltas)** 26h|Reprovado por Falta|CE01, CE03, CE06, CE12|
|CT06|**n1)** 3.00 **n2)** 3.00 **cargaHorária)** 100h **faltas)** 26h|Reprovado por Falta|CE01, CE04, CE07, CE12|
|CT07|**n1)** 5.99 **n2)** 5.99 **cargaHorária)** 100h **faltas)** 26h|Reprovado por Falta|CE01, CE04, CE07, CE12|
|CT08|**n1)** 6.00 **n2)** 6.00 **cargaHorária)** 100h **faltas)** 26h|Reprovado por Falta|CE01, CE05, CE08, CE12|

**Obs:** As classes de equivalência estão disponíveis na tarefa #003, neste github.

Onde:
**CT** = Caso de Teste, seguido de um valor sequencial;
**Valor de entrada** é o valor informado para a variável;
**Resultado esperado** é o resultado que se espera da execução da função;
**Classe de Equivalência** é a identificação de qual classe de equivalência está sendo exercitada pelo caso de teste.
