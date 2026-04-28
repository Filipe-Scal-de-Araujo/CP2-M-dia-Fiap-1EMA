# CP2-Média-Fiap-1EMA
Filipe Scal de Araujo - RM569175

Gabriel de Medeiros de Madureira - RM570297

Luís Gustavo Leonart Evangelista - RM572167


Este é um guia descritivo para o seu script de cálculo de médias acadêmicas. O código foi estruturado para gerenciar notas de dois semestres, incluindo Checkpoints, Challenger Sprints e a Global Solution, seguindo uma lógica comum em instituições de ensino técnico/superior (como a FIAP).



Calculadora de Média Acadêmica (CP2)Este script em Python automatiza o cálculo da média final de um aluno, considerando diferentes pesos para avaliações contínuas e provas globais, além de prever a nota necessária para aprovação e gerenciar situações de exame final.

 

FuncionalidadesCálculo de Checkpoints (CP): Seleciona automaticamente as duas maiores notas entre três entradas para compor a média.

Média de Challenger Sprints (CS): Calcula a média aritmética simples entre dois projetos/entregas.

Cálculo Preditivo: Informa ao usuário quanto ele precisa tirar na Global Solution para atingir a média de aprovação (6.0).

Global Solution (GS): Suporta a entrada da nota principal ou da nota substitutiva.

Cálculo Semestral e Anual:MF1 (1º Semestre): Peso de 40% na média final.MF2 (2º Semestre): Peso de 60% na média final.Gestão de Status: Identifica se o aluno está Aprovado, em Exame ou Retido (DP).



Regra de CálculoA média de cada semestre é calculada seguindo a fórmula:$$MF = \frac{(MCP \times 2) + (MCS \times 2) + (GS \times 6)}{10}$$Onde:MCP: Média dos dois maiores Checkpoints.

MCS: Média dos Challenger Sprints.GS: Nota da Global Solution.A média final anual (MFF) é composta por:MF1 com peso 4 e MF2 com peso 6.
