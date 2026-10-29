# Bikko Web — Portal Oficial & Landing Page (`bikkoweb`)

Portal web oficial, institucional e comercial do ecossistema **Bikko**, englobando os aplicativos **Bikkofy** (para Clientes) e **Bikkerfy** (para Profissionais / Prestadores de Serviço / Bikkers).

A página foi construída com foco em:
1. **Design de Alta Conversão inspirado na Apple, Kiwify e Foomy**: visual escuro sofisticado (*obsidian dark*), tipografia com SF Pro / Inter, *frosted glass* (backdrop-filter blur), bento grid, ícones 3D otimizados em WebP e micro-animações.
2. **SEO Técnico & E-E-A-T Sênior para o Google**: dados estruturados Schema.org JSON-LD (`Organization`, `WebSite`, `SoftwareApplication`, `FAQPage`), meta tags Open Graph / Twitter Card completas, títulos e descrições otimizados para busca orgânica com palavras-chave de cauda longa, pontuação máxima no Core Web Vitals (imagens WebP compactadas em < 25KB, sem dependências pesadas de JavaScript, CSS inlined sem bloqueio de renderização).
3. **Conformidade Legal Google Play & LGPD**: páginas dedicadas e transparentes de **Política de Privacidade (LGPD)**, **Termos de Uso** e **Exclusão de Conta em 1 Toque**.

---

## 📁 Estrutura de Arquivos

| Arquivo / Diretório | Descrição | URL Pública Final |
| :--- | :--- | :--- |
| `index.html` | **Landing Page Comercial & Institucional** de alta conversão | `https://bikkofy.com.br/` |
| `privacidade.html` | **Política de Privacidade Oficial (LGPD)** e Central de Exclusão de Conta | `https://bikkofy.com.br/privacidade.html` |
| `termos.html` | **Termos e Condições Gerais de Uso** (Regras de Intermediação e Pagamento Direto) | `https://bikkofy.com.br/termos.html` |
| `assets/icons/` | Ícones oficiais de alta fidelidade em formato `.webp` dos apps Bikkofy e Bikkerfy | `/assets/icons/` |
| `assets/images/` | Ilustrações 3D de onboarding em formato `.webp` para demonstração visual | `/assets/images/` |
| `assets/categories/` | Ícones 3D em formato `.webp` das categorias de serviços (Eletricista, Encanador, Diarista, etc.) | `/assets/categories/` |

---

## 🚀 Como Hospedar

### Opção 1: Hostinger Web Hosting (Já configurado para `bikkofy.com.br`)
Faça o upload dos arquivos diretamente para a pasta `/domains/bikkofy.com.br/public_html` via painel da Hostinger, Git ou Hostinger MCP.

### Opção 2: Cloudflare Pages / GitHub Pages
1. No repositório [emersonfiwre/bikkoweb](https://github.com/emersonfiwre/bikkoweb):
2. Vá em **Settings > Pages > Source > Deploy from a branch** e selecione a branch `master` e pasta `/ (root)`.
3. Configure o apontamento CNAME para seu domínio customizado `bikkofy.com.br`.

---

## 📱 URLs Oficiais para o Google Play Console

- **Política de Privacidade (Privacy Policy):** `https://bikkofy.com.br/privacidade.html`
- **Exclusão de Conta e Dados (Account Deletion URL):** `https://bikkofy.com.br/privacidade.html#exclusao-de-conta`
- **Termos de Uso (Terms of Service):** `https://bikkofy.com.br/termos.html`
