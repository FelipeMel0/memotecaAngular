# Memoteca - CRUD de Pensamentos

[![Angular](https://img.shields.io/badge/Angular-v14-red.svg?logo=angular)](https://angular.io/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

Projeto desenvolvido em Angular para gerenciar cards com pensamentos, contendo texto, autor e modelo selecionável.

## 📋 Descrição do Projeto

A Memoteca é uma aplicação CRUD (Create, Read, Update, Delete) que permite:

- Criar cards com pensamentos
- Visualizar todos os pensamentos cadastrados
- Editar pensamentos existentes
- Excluir pensamentos
- Cada card contém:
  - Texto do pensamento
  - Autor
  - Modelo de layout selecionável

## 🚀 Como Executar o Projeto

### Pré-requisitos

- Node.js (v14.x ou superior)
- Angular CLI (v14.0.0 ou superior)
- NPM ou Yarn

### Passo a Passo

1. **Instalar dependências**
   ```bash
   # Na pasta raiz do projeto:
   npm install --force
   ```
2. **Iniciar o backend (json-server)**
   ```bash
   # Navegue até a pasta backend
   cd backend
   # Inicie o servidor de mock API
   npm start
   # Mantenha este terminal aberto
   ```
3. **Iniciar o frontend**
   ```bash
   # Volte para a pasta raiz
   cd ..
   # Inicie o servidor Angular
   ng serve
   ```
4. **Acessar a aplicação**
   ```bash
     # Abra seu navegador em:
     http://localhost:4200
   ```
