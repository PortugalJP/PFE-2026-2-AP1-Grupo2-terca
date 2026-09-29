# Scrum - AP1

# Plano de Execução Agile / Scrum

Este documento apresenta a estruturação completa da metodologia **Scrum** para o projeto **PKZ One to One**, detalhando a governança, backlog de desenvolvimento front-end, gerenciamento de Sprints e critérios de qualidade para a entrega do protótipo e aplicação.

---

## 1. Mapeamento de Papéis (Scrum Roles)

* **Product Owner (PO):** Proprietários da academia (com mediação/representação da equipe de alunos frente ao cliente).
  * *Atribuições:* Validação das regras de negócio, priorização do backlog entre os programas PKZ e One to One, e aceite final das entregas nos marcos do projeto (Marco de 28/10/2026).
* **Scrum Master:** Integrante designado da equipe acadêmica.
  * *Atribuições:* Facilitação dos ritos do Scrum, remoção de impedimentos técnicos e garantia do alinhamento do time ao escopo estritamente front-end (*client-side*).
* **Developers (Dev Team):** Alunos da equipe de desenvolvimento front-end e UX/UI Designers.
  * *Atribuições:* Construção do Design System no Figma, implementação dos componentes reutilizáveis, garantia da responsividade, interatividade (JS/Framework) e rotas de integração com o WhatsApp.

---

## 2. Cronograma de Sprints (Release Plan)

O projeto iniciou-se em **24/08/2026** e contempla a entrega do protótipo/primeira etapa em **28/10/2026** (~9 semanas de desenvolvimento).

| Sprint | Período | Foco Principal | Entregáveis |
| :--- | :--- | :--- | :--- |
| **Sprint 0** | 24/08 a 06/09 | Entendimento & Arquitetura | Documento de Visão, 5W2H, AHT, mapa de empatia e alinhamento inicial. |
| **Sprint 1** | 07/09 a 29/09 | UX/UI & Design System | Protótipo de alta fidelidade (Figma), guia de estilos, paleta e componentes base. |
| **Sprint 2** | 01/10 a 13/10 | Landing Page & Marcas | Shell da aplicação, alternância PKZ / One to One, FAQ interativo e galeria. |
| **Sprint 3** | 15/10 a 20/10 | Conversão & Agendamento | Simulação de agenda e CTAs do WhatsApp. |
| **Sprint 4** | 22/10 a 28/10 | Dashboards & Refinamento | Painel de avaliações, acessibilidade, responsividade e preparação da entrega. |

---

## 3. Product Backlog Priorizado

### Épico 1: Design System & Identidade Visual
* **US01 - Suporte a Temas (Light/Dark Mode):** Como visitante, quero alternar entre o modo claro e escuro para ter uma leitura confortável em qualquer ambiente.
* **US02 - Biblioteca de Componentes:** Como desenvolvedor, quero construir componentes globais reutilizáveis (Header, Footer, Botões com estados Hover/Active, Modais e Accordions) para garantir consistência visual.

### Épico 2: Institucional & Dual Branding
* **US03 - Apresentação Institucional:** Como visitante, quero visualizar uma apresentação unificada da marca mãe antes de escolher um programa específico.
* **US04 - Alternância de Programas (PKZ / One to One):** Como visitante, quero alternar entre a PKZ (7-15 anos) e a One to One (17-90 anos) sem recarregar a página para compreender a proposta de cada segmento.
* **US05 - Galeria da Estrutura Física:** Como visitante, quero explorar uma galeria de fotos interativa com pontos clicáveis para conhecer as instalações e equipamentos.
* **US06 - Central de FAQ Integrada:** Como visitante, quero acessar as dúvidas frequentes em formato *accordion* na mesma aba de contato para sanar dúvidas sem abrir chamados.

