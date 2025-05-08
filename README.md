
# Trabalho Infantil – Investigação do Paradoxo da Riqueza 🧑‍🌾

**Autor:** Bruno Timm 
**Orientadora:** Andrea Ferro
**Início do projeto:** Fevereiro de 2025

## Descrição
Este projeto verificar a existência do paradoxo da riqueza no trabalho infantil rural no Brasil, proposto por Bhalotra & Heady (2003, e investigado por Kassouf & Justus (2010) construindo um pseudo-painel a partir de PNADs de diferentes anos.

## Estrutura de Pastas
- `dados_brutos/`: microdados originais das PNADs.
- `dados_tratados/`: arquivos PNAD harmonizados com variáveis de interesse.
- `outputs/`: resultados das regressões, tabelas e gráficos.
- `dofiles/`: scripts `.do` do Stata utilizados para o processamento.

## Como Rodar
1. Baixe os microdados da PNAD e salve em `dados_brutos/`
2. Ajuste os caminhos no do-file `01_criar_pseudo_painel.do`
3. Rode o do-file no Stata para gerar o pseudo-painel
4. Os resultados serão salvos em `outputs/`

## Contato
brunotimm@estudante.ufscar.br
