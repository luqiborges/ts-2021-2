<div align=center>
  <img src="brasaooficialcolorido.png">
</div>

#### <p style="text-align: center;">Universidade Federal de Goiás</p>
#### <p style="text-align: center;">Instituto de Informática</p>
#### <p style="text-align: center;">Bacharelado em Engenharia de Software</p>
#### <p style="text-align: center;">Teste de Software - 2021/2</p>
#### <p style="text-align: center;">Gilmar Ferreira Arantes</p>
####  <p style="text-align: center;"> Prova P2 - 12/04/2022</p>

Matrícula: 201802776

Nome: Lucas Borges de Souza

<font color="green">Nota 7,8</font>

1. Quanto ao Processo de Teste de Software, responda as duas questões seguintes:
   1. (**0,5 ponto**) Defina os seguintes conceitos Processo de Teste de Software, Projeto de Teste de Software e Plano de Teste de Sofware.

    Resposta:
    - O Processo de Teste de Software consiste na <font color="red">execução</font> das fases de iniciação, planejamento, configuração, especificação, execução e encerramento definidas na IEEE Std. 829-1998.
    - O Projeto de Teste de Software é o artefato de entrada na etapa de iniciação do Processo de Teste de Software, o qual é um documento que especifica os detalhes da abordagem de teste para um requisito do software ou combinação deles e identifica casos de teste associados.
    - O Plano de Teste de Software é o artefato de saída da etapa de iniciação do Processo de Teste de Software, que se consiste em um documento com uma abordagem sistemática para o teste do software. Ele geralmente consiste numa modelagem detalhada do fluxo de trabalho durante o processo. Ele visa planejar as atividades a serem realizadas, definir os métodos a serem empregados, planejar a capacidade necessária, estabelecer métricas e formas de acompanhamento do processo. <font color="red">Nota 0,4</font>


   2. (**0,5 ponto**) Descreva o relacionamento existente entre estes conceitos.

    Resposta:
    - O relacionamento existente entre esses conceitos pode ser explicitado de fora para dentro. O Processo de Teste de Software é a camada mais externa, que determina todas as etapas a serem executadas no teste de software. O Projeto de Teste de Software é o artefato de entrada da fase de Iniciação e da fase de Planejamento do Processo de Teste de Software. E o Plano de Testes, por sua vez, é o artefato de saída das fases de iniciação, planejamento, além de ser usado como artefato de entrada em outras etapas do Processo de Teste de Software. <font color="red">Nota 0,4</font>

2. (**1,0 pontos**) Descreva as vantagens para a equipe de desenvolvimento ao se adotar um processo de teste ágil.

    Resposta:
   -  A aplicação de teste ágil proporciona diversas melhorias, não só a nível de qualidade do processo, como também na qualidade do produto. A equipe de desenvolvimento se apresenta mais motivada e segura em relação a qualquer mudança que seja efetuada na aplicação. Os testes ágeis incentivam o protagonismo de todos os envolvidos no projeto, não responsabilizando a qualidade apenas ao departamento de testadores, mas também aos desenvolvedores, gestores e usuários. A sistemática de teste ágil fornece feedback constante à equipe de desenvolvimento, que passa a se comprometer também com a qualidade do produto final, por meio da implementação de testes de unidade (TDD). É comum ao se aplicar teste ágil, confundir o conceito de “agilidade” com “rapidez”, quando na realidade está atrelado à “qualidade” e “integridade” dos artefatos finais entregues. Ao se aplicar uma abordagem ágil, as iterações tendem a ser menores, assim como as entregas tendem a ser efetuadas em um curto prazo de tempo, no entanto cabe a equipe de teste em conjunto com as demais áreas garantir a consistência e qualidade final do produto gerado, assim como a satisfação do cliente diante das suas expectativas. <font color="red">Nota 1,0</font>

