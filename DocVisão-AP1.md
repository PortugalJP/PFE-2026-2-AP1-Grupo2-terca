# Documento de Visão - AP1

# 1. Introdução

## 1.1 Objetivo do documento
  
  Este Documento de Visão tem como objetivo definir, alinhar e detalhar o escopo, as diretrizes estratégicas e os requisitos fundamentais para o desenvolvimento da plataforma web/front-end da *__PKZ e One to One__*. 
 
  O propósito deste documento é orientar a equipe técnica e de produto na construção de toda a aplicação no lado do cliente (client-side). Ele abrange a *__estrutura das páginas, componentes de interface, interações do usuário e a integração dos módulos da plataforma — como a segmentação das marcas (PKZ e One to One)__*.


 ## 1.2 Público-Alvo

Este documento contempla os diferentes perfis de usuários que interagirão com a interface da plataforma web da *__PKZ e One to One__*, categorizados entre usuários externos e internos conforme suas necessidades de uso e navegação:

*__Visitantes / Alunos em Potencial (Leads)__*: Pessoas interessadas em conhecer o centro de treinamento. Necessitam de uma navegação fluida na landing page, entendimento claro sobre os diferenciais entre as marcas e pontos diretos de conversão para agendamento de aula experimental (via WhatsApp).

*__Pais e Responsáveis por Atletas (PKZ – 7 a 15 anos)__*: Responsáveis por atletas infantojuvenis que acessarão o painel para acompanhar o desenvolvimento físico dos jovens.

*__Alunos Adultos (One to One – 17 a 90 anos)__*: Praticantes de musculação e treinamento convencional que buscam uma interface objetiva e de fácil acesso para visualizar informações sobre seus treinos e horários.

*__Equipe de Desenvolvimento Front-End e Designers UX/UI__*: Desenvolvedores e designers responsáveis por construir o layout, aplicar o design system e implementar as interações de tela descritas neste documento.

## 1.3 Escopo do Sistema

O escopo desta aplicação abrange exclusivamente o desenvolvimento front-end da plataforma web da PKZ One to One, contemplando o layout, os componentes de interface, a responsividade e o comportamento no lado do cliente (client-side).

### 1.3.1 Funcionalidades e Telas Incluídas no Escopo
Website Institucional e Landing Page de Conversão:

* Apresentação Institucional: Interface demonstrando a marca unificada PKZ One to One e a divisão operacional dos espaços físicos.

* Segmentação Visual de Marcas: Seções dedicadas para diferenciação clara entre a PKZ (treinamento complexo e alto rendimento infanto-juvenil) e a One to One (musculação e condicionamento para adultos).

* Galeria de Fotos do Espaço: Exibição de ambientes internos e equipamentos para valorização da estrutura.

* Seção de Dúvidas Frequentes (FAQ): Componente sanando dúvidas sobre metodologias, modalidades esportivas e horários, omitindo intencionalmente tabelas de preços estáticas.

* Pontos de Conversão (CTAs): Botões e formulários diretos integrados ao WhatsApp para agendamento de aulas experimentais e atendimento personalizado.

### Design System e Interface (UI/UX):

* Identidade Visual: Aplicação rigorosa da paleta de cores institucional (predominância de azul e branco). Sendo a paleta de cores da __One to One e PKZ__ compostas por: #b3ecff, #00bbff, #014c6f, #000000.

* Componentes Reutilizáveis: Construção de botões, cards, modais e formulários padronizados.

* Responsividade: Layout adaptável para dispositivos móveis, tablets e desktops.


---
 **No dia 15/09/2026, à fim de nos informar, foi-nos dito pelo cliente que em virtude de não haver um manual de marca específico para a PKZ, poderíamos utilizar as mesmas instruções de marca da One to One nos projetos relacionados à PKZ.**
---

# 2. Posicionamento

## 2.1 Oportunidades de Mercado

O mercado de preparação física e academias de alto rendimento enfrenta desafios constantes na comunicação visual de valor, na retenção de alunos e na clareza na prestação de contas dos resultados obtidos. A plataforma web da PKZ One to One surge para capitalizar as seguintes oportunidades estratégicas por meio de uma experiência front-end moderna e centralizada.

* __Segmentação Visual Eficiente de Públicos (Dual Branding):__
Geralmente, academias falham ao tentar se comunicar simultaneamente com públicos díspares. A aplicação front-end permite criar uma arquitetura de navegação intuitiva que separa e valoriza o posicionamento da PKZ (atletas infanto-juvenis e treino complexo) e da One to One (musculação e condicionamento para adultos), sem perder a unidade da marca mãe.

