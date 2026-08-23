# Currículo UP — Landing Page de Pré-Venda de Alta Conversão

Landing page profissional desenvolvida para aquecer, qualificar e direcionar leads de anúncios do Facebook para o atendimento no WhatsApp da **Currículo UP**.

---

## 🚀 Tecnologias Utilizadas (100% Frontend Estático)

- **Frontend:** HTML5 Semântico + CSS3 Customizado (Mobile-First, Flexbox/Grid, zero dependências como Tailwind/Bootstrap) + JavaScript Vanilla Puro.
- **Sem Dependência de Servidor:** Funciona em qualquer servidor estático (GitHub Pages, Netlify, Vercel, Cloudflare, Apache, Nginx) ou abrindo o arquivo `index.html` diretamente no navegador.
- **Integração WhatsApp:** Geração dinâmica no cliente de deep links (`wa.me`) com mensagens pré-preenchidas e codificadas baseadas nas respostas de qualificação do usuário.

---

## 📁 Estrutura de Arquivos

```
curriculo-up-landing/
├── index.html                  # Página principal completa com todas as 11 seções
├── politica-de-privacidade.html# Página e modal de conformidade LGPD
├── assets/
│   ├── css/
│   │   └── style.css           # Design system customizado e responsivo
│   ├── js/
│   │   └── script.js           # Multi-step form client-side, carrossel, accordion
│   └── img/
│       ├── logo.svg            # Logotipo vetorial oficial
│       ├── logo-white.svg      # Versão do logo para rodapé
│       └── vsl-poster.svg      # Thumbnail do player de vídeo VSL
```

---

## ⚙️ Como Configurar

1. **Número do WhatsApp:**
   No arquivo `assets/js/script.js`, altere a constante no topo do arquivo:
   ```javascript
   const CONFIG = {
     WHATSAPP_NUMBER: '5515997606068', // 55 + DDD + Número
   };
   ```

2. **Facebook Pixel & Google Analytics 4 (GA4):**
   No arquivo `index.html`, descomente os blocos `<!-- INSERIR PIXEL ID -->` e `<!-- INSERIR GA4 ID -->` e insira seus IDs de rastreamento.

3. **Vídeo VSL:**
   No arquivo `index.html`, procure pela seção `id="vsl-iframe-wrapper"` e insira o link embed do seu vídeo do YouTube ou Vimeo quando gravado.

---

## 💻 Como Visualizar Localmente

Basta dar dois cliques no arquivo `index.html` ou abrir com qualquer navegador web.
Nenhum interpretador PHP ou backend é necessário.
