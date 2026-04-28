# CP2---media-FIAP-1MA

RM: 572895

Cálculo de Média Anual FIAP

Este projeto em Python realiza o cálculo completo da média anual de um aluno seguindo o modelo de avaliação da FIAP.

Funcionalidades

O programa permite:

Calcular a média dos Checkpoints (CPs) descartando a menor nota
Calcular a média das Sprints (SPs)
Calcular a média semestral (MS1 e MS2)
Considerar Global Solution (GS) ou Substitutiva (SUB) caso necessário
Calcular a Média Final (MF)
Determinar o status do aluno:
Aprovado
Exame
Reprovado

Calcular nova média após exame, se aplicável

Regras de Cálculo

Checkpoints (CP)
São inseridas 3 notas
A menor nota é descartada
A média é feita com as 2 maiores

Sprints (SP)
São inseridas 2 notas
Média simples entre elas

Média Semestral (MS)

Fórmula:

MS = (0.6 × GS) + (0.2 × SP) + (0.2 × MCP)
Caso GS = 0 → usar nota da SUB
Média Final (MF)
MF = (0.4 × MS1) + (0.6 × MS2)
Status do Aluno
Média Final	Situação
≥ 6.0	Aprovado
≥ 4.0 e < 6.0	Exame
< 4.0	Reprovado
Exame

Se o aluno estiver de exame:

MF2 = (MF + EX) / 2
MF2 ≥ 6 → Aprovado
MF2 < 6 → Reprovado

Como usar
Execute o código em um ambiente Python (ex: Google Colab ou terminal)
Insira os valores quando solicitado:
Notas dos checkpoints
Notas das sprints
Nota da Global Solution ou Substitutiva
Nota do exame (se necessário)