* __Otimização do Fluxo de Conversão (Lead Generation sem Fricção):__
A ausência de preços engessados e a substituição de tabelas estáticas por pontos de contato dinâmicos (CTAs focados em agendamento de aulas experimentais) permitem engajar o visitante e direcioná-lo diretamente para a conversão via WhatsApp, onde a negociação personalizada acontece de forma humanizada.

## 2.2 Problemas a serem resolvidos

* Sobrecarga de Atendimento por Dúvidas Repetitivas:
Alto volume de mensagens no WhatsApp perguntando sobre funcionamento, horários e metodologias, devido à falta de uma central de informações clara e acessível no site.

* Falta de Clareza na Diferenciação das Marcas (PKZ vs. One to One):
Dificuldade do público em compreender que, embora façam parte da mesma estrutura, a PKZ foca no público infanto-juvenil com treino complexo e a One to One atende o público adulto com musculação e treino convencional.

## 2.3 Proposta de Solução

A plataforma web front-end resolverá esses problemas por meio de uma experiência de usuário (UX) estruturada e focada em clareza, conversão e acompanhamento didático:

* __Landing Page de Alta Conversão com FAQ Dinâmico:__
Criação de uma seção de dúvidas frequentes que responde claramente sobre metodologia e horários e inserindo botões de ação (CTAs) estratégicos para agendamento de aula experimental e negociação personalizada via WhatsApp.

* __Segmentação Visual e Intuitiva das Marcas:__
Desenvolvimento de uma arquitetura de navegação com páginas e blocos específicos para PKZ (7 a 15 anos) e One to One (17 a 90 anos), permitindo que cada perfil de visitante identifique instantaneamente a proposta adequada às suas necessidades.

* __Design System Unificado e Galeria de Fotos:__
Aplicação do design system institucional (predominância de azul e branco) combinado a uma galeria de imagens atualizadas do espaço físico e equipamentos, transmitindo profissionalismo e modernidade.

-------

## 3. *Descrição de Stakeholders e Usuários*

### 3.1 *Resumo dos Stakeholders*

- **Proprietários da academia** — são os responsáveis pela decisão estratégica e financeira do projeto. Buscam um site que amplie a captação de atletas, fortaleça a marca e otimize a gestão do negócio.
- **Equipe técnica/administrativa** —  composta por treinadores, preparadores físicos e recepcionistas que operam o sistema no dia a dia, alimentando dados de treino e desempenho dos atletas.
- **Equipe de desenvolvimento** — responsável por projetar, implementar e manter o site conforme os requisitos levantados pelos demais stakeholders.

---

### 3.2 **Resumo dos usuários**

- **Administrador** - (proprietário/staff): usuário que gerencia o site e a operação da academia através do sistema. É responsável por cadastrar atletas, criar e editar planos de treino, gerenciar agendamentos e acompanhar relatórios de desempenho e financeiros.

- **Atleta/Aluno** - usuário final que consome os serviços da academia através do site. Utiliza o sistema para visualizar treinos personalizados, acompanhar sua evolução de performance, agendar sessões e se comunicar com treinadores.

-**Visitante** - usuário não cadastrado que navega pelo site em busca de informações institucionais, planos e serviços oferecidos, geralmente como etapa anterior à matrícula.

---

### 3.3 *Ambiente do usuário*
Os administradores e a equipe de staff acessam o sistema majoritariamente por meio de desktop ou notebook, dentro da própria academia, em ambiente de trabalho com conexão estável, frequentemente durante o expediente e entre atendimentos.
Atletas e alunos acessam o site predominantemente via dispositivos móveis (smartphones), em diversos contextos do dia a dia — antes ou depois dos treinos, em trânsito, em casa —, o que exige uma interface responsiva e de fácil uso mesmo em conexões instáveis.
Já os visitantes, acessam tanto por desktop quanto por mobile, geralmente vindos de redes sociais, buscadores ou indicações, estando em seu primeiro contato com a marca.

---

### 3.4 *Necessidades-Chave dos Stakeholders*
Os proprietários da academia têm como necessidades prioritárias uma ferramenta de gestão centralizada que reúna alunos, treinos e agenda em um só lugar, além do aumento da captação de novos atletas por meio do site. Também valorizam relatórios de desempenho do negócio e uma imagem profissional e confiável da marca.

