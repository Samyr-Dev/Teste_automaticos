# 🏦 Gerenciamento de Contas para Testes Unitários (JUnit)

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/Samyr-Dev/Teste_automaticos/blob/main/LICENSE)

## 📝 Descrição do Projeto

Este repositório Java foi desenvolvido com o objetivo principal de fornecer classes de **Gerenciamento de Contas** (`GerenciamentoDeContas` e `GerenciamentoDeContaCorrente`) com diversas regras de negócio. O código é utilizado como base para a criação e execução de **Testes Unitários** usando a *framework* **JUnit 4/5** no ambiente de desenvolvimento Eclipse.

O projeto foca em demonstrar como isolar e testar funcionalidades essenciais de uma aplicação bancária, como saldo, saques, depósitos e transferências. 

![Image of software unit testing diagram](https://github.com/Samyr-Dev/Teste_automaticos/blob/main/assets/licensed-image.jpg)


## 🚀 Tecnologias Utilizadas

* **Linguagem:** Java
* **IDE:** Eclipse
* **Framework de Teste:** JUnit

## ✨ Classes e Funcionalidades

O projeto contém as seguintes classes principais para testes:

| Classe | Descrição | Funcionalidades para Teste |
| :--- | :--- | :--- |
| `ContaCorrente` | Entidade básica que representa uma conta bancária. | **Saldo, Saque, Depósito, Transferência.** |
| `GerenciamentoDeContas` | Regras de negócio e lógica de controle para contas. | **Validações de Saldo, Taxas, Limites.** |
| `TesteGerenciamentoDeContas` | (Classe de Teste) | Implementa os cenários de teste (positivos e negativos) usando anotações **`@Test`** do JUnit. |

## ⚙️ Como Executar os Testes no Eclipse

Este projeto é otimizado para execução dentro do Eclipse IDE.

### Pré-requisitos

1.  **JDK (Java Development Kit)** instalado (versão 8 ou superior).
2.  **Eclipse IDE** configurado para desenvolvimento Java.
3.  **Biblioteca JUnit** configurada no *Build Path* do projeto.

### 1. Clonar o Repositório

Abra o terminal e clone o projeto:

```bash
git clone [https://github.com/Samyr-Dev/Teste_automaticos](https://github.com/Samyr-Dev/Teste_automaticos)
```

## ⚙️ Como Executar

Para executar este projeto em sua máquina:

### Pré-requisitos

Certifique-se de ter o **JDK (Java Development Kit)** instalado (versão 8 ou superior).

### 2. Importar o Projeto no Eclipse
No Eclipse, vá em File (Arquivo) > Import (Importar).

Selecione General (Geral) > Existing Projects into Workspace (Projetos Existentes no Workspace).

Clique em Browse (Procurar...) e selecione a pasta do projeto clonado.

Clique em Finish (Finalizar).

### 3. Configurar a Biblioteca JUnit
Clique com o botão direito no projeto e selecione Properties (Propriedades).

Vá para Java Build Path (Caminho de Build Java) e a aba Libraries (Bibliotecas).

Certifique-se de que a JUnit Library esteja adicionada (se necessário, use Add Library...).

### 4. Executar os Testes Unitários
No Package Explorer do Eclipse, localize a classe de teste (ex: TesteGerenciamentoDeContas).

Clique com o botão direito na classe e selecione Run As (Executar Como) > JUnit Test (Teste JUnit).

---

## 🧑‍💻 Autor

**Samyr Silva Tertuliano Deusdará**

🔗 [Linkedin](https://www.linkedin.com/in/samyrtertuliano)