3. (**1,0 ponto**) Cite pelo menos três características do Teste Exploratório.

    Resposta:
    - Nos testes exploratórios, resultados de teste, casos de teste e documentação de teste são geradas a medida que os testes são realizados.
    - Testes exploratórios são ideais para o teste de aplicações web modernas, desenvolvida seguindo metodologias ágeis.
    - A principal principal desvantagem é o risco do testador desperdiçar muito tempo procurando por coisas para testar  e tentar consertar os defeitos.
    - Pode parecer uma técnica ad-hoc mas uma vez dominada é bastante poderosa em detectar defeitos.
    - Testadores podem interagir com a aplicação da forma como quiserem e usar as informações obtidas para: reagir, alterar o curso, explorar funcionalidades da aplicação sem repressão.

    <font color="red">Nota 1,0</font>

4. Considere os arquivos .java (Banco.java, Agencia.java, Conta.java e BankValidator.java). Nos próprios arquivos .java estão definidas as regras para cadastramento de cada um deles (Banco, Agencia e Conta). Desta forma, pede-se:
   4.1 (**2.0 Pontos**) Definir os cenários de teste suficientes para testar o cadastro e movimentações financeiras envolvendo bancos, agências e contas, conforme especificado. Para cada cenário definir os critérios de teste adequados à definição dos seus casos de teste.

**CENÁRIOS DE TESTE - BANCO**
VARIÁVEL **NÚMERO**
-- CENARIO 01 - SOMENTE NÚMEROS INTEIROS
-- CENARIO 02 - SOMENTE NÚMEROS INTEIROS MAIORES QUE 0
-- CENARIO 03 - QUANTIDADE DE DIGITOS MENOR QUE 3
-- CENARIO 04 - QUANTIDADE DE DIGITOS MAIOR QUE 3
-- CENARIO 05 - QUANTIDADE DE DIGITOS IGUAL A 3

VARIÁVEL **NOME**
-- CENARIO 06 - TAMANHO MENOR QUE 5
-- CENARIO 07 - TAMANHO IGUAL A 5
-- CENARIO 08 - TAMANHO MAIOR QUE 5 E MENOR QUE 100
-- CENARIO 09 - TAMANHO IGUAL A 100
-- CENARIO 10 - TAMANHO MAIOR QUE 100
-- CENARIO 11 - SOMENTE LETRAS

**CENÁRIOS DE TESTE - AGENCIA**
VARIÁVEL **NÚMERO**
-- CENARIO 12 - SOMENTE NÚMEROS INTEIROS
-- CENARIO 13 - SOMENTE NÚMEROS INTEIROS MAIORES QUE 0
-- CENARIO 14 - QUANTIDADE DE DIGITOS MENOR QUE 3
-- CENARIO 15 - QUANTIDADE DE DIGITOS IGUAL A 3
-- CENARIO 16 - QUANTIDADE DE DIGITOS MAIOR QUE 3 E MENOR QUE 5
-- CENARIO 17 - QUANTIDADE DE DIGITOS IGUAL A 5
-- CENARIO 18 - QUANTIDADE DE DIGITOS MAIOR QUE 5

VARIÁVEL **NOME**
-- CENARIO 19 - TAMANHO MENOR QUE 5
-- CENARIO 20 - TAMANHO IGUAL A 5
-- CENARIO 21 - TAMANHO MAIOR QUE 5 E MENOR QUE 100
-- CENARIO 22 - TAMANHO IGUAL A 100
-- CENARIO 23 - TAMANHO MAIOR QUE 100
-- CENARIO 24 - SOMENTE LETRAS

VARIÁVEL **CIDADE**
-- CENARIO 25 - TAMANHO MENOR QUE 5
-- CENARIO 26 - TAMANHO IGUAL A 5
-- CENARIO 27 - TAMANHO MAIOR QUE 5 E MENOR QUE 100
-- CENARIO 28 - TAMANHO IGUAL A 100
-- CENARIO 29 - TAMANHO MAIOR QUE 100
-- CENARIO 30 - SOMENTE LETRAS

