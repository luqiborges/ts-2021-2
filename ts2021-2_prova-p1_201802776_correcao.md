<div align=center>
  <img src="brasaooficialcolorido.png">
</div>

#### <p style="text-align: center;">Universidade Federal de Goiás</p>
#### <p style="text-align: center;">Instituto de Informática</p>
#### <p style="text-align: center;">Bacharelado em Engenharia de Software</p>
#### <p style="text-align: center;">Teste de Software - 2021/2</p>
#### <p style="text-align: center;">Gilmar Ferreira Arantes</p>
####  <p style="text-align: center;"> Prova P1 - 16/02/2022</p>

Matrícula: 201802776
Nome: Lucas Borges de Souza

<p><font color=green>Nota: 8,0.</font></p>

1. Quanto ao objetivo do Teste de Software, responda as duas questões seguintes:
   1. (**0,5 ponto**) Qual o objetivo primário da atividade de teste de software?
   2. (**0,5 ponto**) O que acontece, quando não se atinge este objetivo primário?

Respostas:
1.1) O objetivo primário da atividade de teste de software é revelar a presença de defeitos. <font color=green>Certo.</font>
1.2) Quando não se atinge este objetivo primário de revelar a presença de defeitos, os softwares podem subir para produção com sua qualidade comprometida, podendo resultar em problemas cada vez maiores, como o comprometimento de setores críticos de um sistema, segurança, entre outros aspectos. <font color=red>Errado.</font>

2. (**1,0 ponto**) Explique o que é o teste exaustivo e porque sua execução não é possível.

Resposta:
2) O teste exaustivo é testar um software com todas as possibilidades de entradas e caminhos possíveis. Por exemplo, em um campo de senha, o teste exaustivo seria testar todas as possibilidades de senha existentes, para testar quais senhas são aceitas ou não de acordo com os critérios de aceitações para ela. Nesse sentido, sua execução não é possível por dois fatores cruciais: o custo de se testar todas as possibilidades de todos os campos de entrada, fluxos e caminhos possíveis é extremamente alto e, por isso, não é vantajoso para as instituições; e, mesmo assim, as possibilidades de todos os possíveis caminhos e fluxos podem ser muito grandes ou até infinitas, tornando-se inviável realizar esta modalidade de teste. <font color=green>Certo.</font>

3. (**1,0 ponto**) Cite pelo menos duas limitações da Técnica de Teste Funcional e duas da Técnica de Teste Estrutural.

Resposta:
3)Como exemplos de limitações da técnica de teste funcional, temos: nenhum conhecimento de como o programa está implementado é exigido, assim, depende de uma boa especificação de requisitos; além disso, não é possível garantir que partes essenciais ou críticas do software sejam executadas. Por outro lado, como exemplos de limitações da técnica de teste estrutural, temos: defeitos podem existir mesmo com o fluxo de controle correto;além disso, um módulo pode executar corretamente para diversos casos de testes e falhar para alguns outros. <font color=green>Certo.</font>

4. (**1,0 ponto**) Descreva pelo menos um dos quatro níveis de teste constantes da literatura especializada.

Resposta:
4)Os testes de integração, que <font color=red>são um</font> dos quatro níveis de teste, possuem o objetivo de verificar se as unidades combinadas trabalham bem como um grupo. Testes de integração visam detectar as falhas na interação entre as unidades dentro dos módulos. Existem 2 abordagens principais para este teste: Métodos de baixo para cima e de cima para baixo. O Teste de integração de baixo pra cima começa com unidades de teste, sucessivamente aumentado a complexidade dos módulos do software sob teste. O método de cima pra baixo usa a abordagem oposta, focando em combinações de alto nível primeiro e examinando as mais simples mais tarde.  <font color=green>Certo.</font>

5. (**1.0 ponto**)Descreva qual o propósito do critério de teste funcional Particionamento por Classes de Equivlência.

Resposta:
5)Este critério propõe a divisão dos domínios de entrada e saída em partições, válidas e inválidas. Tais participações são classificadas como equivalentes; tais classes são equivalentes em relação à capacidade de revelar ou não a presença de defeitos, e, por conseguinte, o objetivo principal desse critério é a redução da quantidade de casos de teste necessários, procurando garantir uma boa cobertura do código do produto em teste. <font color=green>Certo.</font>

6. (**1.00 ponto**) Existe algum tipo de hierarquia em relação aos critérios de teste estrutural, todos os nós, todos os arcos e todos os caminhos? Se sim, explique-a, considerando a perspectiva dos níveis de cobertura desejados.

