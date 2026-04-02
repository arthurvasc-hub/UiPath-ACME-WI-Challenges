# 🤖 UiPath - ACME System 1 Challenges (v1.0)

Este repositório contém as minhas soluções para os 5 desafios práticos (Work Items) do **ACME System 1** da UiPath Academy. 

Desenvolvi esses projetos paralelamente ao meu estágio em Hiperautomação. Enquanto no meu dia a dia profissional eu desenvolvo robôs *end-to-end* utilizando filas do Orchestrator e arquitetura Dispatcher/Performer, o foco deste repositório é servir como um laboratório de estudos focado na lógica de automação e preparação para a certificação **UiARD (UiPath Advanced RPA Developer)**.

## 🗂️ Estrutura dos Projetos

Os desafios evoluem em complexidade. Nos últimos, adaptei o padrão de mercado para focar na execução direta da lógica de negócio:

*   **WI1_SimpleFlow:** Resolução do Work Item 1 utilizando uma arquitetura linear.
*   **WI2_SimpleFlow:** Resolução do Work Item 2 focando na manipulação de dados e automação web.
*   **WI3_SimpleFlow:** Resolução do Work Item 3 consolidando o uso de seletores dinâmicos e extração de dados.
*   **WI4_reFramework:** Resolução do Work Item 4 adaptando o **Robotic Enterprise Framework (REFramework)**. Para este exercício (v1.0), a extração de dados (Get Transaction Data) foi simplificada e o uso de filas foi omitido para focar puramente no tratamento de exceções (System/Business) e processamento local.
*   **WI5_Framework:** Resolução do Work Item 5, também aplicando a estrutura de tratamento de erros e logs do REFramework de forma adaptada.

## 🛠️ Tecnologias e Conceitos Aplicados
*   **UiPath Studio**
*   Adaptação do **Robotic Enterprise Framework (REFramework)** para processamento local
*   Automação Web e Extração de Dados (Data Scraping)
*   Tratamento de Exceções e Logs Estruturados

## 📌 Status e Próximos Passos
Esta é a **v1.0** dos projetos. Como próximos passos para aprofundar os estudos, pretendo refatorar os fluxos do WI4 e WI5 para o modelo completo corporativo, separando os processos em *Dispatcher* e *Performer* e integrando com as *Queues* do Orchestrator (prática que já aplico nos meus projetos em produção no estágio).

---
*Desenvolvido por [Arthur Vasconcelos](https://github.com/arthurvasc-hub).*
