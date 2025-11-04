# Desafio-SQL-2
Modelagem de Banco de Dados para Oficina Mecânica

📘 Sobre o Projeto

Este projeto apresenta a modelagem de um banco de dados para uma Oficina Mecânica, com o objetivo de organizar as informações sobre clientes, veículos, tipos de serviços (conserto ou revisão periódica), mecânicos e ordens de serviço.

A proposta foi desenvolver uma estrutura lógica e eficiente para facilitar o controle das operações da oficina, permitindo registrar atendimentos, monitorar reparos e planejar revisões preventivas.

🧩 Objetivos

Criar um modelo relacional funcional e coerente.

Representar as entidades essenciais: Cliente, Mecânico, Serviço e Ordem de Serviço.

Definir o relacionamento entre clientes, veículos e serviços realizados.

Garantir integridade dos dados e facilitar futuras análises de desempenho e produtividade.

🗂️ Estrutura do Projeto

Modelo Conceitual (DER) — Diagrama Entidade-Relacionamento, apresentando todas as entidades e seus relacionamentos.

Modelo Lógico — Conversão do DER para o formato relacional, com definição de chaves primárias e estrangeiras.

Modelo Físico (SQL) — Script SQL para criação das tabelas no banco de dados.

🧠 Entidades Principais

Cliente — Armazena dados de identificação e contato.

Mecânico — Contém informações sobre os profissionais responsáveis pelos serviços.

Serviço — Define o tipo de serviço: Conserto ou Revisão Periódica.

Ordem de Serviço (OS) — Registra o atendimento, vinculando cliente, veículo, mecânico e serviço realizado.

🧾 Regras de Negócio

Cada cliente pode possuir um ou mais veículos.

Cada ordem de serviço deve estar associada a um cliente, um mecânico e um tipo de serviço.

Os serviços podem ser classificados como Conserto ou Revisão Periódica.

Cada mecânico pode executar diversas ordens de serviço.

🧱 Tecnologias Utilizadas

MySQL

MySQL Workbench (modelagem e diagramas)

Azure (opcional para hospedagem)


👩‍💻 Autor(a)

Camila Campos
📚 Estudante de Administração com foco em Análise de Dados e Inteligência Artificial
🌐 [LinkedIn](https://linkedin.com/in/camilascampos)

![Image Alt](https://github.com/CamposCamila/Desafio-SQL-2/blob/72e820f4ac9eefaf5185c03b3258b23c1c84a627/Projeto%20de%20Oficina%20Mec%C3%A2nica%20no%20MySQL.png)
