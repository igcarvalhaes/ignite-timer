# ⏱️ Ignite Timer

<div align="center">
  <img src="https://img.shields.io/badge/React-19.1.0-61DAFB?style=for-the-badge&logo=react" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-5.8.3-3178C6?style=for-the-badge&logo=typescript" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Vite-7.0.4-646CFF?style=for-the-badge&logo=vite" alt="Vite" />
  <img src="https://img.shields.io/badge/Styled_Components-6.1.19-DB7093?style=for-the-badge&logo=styled-components" alt="Styled Components" />
  <img src="https://img.shields.io/badge/React_Router-7.7.1-CA4245?style=for-the-badge&logo=react-router" alt="React Router" />
</div>

<br>

<p align="center">
  <strong>Uma aplicação de timer para técnica Pomodoro desenvolvida durante o curso Ignite da Rocketseat</strong>
</p>

## 📋 Sobre o Projeto

O **Ignite Timer** é uma aplicação web desenvolvida com React e TypeScript que implementa um sistema de timer baseado na técnica Pomodoro. O projeto faz parte do curso **Ignite** da **Rocketseat** e tem como objetivo ensinar conceitos fundamentais de React, como:

- ⚛️ Fundamentos do React com TypeScript
- 🎨 Estilização com Styled Components
- 🏗️ Arquitetura de componentes e layouts
- 🛣️ Roteamento com React Router DOM
- 🔧 Configuração de ambiente com Vite
- 📐 Sistema de temas e design system avançado
- 🎯 Estrutura de pastas escalável

## 🚀 Funcionalidades

### ✅ Implementadas

- 🏗️ Estrutura base da aplicação com roteamento
- 📱 Layout responsivo com Header e navegação
- 🎨 Sistema de temas robusto com paleta de cores completa
- 🧭 Navegação entre páginas (Home e Histórico)
- 📦 Arquitetura de componentes modular
- 🔤 Tipagem completa com TypeScript
- 🌐 Estilos globais com fonte Roboto

### 🔄 Em Desenvolvimento

- [ ] ⏰ Timer configurável para sessões de trabalho
- [ ] ⏸️ Controles de pause e retomada de sessões
- [ ] 📊 Histórico de sessões completadas
- [ ] 📋 Formulário para criação de novos timers
- [ ] 🔔 Notificações de conclusão de sessão
- [ ] 💾 Persistência de dados no localStorage

> **Nota:** Este projeto está em desenvolvimento ativo durante o curso Ignite da Rocketseat.

## 🛠️ Tecnologias Utilizadas

### Frontend

- **React 19.1.0** - Biblioteca para construção de interfaces
- **TypeScript 5.8.3** - Superset JavaScript com tipagem estática
- **Styled Components 6.1.19** - CSS-in-JS para estilização
- **React Router DOM 7.7.1** - Roteamento de páginas
- **Vite 7.0.4** - Build tool e dev server ultra-rápido

### Ferramentas de Desenvolvimento

- **ESLint 9.32.0** - Linter para análise de código
- **@rocketseat/eslint-config** - Configurações de linting da Rocketseat
- **TypeScript ESLint** - Regras específicas para TypeScript
- **React Hooks ESLint Plugin** - Regras para React Hooks

### Fontes

- **Roboto** - Fonte principal da interface
- **Roboto Mono** - Fonte monospace para o timer

## 📁 Estrutura do Projeto

```
ignite-timer/
├── public/                    # Arquivos públicos
│   └── vite.svg              # Favicon
├── src/                      # Código fonte
│   ├── @types/              # Definições de tipos globais
│   │   └── styles.d.ts      # Tipagem do styled-components
│   ├── components/          # Componentes reutilizáveis
│   │   └── Header.tsx       # Componente de cabeçalho
│   ├── layouts/             # Layouts da aplicação
│   │   └── DefaultLayout.tsx # Layout padrão com Header
│   ├── pages/               # Páginas da aplicação
│   │   ├── Home.tsx         # Página principal do timer
│   │   └── History.tsx      # Página de histórico
│   ├── styles/              # Estilos globais e temas
│   │   ├── global.ts        # Estilos globais
│   │   └── themes/          # Definições de temas
│   │       └── default.ts   # Tema padrão com paleta completa
│   ├── App.tsx              # Componente raiz da aplicação
│   ├── Router.tsx           # Configuração de rotas
│   ├── main.tsx             # Ponto de entrada da aplicação
│   └── vite-env.d.ts        # Definições de tipos do Vite
├── index.html               # Template HTML
├── package.json             # Dependências e scripts
├── tsconfig.json            # Configuração principal do TypeScript
├── tsconfig.app.json        # Configuração TS para aplicação
├── tsconfig.node.json       # Configuração TS para Node.js
├── vite.config.ts           # Configuração do Vite
├── eslint.config.js         # Configuração do ESLint
└── .eslintrc.json           # Configuração adicional do ESLint
```

