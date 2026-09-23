# mecaniQA-belo_horizonte
## Contexto do Projeto
Esse projeto é baseado na premissa de criação de um modelo de previsão para Oficinas e Mecânicas, o presente repositório é manifestação da implementação desse planejamento teórico.
Tratando-se também de uma OAT pelos estudantes do polo de Itabuna da UNEX, sobre a direção do Professor **Lucas Almeida**.

### Integrantes
- Natan Correia da Silva
- Clara Gabryellen Paixão Aderno
- Felipe Souza Teixeira da Silva
- Jhon Luiz Sousa Santos
- João Gabriel Aboboreira Rodrigues


## Encontro 09/09/2026
- O Novo Modelo (Com Lags & Rolling) é o que apresenta o melhor desempenho. Ele supera o modelo anterior ao registrar menores taxas de erro em todas as métricas: 
MAE (Erro Absoluto Médio): Caiu de 4.35 para 4.08. 
RMSE (Raiz do Erro Quadrático Médio): Caiu de 5.52 para 5.16. 
MAPE (Erro Percentual Absoluto Médio): Caiu de 15.36% para 14.31%. 
A adição da inteligência temporal (as variáveis lag_1, lag_7 e rolling_mean_7) forneceu ao Random Forest um contexto melhor sobre o comportamento passado dos dados, permitindo que ele errasse menos nas previsões da variável Trocas_Oleo.

