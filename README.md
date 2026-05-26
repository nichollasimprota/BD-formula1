# 🏎️ Sistema de Fórmula 1 — Banco de Dados Relacional

Projeto acadêmico desenvolvido em MySQL com o objetivo de modelar
e consultar dados de um sistema de Fórmula 1.

## 📌 Tabelas
- `tbl_pais` — países dos pilotos e equipes
- `tbl_equipe` — equipes e suas nacionalidades
- `tbl_piloto` — pilotos, equipes e salários
- `tbl_corrida` — grandes prêmios e número de voltas
- `tbl_participante` — relação entre pilotos e corridas

## 🔍 Consultas presentes
- Filtros com `WHERE`, `LIKE` e `BETWEEN`
- Junções com `JOIN`
- Agrupamentos com `GROUP BY` e `AVG`
- Ordenação com `ORDER BY` e `DISTINCT`

## ▶️ Como executar
1. Tenha o MySQL instalado
2. Execute o arquivo `schema.sql` para criar o banco e as tabelas
3. Execute o arquivo `inserts.sql` para popular os dados
4. Execute o arquivo `queries.sql` para rodar as consultas

## 🛠️ Tecnologias
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