A equipe de staff necessita, principalmente, de uma redução do trabalho manual e administrativo, com processos mais ágeis de cadastro e acompanhamento dos alunos.

Os atletas, por sua vez, priorizam o acesso fácil e rápido aos treinos do dia e o acompanhamento visual da sua evolução de performance, além de uma comunicação direta e simples com seus treinadores.

---

###4. Visão Geral do Produto

O produto a ser desenvolvido é um site institucional com múltiplas páginas que centraliza a presença digital de uma empresa esportiva detentora de duas academias: a **PKZ** (foco em atletas de alto rendimento infanto-juvenis, de 7 a 16 anos) e a **One-to-One** (foco em atletas amadores e público em geral de 17+ anos buscando saúde e condicionamento). O objetivo da interface é distribuir essas informações de forma organizada, deixando claro que ambas as frentes fazem parte da mesma metodologia e do mesmo ecossistema, direcionando o usuário para o serviço correto.

### 4.1 Principais funcionalidades
No contexto da interface e da interação do usuário (Front-End), o sistema contará com:

* **Identidade Visual Unificada:** Uma estrutura de navegação distribuída em várias páginas, mas com um design que não fará divisões abruptas de marca. A interface utilizará os mesmos padrões visuais, paleta de cores e tipografia em todo o site para reforçar ao público que a PKZ e a One-to-One são a mesma empresa, trabalhando juntas de forma coesa.

* **Apresentação de Metodologia e Corpo Docente:** Páginas ou seções da interface dedicadas a exibir de forma clara os professores e a forma como trabalham. Isso será construído visualmente com galerias e *cards* informativos que destacam a especialidade de cada profissional.

* **Módulo de Dúvidas Frequentes (FAQ) Interativo:** Implementação de um componente *Accordion* (sanfona interativa), permitindo que o visitante clique nas perguntas para expandir as respostas, mantendo a página limpa e organizada.

* **Integração de Localização:** Exibição interativa de mapas integrados à interface para que o usuário saiba exatamente onde as instalações estão localizadas.

* **Fluxo Direcionado de Contato e Conversão:** A interface guiará o usuário de forma fluida e intencional pela navegação até alcançar o ponto central de contato. Esse fluxo conduzirá o cliente de maneira natural para a área onde ele poderá agendar a sua primeira aula e consultar qual pacote melhor se encaixa no seu orçamento.

### 4.2 Diferenciais em relação a soluções existentes
Enquanto muitos sites de academias apresentam navegação confusa ou separam completamente suas submarcas (gerando dúvida no cliente), esta solução se destaca por:

* **Foco Total em Conversão e Usabilidade:** O diferencial da interface é o seu layout otimizado para exibir menus de navegação claros, informações detalhadas e imagens de alta qualidade das instalações, garantindo um agendamento rápido e sem distrações visuais.

* **Jornada do Usuário (UX) Direcionada:** A interface consegue pegar dois públicos muito distintos (o responsável por um atleta de 10 anos e um adulto buscando emagrecimento) e guiá-los pelas páginas do site sem atritos, mantendo a percepção de uma empresa sólida e de metodologia única.

* **Consistência e Clareza na Navegação:** Mesmo sendo um site com várias páginas, o front-end focará em transições consistentes, garantindo que o usuário nunca se sinta "saindo" de uma academia e entrando em outra, mas sim navegando pelos diferentes serviços oferecidos pela mesma instituição de excelência.

-------

## *5. Requisitos de Alto Nível*

### *Requisitos Funcionais*

