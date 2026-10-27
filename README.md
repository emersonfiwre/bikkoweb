# Bikkofy & Bikkerfy — Portal Web Institucional & Jurídico (`bikkofy-web`)

Repositório estático oficial (HTML5 + CSS3 puro, zero dependências externas) contendo as páginas obrigatórias de **Política de Privacidade (LGPD)**, **Termos e Condições de Uso** e **Instruções de Exclusão de Conta** para aprovação dos aplicativos **Bikkofy** (`br.com.bikkofy.bikko`) e **Bikkerfy** (`br.com.bikkofy.bikker`) na **Google Play Store**.

---

## 📁 Estrutura do Projeto

| Arquivo | Descrição | URL Pública Final |
| :--- | :--- | :--- |
| `index.html` | Portal institucional (preparado para receber a futura Landing Page comercial) | `https://<seu-dominio>/` |
| `privacidade.html` | **Política de Privacidade Oficial** (100% compatível com LGPD e Google Play User Data Policy) | `https://<seu-dominio>/privacidade.html` |
| `privacidade.html#exclusao-de-conta` | Seção dedicada à **Exclusão de Conta e Dados** (in-app e via web/e-mail) | `https://<seu-dominio>/privacidade.html#exclusao-de-conta` |
| `termos.html` | **Termos e Condições Gerais de Uso** (Intermediação, Contrapropostas e Pagamento Direto) | `https://<seu-dominio>/termos.html` |

---

## 🚀 Como Hospedar Gratuitamente em 2 Minutos

### Opção 1: Cloudflare Pages (Recomendado — HTTPS automático e CDN Global)

1. Crie um repositório no GitHub chamado `bikkofy-web` e envie os arquivos deste diretório:
   ```bash
   git add .
   git commit -m "feat: add official privacy policy and terms of use for Google Play"
   git branch -M main
   git remote add origin git@github.com:<SEU_USUARIO>/bikkofy-web.git
   git push -u origin main
   ```
2. Acesse o painel da Cloudflare: **Workers & Pages > Create application > Pages > Connect to Git** (ou **Direct Upload** para arrastar a pasta diretamente sem precisar de Git).
3. Selecione o repositório `bikkofy-web`:
   - **Framework preset:** `None`
   - **Build command:** *(deixe em branco)*
   - **Build output directory:** `/`
4. Clique em **Save and Deploy**. Em segundos, sua página estará no ar em `https://bikkofy-web.pages.dev` (ou no seu domínio próprio `https://bikkofy.com.br`).

---

### Opção 2: GitHub Pages (100% Gratuito direto do GitHub)

1. Suba este repositório para o GitHub.
2. No repositório do GitHub, acesse **Settings > Pages**.
3. Em **Build and deployment > Source**, selecione **Deploy from a branch**.
4. Escolha a branch `main` e a pasta `/ (root)` e clique em **Save**.
5. Aguarde ~1 minuto e acesse:
   - `https://<seu-usuario>.github.io/bikkofy-web/privacidade.html`

---

## 📱 Onde Colar as URLs no Google Play Console

Ao configurar os aplicativos **Bikkofy** (`br.com.bikkofy.bikko`) e **Bikkerfy** (`br.com.bikkofy.bikker`) no **Google Play Console** (menu **Conteúdo do app / App content**):

1. **Política de Privacidade (Privacy Policy):**
   - Cole a URL: `https://<seu-dominio>/privacidade.html`
2. **Exclusão de Conta do App (Data Safety > Account Deletion URL):**
   - Cole a URL direta com âncora: `https://<seu-dominio>/privacidade.html#exclusao-de-conta`
3. **Termos de Uso (dentro dos apps / loja):**
   - Cole a URL: `https://<seu-dominio>/termos.html`
