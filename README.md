# Brazilian Federal Budgetary System: Official Documentary Sources, 2000–2023

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23574321.svg)](https://doi.org/10.5281/zenodo.23574321)

## Descrição

Dataset de proveniência documental contendo fontes oficiais relacionadas ao sistema orçamentário federal brasileiro no período de 2000 a 2023.

O conjunto foi consolidado a partir de tabelas anuais de fontes oficiais e preserva, sempre que possível, a estrutura, a nomenclatura e as categorias documentais divulgadas pelos portais governamentais em cada exercício.

O dataset funciona como um **source registry**, destinado à identificação, rastreabilidade e recuperação das fontes documentais utilizadas na análise longitudinal do sistema orçamentário federal brasileiro.

- **Período:** 2000–2023
- **Número de anos:** 24
- **Registros consolidados:** 2.638
- **Ciclos PPA:** 2000–2003; 2004–2007; 2008–2011; 2012–2015; 2016–2019; 2020–2023
- **Versão:** 1.0
- **Data da consolidação:** 21 de outubro de 2026
- **DOI:** [10.5281/zenodo.23574321](https://doi.org/10.5281/zenodo.23574321)

## Autores

**Aline Araujo Perini**¹*, **Camilla Guimarães**², **Anderson Zanardi de Freitas**³, **Mario Olímpio de Menezes**⁴

¹ MBA in Digital Business and Artificial Intelligence, Department of Economics, Administration and Sociology, University of São Paulo (USP/ESALQ), Piracicaba, SP, Brazil. ORCID: [0000-0002-3058-0224](https://orcid.org/0000-0002-3058-0224).  
² Department of Economics, Administration and Sociology, University of São Paulo (USP/ESALQ), Piracicaba, SP, Brazil.  
³ Nuclear and Energy Research Institute (IPEN/CNEN), São Paulo, SP, Brazil. ORCID: [0000-0003-0263-3541](https://orcid.org/0000-0003-0263-3541).  
⁴ Nuclear and Energy Research Institute (IPEN/CNEN), São Paulo, SP, Brazil. ORCID: [0000-0002-5018-9126](https://orcid.org/0000-0002-5018-9126).

*Corresponding author: alineperini@alumni.usp.br

## Contribuições dos autores

- **Aline Araujo Perini:** Conceptualization; Data Curation; Investigation; Methodology; Validation; Writing – Original Draft.
- **Camilla Guimarães:** Supervision; Methodology; Validation; Writing – Review & Editing.
- **Anderson Zanardi de Freitas:** Supervision; Methodology; Validation; Writing – Review & Editing.
- **Mario Olímpio de Menezes:** Supervision; Methodology; Validation; Writing – Review & Editing.

## Arquivos

- `fontes_orcamentarias_brasil_2000_2023.csv`
- `fontes_orcamentarias_brasil_2000_2023.xlsx`
- `data_dictionary_fontes_orcamentarias_2000_2023.csv`
- `methodology_notes.md`
- `LICENSE`

## Unidade de observação

Cada linha representa uma fonte documental, ato normativo, documento, volume, anexo ou página oficial identificada no mapeamento anual.

O conjunto documenta a proveniência e a localização das fontes. Nesta versão, ele **não constitui um corpus textual integral nem uma base exaustiva de execução financeira**.

## Princípio de preservação histórica

A terminologia e a organização das páginas oficiais foram mantidas conforme divulgadas em cada período.

Mudanças na arquitetura documental entre anos e ciclos são tratadas como parte do próprio dado e não foram harmonizadas retrospectivamente.

Essa decisão permite observar também a evolução da forma de organização, classificação e divulgação das informações orçamentárias pelo Governo Federal.

## Fontes

As fontes principais são páginas oficiais do Governo Federal brasileiro, especialmente os domínios:

- `gov.br`
- `planalto.gov.br`

A coluna `Link oficial` deve ser utilizada para rastreabilidade e eventual recuperação dos documentos.

## Uso recomendado

O dataset pode apoiar:

- localização e recuperação de documentos oficiais;
- construção de corpus para análise textual;
- análise longitudinal da arquitetura documental orçamentária;
- estudos de proveniência e reprodutibilidade;
- análise institucional e contextual do sistema orçamentário;
- LDA e NMF;
- embeddings e clustering semântico;
- topic modeling;
- aplicações de processamento de linguagem natural e análise assistida por LLM.

## Limitações

1. URLs governamentais podem ser reorganizadas, redirecionadas ou descontinuadas.
2. Em alguns registros, o link disponível corresponde à página-mestra ou à categoria documental, e não diretamente ao arquivo PDF.
3. A ausência de determinado tipo de ato no dataset não deve ser interpretada automaticamente como inexistência jurídica ou documental daquele ato.
4. Os textos integrais dos documentos vinculados não estão incluídos nesta versão.
5. As URLs não foram revalidadas em massa durante a consolidação final.
6. A estrutura e a granularidade das páginas governamentais variam entre os exercícios analisados.

## Citação

Araujo Perini, A., Guimarães, C., Zanardi, A. de F., & Menezes, M. O. (2026). *Brazilian Federal Budgetary System: Official Documentary Sources, 2000–2023* [Dataset]. Zenodo. https://doi.org/10.5281/zenodo.23574321

## Repositório permanente

A versão arquivada e citável do dataset está disponível no Zenodo:

**https://doi.org/10.5281/zenodo.23574321**

## Licença

Este dataset é disponibilizado sob a licença **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

A licença aplica-se à compilação, organização e estrutura de metadados produzidas pelos autores. Ela não implica relicenciamento dos documentos governamentais vinculados, cujos direitos, condições de uso e status jurídico permanecem vinculados às respectivas fontes oficiais.
