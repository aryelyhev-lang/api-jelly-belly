# <img src="img/logo.png" height="35" valign="middle"> Jelly Belly Wiki Project

> **Projeto acadêmico de desenvolvimento Full-Stack** integrado ao consumo de APIs públicas, focado em boas práticas de design (UI/UX) e arquitetura de software.

---

## 🎯 Objetivo do Projeto

O desafio proposto pelo professor consistiu em passar por todas as etapas reais de criação de um produto digital:

*   **🔍 Seleção Estratégica**: Escolha de uma API pública oficial (Jelly Belly) e filtragem de **quais endpoints gostaríamos de utilizar** para compor as regras de negócio.
*   **🎨 UI/UX Design**: Criação de um protótipo totalmente navegável no Figma, mapeando a identidade visual e o fluxo das 7 telas principais.
*   **⚙️ Back-End robusto**: Configuração de um servidor local em .NET para persistência e modelagem dos dados estruturados no MySQL.
*   **💻 Front-End Dinâmico**: Implementação de telas modernas e 100% responsivas com HTML5, CSS3 e JavaScript assíncrono (Fetch API).

---

## 🎨 Protótipo Navegável (Figma)

*O fluxo abaixo demonstra o planejamento de transições e interações de layout concebidos antes da etapa de código:*

<br align="center">
<div align="center">
  <img width="480" height="326" alt="Gravando 2026-06-27 143811 (1)" src="https://github.com/user-attachments/assets/685185ee-f000-43e0-8584-5a64a12305c4" />
</div>
<br>

---

## 🛠️ Stack Tecnológica

| Camada | Tecnologia | Função Principal |
| :--- | :--- | :--- |
| **Design** | `Figma` | Prototipagem de Alta Fidelidade |
| **Front-End** | `HTML5 / CSS3` | Estruturação e Estilização Responsiva |
| **Integração** | `JavaScript (ES6)` | Consumo Assíncrono via Fetch API |
| **Back-End** | `C# (.NET Core)` | Criação e Gerenciamento do Servidor da API |
| **Banco de Dados**| `MySQL` | Persistência Local com EF Core Migrations |

---

## 📌 Endpoints Utilizados da API

Para alimentar a interface mapeada no Figma, selecionamos os seguintes recursos:
*   `GET /api/Beans` — Catálogo geral e detalhes dos sabores de feijões.
*   `GET /api/Recipes` — Guia completo de receitas oficiais Jelly Belly.
*   `GET /api/Combinations` — Sugestões de combinações de sabores e misturas mágicas.
