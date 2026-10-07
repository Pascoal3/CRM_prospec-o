# CRM Atlas

Sistema de CRM (Customer Relationship Management) para prospecção e gestão de clientes, construído com **Next.js 16**, **React 19** e **TypeScript**.

## Projeto Principal: `atlas-crm/`

Esta pasta contém a implementação principal do CRM como uma aplicação Next.js completa.

### Tecnologias

- **Framework**: Next.js 16.4.0 (App Router)
- **UI**: React 19.3.0, TailwindCSS v4
- **Estado**: Zustand 5.0.15
- **Gráficos**: Recharts 3.10.1
- **Drag & Drop**: @dnd-kit (core, sortable, utilities)
- **Lint/Type**: ESLint 9, TypeScript 5

### Estrutura

```
atlas-crm/
├── app/              # App Router pages & layouts
├── components/       # Componentes React reutilizáveis
├── lib/              # Utilitários e helpers
├── data/             # Dados estáticos/mock
├── types/            # Tipos TypeScript
├── public/           # Assets estáticos
└── package.json      # Dependências e scripts
```

### Como Executar

```bash
cd atlas-crm
npm install
npm run dev
```

Acesse: [http://localhost:3000](http://localhost:3000)

### Scripts Disponíveis

| Comando | Descrição |
|---------|-----------|
| `npm run dev` | Inicia servidor de desenvolvimento com Turbopack |
| `npm run build` | Build de produção |
| `npm run start` | Inicia servidor de produção |
| `npm run lint` | Executa ESLint |

### Arquivos Legados (Raiz)

Os arquivos `.html` na raiz (`CRM_atlas.html`, `CRM_atlas_v2.html`, `CRM_atlasv3.html`) são versões anteriores em HTML/JS vanilla, mantidas apenas para referência histórica.

### Documentação

- **DESIGN.md** - Diretrizes de design e UI/UX
- **PRODUCT.md** - Especificações de produto e features

## Licença

Projeto privado.