**CENÁRIOS DE TESTE - CONTA**
VARIÁVEL **NÚMERO**
-- CENARIO 31 - CONTEM SOMENTE NÚMEROS
-- CENARIO 32 - QUANTIDADE DE DÍGITOS MENOR QUE 6
-- CENARIO 33 - QUANTIDADE DE DÍGITOS IGUAL A 6
-- CENARIO 34 - QUANTIDADE DE DÍGITOS MAIOR QUE 6
-- CENARIO 35 - NAO CONTEM SOMENTE NUMEROS

VARIÁVEL **TIPO**
-- CENARIO 36 - TIPO DA CONTA IGUAL A "CORRENTE"
-- CENARIO 37 - TIPO DA CONTA IGUAL A "POUPANCA"
-- CENARIO 38 - TIPO DA CONTA DIFERENTE DE "CORRENTE" OU "POUPANCA"

VARIÁVEL **LIMITE**
-- CENARIO 39 - TIPO DA CONTA IGUAL A "CORRENTE"
-- CENARIO 40 - TIPO DA CONTA IGUAL A "POUPANCA"

MÉTODO **DEPOSITAR**
-- CENARIO 41 - SALDO DA CONTA = SALDO ANTERIOR + VALOR.

MÉTODO **SACAR**
-- CENARIO 42 - SALDO DA CONTA = SALDO ANTERIOR - VALOR.

MÉTODO **TRANSFERIR**
-- CENARIO 43 - SALDO DA CONTA ORIGEM = SALDO ANTERIOR CONTA ORIGEM - VALOR E SALDO DA CONTA DESTINO = SALDO ANTERIOR CONTA DESTINO + VALOR

MÉTODO **CREDITAR RENDIMENTOS**
-- CENARIO 44 - APLICAVEL SOMENTE A CONTA DO TIPO POUPANCA

  <font color="red">Nota 1,7</font>

   4.2 (**2.0 Pontos**) Definir os casos de teste suficientes para a cobertura do teste de cada um dos cenários definidos. Documentar os casos de teste no seguinte padrão:

**CASOS DE TESTE - BANCO**
VARIÁVEL **NÚMERO**
|CT|Valores de Entrada|Resultado Esperado|
|---|---|---|
|CT01|**Numero)** 234 | Válido |
|CT02|**Numero)** -123 | Inválido |
|CT03|**Numero)** 23 | Inválido|
|CT04|**Numero)** 2346 | Inválido |
|CT05|**Numero)** 345 | Válido |

VARIÁVEL **NOME**
|CT|Valores de Entrada|Resultado Esperado|
|---|---|---|
|CT06|**Nome)** BAR | Inválido |
|CT07|**Nome)** BANCO | Inválido |
|CT08|**Nome)** BANCO DO BRASIL | Válido|
|CT09|**Nome)** ABC... (100Dígitos) | Inválido |
|CT10|**Nome)** ABC... (+100Dígitos) | Inválido |
|CT11|**Nome)** BANCO 321 | Inválido |

**CASOS DE TESTE - AGENCIA**
VARIÁVEL **NÚMERO**
|CT|Valores de Entrada|Resultado Esperado|
|---|---|---|
|CT12|**Numero)** 12.3 | Inválido |
|CT13|**Numero)** 0000 | Inválido |
|CT14|**Numero)** 12 | Inválido |
|CT15|**Numero)** 123 | Válido |
|CT16|**Numero)** 1234 | Válido |
|CT17|**Numero)** 12345 | Válido |
|CT18|**Numero)** 123456 | Inválido |

VARIÁVEL **NOME**
|CT|Valores de Entrada|Resultado Esperado|
|---|---|---|
|CT19|**Nome)** VILA | Inválido |
|CT20|**Nome)** VILAS | Inválido |
|CT21|**Nome)** VILA NOVA | Válido |
|CT22|**Nome)** AGENCIA TESTE... (100DIGITOS) | Inválido |
|CT23|**Nome)** AGENCIA TESTE... (+100DIGITOS) | Inválido |
|CT24|**Nome)** AGENCIA 123 | Inválido |

