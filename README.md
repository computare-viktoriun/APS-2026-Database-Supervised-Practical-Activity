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

**6. Geração de Relatórios Avançados:** Extrair inteligência avançada dos dados e encapsular regras complexas.

- Entregáveis:
    
    ■ Scripts SQL com 5 consultas de alta complexidade contendo agrupamentos (GROUP BY), filtros sobre grupos (HAVING) e funções de agregação (COUNT, SUM, AVG, MAX, MIN).
