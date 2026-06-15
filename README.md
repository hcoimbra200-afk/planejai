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

Por estar no início da minha jornada como desenvolvedor, optei por melhorar a documentação do projeto. O README original era técnico e voltado para quem já conhecia o projeto. Reescrevi com linguagem mais clara, organizei as seções e adicionei informações sobre o fluxo principal e o aprendizado obtido durante o desafio.

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

## Como testar o fluxo principal

1. Acesse a aplicação no navegador
2. Preencha o formulário com seus dados financeiros (renda, gastos, dívidas e meta)
3. Clique em "Gerar simulação"
4. Aguarde a IA gerar o diagnóstico financeiro personalizado
5. Veja os insights, sugestões e plano de ação na página de resultados

## O que aprendi durante o desafio

- Aprendi o que é React e como ele organiza interfaces em componentes reutilizáveis
- Entendi como o TypeScript ajuda a evitar erros antes mesmo de rodar o código
- Conheci o Vite como ferramenta moderna e rápida para criar projetos React
- Aprendi o que é uma API e como o frontend se comunica com serviços externos
- Entendi como a IA Generativa pode ser integrada em aplicações reais do dia a dia
- Percebi a importância de documentar bem um projeto para que outras pessoas consigam entendê-lo e executá-lo
