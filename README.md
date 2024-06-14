# Análises de operações de crédito dos estados e municípios

# Projeto elaborado durante o treinamento de análise de dados da Data Vikings


<img src="arquivo/imagens/logo_ministerio_da_fazenda.jpg" alt="logo">

Este projeto tem como objetivo analisar os dados públicos dos empréstimos solicitados por entidades públicas. É uma análise descritiva da base de dados, com intuito de demostrar como é realizado um processo de storytelling, com dados públicos e utilizando gráficos mais elaborados.

## 📂 Conteúdo

1. [Descrição dos Dados](#descrição-dos-dados)
2. [Insights Iniciais](#insights-iniciais)
3. [Conclusão](#conclusão)

## Descrição dos Dados

A contratação de operações de crédito por Estados, Distrito Federal e Municípios, incluindo suas autarquias, fundações e empresas estatais dependentes , subordina-se às normas da Lei de Responsabilidade Fiscal (LRF) e das Resoluções do Senado Federal 40/2001 e 43/2001. Os entes subnacionais ou suas empresas estatais não dependentes submetem à Secretaria do Tesouro Nacional (STN) ou à instituição financeira credora um pedido de verificação de limites e condições (PVL) para contratação dessas operações. Para mais informações, acesse o Manual para Instrução de Pleitos (MIP), disponível em https://tesourotransparente.gov.br/mip.

Descrição das variáveis:

- **Interessado:** Nome do ente da Federação ou da empresa estatal interessada no PVL.
- **UF:** Unidade da Federação do ente da Federação ou da empresa estatal interessada no PVL.
- **Tipo de interessado:** Tipo de interessado no PVL: estado, município ou empresa estatal.
- **Tipo de operação:** Tipo da operação de crédito ou concessão de garantia.
- **Finalidade:** Finalidade da operação de crédito ou concessão de garantia.
- **Tipo de credor:** Tipo de credor da operação de crédito ou concessão de garantia.
- **Credor:** Nome do credor da operação de crédito ou concessão de garantia.
- **Moeda:** Moeda em que será contratada a operação de crédito ou a concessão de garantia.
- **Valor:** Valor da operação de crédito ou da concessão de garantia, na moeda de contratação.
- **Número do Processo/PVL:** Nº do processo do Ministério da Economia relacionado ao PVL ou, se não houver processo, seu código de
identificação no SADIPEM.
- **Código IBGE:** Código IBGE do ente da Federação interessado no PVL. Se o interessado por empresa estatal, esse campo
é vazio
- **Status:** Etapa em que se encontra o PVL.
- **Data:** Data em que o PVL foi movimentado no SADIPEM para seu status atual.
- **Analisado por :** Indica se a análise do PVL é de competência da STN ou da instituição financeira credora, nos termos do
art. 10 da LC 148/2014.


## Insights Iniciais

- A maioria dos empréstismos solicitados se dão para utilização em projetos de infraestrutura.
- Depois do real, a moeda mais utilizada é o iene, provavelmente por conta da diferença da taxa de juros praticada pelo Japão.
- A região sul concentra o maior número de pedidos de emprestimos.
  
Mais detalhes podem ser encontrados no arquivo python associado.

## Conclusão

A análise proporcionou insights valiosos sobre a tomada de emprestimos por estados e municípios. A atuação dos bancos estatáis no fomento de crédito para obras e projetos de entes públicos e privados sempre foi conhecido por mim,  mas confesso que foi uma novidade muito grande saber que os estados brasileitos e prefeituras também tomam vultuosos empréstismos em moedas de outros paises. 