## 🚀 Como Executar o Projeto

### Pré-requisitos

- **Node.js** (versão 18 ou superior)
- **npm** ou **yarn**

### Instalação

1. **Clone o repositório**

```bash
git clone https://github.com/igcarvalhaes/ignite-timer.git
cd ignite-timer
```

2. **Instale as dependências**

```bash
npm install
# ou
yarn install
```

3. **Execute o projeto em modo de desenvolvimento**

```bash
npm run dev
# ou
yarn dev
```

4. **Abra o navegador**

   A aplicação estará disponível em `http://localhost:5173`

### Scripts Disponíveis

```bash
# Desenvolvimento
npm run dev          # Inicia o servidor de desenvolvimento

# Build
npm run build        # Gera build de produção (tsc + vite build)
npm run preview      # Visualiza o build de produção

# Linting
npm run lint         # Executa o ESLint para análise de código
```

## 🎨 Sistema de Design

O projeto utiliza um sistema de design robusto baseado em **Styled Components** com uma paleta de cores moderna e acessível.

### Paleta de Cores

```typescript
export const defaultTheme = {
  white: "#fff",

  // Escala de cinzas
  "gray-100": "#e1e1e6",
  "gray-300": "#c4c4cc",
  "gray-400": "#8d8d99",
  "gray-500": "#7c7c8a",
  "gray-600": "#323238",
  "gray-700": "#29292e",
  "gray-800": "#202024",
  "gray-900": "#121214",

  // Verde (sucesso/ativo)
  "green-300": "#00B37E",
  "green-500": "#00875F",
  "green-700": "#015f43",

  // Vermelho (erro/perigo)
  "red-500": "#AB222E",
  "red-700": "#7A1921",

  // Amarelo (atenção)
  "yellow-500": "#FBA94C",
};
```

### Estilos Globais

- **Reset CSS** completo
- **Box-sizing: border-box** para todos os elementos
- **Focus** personalizado com `box-shadow` verde
- **Background** escuro (`gray-900`)
- **Cor de texto** padrão (`gray-300`)
- **Fonte** Roboto aplicada globalmente

### Arquitetura de Componentes

- **Layout System** com `DefaultLayout`
- **Roteamento** estruturado com React Router
- **Theme Provider** para acesso global ao tema
- **Tipagem** completa dos temas com TypeScript

## 🛣️ Roteamento

A aplicação utiliza **React Router DOM** com a seguinte estrutura:

```typescript
Routes:
├── "/" (DefaultLayout)
    ├── "/" → Home (Timer principal)
    └── "/history" → History (Histórico de sessões)
```

## 🤝 Contribuição

Este é um projeto educacional do curso Ignite da Rocketseat. Contribuições são bem-vindas para melhorias e correções!

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto é parte do curso **Ignite** da **Rocketseat** e é destinado para fins educacionais.

## 👨‍💻 Desenvolvedor

**Igor Carvalhaes**

- GitHub: [@igcarvalhaes](https://github.com/igcarvalhaes)

---

<div align="center">
  <p>Desenvolvido com ❤️ durante o curso Ignite da Rocketseat</p>
  
  [![Rocketseat](https://img.shields.io/badge/Rocketseat-8257E6?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAGxSURBVDhPpZM9SwNBEIafgQQSCxsLwcJCG1sLG0uxsLGwsLBQsLCwsLGwsLBQsLCwsLGwsLBQsLCwsLGwsLBQsLCwsLBQsLGwsLBQsLGwsLBQsLBQsLCwsLBQsLCwsLBQsLCwsLBQsLCwsLBQsLCwsLBQsLCwsLBQsLCwsLCwsLCwsLCwsLBQsLGwsLBQsLCwsLBQsLCwsLBQsLCwsLBQsLCwsLBQsLCwsLCwsLCwsLGwsLBQsLCwsLBQsLCwsLBQsLCwsLBQsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLBQsLGwsLBQsLCwsLBQsLGwsLBQsLCwsLBQsLGwsLBQsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwCCwsLKQsLGwsLBQsLCwsLBQsLGwsLBQsLCwsLBQsLGwsLBQsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLBQsLCwsLBQsLGwsLBQsLCwsLBQsLGwsAYjjWiEg2lE&logoColor=white)](https://rocketseat.com.br/)
</div>
