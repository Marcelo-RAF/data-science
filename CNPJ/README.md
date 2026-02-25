# CNPJ Data Pipeline

## Objective
Generate a sample of Brazilian companies (CNPJ), remove opening dates, and automatically enrich missing values using BrasilAPI.

## Data Source
- Receita Federal – Cadastro Nacional da Pessoa Jurídica (CNPJ)
- BrasilAPI

## Pipeline
1. Read raw Receita dataset
2. Generate random sample of 100 CNPJs
3. Remove 20 opening dates
4. Enrich missing values via API
5. Save processed dataset

## Technologies
- Python
- Pandas
- Requests
- Git