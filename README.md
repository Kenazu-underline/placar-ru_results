# placar-ru_results
Resultados das votações da Rinha de Universidades Públicas do Brasil.
_Os dados das disputas serão adicionados conforme forem tratados._


## Histórico de disputas
Tabela contendo os campos:
* date: Data e hora da amostra;
* HAHA: Número de reações "haha";
* LIKE: Número de reações "like";
* LOVE: Número de reações "love";
* SUPPORT: Número de reações "support" (a rinha não faz uso dessa reação);
* WOW: Número de reações "wow";
* SORRY: Número de reações "sorry";
* ANGER: Número de reações "anger";


## Resultados das disputas
Tabela contendo os campos:
* disputa: Identificador da disputa (sigla universidade 1 x sigla universidade 2);
* Uni1_votos: Número de votos recebidos pela universidade 1;
* Uni2_votos: Número de votos recebidos pela universidade 2;
* Uni1_reaction: Nome da reação relativa à universidade 1;
* Uni2_reaction: Nome da reação relativa à universidade 2;

## Metodologia de coleta de dados
O servidor coletou os dados a cada 15 segundos para as primeiras 28 rinhas, posteriormente houve uma instabilidade no uso da API do facebook que forçou as demais rinhas a serem coletadas a cada 5 minutos.

Observações: 
* As rinhas UECE x UFMA, UNEB x UEPG, UFABC x UEPB, UFSC x UFSJ, UFMT x UFG, UFPR x UNIRIO e UEL x UFPel não tem dados históricos disponíveis devido a problema com o servidor;
* Algumas rinhas apresentam dados faltantes, que podem ser observados como zeros ou como lacunas na amostragem;
* Diversas rinhas não apresentam dados completos para as primeiras horas da disputa;
