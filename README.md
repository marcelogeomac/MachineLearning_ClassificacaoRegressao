# MachineLearning_ClassificacaoRegressao
Work course Uniasselvi

Classificação e predição de arrecadação de recursos financeiros derivados da CEFEM a nível nacional.
CEFEM (Compensação Financeira pela Exploração Mineral) estabelecida pela Constituição de 1988 - CEFEM - é a contrapartida financeira paga pelas mineradoras à União, aos Estados, Distrito Federal e Municípios pela utilização econômica dos recursos minerais em seus respectivos territórios.

O cenário mineral evoluiu nas últimas décadas e a legislação que regulamentava a atividade minerária já não atendia às exigências. Tornou-se necessário uma regulação mais moderna, que favorecesse novas oportunidades de desenvolvimento e distribuição das riquezas advindas com a mineração de forma justa e equilibrada a todos os agentes nela envolvidos, após quase duas décadas de luta, a AMIG atuou fortemente para que fosse editada a Medida Provisória nº 789/2017, que tratava da alteração das alíquotas da CFEM.

Principais pontos da CEFEM de acordo com a lei 13.540/2017
1- O titular de direitos minerários que exerça a atividade de mineração;

2- O primeiro adquirente de bem mineral extraído sob o regime de permissão de lavra garimpeira;

3- O adquirente de bens minerais arrematados em hasta pública;

4- Quem exerça, a título oneroso ou gratuito, a atividade de exploração de recursos minerais com base nos direitos do titular original.

Sobre qual valor incide a CEFEM?
A base de cálculo da CFEM é a receita bruta nas operações de venda, deduzindo-se apenas os tributos que incidem sobre a comercialização. Não sendo permitido, portanto, a dedução das despesas com frete e seguro. Em toda e qualquer exportação, a base de cálculo estará sujeita a teste pelo PECEX (Preço sob Cotação de Exportação), ou pelo valor de referência, a ser fixado pela Agência Nacional de Mineração. O valor apurado servirá como base mínima de cálculo da CFEM nas exportações, independentemente do valor declarado pelo contribuinte. No caso de consumo de minério, a CFEM será calculada conforme metodologia regulamentada no Decreto 9.252/2017 que se baseia no valor de mercado do bem mineral, e não mais no custo de produção. Os contribuintes usufruirão de uma redução de 50% no valor a pagar de CFEM, nos casos de venda de rejeitos e estéreis de minerais associados e utilizados em outras cadeias produtivas.

Qual o fator gerador da CEFEM?
Nas saídas por venda entre empresas coligadas ou de um mesmo grupo econômico, ocorrendo a configuração de fato gerador, a base será, no mínimo, o preço corrente do minério. Não configurado o fato gerador na saída, será praticado quando da venda ou consumo pela empresa adquirente, o que ocorrer primeiro, mantendo-se como contribuinte a empresa mineradora.

tab_tax.JPG

Objetivo
Este projeto tem como objetivo aplicar algoritmos de machine learning para classificação e predição de arrecadações CEFEM atuais e futuras a nível nacional.

Especificação Técnica
Dataset: Para desenvolvimento desse projeto, será utilizado o dataset encontrado no sítio estatal (www.dados.gov.br) denominado Compensação Financeira pela Exploração de Recursos Minerais (CFEM), disponível em: < https://dados.gov.br/dataset/sistema-arrecadacao>.

Formato: A base de dados está em formato CSV, estando divivida em três domínios (Arrecadação por CEFEM, Autuação sobre CEFEM e Distribuição de CEFEM), colunas numéricas, alfanuméricas, texto, datas, categoria e etc.

Métodos de Pŕe-processamento: Necessário compor o dataset num SGBD (relacional) para tratamento e limpeza dos dados, além de criar relações entre domínios, será utilizado o SQL Lite na plataforma AWS:

Algoritmos Avaliados: Serão avaliados os algoritmos SVM, Regressão Logística utilizando método supervisionado.

Bibliografia
AMIG - Associação dos Municípios Mineradores de Minas Gerais, https://www.amig.org.br/paginas-extras/o-que-e-a-cfem
