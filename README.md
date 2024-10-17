# Agro Solo Database

<p align="center">
<a href="https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Administração Paulista" border="0" width=40% height=40%></a>
</p>

## 📜 Descrição

Este projeto tem como objetivo desenvolver um banco de dados relacional para armazenar informações relacionadas à análise de solo, sensores de umidade, nutrição e irrigação de culturas agrícolas. O sistema foi projetado para gerenciar dados de sensores e irrigação, otimizando a gestão agrícola com base em informações precisas.

## 🌱 Tecnologias Utilizadas

- **MySQL**: Utilizado para o desenvolvimento do banco de dados relacional.
- **SQL Designer**: Utilizado para modelagem do banco de dados.
- **Prompt de Comando**: Executado localmente para criar e manipular as tabelas do banco de dados.
- **GitHub**: Para controle de versionamento e colaboração.

## 🗃 Estrutura do Banco de Dados

O banco de dados foi modelado para representar os seguintes elementos:

- **Sensores**: Contém informações sobre os sensores instalados no campo.
- **Leituras dos Sensores**: Armazena os dados coletados dos sensores em tempo real.
- **Cultura**: Informações sobre a cultura plantada, como o tipo de cultura e a área plantada.
- **Irrigação**: Registros das atividades de irrigação, incluindo quantidade de água aplicada.
- **Histórico**: Registra as informações relacionadas ao histórico de leituras de sensores e irrigação, vinculando as leituras e os sensores às culturas.

### 🔗 Relacionamentos

- **Histórico**: Relacionado com as tabelas de sensores e cultura, para acompanhar a evolução das leituras e atividades de irrigação em um período de tempo.
- **Leitura_Sensor**: Conectado diretamente com a tabela Sensores, armazenando os valores coletados.

## 📁 Estrutura de Pastas

Dentre os arquivos e pastas presentes na raiz do projeto, definem-se:

- **`.venv`**: Contém o ambiente virtual do Python com todas as bibliotecas necessárias para o desenvolvimento e execução do projeto.
- **`scripts`**: Pasta que pode conter scripts auxiliares para automatizar tarefas do desenvolvimento.
- **`src`**: Todo o código-fonte do projeto se encontra aqui, incluindo arquivos principais como `main.py`.
- **`README.md`**: Este arquivo que serve como guia e explicação geral sobre o projeto.

## 🔧 Como Executar o Código

1. Instale o Python na sua máquina.
2. Recomenda-se usar as IDEs PyCharm ou Visual Studio Code.
3. Adicione a pasta `.venv` ao seu projeto.
4. Instale as bibliotecas necessárias:
   - `oracledb`
   - `pandas`
5. Importe as bibliotecas necessárias no seu código:
   ```python
   import os
   import datetime
   import oracledb
   import pandas as pd
   import sys
   import json
