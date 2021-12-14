# MELI - Desafio

## Data Engineer

> Queremos que demonstre seu conhecimento no desenvolvimento de APIs. Crie uma API REST, hospede essa API em um Cloud Provider gratuito (Google App Engine,
Amazon AWS, etc.). Você deve criar um endpoint, o qual receberá como parâmetro um JSON com uma chave genérica, realize a consulta em um banco de dados qualquer e retorne os registros correspondentes. Demonstre o funcionamento (por exemplo, via POSTMAN) e detalhe o código desenvolvido (pode ser por vídeo).

## Data Science

O arquivo dados.csv possui os dados para este projeto. Sobre ele pedimos que:
1. Desenvolva um modelo para predizer a variável Fraude (1-Sim, 0-Não). Quais técnicas testou? Qual selecionou como melhor abordagem? Explique!
1. Compare o desempenho do seu algoritmo com o desempenho de um modelo anterior, cujo resultado é encontrado na coluna Score do dataset. Quais métricas usou e qual sua conclusão?
1. Como você pode garantir que o desempenho do modelo no laboratório vai ser um proxy para o desempenho do modelo em produção?
1. Supondo que o desempenho produtivo seja muito diferente do esperado, quais você acha que são as causas mais prováveis?
1. Com a informação adicional de que uma fraude custa 10 vezes mais para a empresa do que o bloqueio incorreto de um pagamento, o que você faria de diferente?
1. Queremos encontrar o ponto de corte ideal para o modelo já treinado apresentado na parte (Score, onde 0 (zero) é o risco mais baixo e 100 (cem) o mais alto). Sabemos que MELI ganha 10% do valor de um pagamento aprovado corretamente e a cada fraude aprovada perdemos 100% do valor do pagamento.Defina o ponto de corte que maximize os lucros do MELI, de forma que todos os pagamentos com menor Score sejam aprovados e os maiores sejam rejeitados.
1. Seomodeloprecisarresponderonline,nomenortempopossível,oqueisso mudaria suas decisões no item 1?
1. Comocolocaressemodeloemprodução?

Observações:
- A coluna "Fraude" é o flag para aprender.
- A coluna “Score” corresponde ao resultado do algoritmo a ser substituído.
- O formato dos números atende ao delimitador “.” (ponto) para casas decimais e “,” (vírgula) para milhares.
