
# 🏗️ 4. Projeto da Solução

⚠️ **Importante:**  
Esta seção é um **Documento Vivo**. Deve ser atualizada ao final de cada Sprint, refletindo exclusivamente o que já foi implementado no código.

Não devem ser documentados componentes, tabelas ou funcionalidades que ainda não foram desenvolvidos.

---

# 🔷 4.1 Arquitetura da Solução (Sprint 1 e 2)

Apresente um diagrama macro demonstrando como os componentes do sistema se comunicam.

A arquitetura deve evidenciar o modelo de **Fatias Verticais**, mostrando claramente o fluxo:

Front-end → API (Back-end) → Banco de Dados

---

## 📌 Exemplo Ilustrativo de Arquitetura

(./images/DR_Arquitetura.png)
 
 >FONTE: https://www.researchgate.net/figure/Figura-2-Diagrama-de-arquitectura-del-sistema_fig1_361400461 



No exemplo acima:

- O usuário interage com o Front-end
- O Front-end consome endpoints da API
- A API executa regras de negócio
- A API persiste dados no Banco

---

📌 Insira abaixo o diagrama real do seu projeto:

(Insira aqui a imagem do Diagrama de Arquitetura)

Sugestão de ferramentas:
- Draw.io
- Lucidchart

---

# 🔷 4.2 Tecnologias Utilizadas (Sprint 1)

Descreva as tecnologias efetivamente adotadas pelo grupo.

## 📋 Exemplo de Preenchimento

| Dimensão | Tecnologia Escolhida |
|-----------|----------------------|
| Banco de Dados | PostgreSQL |
| Back-end (API) | C# (.NET 8) |
| Front-end | React |
| Hospedagem | Render |
| Versionamento | GitHub + GitHub Projects |

⚠️ Utilize apenas tecnologias realmente implementadas.

---

# 🔷 4.3 Wireframes ou Mockups (A partir da Sprint 2)

Apresente os protótipos das funcionalidades desenvolvidas na Sprint atual.

Cada Wireframe ou Mockups devem estar associados a pelo menos:

- Um Requisito Funcional (RF-XX)
- Uma História de Usuário

---

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

📌 Inserir abaixo os wireframes reais do projeto:

(Imagem ou link do Figma / Balsamiq / MarvelApp)

---

# 🔷 4.4 Modelagem de Dados (Sprint 2 e 3)

A modelagem de dados deve acompanhar a evolução do sistema.

---

## 🔹 4.4.1 Script Físico (Sprint 2 – MVP)

Entregar o script físico correspondente à primeira Fatia Vertical.

📁 O arquivo deve estar salvo em:

src/bd/

---

### 📌 Exemplo Ilustrativo (SQL)

```sql
CREATE TABLE Usuario (
    Id SERIAL PRIMARY KEY,
    Nome VARCHAR(100) NOT NULL,
    Email VARCHAR(150) UNIQUE NOT NULL,
    Senha VARCHAR(255) NOT NULL,
    Endereco VARCHAR(200)
);

Descrição:

A tabela Usuario atende ao requisito RF-01 (Cadastro de Usuário).
O campo Email possui restrição UNIQUE para evitar duplicidade.

🔹 4.4.2 Modelo Entidade-Relacionamento (Sprint 3 – Core)

O Modelo ER deve ser gerado por Engenharia Reversa, representando exatamente o banco implementado.

📌 Exemplo Conceitual Simplificado
Usuario
-------
Id (PK)
Nome
Email
Senha
Endereco

Pedido
-------
Id (PK)
Data
UsuarioId (FK)

Relacionamento:
Usuario 1:N Pedido

O modelo demonstra que:

Um usuário pode possuir vários pedidos.

O relacionamento é implementado por meio da chave estrangeira UsuarioId.

📌 Inserir abaixo a imagem do Modelo ER completo:

(Imagem do DER gerado via Engenharia Reversa)

Ferramentas sugeridas:

MySQL Workbench

DbDesigner

Lucidchart





