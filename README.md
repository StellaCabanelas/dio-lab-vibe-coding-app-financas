# Trocado 💸

## Sobre o projeto

O **Trocado** é um aplicativo de finanças pessoais que simplifica o controle financeiro por meio de uma interface conversacional. Em vez de preencher formulários ou planilhas, o usuário registra receitas e despesas escrevendo mensagens em linguagem natural.

O sistema interpreta as informações fornecidas, identifica valores e categorias automaticamente, atualiza o saldo do usuário e gera relatórios para acompanhamento financeiro.

---

## Objetivo

Desenvolver uma experiência simples e intuitiva para gerenciamento de finanças pessoais, utilizando IA para transformar conversas em registros financeiros organizados.

---

## PRD (Prompt Final)
```txt
# Documento de Requisitos do Produto (PRD)
# Aplicativo de Organização de Finanças Pessoais Conversacional

# 1. Visão Geral
O aplicativo tem como objetivo ajudar jovens adultos (20–29 anos) a organizar suas finanças de forma prática e acessível, utilizando uma interface baseada em conversas. A proposta é substituir planilhas e formulários complexos por interações naturais e recomendações personalizadas.

# 2. Problema
Muitos usuários desistem de controlar seus gastos porque os aplicativos atuais exigem muita entrada manual e oferecem pouca personalização. O MVP busca resolver isso com uma experiência de chat simples e relatórios claros.

# 3. Público-Alvo
- Jovens adultos entre 20–29 anos
- Pessoas iniciantes em organização financeira
- Usuários que buscam praticidade e linguagem acessível

# 4. Funcionalidades-Chave
1. Registro de gastos via chat em linguagem natural
2. Classificação automática das transações
3. Definição e acompanhamento de metas financeiras
4. Dicas de economia do “Agente Financeiro” em tom descontraído
5. Relatórios simples e personalizados

# 5. Principais Telas
- Tela de Conversa: registro de gastos e interação com o agente
- Tela de Metas: definição e acompanhamento de objetivos
- Tela de Relatórios: gráficos básicos e insights semanais/mensais
- Tela de Dicas: recomendações de economia personalizadas

# 6. Recursos Necessários
- Processamento de linguagem natural para interpretar mensagens
- Algoritmo de classificação automática de transações
- Banco de dados para armazenar gastos e metas
- Sistema de relatórios com visualizações básicas
- Motor de recomendações para dicas de economia

# 7. Validação Inicial
- Teste com grupo piloto de 10–20 jovens adultos
- Métricas principais:
  - Facilidade de registro de gastos
  - Engajamento com dicas
  - Retenção semanal
- Feedback qualitativo sobre experiência de uso e substituição de planilhas
      
# 8. Próximos Passos
- Criar protótipo navegável com foco nas telas de Conversa e Relatórios
- Validar com usuários reais antes de expandir para funcionalidades avançadas
```
---
### Prompt utilizado do Lovable

Crie um app de finanças com base no seguinte PRD (product requirements document):

---

### Exemplos de Interação no APP

**Entrada**

> Recebi meu salário hoje. Foram 4000 reais.

**Saída**

> Entrada de R$ 4.000,00 registrada na categoria Salário.

**Entrada**

> Gastei 50 reais de Uber.

**Saída**

> Registrei R$ 50,00 na categoria Transporte.

**Entrada**

> Comprei uma roupa de 160 reais.

**Saída**

> Registrei R$ 160,00 na categoria Compras.

---

## Prints das Interações com a IA

### Conversa com o assistente financeiro

<img width="807" height="618" alt="Captura de Tela 2026-09-27 às 18 08 18" src="https://github.com/user-attachments/assets/dd0df262-9057-4eb3-8ee6-4993e4d49dcd" />

O usuário registra movimentações financeiras em linguagem natural e o assistente interpreta automaticamente os dados para criar os lançamentos.

### Metas financeiras

<img width="872" height="577" alt="Captura de Tela 2026-09-27 às 18 08 33" src="https://github.com/user-attachments/assets/d6234f7f-1644-4c10-976f-ec4037e490f8" />

Tela para criação e acompanhamento de objetivos financeiros, permitindo visualizar o progresso acumulado.

### Relatórios

<img width="786" height="633" alt="Captura de Tela 2026-09-27 às 18 09 07" src="https://github.com/user-attachments/assets/7e523df7-3766-42f0-a99a-113046ceb084" />

Painel com indicadores financeiros, distribuição de gastos por categoria e resumo do período selecionado.

### Dicas

<img width="779" height="621" alt="Captura de Tela 2026-09-27 às 18 09 50" src="https://github.com/user-attachments/assets/dfa38ee7-52a0-42de-94a8-b2c58c645aad" />

Tela com dicas gerada pela própria IA baseado no relatório do usuário.

---

## O que o aplicativo faz

O Trocado permite que usuários:

- Registrem receitas e despesas por conversa.
- Acompanhem saldo financeiro em tempo real.
- Organizem gastos por categoria.
- Criem metas de economia.
- Visualizem o progresso das metas.
- Consultem relatórios financeiros semanais e mensais.
- Identifiquem quais categorias consomem mais recursos.
- Tenham uma experiência mais simples e acessível para educação financeira.

---

## Reflexão sobre o Processo

### O que funcionou bem?

- A velocidade de desenvolvimento utilizando IA.
- A geração inicial das interfaces.
- A prototipação rápida das funcionalidades.
- A facilidade de transformar ideias em telas funcionais.

### O que não funcionou como o esperado?

- Foi necessário validar e ajustar detalhes da experiência do usuário manualmente.

### O que aprendi sobre conversar com IAs?

- Prompts mais específicos geram resultados melhores.
- Dividir requisitos em etapas facilita a geração de funcionalidades.
- A IA funciona melhor quando recebe contexto claro e exemplos.
- O processo é iterativo e exige testes constantes.
- A IA acelera o desenvolvimento, mas não substitui a validação do desenvolvedor.

---

## Tecnologias Utilizadas

- Lovable
- Copilot
- Inteligência Artificial Generativa
