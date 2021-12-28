**Tarefa 003 - 21/12/2021 - Definição de Classes de Equivalência**

**Aluno:** Lucas Borges de Souza

**Matrícula:** 201802776

| **ID** | **Descrição** | **V/I** | **E/S** |
| --- | --- | --- | --- |
| CE01 | Quantidade de faltas superior a 25% da carga horária | I | E |
| CE02 | Quantidade de faltas inferior ou igual a 25% da carga horária | V | E |
| CE03 | Média entre nota1 e nota2 menor que 3.0 | I | E |
| CE04 | Média entre nota1 e nota2 maior ou igual a 3.0 e menor que 6.0 | I | E |
| CE05 | Média entre nota1 e nota2 maior que 6.0 | V | E |
| CE06 | Quantidade de faltas superior a 25% da carga horária e média entre nota1 e nota2 menor que 3.0 | I | E |
| CE07 | Quantidade de faltas superior a 25% da carga horária e média entre nota1 e nota2 maior ou igual a 3.0 e menor que 6.0 | I | E |
| CE08 | Quantidade de faltas superior a 25% da carga horária e média entre nota1 e nota2 maior ou igual a 6.0 | I | E |
| CE09 | Quantidade de faltas inferior ou igual a 25% da carga horária e média entre nota1 e nota2 menor que 3.0 | I | E |
| CE10 | Quantidade de faltas inferior ou igual a 25% da carga horária e média entre nota1 e nota2 maior ou igual a 3.0 e menor que 6.0 | I | E |
| CE11 | Quantidade de faltas inferior ou igual a 25% da carga horária e média entre nota1 e nota2 maior ou igual a 6.0 | V | E |
| CE12 | Reprovado por Falta | I | S |
| CE13 | Reprovado por Média | I | S |
| CE14 | Recuperação | I | S |
| CE15 | Aprovado | V | S |

| **ID** | **Valor de Entrada** | **Resultado Esperado** | **CE** |
| --- | --- | --- | --- |
| CT01 | **n1)** 10.0 **n2)** 10.0 **cargaHorária)** 64h **faltas)** 30h | Reprovado por Falta | CE01, CE05, CE08, CE12 |
| CT02 | **n1)** 3.0 **n2)** 4.0 **cargaHorária)** 64h **faltas)** 17h | Reprovado por Falta | CE01, CE04, CE07, CE12 |
| CT03 | **n1)** 3.0 **n2)** 2.0 **cargaHorária)** 64h **faltas)** 8h | Reprovado por Média | CE02, CE03, CE07, CE13 |
| CT04 | **n1)** 0.0 **n2)** 5.0 **cargaHorária)** 64h **faltas)** 8h | Reprovado por Média | CE02, CE03, CE07, CE13 |
| CT05 | **n1)** 3.0 **n2)** 5.0 **cargaHorária)** 64h **faltas)** 8h | Recuperação | CE02, CE04, CE10, CE14 |
| CT06 | **n1)** 10.0 **n2)** 1.0 **cargaHorária)** 64h **faltas)** 8h | Recuperação | CE02, CE04, CE10, CE14 |
| CT07 | **n1)** 10.0 **n2)** 10.0 **cargaHorária)** 64h **faltas)** 0h | Aprovado | CE02, CE05, CE11, CE15 |
| CT08 | **n1)** 10.0 **n2)** 8.0 **cargaHorária)** 64h **faltas)** 8h | Aprovado | CE02, CE05, CE11, CE15 |
| CT09 | **n1)** 7.0 **n2)** 6.0 **cargaHorária)** 64h **faltas)** 24h | Reprovado por falta | CE01, CE05, CE08, CE12 |