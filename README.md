# Ethena Clone Template

Este é um template React que replica a estrutura visual do site Ethena.fi, criado para seu projeto particular.

## Estrutura do Projeto

O projeto foi construído usando React com TypeScript, Tailwind CSS e várias bibliotecas modernas para garantir um design responsivo e de alta qualidade.

### Componentes Principais

1. **Navbar** - Barra de navegação superior com logo, links e botão de ação
2. **HeroSection** - Seção principal com título e globo 3D animado
3. **Globe** - Componente de globo 3D animado usando Canvas
4. **StatsSection** - Seção de estatísticas na parte inferior

## Como Usar

### Instalação

```bash
# Navegue até a pasta do projeto
cd ethena-clone

# Instale as dependências
pnpm install

# Inicie o servidor de desenvolvimento
pnpm run dev
```

### Personalização

Para personalizar o template para seu projeto:

1. **Alterar Textos e Conteúdo**:
   - Edite os textos em `src/components/HeroSection.tsx` e `src/components/StatsSection.tsx`
   - Atualize os links de navegação em `src/components/Navbar.tsx`

2. **Modificar Cores e Estilos**:
   - As cores principais podem ser ajustadas em `src/index.css`
   - Os estilos específicos de componentes estão em seus respectivos arquivos

3. **Adicionar Novas Seções**:
   - Crie novos componentes em `src/components/`
   - Importe e adicione-os em `src/App.tsx`

## Recursos Técnicos

- **React + TypeScript**: Para desenvolvimento robusto e tipado
- **Tailwind CSS**: Para estilização rápida e responsiva
- **shadcn/ui**: Componentes UI reutilizáveis
- **Canvas API**: Para animação do globo 3D
- **Design Responsivo**: Adaptável a dispositivos móveis e desktop

## Construção para Produção

```bash
# Gere a versão de produção
pnpm run build

# Visualize a versão de produção localmente
pnpm run preview
```

## Estrutura de Arquivos

```
src/
├── assets/       # Recursos estáticos
├── components/   # Componentes React
│   ├── ui/       # Componentes de UI reutilizáveis
│   ├── Navbar.tsx
│   ├── Globe.tsx
│   ├── HeroSection.tsx
│   └── StatsSection.tsx
├── hooks/        # Hooks personalizados
├── lib/          # Utilitários e funções auxiliares
├── App.tsx       # Componente principal
└── index.css     # Estilos globais
```

Este template foi criado para facilitar o desenvolvimento de um site similar ao Ethena.fi, mantendo a mesma estética visual e experiência de usuário.
