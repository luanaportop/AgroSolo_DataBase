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

- **`Agro_Solo_Database.sql`**: Contém o código SQL do banco de dados.
- **`Agro_Solo_Database.xml`**: Contém o código em XML.
- **`image.png`**: Imagem do programa sendo executado.
- **`imagme_banco`**: Imagem do modelo relacional.

## 🔧 Como Executar o Código

Clone este repositório:
1. git clone https://github.com/luanaportop/AgroSolo_DataBase

2. Execute o script SQL no seu banco de dados MySQL para criar as tabelas e relacionamentos.

3. Customize as inserções de dados de acordo com as suas necessidades. 

