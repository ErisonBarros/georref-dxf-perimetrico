# Georreferenciador DXF por Roteiro Perimétrico
---
[![ORCID](https://img.shields.io/badge/ORCID-0000--0003--4879--6880-a6ce39?logo=orcid&logoColor=white)](https://orcid.org/0000-0003-4879-6880)
[![License](https://img.shields.io/badge/license-Private-red.svg)]()
[![Maintained](https://img.shields.io/badge/maintained-yes-brightgreen.svg)]()
[![GitHub](https://img.shields.io/badge/github-ErisonBarros-blue.svg)](https://github.com/ErisonBarros)
---
Automatize o georreferenciamento de plantas cadastrais, topográficas e fundiárias a partir de arquivos DXF não georreferenciados e roteiros perimétricos contendo coordenadas oficiais.

Esta Skill foi desenvolvida para identificar automaticamente o perímetro do imóvel, correlacionar os vértices do desenho com os vértices do memorial descritivo e reposicionar toda a planta em suas coordenadas reais, preservando integralmente a estrutura original do arquivo CAD.

## Principais Recursos

✅ Georreferenciamento automático de arquivos DXF

✅ Leitura de memoriais descritivos e roteiros perimétricos

✅ Compatível com coordenadas UTM e Geográficas

✅ Suporte a SIRGAS2000, WGS84 e SAD69

✅ Preservação total de layers, blocos, textos e cotas

✅ Correção automática de translação, rotação e escala

✅ Validação de fechamento e consistência geométrica

✅ Geração de relatório técnico das transformações aplicadas

## Casos de Uso

* Regularização Fundiária (REURB)
* Georreferenciamento de Imóveis Rurais
* Cadastro Técnico Multifinalitário
* Atualização Cartográfica
* Projetos de Engenharia e Infraestrutura
* Conversão de plantas antigas para sistemas georreferenciados
* Integração de levantamentos topográficos com bases oficiais

## Fluxo de Processamento

1. Importação do arquivo DXF.
2. Identificação automática do perímetro.
3. Leitura do roteiro perimétrico ou memorial descritivo.
4. Correspondência entre vértices do desenho e coordenadas oficiais.
5. Cálculo das transformações geométricas.
6. Aplicação de translação, rotação e ajuste de escala.
7. Validação das coordenadas finais.
8. Exportação do novo DXF georreferenciado.
9. Emissão de relatório técnico.

## Diferenciais

Ao contrário de soluções que recriam ou redesenham entidades, esta Skill realiza apenas transformações geométricas globais, garantindo que:

* Nenhuma entidade seja recriada.
* Nenhum bloco seja explodido.
* Nenhum estilo seja alterado.
* Nenhuma informação gráfica seja perdida.
* A aparência do desenho permaneça exatamente igual ao original.

## Compatibilidade

* AutoCAD
* Civil 3D
* TopoCAD
* TopoEVN
* QGIS
* BricsCAD
* DraftSight
* Sistemas GIS compatíveis com DXF

## Público-Alvo

* Engenheiros Cartógrafos
* Engenheiros Agrimensores
* Engenheiros Civis
* Técnicos em Agrimensura
* Profissionais de Geoprocessamento
* Empresas de Regularização Fundiária
* Escritórios de Topografia
* Órgãos Públicos de Cadastro Territorial

## Objetivo

Transformar desenhos CAD locais em arquivos georreferenciados precisos, compatíveis com normas técnicas e prontos para utilização em processos de cadastro, georreferenciamento, regularização fundiária e registro imobiliário.

**Tags:** `dxf` `cad` `autocad` `georreferenciamento` `topografia` `agrimensura` `regularizacao-fundiaria` `sig` `gis` `sirgas2000` `utm` `cartografia` `engenharia-cartografica` `memorial-descritivo` `roteiro-perimetrico` `reurb` `geoprocessamento` `land-surveying` `cadastral-mapping` `surveying`

