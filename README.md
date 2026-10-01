# AVALON — Termo de Abertura do Projeto (TAP)

> **Projeto Integrado** — SENAI Jandira | Curso Técnico em Desenvolvimento de Sistemas</br>
> **Empresa / Equipe:** Nexus

---

## 1. Identificação do Projeto

| Campo | Valor |
|---|---|
| **Nome do Projeto** | AVALON — Plataforma Integrada de Gestão e Conformidade do Funcionário |
| **Empresa / Equipe** | Nexus |
| **Curso** | Técnico em Desenvolvimento de Sistemas |
| **Instituição** | SENAI Jandira |
| **Data de Início** | 14/08/2026 |
| **Data de Entrega** | 18/12/2026 |
| **Horas Totais Estimadas/Investidas** | *[a confirmar]* |

## 2. Descrição do Projeto

O **AVALON** é uma plataforma integrada de gestão de recursos humanos, com autoatendimento para o Colaborador e um painel administrativo completo para o RH e para Gestores de equipe. O sistema cobre cadastro e autenticação, jornada e escala, férias e folgas, benefícios, documentos, pesquisas de experiência, avaliação de fatores psicossociais, feedback, indicadores e painéis analíticos, um motor de regras para classificação automática, planos de ação e notificações.

Toda a plataforma é construída sobre uma **Camada Central de Guardrails Transversais**: validação estrita de permissão por nível de campo, privacidade diferencial por **k-anonimato** em dados sensíveis (pesquisas e avaliações psicossociais), trilha de auditoria *append-only* e conformidade com a **LGPD**.

## 3. Justificativa

A gestão de pessoas envolve dados sensíveis — desde informações cadastrais até avaliações de risco psicossocial, hoje também uma exigência regulatória (NR-1) para empresas brasileiras — que raramente são tratados por sistemas pensados desde o início para privacidade e controle de acesso granular. A maioria das soluções de RH no mercado trata segurança e anonimato como funcionalidades adicionais, não como arquitetura central.

Este projeto justifica-se por propor uma plataforma em que o controle de acesso, o anonimato de pesquisas e a conformidade com a LGPD são parte da arquitetura desde a primeira linha de requisito — permitindo, ao mesmo tempo, a aplicação prática de um ciclo completo de engenharia de software (levantamento de requisitos, modelagem de dados, back-end, front-end, mobile e testes) dentro do curso técnico.

## 4. Objetivos

**Objetivo geral:** desenvolver uma plataforma web e mobile de gestão de colaboradores que centralize cadastro, jornada, férias, benefícios, documentos, pesquisas, avaliação de fatores psicossociais, feedback e planos de ação, com segurança e anonimato garantidos por arquitetura.

**Objetivos específicos:**
- Levantar e documentar requisitos funcionais, não funcionais e regras de negócio completos antes do início da implementação.
- Implementar controle de acesso por perfil (Colaborador, Gestor, RH), validado no backend em toda operação sensível.
- Garantir anonimato real (k-anonimato) nas pesquisas de experiência e nas avaliações de fatores psicossociais.
- Entregar um Plano de Teste de Software com rastreabilidade entre cada caso de teste e os requisitos que ele valida.

## 5. Escopo

| Módulo | Módulo | Módulo |
|---|---|---|
| Autenticação e Perfis | Jornada e Escala | Pesquisas de Experiência |
| Dashboards | Férias e Folgas | Avaliação de Fatores Psicossociais |
| Gestão de Colaboradores | Benefícios | Feedback |
| Documentos | Indicadores e Painéis Analíticos | Motor de Regras |
| Planos de Ação | Notificações | |

**Fora do escopo:** integração real com sistemas de folha de pagamento de terceiros, homologação física de atestados junto a clínicas externas, diagnóstico clínico/psicológico individual, e módulos de treinamento ou e-learning.

## 6. Equipe do Projeto

| Nome | Função |
|---|---|
| Daniele Silva Santos | Gerente de Projetos (Product Owner) |
| Geovane Santos | DBA |
| Matheus Aguiar | Desenvolvedor Back-end |
| Vitor Isidio | Desenvolvedor Front-end |

## 7. Documentação do Projeto

| Documento | Caminho |
|---|---|
| Documentação de Requisitos Funcionais (RF) | [`docs/RF-Documentacao-de-Requisitos.pdf`](docs/RF-Documentacao-de-Requisitos.pdf) |
| Documentação de Requisitos Não Funcionais (RNF) | [`docs/RNF-Documentacao-de-Requisitos.pdf`](docs/RNF-Documentacao-de-Requisitos.pdf) |
| Documentação de Regras de Negócio (RN) | [`docs/RN-Regras-de-Negocio.pdf`](docs/RN-Regras-de-Negocio.pdf) |
| Plano de Teste de Software (Roteiro de Testes) | [`docs/Plano-de-Teste-de-Software.pdf`](docs/Plano-de-Teste-de-Software.pdf) |
| EAP / WBS do Projeto (Miro) | [`Estrutura Analítica do Projeto`](https://miro.com/app/board/uXjVHgEmHAg=/) |

## 8. Repositórios do Projeto

| Repositório | Link |
|---|---|
| Central (Requisitos e Documentação) | [AVALON-DOCUMENTAÇÃO](https://github.com/Daniele-SS/NEXUS) |
| Banco de Dados | [AVALON-BANCO_DE_DADOS](https://github.com/Daniele-SS/AVALON-BANCO_DE_DADOS.git) |
| Back-End / API | [AVALON-BACK_END](https://github.com/Daniele-SS/AVALON-BACK_END.git) |
| Front-End | [AVALON-FRONT_END](https://github.com/Daniele-SS/AVALON-FRONT_END.git) |

## 9. Status Atual

| Frente | Status |
|---|---|
| Levantamento de Requisitos (RF/RNF/RN) | ✅ Concluído |
| Modelo Conceitual e Lógico (DER) | ✅ Concluído |
| Scripts SQL (criação de tabelas) | 🔄 Em andamento |
| Protótipos Web e Mobile (Figma) | ✅ Concluído |
| Back-End / API | ⏳ Não iniciado |
| Front-End (implementação) | ⏳ Não iniciado |
| Mobile (implementação) | ⏳ Não iniciado |
| Plano de Teste de Software | 🔄 Em andamento — 2 de 14 módulos |

---

*Licença: ver [LICENSE](LICENSE) na raiz deste repositório.*
