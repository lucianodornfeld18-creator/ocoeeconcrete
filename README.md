# Ocoee Concrete & Pavers — Website

**Site:** https://ocoeeconcrete.com  
**Telefone:** (689) 243-5726  
**Stack:** HTML estático · Cloudflare Pages (deploy automático via GitHub)

---

## 🚀 Deploy no Cloudflare Pages (passo a passo)

### 1. Suba este repositório no GitHub

```bash
# No seu computador, dentro da pasta ocoeeconcrete/:
git init
git add .
git commit -m "Initial commit — Ocoee Concrete & Pavers website"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/ocoeeconcrete.git
git push -u origin main
```

### 2. Conecte ao Cloudflare Pages

1. Acesse [dash.cloudflare.com](https://dash.cloudflare.com)
2. Vá em **Workers & Pages** → **Create** → **Pages** → **Connect to Git**
3. Selecione o repositório `ocoeeconcrete`
4. Configurações de build:
   - **Framework preset:** None
   - **Build command:** *(deixar vazio)*
   - **Build output directory:** `/` *(raiz)*
5. Clique **Save and Deploy**

### 3. Domínio personalizado

1. No painel do Cloudflare Pages → **Custom domains** → **Set up a custom domain**
2. Digite `ocoeeconcrete.com`
3. Siga as instruções para apontar os nameservers do seu registrador para a Cloudflare

**Deploy automático:** a cada `git push` na branch `main`, o Cloudflare Pages faz o deploy em ~1 minuto automaticamente. ✅

---

## 📁 Estrutura de Pastas

```
ocoeeconcrete/
├── index.html              ← Homepage
├── 404.html                ← Página de erro
├── sitemap.xml
├── robots.txt
├── _redirects              ← Redirects Cloudflare Pages
├── _headers                ← Security headers
├── images/                 ← Todas as imagens (18 fotos)
├── about/
│   └── index.html
├── contact/
│   └── index.html
├── privacy-policy/
│   └── index.html
├── terms/
│   └── index.html
├── pavers/
│   ├── index.html          ← Página principal de pavers
│   ├── ocoee/
│   ├── winter-garden/
│   ├── kissimmee/
│   ├── windermere/
│   ├── apopka/
│   ├── davenport/
│   └── clermont/
├── concrete/
│   ├── index.html          ← Página principal de concrete
│   └── ocoee/
└── blog/
    ├── index.html
    ├── cost-pavers-ocoee/
    ├── best-pavers-central-florida/
    └── concrete-vs-pavers-driveway/
```

---

## 📊 Páginas — Total: 20 páginas HTML

| Página | URL | Prioridade SEO |
|--------|-----|---------------|
| Homepage | / | ⭐⭐⭐ |
| Pavers Main | /pavers/ | ⭐⭐⭐ |
| Concrete Main | /concrete/ | ⭐⭐⭐ |
| Contact | /contact/ | ⭐⭐⭐ |
| Pavers Ocoee | /pavers/ocoee/ | ⭐⭐⭐ |
| Pavers Winter Garden | /pavers/winter-garden/ | ⭐⭐⭐ |
| Pavers Kissimmee | /pavers/kissimmee/ | ⭐⭐⭐ |
| Pavers Windermere | /pavers/windermere/ | ⭐⭐ |
| Pavers Apopka | /pavers/apopka/ | ⭐⭐ |
| Pavers Davenport | /pavers/davenport/ | ⭐⭐ |
| Pavers Clermont | /pavers/clermont/ | ⭐⭐ |
| Concrete Ocoee | /concrete/ocoee/ | ⭐⭐ |
| About | /about/ | ⭐ |
| Blog Index | /blog/ | ⭐⭐ |
| Blog: Cost Pavers Ocoee | /blog/cost-pavers-ocoee/ | ⭐⭐ |
| Blog: Best Pavers FL | /blog/best-pavers-central-florida/ | ⭐⭐ |
| Blog: Concrete vs Pavers | /blog/concrete-vs-pavers-driveway/ | ⭐⭐ |
| Privacy Policy | /privacy-policy/ | — |
| Terms | /terms/ | — |
| 404 | /404.html | — |

---

## 🛠️ Próximos Passos Pós-Deploy

- [ ] Registrar no **Google Search Console** e submeter o sitemap: `https://ocoeeconcrete.com/sitemap.xml`
- [ ] Criar/verificar **Google Business Profile** em business.google.com
- [ ] Cadastrar no **Yelp, Angi, Thumbtack** (citar URL do site)
- [ ] Adicionar link real do Google Business nos footers (substituir placeholder)
- [ ] Configurar **Google Analytics (GA4)** — inserir script antes de `</head>` em cada página
- [ ] Pedir aos clientes satisfeitos que deixem review no Google

---

## 📞 Contato / Suporte

**WhatsApp:** +1 (689) 243-5726  
**Site:** https://ocoeeconcrete.com
