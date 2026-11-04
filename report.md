Relatório de Análise Exploratória e Qualidade de Dados: Festa em Cena

1. Qualidade dos Dados e Validação de Hipóteses

A análise da base de dados de vendas da Festa em Cena (1.500 registros) revelou a necessidade de tratamentos prévios indispensáveis para a confiabilidade analítica. Foram identificados 18 registros com categorias ausentes, 1.482 descrições com inconsistências de formatação (espaços excedentes e pontuações indevidas) e 26 pedidos com inconsistências numéricas (preços ou quantidades nulos/negativos).

No aspecto temporal e de status, 143 pedidos apresentaram ausência da data de entrega. Investigou-se a hipótese de que a falta de data de entrega estaria restrita a pedidos cancelados. A hipótese mostrou-se falsa: embora 109 pedidos sem entrega fossem de fato cancelados, identificou-se um grupo de 34 pedidos com status "Concluído" sem o registro da data de entrega. Como não foram encontradas duplicidades de pedido_id, conclui-se que o problema decorre de falhas no registro operacional do sistema, e não de inconsistências na transmissão de dados.

2. Descobertas e Insights de Negócio

Descoberta 1: Canal Web lidera pedidos, mas concentra cancelamentos e devoluções

O canal Web registrou o maior volume de pedidos, totalizando 666 registros (44,40% do total), seguido pela Loja Física com 551 (36,73%) e Mercado com 283 (18,87%). Contudo, a taxa de sucesso da Web é a menor entre os canais: 14,56% dos seus pedidos resultaram em cancelamento ou devolução (85,44% de taxa de conclusão). Em comparação, a Loja Física obteve 92,20% de conversão concluída e o canal Mercado atingiu 94,70%. Do total de 155 pedidos com problemas de conclusão na empresa, 62,58% têm origem na Web.

Limitação: Os dados representam pedidos registrados e não medem o custo logístico do processo de devolução nem a satisfação do cliente após a troca.

Descoberta 2: Sazonalidade acentuada e concentração de compras no período noturno

A distribuição temporal confirma a extrema sazonalidade do negócio. O mês de Outubro concentrou 52,54% de todas as vendas em 2024 (393 pedidos) e 54,81% em 2025 (410 pedidos). Além disso, identificou-se um forte padrão comportamental no horário das compras: nos dois anos analisados, mais de 53% dos pedidos diários foram realizados no período noturno, entre 18:00 e 23:59 (53,74% em 2024 e 56,28% em 2025). O volume de vendas decresce de forma acentuada logo nos primeiros dias de novembro pós-Halloween.

Limitação: A base contempla dados de apenas quatro meses por ano (agosto a novembro), impossibilitando projeções para o primeiro semestre.

3. Conclusão e Recomendações Operacionais

Para mitigar o impacto dos cancelamentos na Web, recomenda-se revisar a clareza das descrições e tabelas de medidas dos produtos. Adicionalmente, a infraestrutura dos servidores Web e a escala de atendimento devem ser reforçadas no período noturno do mês de outubro para suportar a alta demanda de tráfego concentrada nesse intervalo.