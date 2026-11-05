# 💸 App de Organização de Finanças Pessoais

PRD refinado no Copilot Web: 

```markdown
# PRD - Assistente de Finanças Pessoais Conversacional

## 1. Visão Geral do Produto

Criar um aplicativo de finanças pessoais que permita ao usuário registrar, consultar e organizar suas finanças por meio de conversas em linguagem natural.

O objetivo é substituir processos complexos de preenchimento manual por uma experiência simples baseada em chat, permitindo que qualquer pessoa acompanhe sua vida financeira sem precisar entender planilhas ou conceitos financeiros avançados.

### Princípio de Design

O produto deverá seguir os princípios de Design Universal, garantindo que a experiência seja simples, acessível e eficiente para o maior número possível de usuários, independentemente de idade, experiência com tecnologia, condições cognitivas, limitações visuais ou motoras.

A interface deve priorizar clareza, simplicidade, legibilidade e redução da carga cognitiva.

---

## 2. Problema

Grande parte das pessoas abandona aplicativos financeiros porque:

- Exigem cadastro manual constante de despesas e receitas.
- Possuem interfaces complexas.
- Requerem conhecimento financeiro prévio.
- Apresentam relatórios difíceis de interpretar.
- Não oferecem recomendações personalizadas.

Como consequência, os usuários perdem visibilidade sobre seus gastos e têm dificuldade em criar hábitos financeiros saudáveis.

---

## 3. Objetivo do Produto

Permitir que usuários iniciantes organizem suas finanças apenas conversando com um agente financeiro virtual.

Ao final da primeira semana de uso, o usuário deve ser capaz de:

- Registrar receitas e despesas.
- Entender para onde seu dinheiro está indo.
- Definir uma meta financeira simples.
- Receber sugestões práticas para economizar.

---

## 4. Público-Alvo

### Primário

Pessoas entre 18 e 45 anos que:

- Nunca utilizaram aplicativos financeiros.
- Têm dificuldade em manter planilhas.
- Desejam melhorar a organização financeira.

### Secundário

Usuários que já utilizam aplicativos financeiros, mas buscam uma experiência mais simples e conversacional.

---

## 5. Proposta de Valor

"Organize sua vida financeira conversando como se estivesse falando com um amigo especialista em finanças."

Além disso, a experiência deve ser acessível, inclusiva e utilizável pelo maior número possível de pessoas.

---

## 6. MVP - Escopo Inicial

### Funcionalidade 1: Registro de Transações por Linguagem Natural

O usuário poderá escrever mensagens como:

> Gastei R$ 45 no almoço

> Recebi R$ 2.500 de salário

O sistema deverá identificar automaticamente:

- Tipo da transação (receita ou despesa)
- Valor
- Categoria
- Data

---

### Funcionalidade 2: Classificação Automática

Categorias iniciais:

- Alimentação
- Transporte
- Moradia
- Lazer
- Saúde
- Educação
- Compras
- Salário
- Outros

A IA sugerirá a categoria automaticamente.

---

### Funcionalidade 3: Metas Financeiras

O usuário poderá criar metas como:

> Quero economizar R$ 3.000 para viajar

O sistema deverá:

- Registrar a meta.
- Exibir progresso.
- Informar percentual alcançado.

---

### Funcionalidade 4: Agente Financeiro

O assistente analisará os dados registrados e enviará insights como:

- "Você gastou 20% mais com alimentação este mês."
- "Se reduzir R$ 10 por dia em delivery, economizará R$ 300 por mês."
- "Sua meta de viagem está 65% concluída."

---

### Funcionalidade 5: Relatórios Simplificados

Visualizações:

- Gastos por categoria
- Receitas x despesas
- Evolução mensal
- Progresso das metas

Priorizar gráficos simples e fáceis de entender.

---

## 7. Fluxo Principal do Usuário

### Primeiro Acesso

1. Usuário cria conta.
2. Define objetivo financeiro principal.
3. Recebe explicação rápida sobre o aplicativo.

### Uso Diário

1. Usuário envia mensagem.
2. Sistema interpreta a mensagem.
3. Transação é registrada.
4. Usuário recebe confirmação.

Exemplo:

Usuário:

> Gastei R$ 80 no mercado hoje.

Sistema:

> Despesa registrada: R$ 80 em Alimentação.

---

## 8. Telas do MVP

### Tela 1 - Onboarding

Objetivo:

Apresentar a proposta do aplicativo.

Elementos:

- Boas-vindas
- Objetivo financeiro inicial
- Botão começar

---

### Tela 2 - Chat Principal

Objetivo:

Centro da experiência do produto.

Elementos:

- Histórico de conversas
- Campo de mensagem
- Sugestões rápidas

---

### Tela 3 - Dashboard

Objetivo:

Resumo financeiro.

Elementos:

- Saldo atual
- Gastos do mês
- Receitas do mês
- Gráficos simples

---

### Tela 4 - Metas

Objetivo:

Acompanhar objetivos financeiros.

Elementos:

- Lista de metas
- Percentual atingido
- Previsão de conclusão

---

### Tela 5 - Perfil

Objetivo:

Configurações do usuário.

Elementos:

- Dados pessoais
- Preferências
- Configurações de notificação

---

## 9. Design Universal e Acessibilidade

O sistema deverá:

- Ser utilizável por pessoas com diferentes níveis de alfabetização digital.
- Utilizar linguagem simples e sem jargões financeiros.
- Possuir contraste adequado para leitura.
- Utilizar fontes legíveis e escaláveis.
- Funcionar adequadamente em dispositivos móveis e desktop.
- Minimizar a quantidade de ações necessárias para concluir tarefas.
- Evitar sobrecarga visual e excesso de informações simultâneas.
- Possuir compatibilidade com leitores de tela sempre que possível.
- Utilizar ícones acompanhados de texto explicativo.
- Oferecer feedback claro após cada ação realizada.
- Priorizar a redução da carga cognitiva em todas as jornadas do usuário.
- Garantir que usuários iniciantes consigam executar tarefas essenciais sem treinamento prévio.

### Regra de UX

Toda funcionalidade proposta deve passar pelo seguinte filtro:

> Um usuário iniciante, com baixa familiaridade tecnológica e sem conhecimento financeiro prévio deve conseguir utilizar a funcionalidade sem treinamento.

---

## 10. Requisitos Não Funcionais

- Interface mobile-first.
- Tempo de resposta inferior a 3 segundos.
- Linguagem simples e amigável.
- Design consistente em todas as telas.
- Histórico persistente de conversas.
- Proteção de dados financeiros.
- Arquitetura preparada para evolução futura.
- Experiência otimizada para acessibilidade e Design Universal.

---

## 11. Critérios de Sucesso

O MVP será considerado validado se:

- 70% dos usuários conseguirem registrar uma transação sem ajuda.
- Usuários registrarem ao menos 5 transações na primeira semana.
- Pelo menos 50% criarem uma meta financeira.
- Os usuários relatarem facilidade de uso em pesquisas qualitativas.

---

## 12. Hipóteses a Validar

### Hipótese 1

Usuários preferem registrar gastos via conversa ao invés de formulários.

### Hipótese 2

Insights automáticos aumentam o engajamento.

### Hipótese 3

Uma interface baseada em chat reduz a curva de aprendizado.

### Hipótese 4

Uma experiência baseada em Design Universal aumenta a retenção de usuários iniciantes.

---

## 13. Plano de Validação Inicial

### Etapa 1 - Protótipo no Lovable

Criar fluxo navegável contendo:

- Login
- Onboarding
- Chat
- Dashboard
- Metas

### Etapa 2 - Testes com 5 a 10 pessoas

Avaliar:

- Facilidade de registro
- Clareza dos relatórios
- Utilidade dos insights
- Compreensão geral da interface
- Tempo necessário para concluir tarefas básicas

### Etapa 3 - Coleta de Feedback

Perguntas sugeridas:

- O que foi mais fácil?
- O que foi mais difícil?
- Você substituiria seu método atual por este aplicativo?
- Continuaria utilizando semanalmente?
- Houve algum momento de confusão?
- Você precisou de ajuda para entender alguma funcionalidade?

---

## 14. Diretrizes para Implementação com IA

Durante o desenvolvimento, priorizar:

- Simplicidade antes de complexidade.
- Conversação antes de formulários.
- Clareza antes de densidade de informação.
- Acessibilidade antes de personalizações avançadas.
- Experiência mobile como prioridade.
- Design Universal como princípio orientador de todas as decisões de produto e UX.

Fora do escopo do MVP:

- Integração bancária automática.
- Investimentos.
- Planejamento tributário.
- Cartões de crédito múltiplos.
- Controle financeiro empresarial.
- Funcionalidades avançadas de contabilidade.


```