VARIÁVEL **CIDADE**
|CT|Valores de Entrada|Resultado Esperado|
|---|---|---|
|CT25|**Cidade)** CIDA | Inválido |
|CT26|**Cidade)** VILAS | Inválido |
|CT27|**Cidade)** CALDAS NOVAS | Válido |
|CT28|**Cidade)** CIDADE TESTE... (100DIGITOS) | Inválido |
|CT29|**Cidade)** CIDADE TESTE... (+100DIGITOS) | Inválido |
|CT30|**Cidade)** CIDADE 123 | Inválido |

**CASOS DE TESTE - CONTA**
VARIÁVEL **NÚMERO**
|CT|Valores de Entrada|Resultado Esperado|
|---|---|---|
|CT31|**Numero)** K123 | Inválido |
|CT32|**Numero)** 12345 | Inválido |
|CT33|**Numero)** 123456 | Válido |
|CT34|**Numero)** 1234568 | Inválido |
|CT35|**Numero)** K1245 | Inválido |

VARIÁVEL **TIPO**
|CT|Valores de Entrada|Resultado Esperado|
|---|---|---|
|CT36|**TipoConta)** CORRENTE | Válido |
|CT37|**TipoConta)** POUPANCA | Válido |
|CT38|**TipoConta)** CONTADIFERENTE | Inválido |

VARIÁVEL **LIMITE**
|CT|Valores de Entrada|Resultado Esperado|
|---|---|---|
|CT39|**Limite)** CORRENTE | Válido |
|CT40|**Limite)** POUPANCA | Inválido |

MÉTODO **DEPOSITAR**
|CT|Valores de Entrada|Resultado Esperado|
|---|---|---|
|CT41|**Saldo)** R$100,00 **Valor)** R$30,00 | **Saldo Final)** R$130,00 |

MÉTODO **SACAR**
|CT|Valores de Entrada|Resultado Esperado|
|---|---|---|
|CT42|**Saldo)** R$100,00 **Valor)** R$30,00 | **Saldo Final)** R$70,00 |

MÉTODO **TRANSFERIR**
|CT|Valores de Entrada|Resultado Esperado|
|---|---|---|
|CT43|**SaldoOrigem)** R$100,00 **SaldoDestino)** R$100,00 **Valor)** R$30,00 |**SaldoOrigem)** R$70,00 **SaldoDestino)** R$130,00|

MÉTODO **CREDITAR RENDIMENTOS**
|CT|Valores de Entrada|Resultado Esperado|
|---|---|---|
|CT44|**TipoConta)** CORRENTE | Válido |

<font color="red">Nota 1,7</font>

   3. (3.0 Pontos) Implementar (na linguagem de programação java) as classes para o teste da criação dos objetos e das movimentações financeiras envolvendo bancos e agências e contas.
<font color="red">Nota 1,6</font>

INSTRUÇÕES:
1. Tipo: Prova individual;
2. Local de Entrega: Plataforma Turing.
3. Forma de Entrega: arquivo compactado contendo:
   1. Este arquivo md, respondido.
   2. Classes de teste para (BancoTest, AgenciaTest e ContaTest);
   3. O arquivo compactado deverá ter o seguinte nome prova_p2<mat>.zip, onde mat é o número da matrícula do aluno(a).
5. Data da Entrega: 12/04/2022, as 22hs.
6. Critério de Aceitação: arquivo entregue, conforme solicitado.
7. Obs: segue no mesmo pacote o arquivo "org.apache.commons.lang.StringUtils", que é uma dependência do projeto. É deve ser inserida no _classpath_ do projeto de implementação da questão 4, caso não esteja utilizando o _maven_.
