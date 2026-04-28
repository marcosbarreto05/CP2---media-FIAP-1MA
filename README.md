# CP2---media-FIAP-1MA

RM: 572895

Cálculo de Média Anual FIAP

Este projeto em Python foi desenvolvido para calcular a média anual de um aluno da FIAP, considerando as regras de avaliação dos dois semestres.

O programa solicita as notas do aluno e realiza automaticamente:

Média dos Checkpoints (descartando a menor nota);
Média dos Sprints;
Nota da Global Solution;
Uso de Substitutiva, caso necessário;
Média semestral;
Média final anual.

Verificação de status:
Aprovado;
Exame;
Reprovado.

Critérios Utilizados

Cada semestre possui:
3 Checkpoints (CP1, CP2, CP3)
A menor nota é descartada
Média das 2 maiores = MCP

2 Sprints (SP1 e SP2)
Média simples = SP

1 Global Solution (GS)
Peso maior no semestre

Fórmula da Média Semestral:
MS = 0.6 * GS + 0.2 * SP + 0.2 * MCP

Fórmula da Média Final:
MF = 0.4 * MS1 + 0.6 * MS2

Resultado Final

Após calcular a média final:

MF ≥ 6.0 → Aprovado 
4.0 ≤ MF < 6.0 → Exame 
MF < 4.0 → Reprovado 

Se o aluno ficar de exame:

MF2 = (EX + MF) / 2

Se MF2 ≥ 6, aprovado.
