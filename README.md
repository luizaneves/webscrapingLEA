# Trabalho de Webscraping - Laboratório de Estatística Aplicada

Neste trabalho, iremos explorar como obeter dados de um site por meio de técnicas de webscraping estudadas em aula e, em seguida, será realizada uma análise dos dados.

---

## Introdução

É amplamente reconhecido que o planejamento financeiro é essencial para alcançar objetivos de longo prazo, seja para garantir uma aposentadoria confortável ou realizar outras metas importantes. Nesse contexto, uma das formas de investimento é em renda variável, em que indivíduos podem comprar a participação em uma empresa de capital aberto e se beneficiar de possíveis lucros futuros ou de uma valorização do preço do ativo adquirido.  

Por esse motivo, para a realização deste trabalho foi selecionado o site www.fundamentus.com.br, que busca difundir informações sobre empresas de capital aberto para a tomada de decisões de investimento mais conscientes. Nele, é possível encontrar informações detalhadas sobre indicadores financeiros, valor de mercado, fatos relevantes e rentabilidade, o que proporciona uma visão clara do desempenho das empresas e contribui para decisões mais conscientes. No entanto, com mais de 400 empresas sendo negociadas, o trabalho manual de coletar informações de cada uma para a tomada de decisões de investimento se torna exaustivo, o que abre espaço para que técnicas de webscraping sejam utilizadas como um próximo passo para democratizar o acesso à informação e transparência do mercado financeiro. 

Assim, foi estudado e realizado o proceso de extração das informações desse site e, em seguida, foram escolhidas algumas variáveis para serem analisadas. As variáveis escolhidas foram:

- Ticker ou Papel: identificador de cada ação
- Setor de atuação
- Subsetor de atuação
- Vol $ méd (2m): volume médio de negociação nos últimos dois meses;
- Valor de mercado: número de ações multiplicado pelo preço de cada ação;
- Valor da firma: valor de mercado somado à dívida líquida;
- Dia: valorização da ação no último dia;
- Mês: valorização da ação no último mês;
- 30 dias: valorização da ação nos últimos 30 dias;
- 12 meses: valorização da ação nos últimos 12 meses;
- 2024: valorização da ação em 2024;
- 2023: valorização da ação em 2023;
- Marg. EBIT: EBIT (Lucro antes de Juros e Impostos) dividido pela Receita Líquida
- Marg. Líquida: Lucro líquido divido pela receita líquida;
- Marg. Bruto: Lucro Bruto dividido pela receita líquida;
- ROE: lucro líquido dividido pelo patrimônio líquido (mede a qualidade da alocação de recursos dentro da empresa);
- P/L: preço sobre lucro (mede o quanto está sendo pago pelo lucro gerado);
- P/PL: preço sobre patrimônio líquido (mede o quanto está sendo pago por cada real no patrimônio líquido da empresa);
- Div Br/ Patrim: dívida bruta sobre o patrimônio líquido (mede o grau de endividamento);
- Dívida Líquida;
- Receita Líquida (nos últimos 12 meses e nos últimos 3 meses);
- Lucro Líquido (nos últimos 12 meses e nos últimos 3 meses);
- Patrimônio Líquido.

Ao todo, muitas variáveis foram inclusas, algumas podendo ser redundantes. Durante o estudo, cada uma foi analisada e algumas foram removidas conforme seu grau de correlação com as demais.

O objetivo da análise estatística neste trabalho foi de tentar captar padrões nos dados, relações entre as variáveis e identificar subgrupos de empresas que possam ter perfis similares por meio de modelos de cluster, como o K-Means e o DBSCAN. 
