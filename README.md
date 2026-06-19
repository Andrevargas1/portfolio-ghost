# 👻 Ghost — Sistema de Gestão de Atendimentos

> Case real de raciocínio de Product Owner aplicado a uma iniciativa pessoal, documentado por **André Vargas** durante sua atuação como Analista de Suporte Pleno.

[![Status](https://img.shields.io/badge/status-em%20uso%20real-success)]()
[![Tipo](https://img.shields.io/badge/tipo-case%20pessoal-purple)]()
[![Adoção](https://img.shields.io/badge/ado%C3%A7%C3%A3o-3%20a%205%20colegas-blueviolet)]()

---

## 📖 Sobre este repositório

Este repositório documenta, em formato de **case de produto**, o Ghost — uma ferramenta desktop que concebi e dirigi para resolver uma dor real do meu dia a dia como Analista de Suporte: a fragmentação do fluxo de atendimento entre Notepad, sistemas externos e compilação manual de relatórios.

O objetivo aqui **não é apresentar o código-fonte** — é demonstrar o raciocínio de produto por trás de cada funcionalidade: discovery, priorização, definição de escopo e validação iterativa através do uso real.

📄 **[Baixar o portfólio completo em PDF](./docs/Portfolio_Ghost.pdf)**

---

## 🎯 O Problema

O fluxo de atendimento era fragmentado:
- Chamados realizados via navegador em sistema externo de difícil navegação
- Anotações em Notepad sem estrutura
- Compilação manual diária de tudo que foi atendido para envio no Teams
- Nenhuma forma simples de consultar chamados anteriores ou documentar soluções

## 💡 A Solução

Uma ferramenta desktop própria, construída ao longo de ciclos iterativos de uso real, com os seguintes módulos:

| Módulo | Problema que resolve |
|---|---|
| 🎫 **Gestão de Chamados** | Registro estruturado, com prints e busca por histórico |
| 📊 **Relatório Diário** | Geração automática do resumo do dia, com filtros personalizados |
| 👥 **Base de Clientes** | Cadastro com contexto e métricas correlacionadas |
| 📚 **Base de Conhecimento** | Artigos reutilizáveis por categoria |
| 🌐 **Navegador Integrado** | Elimina necessidade de alternar entre janelas |
| 📌 **Kanban de Backlogs** | Visibilidade de demandas pessoais em aberto |

**Stack utilizada:** Python, PySide6, SQLite, Supabase

## 📝 User Stories (resumo)

| ID | Módulo | Como... | Quero... | Prioridade |
|---|---|---|---|---|
| US-01 | Chamados | Analista de suporte | registrar chamados com descrição e solução | Alta |
| US-02 | Chamados | Analista de suporte | filtrar e pesquisar chamados anteriores | Alta |
| US-04 | Relatório | Analista de suporte | gerar relatório diário automaticamente | Alta |
| US-05 | Clientes | Analista de suporte | cadastrar clientes com histórico correlacionado | Alta |
| US-08 | Navegador | Analista de suporte | acessar o sistema de atendimento sem trocar de janela | Média |

> User stories completas, critérios de aceite e backlog priorizado disponíveis no [PDF completo](./docs/Portfolio_Ghost.pdf).

## ✅ Resultado

A ferramenta foi **adotada espontaneamente por 3 a 5 colegas**, sem nenhum tipo de homologação formal da empresa — uma validação orgânica de que a solução resolvia uma dor real e compartilhada pela equipe. Reduziu significativamente o tempo gasto na montagem do relatório diário.

---

## 🧠 Habilidades de produto demonstradas

- **Discovery**: identificação de dor real antes de propor solução
- **Visão de usuário**: foco no fluxo real de trabalho do analista
- **Priorização**: MVP centrado nas funcionalidades de maior impacto imediato
- **Iteração**: evolução do produto com base no feedback de uso
- **Validação**: adoção por pares como prova de valor da solução

---

## 👤 Sobre mim

**André Alberto Vargas do Rosário**
Analista de Suporte em transição para Produto | PSPO I em andamento

- 📧 andre.rosario.cccc@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/ACoAAB2YIaQBXNac5mVUaTpfiIa-LvsLpsK4GQ0)
- 📄 [Currículo completo](./docs/CV_Andre_Vargas.pdf)
- 🔗 Veja também: [Case RustDesk — Substituição de Ferramentas de Acesso Remoto](https://github.com/Andrevargas1/portfolio-rustdesk)
