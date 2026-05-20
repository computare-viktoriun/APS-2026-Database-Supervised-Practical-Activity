# 🌎 APS 2026 - Banco de Dados - Atividade Prática Supervisionada / APS 2026 - Database - Supervised Practical Activity

**TEMA:** Rastreamento de Detritos Espaciais (Lixo Espacial): Controle de segurança orbital. Satélites ativos, fragmentos de lixo (tamanho, velocidade, órbita), empresas/países responsáveis, alertas de colisão e missões de limpeza.

---

## 📃 **DESCRIÇÃO DA ATIVIDADE:**

Implementar um projeto completo de banco de dados, de acordo com o tema sorteado, com os seguintes requisitos:

**1. Modelagem Conceitual:** Analisar o tema e definir as regras de negócio iniciais. É a fase de abstração, focada em entender "o que" o sistema faz.

- Entregáveis:
    
    ■ Redação do minimundo (documento narrativo descrevendo o funcionamento e as regras do cenário).
    
    ■ Diagrama Entidade-Relacionamento completo, com entidades, atributos principais e cardinalidades claramente definidas.
    

---

**2. Modelagem Lógica:** Traduzir o modelo conceitual (DER) desenvolvido no passo 1 para o modelo relacional, garantindo que o banco não terá redundâncias prejudiciais.

- Entregáveis:
    
    ■ Esquema/Diagrama Relacional completo.
    
    ■ Aplicação das regras de normalização (garantir minimamente a 3FN).
    
    ■ Definição clara de chaves primárias (PK) e chaves estrangeiras (FK).
    

---

**3. Modelagem Física e DDL:** Pegar o modelo lógico desenvolvido no passo 2 e escrever o código real para criar a estrutura no SGBD.

- Entregáveis:
    
    ■ Script SQL estruturado com a definição estratégica e otimizada dos tipos de dados e implementação das restrições (NOT NULL, UNIQUE, PRIMARY KEY, e FOREIGN KEY).
    

---

**4. População do Banco de Dados e DML:** Dar vida à estrutura vazia criada no Passo 3, gerando dados realistas e massivos que permitam testes e relatórios.

- Entregáveis
    
    ■ Scripts SQL de inserção para todas as tabelas, com 15 ou mais registros e que respeite a integridade referencial na hora da inserção.
    

---

**5. Geração de Relatórios Simples:** Consultar o banco populado no passo 4 para responder a perguntas reais do negócio e provar que a modelagem suporta as operações do dia a dia.

- Entregáveis:
    
    ■ Scripts SQL com 10 consultas baseadas em cenários práticos descritos no minimundo.
    
    ■ As queries devem conter complexidade intermediária, englobando obrigatoriamente: INNER JOIN, LEFT JOIN/RIGHT JOIN, WHERE com múltiplos operadores (lógicos e relacionais), e ORDER BY.
    

---


# 📃 **ACTIVITY DESCRIPTION:**

Implement a complete database project, according to the assigned theme, with the following requirements:

**1. Conceptual Modeling:** Analyze the theme and define the initial business rules. This is the abstraction phase, focused on understanding "what" the system does.

- Deliverables:

■ Mini-world writing (narrative document describing the operation and rules of the scenario).

■ Complete Entity-Relationship Diagram, with clearly defined entities, main attributes, and cardinalities.

---

**2. Logical Modeling:** Translate the conceptual model (ERD) developed in step 1 into a relational model, ensuring that the database will not have harmful redundancies.

- Deliverables:

■ Complete Relational Schema/Diagram.

■ Application of normalization rules (guaranteeing at least 3NF).

■ Clear definition of primary keys (PK) and foreign keys (FK).

--

**3. Physical Modeling and DDL:** Take the logical model developed in step 2 and write the actual code to create the structure in the DBMS.

- Deliverables:

■ Structured SQL script with the strategic and optimized definition of data types and implementation of constraints (NOT NULL, UNIQUE, PRIMARY KEY, and FOREIGN KEY).
**6. Geração de Relatórios Avançados:** Extrair inteligência avançada dos dados e encapsular regras complexas.

- Entregáveis:
    
    ■ Scripts SQL com 5 consultas de alta complexidade contendo agrupamentos (GROUP BY), filtros sobre grupos (HAVING) e funções de agregação (COUNT, SUM, AVG, MAX, MIN).

---

**4. Database Population and DML:** Bring the empty structure created in Step 3 to life, generating realistic and massive data that allows for testing and reporting.

- Deliverables

■ SQL insertion scripts for all tables, with 15 or more records, respecting referential integrity during insertion.

---

**5. Simple Report Generation:** Query the populated database from Step 4 to answer real business questions and prove that the model supports day-to-day operations.

- Deliverables:

■ SQL scripts with 10 queries based on practical scenarios described in the mini-world.

■ The queries must have intermediate complexity, necessarily including: INNER JOIN, LEFT JOIN/RIGHT JOIN, WHERE with multiple operators (logical and relational), and ORDER BY.

---

**6. Advanced Reporting:** Extract advanced intelligence from data and encapsulate complex rules.

- Deliverables:

■ SQL scripts with 5 highly complex queries containing groupings (GROUP BY), filters on groups (HAVING), and aggregation functions (COUNT, SUM, AVG, MAX, MIN).
