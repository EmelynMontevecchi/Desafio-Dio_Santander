# Santander 2025 - Ciência de Dados com Python 
**Pipeline ETL com Python + Mock de IA Generativa**

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

## Sobre o Projeto
Recriei o desafio oficial da **Santander Dev Week 2023** exatamente como ele era proposto:

- Extrair uma lista de IDs de clientes  
- Gerar mensagens de marketing personalizadas sobre investimentos  
- Atualizar o campo "news" de cada usuário

**Realidade 2025**:  
A API original (`sdw-2023-prd.up.railway.app`) está offline desde 2024 e os mocks públicos também sumiram.  
Por isso fiz tudo **100% local com dados mockados** – exatamente como a maioria dos alunos está fazendo hoje.

## O que o código faz (passo a passo)

```text
1. Lê os 5 IDs do arquivo SDW2023.csv (ou cria direto no código)
2. Carrega os dados completos dos clientes (nome, saldo, conta, cartão...)
3. Gera uma mensagem personalizada e realista para cada cliente
4. Adiciona a mensagem no campo "news" (exatamente o formato que a API esperava)
5. Simula o envio (PUT) para a API
