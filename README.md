# Planejador de Viagem Frontend

Bem-vindo ao projeto Planejador de Viagem! Este projeto foi desenvolvido para ajudar você a planejar suas viagens de forma eficiente.

## Tabela de Conteúdos

- [Instalação](#instalação)
- [Uso](#uso)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)

## Instalação

Para começar com o projeto, siga estes passos:

1. **Clone o repositório:**

   ```bash
    git clone <repository-url>
    cd Planejador-Viagem-Front-master/frontend
   ``` 

2. **Instale as dependências:**

    Certifique-se de ter o Node.js instalado. Então, execute:

   ```bash
    npm install
   ``` 

## Uso

Para iniciar a aplicação, execute:

```bash
npm run dev
```

Isso iniciará o servidor de desenvolvimento. Você pode acessar a aplicação em `http://localhost:3000`.

## Estrutura do Projeto

A estrutura do projeto é a seguinte:

```bash
Planejador-Viagem-Front-master
├── frontend                # Diretório principal do frontend
│   ├── public              # Arquivos estáticos públicos
│   ├── src                 # Código-fonte da aplicação
│   │   ├── assets          # Arquivos de mídia e outros assets
│   │   ├── components      # Componentes React
│   │   ├── pages           # Páginas da aplicação
│   │   ├── services        # Serviços e lógica de negócio
│   │   ├── styles          # Arquivos de estilos (CSS, SCSS)
│   │   ├── utils           # Funções utilitárias
│   │   ├── App.tsx         # Componente principal da aplicação
│   │   └── main.tsx        # Ponto de entrada do aplicativo
│   ├── .eslintrc.cjs       # Configurações do ESLint
│   ├── .gitignore          # Arquivos e diretórios ignorados pelo git
│   ├── index.html          # Ponto de entrada HTML
│   ├── package.json        # Metadados do projeto e dependências
│   ├── package-lock.json   # Arquivo de lock do npm
│   ├── postcss.config.js   # Configurações do PostCSS
│   ├── tailwind.config.js  # Configurações do Tailwind CSS
│   ├── tsconfig.json       # Configurações do TypeScript
│   ├── tsconfig.app.json   # Configurações adicionais do TypeScript para a aplicação
│   ├── tsconfig.node.json  # Configurações do TypeScript para Node.js
│   └── vite.config.ts      # Configurações do Vite
```

## Tecnologias Utilizadas

- **Node.js**: Ambiente de execução JavaScript
- **TypeScript**: Superconjunto tipado de JavaScript
- **React**: Biblioteca JavaScript para construção de interfaces de usuário
- **Vite**: Ferramenta de construção rápida
- **Tailwind CSS**: Framework de CSS utilitário
- **ESLint**: Ferramenta de linting para JavaScript e TypeScript