Interações com o Loveble: 

> Crie um app de Finanças pessoais com base no seguinte PRD (Product Requirements Document): {PRD}

> Corrigir erro (De falha na criação da solução - tela branca)

> Tentei criar uma meta chamada Reserva de Emergencia mas ela não apareceu no componente. A impressão que tive foi que apenas o assistente a reconheceu, poderia verificar? Além disso, onde vejo os gráficos e extrato?

Resultado final no Loveble: https://everyday-expense-oracle.lovable.app/

### Funcionalidades

- Registro de despesas e receitas por meio de conversas.
- Classificação automática das movimentações em categorias financeiras.
- Dashboard com resumo financeiro, saldo, receitas e despesas.
- Visualização da distribuição dos gastos por categoria.
- Histórico de movimentações registradas.
- Criação e acompanhamento de metas financeiras.
- Interface simples inspirada nos princípios de Design Universal.
- Navegação organizada entre Conversa, Painel, Metas e Perfil.

## Reflexão sobre o Processo

### O que funcionou bem?

- A elaboração do PRD trouxe clareza sobre objetivos e funcionalidades facilitando o processo de criação no momento da utilização no Loveble (devido a limitação de créditos diários).
- A abordagem conversacional tornou o fluxo de registro financeiro simples e intuitivo.
- A divisão do sistema em módulos facilitou a implementação e organização da interface.
- Os conceitos de Design Universal ajudaram a criar uma experiência mais acessível e amigável.

### O que não funcionou como o esperado?

- Algumas funcionalidades exigiram refinamento para interpretar corretamente entradas em linguagem natural.
- Alguns comportamentos da aplicação só se tornaram claros após testes práticos e iterações.

### O que aprendi sobre conversar com IAs?

- Quanto mais específico o contexto fornecido, melhores tendem a ser os resultados.
- Um PRD bem estruturado reduz ambiguidades e retrabalho.
- Desenvolver de forma incremental produz resultados mais consistentes do que tentar gerar toda a aplicação de uma vez.
- Definir claramente objetivos, restrições e critérios de experiência melhora significativamente a qualidade das entregas.

---

# Próximos Passos

## Melhorias planejadas

- Insights financeiros automáticos.
- Recomendações personalizadas de economia.
- Gráficos avançados de evolução financeira.
- Histórico conversacional persistente.
- Notificações e lembretes.
- Exportação de relatórios.
- Modo escuro.
- Recursos avançados de acessibilidade.

---