### Épico 3: Fluxo de Agendamento & Conversão
* **US07 - Quiz de Recomendação:** Como visitante, quero responder a um quiz sobre objetivos e faixa etária para receber uma recomendação de plano personalizada.
* **US08 - Agenda Interativa:** Como visitante, quero consultar uma simulação de agenda com dias e horários vagos para planejar minha aula experimental.
* **US09 - Conversão via WhatsApp:** Como visitante, quero confirmar meu agendamento gerando uma mensagem pré-formatada para o WhatsApp da recepção.


### Épico 4: Módulo Administrativo / Staff
* **US13 - Visão Geral do Treinador:** Como treinador, quero visualizar os alunos agendados no dia em cartões com alertas visuais.

* **US14 - Registro Rápido de Feedback:** Como treinador, quero registrar notas da sessão através de botões interativos para atualizar o histórico do aluno.

---

## 4. Detalhamento de User Stories

### **US04 – Alternância Dinâmica de Marcas (PKZ / One to One)**
* **Descrição:** Como visitante do site, quero poder alternar visualmente o conteúdo entre PKZ e One to One com um único clique para entender os públicos e metodologias específicas sem trocar de site.
* **Critérios de Aceite:**
  * Componente de seleção visível na seção principal.
  * Alteração de textos, imagens, faixas etárias e chamadas sem recarregar a página (*client-side*).
  * Manutenção dos padrões do Design System (predominância de azul e branco).
  * Transição suave entre a alternância dos estados.

---

### **US08 – Simulação de Agendamento de Aula Experimental**
* **Descrição:** Como usuário interessado, quero selecionar um dia e horário disponível na agenda simulada para agendar minha aula experimental.
* **Critérios de Aceite:**
  * O usuário deve selecionar previamente o programa (PKZ ou One to One).
  * Exibição clara de dias e horários livres vs. ocupados.
  * Resumo dos dados antes do direcionamento final.
  * Validação do preenchimento do nome do aluno/atleta.

---

### **US09 – Integração de Conversão via WhatsApp**
* **Descrição:** Como usuário que concluiu a seleção da aula ou tirou dúvidas no FAQ, quero ser redirecionado ao WhatsApp com mensagem pronta para acelerar a matrícula.
* **Critérios de Aceite:**
  * O botão de CTA deve gerar um link `https://wa.me/...` funcional.
  * A mensagem deve concatenar automaticamente: Programa + Dia/Horário + Nome do Aluno.
  * Compatibilidade com navegadores desktop e dispositivos móveis.

---

## 5. Definições de Qualidade (DoR & DoD)

+-----------------------------------------------------------------------+
|                     DEFINITION OF READY (DoR)                         |
|  1. User Story no formato "Como / Quero / Para".                       |
|  2. Critérios de aceite validados pelo PO.                             |
|  3. Protótipo/Wireframe da tela disponível no Figma.                  |
|  4. Dependências técnicas identificadas.                              |
+-----------------------------------------------------------------------+
|
v
+-----------------------------------------------------------------------+
|                     DEFINITION OF DONE (DoD)                          |
|  1. Código desenvolvido e modularizado em componentes.                |
|  2. Layout 100% responsivo (Mobile, Phablet e Desktop).               |
|  3. Suporte aos modos Light e Dark implementado.                      |
|  4. Contraste e acessibilidade validados (WCAG AA).                   |
|  5. Code review aprovado no repositório Git.                          |
|  6. Homologação efetuada pelo Product Owner.                          |
+-----------------------------------------------------------------------+

---

## 6. Governança e Ritos Scrum

* **Sprint Planning:** Realizada no início de cada ciclo de 2 semanas (1h). Definição do *Sprint Goal* e seleção dos itens do backlog.
* **Weekand Scrum:** Encontros semanais de 15 minutos para alinhamento de progresso e identificação de impedimentos.
* **Sprint Review:** Apresentação dos componentes e fluxos construídos ao final de cada Sprint (30 min).
* **Sprint Retrospective:** Análise interna da equipe sobre processos, uso do Git/Figma e pontos de melhoria técnica (30 min).