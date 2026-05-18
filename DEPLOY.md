# 📖 Guia de Deploy - GitHub e Vercel

## ✅ O projeto já está pronto!

Os arquivos configurados:
- ✅ `.gitignore` - Arquivos a ignorar no Git
- ✅ `README.md` - Documentação do projeto
- ✅ `vercel.json` - Configuração do Vercel
- ✅ `package.json` - Metadados do projeto

---

## 🚀 Passo 1: Preparar no GitHub

### 1.1 Criar repositório (se ainda não tiver)

```bash
cd c:\Users\hugob\Downloads\stitch_varandaspg_website_template\stitch_varandaspg_website_template

# Inicializar Git (se primeira vez)
git init

# Adicionar todos os arquivos
git add .

# Commit inicial
git commit -m "Initial commit: Varandas Restaurante website"
```

### 1.2 Conectar com GitHub

```bash
# Adicionar repositório remoto (substitua USERNAME/REPO-NAME)
git remote add origin https://github.com/USERNAME/varandas-restaurante-website.git

# Fazer push
git branch -M main
git push -u origin main
```

> 💡 **Dica**: Se ainda não tiver repositório no GitHub, acesse [github.com/new](https://github.com/new) e crie um novo.

---

## 🌐 Passo 2: Deploy no Vercel

### Opção A: Via Dashboard Vercel (Mais fácil)

1. Acesse [vercel.com](https://vercel.com)
2. Clique em **"New Project"**
3. Selecione seu repositório do GitHub
4. Clique em **"Deploy"**
5. Pronto! ✅

### Opção B: Via Vercel CLI

```bash
# Instalar Vercel CLI (global)
npm install -g vercel

# No diretório do projeto
vercel

# Seguir as instruções interativas
```

---

## 📋 Checklist Final

- [ ] Repositório GitHub criado e código enviado
- [ ] Vercel conectado ao repositório
- [ ] Deploy realizado com sucesso
- [ ] Site acessível via URL do Vercel
- [ ] Domínio customizado configurado (opcional)

---

## 🔗 URLs Importantes

- **GitHub**: https://github.com/USERNAME/varandas-restaurante-website
- **Vercel Dashboard**: https://vercel.com/dashboard
- **Seu Site**: https://seu-projeto.vercel.app

---

## 📝 Próximos Passos

1. Editar `package.json` com informações reais
2. Configurar domínio customizado no Vercel (se tiver)
3. Adicionar analytics (Google Analytics, etc)
4. Configurar emails de contato

---

## 💬 Dúvidas?

- GitHub Docs: https://docs.github.com
- Vercel Docs: https://vercel.com/docs
- Git Tutorial: https://git-scm.com/doc
