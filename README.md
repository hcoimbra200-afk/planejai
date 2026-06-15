# Planej.ai — Educador Financeiro Inteligente

Aplicação web de planejamento financeiro pessoal desenvolvida com React, TypeScript e IA Generativa (Google Gemini), construída durante o bootcamp da DIO.

## O que o projeto faz

O usuário preenche um formulário com informações sobre renda, gastos fixos, dívidas e uma meta financeira. A aplicação usa a API do Google Gemini para gerar um diagnóstico personalizado com sugestões práticas, ideias de renda extra e um plano de ação.

## Tecnologias utilizadas

- React 19
- TypeScript
- Vite
- Tailwind CSS
- React Router DOM
- Google Gemini API
- LocalStorage (persistência dos dados)
- Lucide React (ícones)

## Funcionalidades

- Formulário multi-step com barra de progresso
- Tema claro e escuro
- Máscara de moeda nos campos financeiros
- Persistência de dados no localStorage
- Integração com IA Generativa para geração de insights
- Estados de carregamento e erro na chamada da API
- Diagnóstico financeiro personalizado

## Melhoria implementada

Melhoria da documentação do projeto com README mais completo e detalhado, descrevendo o fluxo da aplicação, tecnologias utilizadas e funcionalidades implementadas.

## Como executar

```bash
# Clone o repositório
git clone https://github.com/hcoimbra200-afk/planejai

# Entre na pasta
cd planejai

# Instale as dependências
pnpm install

# Crie o arquivo .env.local e adicione sua chave do Google Gemini
VITE_GEMINI_API_KEY=sua_chave_aqui

# Inicie o projeto
pnpm run dev
```

## O que aprendi

- Como estruturar uma aplicação React com TypeScript do zero
- Como criar formulários multi-step com controle de estado
- Como integrar uma API de IA Generativa em uma aplicação frontend
- Como usar Context API para gerenciar temas
- Como persistir dados no localStorage
