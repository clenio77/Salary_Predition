# Salary_Predition
Projeto de Machine Learning para prever Salário

![](banner-real3.png)

Este é um projeto usando dados desse  [link do kaggle](https://www.kaggle.com/datahackers/pesquisa-data-hackers-2019)
Foram usadas ferramentas como: 
- Python
- Pandas
- Pycaret
- RandonForest
- Streamlit

### Informação sobre o Dataset usado
Pesquisa de mercado de Data Science no Brasil feita pela comunidade Data Hackers. A pesquisa foi conduzida de forma online durante o mês de Novembro de 2019.

O dataset foi anonimizado ao remover alguns outliers que poderiam identificar o entrevistado e, portanto, nem todos os dados coletados na pesquisa estarão disponíveis aqui. Estados com menor incidência de resposta, como aqueles das regiões Norte, Nordeste e Centro-Oeste terão apenas sua região indicada no dataset, também como consequência do processo de anonimização.

As perguntas cujas respostas são multi-valoradas ocupam mais de uma coluna no dataset. Portanto, para diferenciar quais colunas pertencem a quais perguntas, cada coluna é identificada com uma tupla. Sendo o primeiro identificador o da pergunta, e, no caso de várias respostas, o segundo identificador referencia a alternativa escolhida. As perguntas mapeadas são mostradas abaixo (lembrando que algumas foram removidas e outras tiveram alguns outliers transformados/apagados no processo de anonimização)

Pergunta_1 (P1) = Idade? [Mascarada]

Pergunta_2 (P2) = Gênero? [Mascarada]

Pergunta_3 (P3) = Atualmente você vive no Brasil?

Pergunta_4 (P4) = Em que país você vive hoje?

Pergunta_5 (P5) = Em que estado você vive hoje? [Mascarada]

Pergunta6 (P6) = Na questão anterior você disse que vive em . Esse é seu estado de origem (onde nasceu ou se formou)?

Pergunta_7 (P7) = Qual seu estado de origem?

Pergunta_8 (P8) = Qual seu nível de ensino?

Pergunta_9 (P9) = Qual sua área de formação?

Pergunta_10 (P10) = Qual sua situação atual de trabalho?

Pergunta_11 (P11) = A empresa em que você trabalha pertence a qual setor?

Pergunta_12 (P12) = A empresa em que você trabalha possui quantos funcionários atualmente?

Pergunta_13 (P13) = Você atua como gestor?

Pergunta_14 (P14) = Qual das opções abaixo definem melhor seu cargo de trabalho atual como gestor?

Pergunta_15 (P15) = Qual das opções abaixo definem melhor seu cargo de trabalho atual?

Pergunta_16 (P16) = Qual sua faixa salarial atual? [Mascarada]

Pergunta_17 (P17) = Quanto tempo de experiência na área de dados você tem?

Pergunta_18 (P18) = Quanto tempo de experiência na área de TI/Engenharia de Software você teve antes de começar a trabalhar na área de dados?

Pergunta_19 (P19) = Você se considera um profissional que atua na área de Data Science?

Pergunta_20 (P20) = Quais dos métodos listados abaixo você costuma utilizar no trabalho?

Pergunta_21 (P21) = Quais das linguagens de programação listadas abaixo você utiliza no trabalho?

Pergunta_22 (P22) = Entre as linguagens de programação listadas abaixo, qual é a que você mais utiliza no trabalho? [Mascarada]

Pergunta_23 (P23) = Quais das fontes de dados listadas você já analisou no trabalho?

Pergunta_24 (P24) = Entre as fontes de dados listadas, quais você utiliza na maior parte do tempo? Selecione no máximo duas opções que você mais utiliza.

Pergunta_25 (P25) = Quais das opções de Cloud listadas abaixo você utiliza no trabalho?

Pergunta_26 (P26) = Quais dos bancos de dados/fontes de dados listados abaixo você utiliza para consultar informações, e posteriormente analisar, no trabalho?

Pergunta_27 (P27) = Quais as Ferramentas de Business Intelligence você utiliza no trabalho?

Pergunta_28 (P28) = Quais as tecnologias são utilizadas como ferramenta de ETL no seu trabalho?

Pergunta_29 (P29) = Sua organização possui um Data Warehouse?

Pergunta_30 (P30) = Qual tecnologia utilizada como plataforma do Data Warehouse?

Pergunta_31 (P31) = Quais das iniciativas do Data Hackers que você já acessou/acompanhou?

Pergunta_32 (P32) = Entre as iniciativas do Data Hackers qual a sua preferida?

Pergunta_33 (P33) = De quais outras formas que você costuma se atualizar no mundo dos dados?

Pergunta_34 (P34) = Em quais dessas plataformas listadas abaixo você já iniciou/completou cursos na área de Data Science?

Pergunta_35 (P35) = Dentre as plataformas listadas abaixo qual foi a sua preferida para cursos de Data Science?

Pergunta_36 (P36) = Você deseja participar do sorteio?

Além dessas, derivamos algumas outras colunas:
- Derivado_1 (D1) = Macrorregião em que mora

- Derivado_2 (D2) = Macrorregião em que nasceu

- Derivado_3 (D3) = Área de formação anonimizada

- Derivado_4 (D4) = Setor de mercado anonimizado

- Derivado_5 (D5) = Nível de gerência anonimizado

- Derivado_6 (D6) = Cargo anonimizado

Como esse era um dataset com muitas colunas( 185), agente mapeou algumas informações,
que agente considerou sinônimas e agrupamos essas informações.
Nas quais vamos trabalhar com 15 colunas e 1765 linhas.



Para qualquer dúvida, sugestão ou outra coisa qualquer, pode me encontrar
nas minhas redes sociais:

[instagram](https://www.instagram.com/afonso.clenio/)  -   [linkedin](https://www.linkedin.com/in/clenio-oliveira)  -   [Twitter](https://twitter.com/clenioafonso)  -  [Email](mailto:clenioti@gmail.com)


 



