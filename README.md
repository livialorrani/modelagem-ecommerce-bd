# 🚀 Refinando um Projeto Conceitual de Banco de Dados – E-COMMERCE

Este repositório contém o projeto de refinamento e melhoria de um banco de dados conceitual para um e-commerce, originalmente proposto como um desafio pela DIO. O objetivo principal é otimizar a estrutura do banco de dados, melhorar o desempenho, e garantir a aderência às melhores práticas de modelagem de dados.

## 🎯Objetivos

* Refinar o modelo conceitual original para um modelo lógico mais robusto e eficiente.
* Implementar melhorias na estruturação.
* Aplicar boas práticas de modelagem de dados, como normalização e padronização de nomes.

## 📌 Melhorias Implementadas

### 1. Cliente PJ e PF
- Agora há uma distinção clara entre clientes Pessoa Jurídica (PJ) e Pessoa Física (PF), garantindo que uma conta seja apenas de um tipo.

### 2. Pagamento
- Criada uma tabela de pagamentos que permite múltiplas formas de pagamento, melhorando a flexibilidade do sistema.

### 3. Entrega
- Adicionados os campos `status_entrega` e `codigo_rastreio` para melhor acompanhamento do envio e recebimento de pedidos.

### 4. Outras Melhorias
- Melhor estruturação dos nomes das tabelas e colunas para evitar espaços e facilitar consultas.
- Ajuste nos tipos de dados: valores monetários agora utilizam `DECIMAL(10,2)`, garantindo maior precisão.
- Removidos caracteres especiais e espaços dos nomes das tabelas e colunas para aderência às boas práticas.
- Normalização dos relacionamentos para melhorar a integridade e eficiência do banco de dados.

Este refinamento visa otimizar o desempenho, a manutenção e a escalabilidade da base de dados.

## 🗂 Arquivos Incluídos

* `diagrama_ER_refinado.pdf`: Diagrama Entidade-Relacionamento do banco de dados refinado.
* `README.md`: Este arquivo, contendo informações sobre o projeto.

## Conecte-se comigo!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/livialorrani/)
[![Perfil DIO](https://img.shields.io/badge/-Meu%20Perfil%20na%20DIO-0077B5?style=for-the-badge&logo=gitbook&logoColor=white)](https://www.dio.me/users/livialorrani_s) 
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/livialorrani)
