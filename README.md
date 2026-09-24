# Gerenciador de Tarefas

Aplicação de lista de tarefas construída com React + Vite, com interface moderna em Tailwind CSS. O projeto permite cadastrar tarefas, marcar como concluídas, visualizar detalhes de cada item e remover registros da lista.

## Funcionalidades

- Adicionar novas tarefas com título e descrição
- Marcar ou desmarcar tarefas como concluídas
- Visualizar os detalhes da tarefa em uma página separada
- Excluir tarefas da lista
- Persistência dos dados no navegador com `localStorage`
- Navegação entre páginas com `react-router-dom`

## Tecnologias utilizadas

- React
- Vite
- React Router DOM
- Tailwind CSS
- Lucide React
- UUID

## Versão em produção

O projeto também está disponível online em:

```text
https://curso-react-rqy0.onrender.com/
```

## Build de produção

Para gerar a build final:

```bash
npm run build
```

## Estrutura do projeto

```text
curso-react/
├── public/
├── src/
│   ├── componentes/
│   │   ├── AddTask.jsx
│   │   └── tasks.jsx
│   ├── pages/
│   │   └── TaskPage.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── package.json
├── vite.config.js
├── tailwind.config.js
├── postcss.config.js
├── index.html
└── README.md
```

## Observações

A aplicação usa o `localStorage` para manter as tarefas salvas mesmo após recarregar a página. A navegação para a tela de detalhes é feita pela rota `/task`, passando os dados por query string.