- __Alternância entre Marcas:__ A interface deverá permitir alternar entre PKZ e One to One, adaptando os textos, as imagens e as chamadas de ação sem recarregar a página.
- __Contato pelo WhatsApp:__ A interface deverá disponibilizar botões para abrir o WhatsApp com mensagens pré-formatadas conforme a marca e a seção selecionadas, facilitando o agendamento de aulas experimentais e a solicitação de informações.
- __Quiz Interativo:__ A interface deverá apresentar perguntas sobre objetivo, faixa etária e frequência de treino, exibir uma recomendação de pacote com base nas respostas e oferecer um botão para solicitar orçamento personalizado pelo WhatsApp.
- __Galeria Interativa:__ A interface deverá permitir a navegação por fotos dos ambientes e equipamentos, com pontos clicáveis que apresentem informações sobre a finalidade de cada espaço ou equipamento.
- __Painel de Desempenho:__ A interface deverá permitir que pais e alunos visualizem os resultados dos 16 testes físicos em gráficos de evolução e de radar, com acesso às notas técnicas do treinador associadas às avaliações.
- __Comparação de Avaliações:__ A interface deverá permitir a seleção de duas datas de avaliação para comparar os resultados lado a lado, destacando as variações percentuais de desempenho.
- __Exportação de Relatórios:__ A interface deverá permitir gerar e baixar um relatório visual em formato de imagem (PNG), contendo gráficos e notas técnicas, para facilitar o compartilhamento dos resultados.
- __Agenda dos Treinadores:__ A interface deverá apresentar os alunos agendados para o dia em cartões com sinalizações de dor relatada, carga elevada ou treino regular, facilitando a consulta antes de cada atendimento.
- __Feedback Rápido:__ A interface deverá oferecer opções clicáveis para registrar observações da sessão, como dor, foco em mobilidade, treino intenso e ajuste de carga, compondo automaticamente uma nota para o próximo atendimento.

### *Requisitos Não Funcionais*

- __Interface Amigável:__ A plataforma deverá possuir uma interface intuitiva, objetiva e de fácil utilização, com navegação clara para visitantes, alunos, responsáveis e treinadores.
- __Responsividade:__ A interface deverá adaptar-se a celulares, tablets e computadores, mantendo textos legíveis e botões com tamanho e espaçamento adequados à interação por toque.
- __Consistência Visual:__ A interface deverá seguir a identidade visual das marcas, mantendo a base institucional em azul e branco, com destaques específicos para PKZ e One to One e padronização de botões, cartões e formulários.
- __Acessibilidade:__ A interface deverá apresentar contraste adequado, permitir navegação por teclado e identificar alertas com textos ou ícones, sem depender exclusivamente de cores.
- __Desempenho:__ A interface deverá otimizar o carregamento de imagens e gráficos e apresentar transições suaves, sem bloquear a navegação ou a interação com os componentes.

---

## *6. Restrições e Premissas*

### *Restrições*

- __Tempo limitado.__
- __Infraestrutura limitada.__
- __Orçamento limitado.__
- __Inexistência de uma equipe de TI para manutenções e adições.__

---

## *Premissas*

- __Haverá uma ótima adesão dos clientes ao novo sistema.__
- __Haverá uma mobilização da empresa para a contratação de serviços de TI.__
- __As novas ferramentas da platafoma serão um diferencial da empresa no mercado.__
- __Profissionalização do uso da marca de forma geral.__

---
# 7. Riscos e Dependências

## 7.1 Riscos:

__Vazamento de Dados Pessoais e Sensíveis__: Risco de invasão ou brecha de segurança expor dados cadastrais dos alunos

__Fraudes em Transações de Cartão de Crédito__: Tentativas de chargeback, transações fraudulentas ou ataques do tipo brute force no checkout online.

__Queda do Servidor / Indisponibilidade__: Indisponibilidade do site em momentos críticos de campanhas de marketing ou matrículas

__Lentidão no Carregamento__: Tempo de resposta alto devido ao carregamento de mídias pesadas (vídeos de treinos, imagens de alta resolução da estrutura)


## 7.2 Depêndencias

__Acesso à Internet Móvel/Wi-Fi pelo Cliente__: O site exige que o cliente tenha uma conexão de internet estável (3G/4G/5G ou Wi-Fi) para visualizar a grade de aulas, efetuar pagamentos ou agendar aulas experimentais.


__Comunicação em Tempo Real na Recepção__: Caso o site possua uma área administrativa ou balcão de check-in integrado, a equipe da recepção da academia depende diretamente da internet local para validar cadastros e agendamentos feitos pelo site.

__Provedor de Hospedagem__ :O código-fonte do site e os bancos de dados dependem de servidores ativos e configurados com suporte a tecnologias modernas (Node.js, PHP, Python, bases de dados MySQL/PostgreSQL, etc.)


[1.  Introdução](#1-introdução) [1.1 Objetivo do documento](#11-objetivo-do-documento) [1.2 Publico alvo](#12-público-alvo) [1.3 Escopo do sistema](#13-escopo-do-sistema)

[1.3.1 Funcionalidades e telas incluídas no escopo](#131-funcionalidades-e-telas-incluídas-no-escopo) [2.Posicionamento](#2-posicionamento)


[2.1 oportuidades de mercado](#21-oportunidades-de-mercado)