Resposta:
6)Em relação aos critérios de teste estrutural, existe uma hierarquia que resulta em diversos níveis de cobertura que são definidos em função dos elementos do GFC(Grafo de Fluxo de Controle), isto é, os nós, arcos e caminhos. Sendo assim, os níveis de cobertura dizem respeito à porcentagem dos requisitos que foram testados versus o total de requisitos gerados. Chegando a oito diferentes níveis de cobertura, definidos por Copeland. Quanto maior o nível, maior o rigor do critério de teste, ou seja, mais casos de teste ele exige para ser satisfeito. Desse modo, no nível 0, tem-se: qualquer valor de cobertura inferior a 100% da cobertura de todos os comandos. No nível 1: 100% de cobertura dos comandos. No nível 2: 100% de cobertura de decisões. No nível 3: 100% de cobertura de condições. No nível 4: 100% de cobertura de decisões e condições. No nível 5: 100% de cobertura de condições múltiplas. No nível 6: cobertura de loops. Segue-se esta lógica de aumentar a cobertura conforme se aumentam os níveis, até atingir por fim o nível 7, no qual se tem 100% de cobertura de caminhos. <font color=green>Certo.</font>

7. Considere a especificação, a seguir, de um hipotético programa que objtiva a classificação de um triângulo, a partir dos valores informados para os seus três lados.

   a) Dado um triângulo cujos segmentos medem A, B e C, que são números inteiros positivos na faixa de 0 a 100. Esse triângulo somente existirá se: (A + B < C) ou (A + C < B) ou (B + C < A).
   b) Quanto às medidas dos seus lados o triângulo, poderá ser classicado em:
         • Isósceles = quando possui dois lados com a mesma medida;
         • Escaleno = quando todos os seus lados têm medidas diferentes;
         • Equilátero = quando todos os lados tem a mesma medida;
         • Acutângulo = quando o quadrado de um dos seus lados é menor que a soma do quadrado dois outros dois. (A<sup>2</sup> < B<sup>2</sup> + C<sup>2</sup>).
         • Retângulo: quando o quadrado de um dos seus lados é igual à soma do quadrado dois outros dois. (A<sup>2</sup> = B<sup>2</sup> + C<sup>2</sup>).
         • Obtusângulo: quando o quadrado de um dos seus lados é maior que a soma do quadrado dois outros dois. A<sup>2</sup> > B<sup>2</sup> + C<sup>2</sup>.

7.1 (**2.0 pontos**) Definir uma tabela de decisão para o teste tanto da existência do triângulo, quanto para a definição do seu tipo. Consulte exemplo de tabela de decisão na tarefa 005.

| Causas // Regras ->|R1|R2|R3|R4|R5|R6|R7|R8|R9|
|--|--|--|--|--|--|--|--|--|--|
| (A + B > C) ou (A + C > B) ou (B + C > A)| Não | Sim | Sim | Sim | Sim | Sim | Sim | Sim | Sim |
| A = B| Não | Sim | Sim | Sim | Sim | Não | Não | Não | Não |
| A = C| Não | Sim | Sim | Não | Não | Sim | Sim | Não | Não |
| B = C| Não | Sim | Não | Sim | Não | Sim | Não | Sim | Não |


| Efeitos // Regras -> |R1|R2|R3|R4|R5|R6|R7|R8|R9|
|--|--|--|--|--|--|--|--|--|--|
| Impossível| | | X | X | | X | | | |
| Triângulo Não Existe | X | | | | | | | | |
| Triângulo Isósceles| | | | | X | | X | X | |
| Triângulo Escaleno| | | | | | | | | X |
| Triângulo Equilátero| | X | | | | | | | |

<font color=orange>Parcialmente correto. Nota 1,5.</font>

7.2 (**2.0 pontos**) Criar os conjunto de casos de teste necessários para a cobertura das combinações constantes da tabela de decisão, seguindo o seguinte padrão:
|CT|Lado A|Lado B|Lado C|Resultado|
|---|---|---|---|---|
|CT1| 20 | 15 | 5 | Triângulo Não Existe |
|CT2| 65 | 65 | 65 | Triângulo Isósceles |
|CT3| 20 | 30 | 50 | Triângulo Escaleno |
|CT4| 77 | 77 | 77 | Triângulo Equilátero |

<font color=orange>Parcialmente correto. Os CT2 e CT3, falharam. Nota 1,0.</font>

INSTRUÇÕES:
1. Tipo: Prova individual;
2. Local de Entrega: Plataforma Turing
3. Forma de Entrega: Entregar este arquivo, editado com suas respostas, no formato .md, nominado da seguinte forma: ts2021-2_prova-p1_mat.md, onde mat deverá ser substituído pelo número da sua matrícula.
4. **Entrega diferente da especificada não será avaliada.**
5. Data da Entrega: 22/02/2022, as 23h59min.
6. Critério de Aceitação: arquivo entregue, conforme solicitado.
