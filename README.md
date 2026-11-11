# 💸 App Moedas no Lugar - PauloMedeiros-  App de Finanças Pessoais com Vibe Codding

Sobre o Projeto

O Moedas no Lugar é um aplicativo de finanças pessoais com foco em simplicidade, acessibilidade e educação financeira.

A proposta é permitir que usuários registrem gastos, acompanhem metas financeiras e recebam orientações através de uma experiência conversacional em linguagem natural, reduzindo a complexidade comum dos aplicativos financeiros tradicionais.
Foi um desafio da DIO criar um app de finanças usando Vibe Coding com PRD.



PRD refinado no Copilot

# AI-OPTIMIZED PRD
# Assistente Financeiro Conversacional

## Product Vision

Criar um aplicativo de finanças pessoais baseado em conversação que permita ao usuário registrar despesas, acompanhar metas financeiras e receber orientações educativas apenas conversando em linguagem natural.

O principal objetivo é reduzir a complexidade normalmente associada ao controle financeiro pessoal.

O produto deve funcionar como um Agente Financeiro Educacional, não como um consultor financeiro profissional.

---

# Problem Statement

Muitas pessoas abandonam aplicativos de controle financeiro porque:

- Exigem entrada manual excessiva.
- Possuem interfaces complexas.
- Utilizam termos financeiros difíceis.
- Não geram valor imediato para o usuário.

O produto deve transformar conversas em informações financeiras estruturadas de forma simples e intuitiva.

---

# Target Audience

## Primary Users

- Iniciantes em finanças pessoais.
- Pessoas sem experiência com aplicativos financeiros.
- Usuários que desejam criar hábitos financeiros saudáveis.

## Secondary Users

- Estudantes.
- Jovens profissionais.
- Famílias.
- Usuários interessados em educação financeira.

---

# Core Product Principle

Se o usuário não entender uma funcionalidade em menos de 10 segundos, a interface deve ser simplificada.

A simplicidade deve sempre ter prioridade sobre a quantidade de funcionalidades.

---

# Universal Design Requirement (Mandatory)

Toda solução gerada deve seguir princípios de Design Universal.

Objetivo:

Permitir que o maior número possível de pessoas utilize o produto independentemente de:

- Idade.
- Conhecimento tecnológico.
- Limitações motoras.
- Limitações cognitivas.
- Limitações visuais.

Requisitos obrigatórios:

- WCAG 2.2 nível AA.
- Alto contraste.
- Navegação por teclado.
- Compatibilidade com leitores de tela.
- Tipografia escalável.
- Componentes acessíveis.
- Linguagem simples.
- Baixa carga cognitiva.
- Mobile-first.
- Responsividade completa.

Nenhuma tela deve depender exclusivamente de cor para transmitir informação.

Todos os ícones devem possuir texto auxiliar.

---

# Functional Requirements

## FR01 - Conversational Expense Tracking

Usuário deve conseguir registrar gastos em linguagem natural.

Exemplos:

"Gastei R$ 80 no mercado."

"Paguei R$ 120 de gasolina."

"Comprei um lanche por R$ 25."

O sistema deve extrair:

- Valor
- Categoria
- Data
- Descrição

Sem exigir preenchimento manual adicional.

---

## FR02 - Automatic Categorization

Categorias padrão:

- Alimentação
- Transporte
- Moradia
- Saúde
- Educação
- Lazer
- Compras
- Contas
- Investimentos
- Outros

Usuário pode corrigir categorias.

O sistema deve aprender preferências futuras.

---

## FR03 - Financial Goals

Usuário pode criar metas.

Exemplos:

- Reserva de Emergência
- Viagem
- Computador
- Automóvel

Cada meta deve exibir:

- Valor objetivo
- Valor acumulado
- Percentual concluído
- Estimativa de conclusão

---

## FR04 - Financial Coach

O sistema deve gerar orientações educativas.

Exemplos:

- Dicas de economia
- Hábitos financeiros
- Alertas de excesso de gastos
- Incentivos ao planejamento

Tom:

- Educativo
- Positivo
- Motivador

Nunca culpabilizar o usuário.

---

## FR05 - Reports

Disponibilizar:

- Gastos mensais
- Gastos por categoria
- Evolução financeira
- Metas
- Tendências

Visualização simples e intuitiva.

---

## FR06 - Investment Education

Fornecer conteúdo educativo sobre:

- Tesouro Selic
- CDB
- ETF
- Previdência
- Fundos

Restrições:

- Não fornecer recomendação profissional.
- Não prometer rentabilidade.
- Não sugerir ativos específicos para compra.

---

## FR07 - Fraud Prevention

Apresentar conteúdos educativos sobre:

- Golpes financeiros
- Phishing
- Engenharia social
- Pirâmides financeiras
- Fraudes digitais

Exibir alertas preventivos regularmente.

---

# AI Assistant Behavior

Nome do Assistente:

Agente Financeiro

Personalidade:

- Educado
- Didático
- Acessível
- Motivador
- Objetivo

Deve agir como:

- Educador financeiro
- Organizador financeiro

Não deve agir como:

- Assessor financeiro
- Consultor de investimentos
- Planejador patrimonial

Jamais:

- Prometer ganhos.
- Prometer retorno financeiro.
- Garantir resultados.

---

# User Stories

## Registro de Gastos

Como usuário

Quero registrar gastos através de conversa

Para evitar preenchimento manual.

### Acceptance Criteria

- O sistema identifica valor.
- O sistema identifica categoria.
- O sistema sugere descrição.
- O processo leva menos de 10 segundos.

---

## Metas

Como usuário

Quero criar metas financeiras

Para acompanhar meu progresso.

### Acceptance Criteria

- Criação em menos de 30 segundos.
- Visualização imediata do progresso.
- Atualização automática.

---

## Relatórios

Como usuário

Quero entender para onde meu dinheiro está indo

Para melhorar minhas decisões financeiras.

### Acceptance Criteria

- Relatórios simples.
- Gráficos legíveis.
- Linguagem não técnica.

---

# Main User Flows

## Fluxo 01

Registrar gasto

Home
→ Chat
→ Mensagem do usuário
→ IA interpreta
→ Transação criada
→ Confirmação

---

## Fluxo 02

Criar meta

Home
→ Metas
→ Nova Meta
→ Definição de valor
→ Meta criada

---

## Fluxo 03

Consultar situação financeira

Home
→ Relatórios
→ Resumo mensal
→ Insights da IA

---

# Screens

## Dashboard

Objetivo:

Fornecer visão geral da vida financeira.

Componentes:

- Saldo estimado
- Gastos do mês
- Metas
- Atalho para chat
- Alertas

---

## Chat

Objetivo:

Centralizar interação com o usuário.

Componentes:

- Conversa
- Sugestões rápidas
- Histórico de mensagens

---

## Transactions

Componentes:

- Lista de transações
- Busca
- Filtros
- Edição

---

## Goals

Componentes:

- Metas
- Evolução
- Indicadores

---

## Reports

Componentes:

- Gráficos
- Categorias
- Tendências

---

## Learning Center

Componentes:

- Economia
- Investimentos
- Segurança Financeira

---

# Technical Requirements

Frontend:

- React
- TypeScript
- TailwindCSS
- Shadcn/UI

Backend:

- Supabase

Database:

- PostgreSQL

Authentication:

- Supabase Auth

AI Layer:

- OpenAI API

Charts:

- Recharts

Hosting:

- Vercel

---

# Initial Database Schema

Users

- id
- name
- email
- created_at

Transactions

- id
- user_id
- value
- category
- description
- transaction_date
- created_at

Goals

- id
- user_id
- title
- target_amount
- current_amount
- target_date

Messages

- id
- user_id
- role
- content
- created_at

---

# Success Metrics

MVP será considerado validado se:

- 80% dos usuários registrarem um gasto sem ajuda.
- Tempo médio de registro inferior a 30 segundos.
- Retenção de 7 dias acima de 30%.
- NPS superior a 40.
- Precisão de categorização acima de 80%.

---

# MVP Scope

Incluir:

- Chat financeiro
- Registro de gastos
- Metas financeiras
- Relatórios
- Educação financeira
- Alertas de segurança

Não incluir:

- Open Finance
- Integração bancária
- Cartão
- PIX
- Transferências
- Compra de investimentos
- Consultoria financeira

---

# Expected Output From Lovable

Gerar uma aplicação completa com:

- Design moderno
- Mobile-first
- Design Universal
- Componentes acessíveis
- Estrutura escalável
- Banco de dados configurado
- Fluxos funcionais
- Dados simulados para demonstração

Priorizar usabilidade e simplicidade acima de funcionalidades avançadas.
...
Interações com o Lovable

> Como você quer organizar o chat com o Agente Financeiro?
Uma conversa única
> Além de e-mail e senha, o que guardar no perfil de cada pessoa?
Nome de exibição, Renda mensal
> Qual estilo visual combina mais com o app?
Azul sereno
> 
Resultado: https://caminho-do-equil.lovable.app
modelo simples sem interação: https://moedas-no-lugar.lovable.app/

<img width="1329" height="607" alt="image" src="https://github.com/user-attachments/assets/79aaa5ae-7af1-46b4-88e3-a18649bcfd51" />


<img width="484" height="2268" alt="image" src="https://github.com/user-attachments/assets/45952296-8aae-4569-99d7-edc65431011c" />


Reflexão sobre o Projeto:
- Um bom PRD otimiza de forma significativa a construção do processo deixando os critérios, requerimentos, modos de ação e criação muito mais fácil e intuitivo  sem contar na economia ao usar os créditos por deixar já estruturado.
- O que funcionou bem?
  *A transformação do PRD em uma aplicação funcional foi rápida.
  *O refinamento iterativo através de perguntas do Lovable ajudou a definir melhor os requisitos.
  *A abordagem natural facilitou a prototipação sem ser necessário conhecimento aprofundado de programação.
- O que não funcionou bem?
   *Foi necessário revisar e ajustar requisitos para obter resultados mais alinhados à proposta.
   *Alguns detalhes precisaram de refinamento manual.
- O que aprendeu sobre conversar com IAs?
   Um PRD estruturado produz assim como um prompt bem especificados produzem melhores resultados e que a IA trabalha melhor quanto mais contexto, objetivos claros recebe.


> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
