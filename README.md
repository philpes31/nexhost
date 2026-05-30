# ⚡ NexHost — Site de Hospedagem

Site profissional de hospedagem com painel administrativo completo.

## 🚀 Como rodar localmente

### Pré-requisitos
- [Node.js 18+](https://nodejs.org) instalado

### Instalação

```bash
# 1. Entre na pasta do projeto
cd nexhost

# 2. Instale as dependências
npm install

# 3. Rode em modo desenvolvimento
npm run dev
```

Acesse: **http://localhost:3000**

---

## 📦 Estrutura do Projeto

```
nexhost/
├── index.html          # HTML base
├── vite.config.js      # Configuração do Vite
├── package.json        # Dependências
├── vercel.json         # Config deploy Vercel
├── netlify.toml        # Config deploy Netlify
└── src/
    ├── main.jsx        # Ponto de entrada React
    └── App.jsx         # Aplicação completa
```

---

## 🌐 Como publicar online

### Opção 1 — Vercel (Recomendado)

```bash
# Instale a CLI da Vercel
npm install -g vercel

# Faça o deploy
vercel

# Ou conecte ao GitHub e deploy automático
```

### Opção 2 — Netlify (Arrastar e soltar)

```bash
# Gere os arquivos de produção
npm run build

# Acesse netlify.com e arraste a pasta "dist" para a tela
```

### Opção 3 — GitHub Pages

```bash
# Edite o package.json: mude "homepage" para sua URL do GitHub
# Depois execute:
npm run deploy
```

### Opção 4 — Hospedagem Tradicional (cPanel)

```bash
# Gere os arquivos de produção
npm run build

# Envie o conteúdo da pasta "dist" para public_html via FTP ou cPanel
```

---

## 🔐 Acesso ao Painel Admin

- Clique em **"Admin"** no menu do site
- Senha padrão: **admin123**
- Você pode alterar a senha dentro do painel em **Segurança**

---

## ✨ Funcionalidades

- ✅ 6 páginas: Início, Sobre, Domínios, Planos, Blog, Contato
- ✅ Painel admin completo com 14 seções de configuração
- ✅ Chat flutuante com respostas automáticas
- ✅ Barra promocional configurável
- ✅ Verificador de domínio em tempo real
- ✅ FAQ com acordeão
- ✅ Depoimentos de clientes
- ✅ Dados salvos automaticamente
- ✅ Design responsivo mobile
- ✅ SEO configurável pelo painel

---

## 🛠️ Tecnologias

- **React 18** — Interface
- **Vite 5** — Build tool
- **CSS-in-JS** — Estilização inline
- **Google Fonts** — Tipografia (Syne + Inter)
