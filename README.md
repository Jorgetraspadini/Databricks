# Treinamento de Engenharia de Dados

## Construção de uma Plataforma Analítica para Gestão de Pagamentos Bancários

## Visão Geral

Este projeto faz parte do programa de capacitação em Engenharia de Dados e tem como objetivo simular um cenário real de negócio encontrado em instituições financeiras.

Durante quatro semanas, os participantes atuarão como engenheiros de dados responsáveis por estruturar, transformar e disponibilizar informações estratégicas relacionadas às operações de pagamento de clientes de um banco. O desafio reproduz situações comuns do mercado financeiro, envolvendo integração de dados, padronização de informações, modelagem analítica e construção de processos escaláveis para apoio à tomada de decisão.

Ao longo do treinamento, os participantes terão contato com todas as etapas do ciclo de desenvolvimento de uma solução de dados moderna, desde a ingestão até a disponibilização de informações consolidadas para consumo analítico.

## Contexto de Negócio

Uma área responsável por pagamentos de clientes possui diferentes bases de dados que suportam suas operações:

1. Histórico de cotação do dólar;
2. Cadastro de clientes;
3. Catálogo de produtos financeiros;
4. Histórico de transações realizadas pelos clientes.

Atualmente, essas informações encontram-se distribuídas em arquivos CSV e apresentam desafios comuns em ambientes corporativos, como diferenças de nomenclatura, inconsistências de formatos e ausência de padronização entre sistemas.

Além disso, parte dos produtos possui valores registrados em moedas distintas, dificultando análises consolidadas sobre faturamento, comportamento de consumo e evolução financeira dos clientes ao longo do tempo.

Diante desse cenário, surge a necessidade de construir uma plataforma de dados capaz de integrar, organizar e transformar essas informações em ativos confiáveis para análise e tomada de decisão.

## Objetivo do Treinamento

O principal objetivo é desenvolver uma solução completa de Engenharia de Dados que permita transformar dados brutos em informações estruturadas, confiáveis e preparadas para análises de negócio.

Ao final do treinamento, os participantes deverão ser capazes de:

1. Implementar processos de ingestão de dados em ambiente Databricks;
2. Aplicar tratamentos e padronizações em conjuntos de dados;
3. Desenvolver modelos de dados voltados para consumo analítico;
4. Criar processos de transformação e enriquecimento de informações;
5. Automatizar consolidações de informações financeiras;
6. Versionar e organizar códigos seguindo boas práticas de Engenharia de Software.

## Escopo da Solução

### Ingestão de Dados

Realizar a carga das bases de origem disponibilizadas em formato CSV para o ambiente Databricks.

### Padronização e Qualidade dos Dados

Aplicar processos de limpeza, transformação e padronização dos registros, incluindo:

1. Adequação de nomenclaturas;
2. Padronização de colunas;
3. Tratamento de inconsistências;
4. Definição de convenções de nomenclatura;
5. Organização das camadas de dados.

### Governança e Modelagem

Estruturar uma camada de documentação e governança contendo:

1. Nome lógico e físico das tabelas;
2. Descrição funcional dos dados;
3. Metadados técnicos;
4. Tipagem das colunas;
5. Regras de negócio aplicadas;
6. Dicionário de dados.

### Enriquecimento das Transações

Implementar processos que permitam:

1. Identificar valores registrados em diferentes moedas;
2. Realizar conversões utilizando o histórico cambial;
3. Disponibilizar os valores das transações em Real (BRL) e Dólar (USD);
4. Garantir consistência para análises financeiras futuras.

### Consolidação de Informações

Construir uma tabela analítica consolidada contendo:

1. Histórico de compras por cliente;
2. Valores totais por período;
3. Indicadores financeiros mensais;
4. Evolução de faturamento em diferentes moedas.

Essa camada servirá como base para futuras iniciativas analíticas, dashboards e indicadores de negócio.

## Tecnologias Utilizadas

O desenvolvimento será realizado utilizando tecnologias amplamente adotadas pelo mercado de dados moderno:

1. **Databricks**
2. **PySpark**
3. **GitHub**
4. **Python**
5. **Arquitetura Medallion**

## Metodologia de Trabalho

Durante as quatro semanas do treinamento, os participantes irão aplicar conceitos de:

1. Engenharia de Dados;
2. Data Quality;
3. Modelagem Analítica;
4. Desenvolvimento em Ambiente Databricks;
5. Governança de Dados;
6. Versionamento de Código;
7. Boas Práticas de Desenvolvimento Colaborativo.

A proposta é proporcionar uma experiência próxima à realidade encontrada em projetos corporativos, permitindo que os participantes desenvolvam habilidades técnicas e práticas alinhadas às necessidades atuais do mercado.

## Controle de Versão

Todo o código desenvolvido ao longo do treinamento será armazenado e versionado em repositórios GitHub, seguindo boas práticas de desenvolvimento colaborativo.

O versionamento permitirá:

1. Rastreabilidade das alterações;
2. Controle de versões;
3. Colaboração entre os participantes;
4. Gestão de releases;
5. Padronização do processo de desenvolvimento.

## Resultado Esperado

Ao término do treinamento, será disponibilizada uma solução completa de Engenharia de Dados capaz de transformar dados operacionais em informações estruturadas e confiáveis, fornecendo uma visão consolidada dos gastos dos clientes ao longo do tempo e criando uma base sólida para futuras análises, indicadores de negócio e iniciativas de Data Analytics.

---

### Tabelas Bases  
**Clientes.csv:** Bases contendo dados dos clientes  
**Produtos.csv**: Contem dados sobre os produtos  
**Transacoes.csv**: Contem informacoes e historico de transação  
**Cotacao_usd.csv**: Cotação do dolar dia  

### Notebook
**1.0_Criação_bases.ipynb**: Arquivo contendo comando de criação do catalago, Schema e tabelas 