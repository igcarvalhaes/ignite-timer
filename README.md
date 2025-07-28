# ⏱️ Ignite Timer

<div align="center">
  <img src="https://img.shields.io/badge/React-19.1.0-61DAFB?style=for-the-badge&logo=react" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-5.8.3-3178C6?style=for-the-badge&logo=typescript" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Vite-7.0.4-646CFF?style=for-the-badge&logo=vite" alt="Vite" />
  <img src="https://img.shields.io/badge/Styled_Components-6.1.19-DB7093?style=for-the-badge&logo=styled-components" alt="Styled Components" />
</div>

<br>

<p align="center">
  <strong>Uma aplicação de timer para técnica Pomodoro desenvolvida durante o curso Ignite da Rocketseat</strong>
</p>

## 📋 Sobre o Projeto

O **Ignite Timer** é uma aplicação web desenvolvida com React e TypeScript que implementa um sistema de timer baseado na técnica Pomodoro. O projeto faz parte do curso **Ignite** da **Rocketseat** e tem como objetivo ensinar conceitos fundamentais de React, como:

- ⚛️ Fundamentos do React com TypeScript
- 🎨 Estilização com Styled Components
- 🏗️ Arquitetura de componentes
- 🔧 Configuração de ambiente com Vite
- 📐 Sistema de temas e design system

## 🚀 Funcionalidades

- [ ] ⏰ Timer configurável para sessões de trabalho
- [ ] ⏸️ Pause e retomada de sessões
- [ ] 📊 Histórico de sessões completadas
- [ ] 🎯 Interface intuitiva e responsiva
- [ ] 🌙 Sistema de temas (claro/escuro)

> **Nota:** Este projeto está em desenvolvimento ativo. As funcionalidades marcadas serão implementadas ao longo do curso.

## 🛠️ Tecnologias Utilizadas

### Frontend

- **React 19.1.0** - Biblioteca para construção de interfaces
- **TypeScript 5.8.3** - Superset JavaScript com tipagem estática
- **Styled Components 6.1.19** - CSS-in-JS para estilização
- **Vite 7.0.4** - Build tool e dev server

### Ferramentas de Desenvolvimento

- **ESLint** - Linter para análise de código
- **TypeScript ESLint** - Regras específicas para TypeScript
- **React Hooks ESLint Plugin** - Regras para React Hooks

## 📁 Estrutura do Projeto

```
ignite-timer/
├── public/                 # Arquivos públicos
│   └── vite.svg           # Favicon
├── src/                   # Código fonte
│   ├── components/        # Componentes reutilizáveis
│   │   ├── Button.tsx     # Componente de botão
│   │   └── Button.styles.ts # Estilos do botão
│   ├── styles/           # Estilos globais e temas
│   │   └── themes/       # Definições de temas
│   │       └── default.ts # Tema padrão
│   ├── App.tsx          # Componente principal
│   ├── main.tsx         # Ponto de entrada da aplicação
│   └── vite-env.d.ts    # Definições de tipos do Vite
├── index.html            # Template HTML
├── package.json          # Dependências e scripts
├── tsconfig.json         # Configuração TypeScript
├── vite.config.ts        # Configuração do Vite
└── eslint.config.js      # Configuração do ESLint
```

## 🚀 Como Executar o Projeto

### Pré-requisitos

- Node.js (versão 18 ou superior)
- npm ou yarn

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
npm run build        # Gera build de produção
npm run preview      # Visualiza o build de produção

# Linting
npm run lint         # Executa o ESLint
```

## 🎨 Sistema de Design

O projeto utiliza um sistema de design baseado em **Styled Components** com suporte a temas. Atualmente implementa:

### Tema Padrão

```typescript
export const defaultTheme = {
  primary: "purple",
  secondary: "orange",
  white: "#fff",
};
```

### Variantes de Componentes

O sistema suporta diferentes variantes para componentes:

- `primary` - Cor principal (roxo)
- `secondary` - Cor secundária (laranja)
- `danger` - Para ações destrutivas (vermelho)
- `success` - Para ações de sucesso (verde)

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
  
  [![Rocketseat](https://img.shields.io/badge/Rocketseat-8257E6?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAGxSURBVDhPpZM9SwNBEIafgQQSCxsLwcJCG1sLG0uxsLGwsLBQsLCwsLGwsLBQsLCwsLGwsLBQsLCwsLGwsLBQsLCwsLBQsLGwsLBQsLGwsLBQsLBQsLCwsLBQsLCwsLBQsLCwsLBQsLCwsLBQsLCwsLBQsLCwsLBQsLCwsLBQsLCwsLCwsLCwsLCwsLBQsLGwsLBQsLCwsLBQsLCwsLBQsLCwsLBQsLCwsLBQsLCwsLCwsLCwsLGwsLBQsLCwsLBQsLCwsLBQsLCwsLBQsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLBQsLGwsLBQsLCwsLBQsLGwsLBQsLCwsLBQsLGwsLBQsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwCCwsLKQsLGwsLBQsLCwsLBQsLGwsLBQsLCwsLBQsLGwsLBQsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLCwsLBQsLCwsLBQsLGwsLBQsLCwsLBQsLGwsAYjjWiEg2lE&logoColor=white)](https://rocketseat.com.br/)
</div>
