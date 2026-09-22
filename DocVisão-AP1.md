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

## Escopo do Sistema

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

## Problemas a serem resolvidos

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