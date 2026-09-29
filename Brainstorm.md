# Brainstorming — AP1 (PKZ One to One)

## 1. Mapeamento de Problemas x Ideias de Solução (UX/UI)

* **Problema: Fragmentação da marca e dúvida no cliente sobre o espaço físico.**
  * *Causa:* Apresentar PKZ e One to One como empresas separadas passa a ideia de locais distintos.
  * *Ideia de Solução:* **Paleta e Design System Unificados.** Usar uma base visual única em azul (`#00bbff`, `#014c6f`, `#06121A`) e branco para passar a ideia de que é tudo uma empresa só (*Dual Branding* integrado).

* **Problema: Perda de foco e confusão no primeiro contato.**
  * *Causa:* Colocar botões de escolha e menus complexos logo no topo assusta quem ainda não conhece a proposta.
  * *Ideia de Solução:* **Nada de botão logo de cara!** Primeiro vem uma apresentação institucional acolhedora da marca mãe na *Hero Section*. Depois que a pessoa entende o ecossistema, ela escolhe para onde ir.

* **Problema: Sobrecarga de mensagens repetitivas no WhatsApp.**
  * *Causa:* Perguntas frequentes sobre horários, faixas etárias e metodologias chegam direto na recepção.
  * *Ideia de Solução:* **Juntar Contatos + FAQ na mesma seção.** Usar o formato de *Accordion* (sanfona) para a pessoa tirar as dúvidas antes de clicar no botão de atendimento, filtrando chamados desnecessários.

* **Problema: Fricção e demora no agendamento de aulas experimentais.**
  * *Causa:* Dificuldade em visualizar dias e horários livres sem trocar várias mensagens.
  * *Ideia de Solução:* **Simular uma agenda visual.** Criar um componente onde a pessoa bate o olho e já vê os dias e horários vagos de forma intuitiva.

* **Problema: Incomodo visual ao acessar em ambientes escuros.**
  * *Causa:* Telas muito claras incomodam alunos e atletas consultando treinos à noite.
  * *Ideia de Solução:* **Modo Claro / Escuro.** Ter os dois temas disponíveis através de uma chave seletora (*toggle*) na interface.

---

## 2. Brainstorming da Landing Page & Navegação

* **Apresentação Institucional (Hero Section):**
  * Mensagem central unificada: *"Uma só proposta: mais performance para todas as fases."*
  * Apresentação da estrutura física compartilhada antes de qualquer divisão.

* **Seção de Decisão ("Qual é o seu caminho?"):**
  * **Botão PKZ:** Direciona visualmente para a frente de 7 a 15 anos (preparação física esportiva, desenvolvimento e alto rendimento infanto-juvenil).
  * **Botão One to One:** Direciona para a frente de 17 a 90 anos (musculação, treino funcional e condicionamento para adultos/idosos).

* **Galeria da Estrutura Física:**
  * Fotos da academia com pontos clicáveis (*hotspots*) detalhando equipamentos e ambientes.

* **Quiz Interativo de Recomendação:**
  * Perguntas rápidas sobre idade e objetivo para recomendar o plano correto automaticamente.

---

## 3. Brainstorming do Módulo de Agendamentos

* **Conceito Visual:** *"Bater o olho e identificar"*.
* **Fluxo de Escolha:**
  1. Selecionar a modalidade (PKZ ou One to One).
  2. Visualizar os dias com vagas destacadas no calendário.
  3. Clicar no horário vago desejado.
  4. Gerar mensagem pré-formatada para confirmação final via WhatsApp.

---

## 4. Brainstorming dos Dashboards (Área do Aluno e Staff)

* **Dashboard do Aluno / Atleta (Foco em Evolução):**
  * **Gráfico de Radar:** Exibição visual das valências físicas dos 16 testes.
  * **Gráfico de Linha:** Histórico de evolução ao longo do tempo.
  * **Comparativo Lado a Lado:** Comparação direta de duas avaliações anteriores.
  * **Notas do Treinador:** Observações técnicas do avaliador.
  * **Exportação em PNG:** Download do cartão de desempenho para compartilhamento.

* **Dashboard do Treinador / Staff (Foco Operacional):**
  * **Visão Diária:** Cartões com a lista de alunos agendados para o dia.
  * **Sinalizações Visuais Rápidas (*Badges*):**
    * 🔴 *Alerta de Dor:* Aluno com desconforto recente.
    * 🟡 *Carga Elevada:* Aluno em fase picos de treino.
    * 🔵 *Treino Regular:* Acompanhamento padrão.
  * **Feedback Rápido:** Botões clicáveis de observações para a próxima sessão (ex.: *Ajustar carga*, *Foco em mobilidade*).

---

## 5. Brainstorming de Governança, Sprints e Qualidade

* **Divisão de Sprints (Marco de entrega: À definir):**
  * *Sprint 0 (24/08 a 06/09):* Levantamento de requisitos, Visão do Produto e 5W2H.
  * *Sprint 1 (07/09 a 20/09):* Protótipo no Figma, Design System e modo claro/escuro.
  * *Sprint 2 (21/09 a 04/10):* Shell do site, alternância PKZ/One to One, galeria e FAQ.
  * *Sprint 3 (05/10 a 18/10):* Simulação da agenda, quiz e integração com WhatsApp.
  * *Sprint 4 (19/10 a 28/10):* Dashboard com gráficos, testes de responsividade e entrega.

* **Critérios de Entrada (Definition of Ready - DoR):**
  * Nenhuma tarefa entra na Sprint sem User Story clara (*Como/Quero/Para*), critérios de aceite, protótipo desenhado no Figma e dependências mapeadas.

* **Critérios de Saída (Definition of Done - DoD):**
  * A tarefa só é considerada pronta se estiver codificada em componentes reutilizáveis, 100% responsiva (Mobile/Desktop), testada nos temas claro/escuro, com contraste acessível (WCAG AA) e aprovada no *code review* e pelo PO.