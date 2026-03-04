# Um Comparativo dos Métodos de Markotiwz e de Aprendizado por Reforço Profundo na Otimização de Carteiras de Fundos Imobiliários

### RESUMO
A otimização de carteiras tem por objetivo equilibrar riscos e retornos de diferentes ativos compondo uma carteira eficiente sendo essencial para gestão de investimentos. No mercado brasileiro de fundos imobiliários (FIIs), essa é uma tarefa complexa devido à heterogeneidade de liquidez e à influência de fatores macroeconômicos. Este trabalho compara e desenvolve a otimização de carteiras a partir de duas abordagens: o clássico modelo de Markowitz e o Aprendizado Profundo com Reforço (Deep Reinforcement Learning – DRL). São empregados dados históricos de FIIs listados na B3 entre 2020 e 2024, com liquidez mínima de R$ 1 milhão/dia. Os resultados evidenciam a viabilidade da solução de Aprendizado por Reforço Profundo, embora soluções exatas ainda apresentem resultados melhores no curto prazo. 

**Palavras-chave**: Otimização de carteiras. Teoria Moderna do Portfólio. Fundos Imobiliários. Inteligência Artificial. Aprendizado por Reforço Profundo.

### ABSTRACT
Portfolio optimization aims to balance the risks and returns of different assets by creating an efficient portfolio that is essential for investment management. The Brazilian real estate fund market (FIIs) is a complex task due to the heterogeneity of liquidity and the influence of macroeconomic factors. This work compares and develops portfolio optimization based on two approaches: the classic Markowitz model and Deep Reinforcement Learning (DRL). Historical data of FIIs listed in B3 between 2020 and 2024 are included, with minimum liquidity of R$ 1 million/day. The results demonstrate the viability of the solution of Learned by Reforço Profundo, embora exatas solutions ainda presentem better results in the short term.

**Keywords**: Portfolio optimization. Modern Portfolio Theory. Real Estate Investment Trusts. Artificial Intelligence. Deep Reinforcement Learning.

### Dados  
Dados de Fundos de Investimento Imobiliário (FIIs) listados na B3 (2020-2025) e com média de liquidez diária superior a R$ 1 milhão: 
- [Base Cota Ajustada.csv](https://github.com/FII-MARKOTIWZ-REFORCO/RCS/raw/refs/heads/main/Base%20Cota%20Ajustada.csv) (valores de cotas ajustados por rendimentos e desdobramentos, utilizada para o cálculo dos retornos diários)
- [Base Cota Mercado.csv](https://github.com/FII-MARKOTIWZ-REFORCO/RCS/raw/refs/heads/main/Base%20Cota%20Mercado.csv) (cotações de fechamento de mercado, para o cálculo das covariâncias e volatilidades)
