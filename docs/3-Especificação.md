
# 3. Especificações do Projeto

📌 **Pré-requisito:** Planejamento do Projeto (Cronograma e Sprints definidos).

Nesta seção serão detalhados:

- ✅ Requisitos Funcionais  
- ✅ Histórias de Usuário  
- ✅ Requisitos Não Funcionais  
- ✅ Restrições do Projeto  

O objetivo é organizar claramente as funcionalidades, qualidades e limites da solução.

---

# 3.1 Requisitos Funcionais

Os **Requisitos Funcionais (RF)** descrevem o que o sistema deve fazer.

📌 Cada requisito deve:
- Representar uma funcionalidade única
- Ser claro e objetivo
- Orientar diretamente o desenvolvimento

---

## Tabela de Requisitos Funcionais

| ID    | Descrição do Requisito | Prioridade |
|-------|------------------------|------------|
| RF-01 | O sistema deve permitir que os usuários criem uma conta informando nome, e-mail, senha e endereço. | 🔴 ALTA |
| RF-02 | O sistema deve permitir que os usuários adicionem produtos ao carrinho de compras. | 🟡 MÉDIA |
| RF-03 | (Descreva aqui o requisito funcional 3 do seu sistema) | (Alta/Média/Baixa) |
| RF-04 | (Descreva aqui o requisito funcional 4 do seu sistema) | (Alta/Média/Baixa) |
| RF-05 | (Descreva aqui o requisito funcional 5 do seu sistema) | (Alta/Média/Baixa) |
| RF-06 | (Descreva aqui o requisito funcional 6 do seu sistema) | (Alta/Média/Baixa) |
| RF-07 | (Descreva aqui o requisito funcional 7 do seu sistema) | (Alta/Média/Baixa) |
| RF-08 | (Descreva aqui o requisito funcional 8 do seu sistema) | (Alta/Média/Baixa) |
| RF-09 | (Descreva aqui o requisito funcional 9 do seu sistema) | (Alta/Média/Baixa) |
| RF-10 | (Descreva aqui o requisito funcional 10 do seu sistema) | (Alta/Média/Baixa) |

---

# 3.2 Histórias de Usuário

Cada história deve seguir o padrão ensinado na disciplina:

> **Como** [persona],  
> **eu quero** [funcionalidade],  
> **para que** [benefício].

⚠️ **ATENÇÃO:**  
Cada História de Usuário deve estar associada a um Requisito Funcional específico (RF-XX).

---

## Exemplos

**História 1 (relacionada ao RF-01):**  
Como usuário, quero registrar minhas tarefas para não esquecer de fazê-las.

**História 2 (relacionada ao RF-02):**  
Como administrador, quero alterar permissões para controlar o acesso ao sistema.

---

## Histórias do Projeto

---

### História 1 (relacionada ao RF-01)

Como __________________________________________  
Eu quero _______________________________________  
Para que _______________________________________

---

### História 2 (relacionada ao RF-02)

Como __________________________________________  
Eu quero _______________________________________  
Para que _______________________________________

---

### História 3 (relacionada ao RF-__)

Como __________________________________________  
Eu quero _______________________________________  
Para que _______________________________________

---

> 💡 Dica: Agrupe as histórias por módulo (Cadastro, Relatórios, Pagamentos, etc.) para melhor organização.

---

# 3.3 Requisitos Não Funcionais

Os **Requisitos Não Funcionais (RNF)** definem características de qualidade do sistema, como:

- ⚡ Desempenho  
- 🔒 Segurança  
- 🎨 Usabilidade  
- 📈 Escalabilidade  
- 🌐 Compatibilidade  

Eles garantem a qualidade da solução.

---

## Tabela de Requisitos Não Funcionais

| ID     | Descrição do Requisito | Prioridade |
|--------|------------------------|------------|
| RNF-01 | O sistema deve carregar as páginas em até 3 segundos. | 🟡 MÉDIA |
| RNF-02 | O sistema deve proteger as informações dos clientes por meio de criptografia. | 🔴 ALTA |
| RNF-03 | (Descreva aqui o requisito não funcional 3 do seu sistema) | (Alta/Média/Baixa) |
| RNF-04 | (Descreva aqui o requisito não funcional 4 do seu sistema) | (Alta/Média/Baixa) |
| RNF-05 | (Descreva aqui o requisito não funcional 5 do seu sistema) | (Alta/Média/Baixa) |
| RNF-06 | (Descreva aqui o requisito não funcional 6 do seu sistema) | (Alta/Média/Baixa) |

---

## 3.4 Regras de Negócio

As regras de negócio definem as diretrizes, políticas corporativas e condições lógicas que determinam como o sistema deve se comportar em situações específicas, independentemente da tecnologia utilizada. Elas traduzem as necessidades e restrições do mundo real para o software.

Para garantir a clareza, a equipe pode estruturar essas regras utilizando blocos lógicos condicionais (baseado nos conceitos apresentados pela [Alura](https://www.alura.com.br/artigos/o-que-sao-regras-de-negocio)):

*   **if/then (se/então):** Se determinada condição for verdadeira, então será tomada determinada ação.
    *   *Caso de uso:* “Se um usuário tem saldo na conta acima de X, a opção de empréstimo estará liberada.”
*   **if/else (se/senão):** Se determinada condição for verdadeira, o resultado será X; senão, o resultado será Y.
    *   *Caso de uso:* “Se o CEP do usuário for 35XXX-XX o frete é gratuito; em qualquer outro caso, fazer o cálculo do frete.”
*   **only if (apenas se):** Apenas se determinada condição for verdadeira, será tomada determinada ação.
    *   *Caso de uso:* “Apenas usuários cadastrados como gerentes poderão acessar a área de admin do sistema.”

Abaixo, liste as regras de negócio identificadas no projeto:

| ID | Descrição da Regra de Negócio | Formato Lógico |
| :--- | :--- | :--- |
| **RN 01** | (Descreva a regra de negócio do seu projeto) | (Ex: if/then) |
| **RN 02** | | |
| **RN 03** | | |
| **RN 04** | | |


⚠️ **Diferente dos RNFs, as restrições impõem limites fixos ao projeto.**

---


> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
