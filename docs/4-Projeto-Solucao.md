
# 🏗️ 4. Projeto da Solução

> ⚠️ **Aviso aos Squads (Software House)**
>
> Esta seção **não deve ser preenchida integralmente antes da codificação**.
> Trata-se de um **Documento Vivo**, que deverá ser atualizado **incrementalmente a cada Sprint**, refletindo fielmente o código real implementado.

---

## 4.1 Arquitetura da Solução (Sprint 1 e 2)

Apresente um **diagrama macro** demonstrando como os componentes do sistema se comunicam.

A arquitetura deve refletir o modelo de **fatias verticais**, evidenciando o fluxo:

**Front-end → API (Back-end) → Banco de Dados**

📌 O diagrama deve representar:
- Camada de Apresentação
- Camada de Aplicação / API
- Camada de Persistência
- Comunicação entre camadas

### 📎 Inserir AQUI o Diagrama de Arquitetura do Projeto do Grupo


xxxxxxx  Imagem do grupo xxxxx


💡 Dica: Ferramentas recomendadas:

          - Draw.io
          - Lucidchart
          - Figma

---

## 4.2 Tecnologias Utilizadas (Sprint 1)

Descreva as tecnologias, linguagens, frameworks, bibliotecas e serviços escolhidos pelo Squad.

| Dimensão | Tecnologia Escolhida |
|----------|----------------------|
| Banco de Dados (SGBD) | Ex: SQL Server, PostgreSQL ou MongoDB |
| Back-end (API) | Ex: C# (.NET Core) |
| Front-end / Mobile | Ex: HTML + CSS + JavaScript, React ou Flutter |
| Hospedagem / Deploy | Ex: Azure, AWS, Render ou Railway |
| Gestão e Versionamento | GitHub e GitHub Projects (Kanban) |

> ⚠️ **Observação:** GitHub Pages não executa back-end.
  ⚠️ Utilize apenas tecnologias realmente implementadas.

---

#  4.3 Wireframes ou Mockups (A partir da Sprint 2)

Apresente os protótipos das telas (Wireframes/Mockups) apenas das funcionalidades que estão sendo implementadas na Sprint atual.

Cada Wireframe ou Mockups devem estar associados a pelo menos:

- Um Requisito Funcional (RF-XX)
- Uma História de Usuário


## 📌 Exemplo Ilustrativo – Tela de Cadastro (RF-01)

História associada:  
Como usuário, quero criar uma conta para acessar o sistema.

Representação simplificada do Wireframe:

| Criar Conta |
| Nome: [] |
| Email: [] |
| Senha: [] |
| Endereço: [] |
| |
| [ Cadastrar ] |

Descrição acadêmica:

A interface contempla todos os campos exigidos pelo RF-01 e permite persistência no banco após validação no backend.
---
### 📌 Ferramentas sugeridas:
- Figma  
- MarvelApp  
- Balsamiq  
---

### 📎 Inserir AQUI Wireframes/ Mockups do Projeto de Software

  xxxxxxx  Imagem do grupo xxxxx



---

## 4.4 Modelagem de Dados (Sprint 2 e 3)

O sistema exige persistência de dados.

A documentação do banco seguirá a abordagem de **entrega contínua**, sendo expandida conforme evolução do projeto.

---

### 4.4.1 Script Físico (Entrega na Sprint 2 - MVP)

Para a primeira fatia vertical (MVP), o Squad deverá entregar o **script de criação das tabelas ou coleções utilizadas**.

#### 🔹 Para Banco Relacional (SQL)

Incluir:

- Comandos `CREATE TABLE`
- Definição de chave primária (PK)
- Definição de chaves estrangeiras (FK)

**Exemplo:**

```sql
CREATE TABLE Usuario (
    Id INT PRIMARY KEY,
    Nome VARCHAR(100),
    Email VARCHAR(150) UNIQUE,
    Senha VARCHAR(200)
);
```

---

### Para Banco NoSQL

Incluir a estrutura dos documentos JSON (Schema).

**Exemplo:**

```json
{
  "nome": "João Silva",
  "email": "joao@email.com",
  "senha": "hash_da_senha"
}
```

###📁 Obrigatório

O arquivo .sql ou .js deve ser salvo na pasta: src/bd

 - É permitido colar um trecho do script no README apenas para visualização rápida.
   

#### 4.4.2 Modelo Entidade-Relacionamento (Entrega na Sprint 3 - Core)

Com o sistema evoluído, apresentar o Modelo ER completo.

📌 Requisitos:

O diagrama deve representar fielmente o banco já implementado.

Deve refletir exatamente o que foi criado nas Sprints 2 e 3.

Não incluir tabelas que não existam no código.

Contemplar:

- Todas as entidades
- Atributos
- Relacionamentos

Controle de acesso de usuários

###📎 Inserir Modelo ER

[Inserir imagem do Modelo ER aqui]

🔧 Ferramentas Sugeridas
- MySQL Workbench (engenharia reversa automática)
- DbDesigner
- Lucidchart
