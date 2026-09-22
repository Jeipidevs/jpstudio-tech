# JPStudio — Link in Bio Oficial (jpstudio.tech)

Link in bio oficial e central de redirecionamentos de **João Pedro Schmitz** (Fundador da **JPStudio**), desenhado especificamente para a bio do Instagram e presença digital de alta conversão.

- **Domínio Principal:** [https://jpstudio.tech](https://jpstudio.tech)
- **Infraestrutura:** Docker (Nginx Alpine) rodando no EasyPanel com SSL automático via Traefik.
- **Stack Técnica:** HTML5 semântico, CSS puro customizado com Design System Cyber Dark Luxury, Vanilla JS para micro-interações e Schema.org JSON-LD para SEO & AI Engines.

---

## 🎯 Redirecionamentos Estratégicos

1. 💻 **Tenha seu Sistema** → [https://dev.jpstudio.tech](https://dev.jpstudio.tech)
2. 📈 **Gestão de Tráfego Pago** → [https://bio.jpstudio.tech](https://bio.jpstudio.tech)
3. 💬 **WhatsApp Oficial** → Atendimento e orçamentos diretos com o fundador
4. 📸 **Instagram** → [@jpschmitz.dev](https://www.instagram.com/jpschmitz.dev/)
5. 💼 **LinkedIn** → [/in/devjoaoschmitz](https://www.linkedin.com/in/devjoaoschmitz)
6. 🐙 **GitHub** → [@Jeipidevs](https://github.com/Jeipidevs)

---

## 🚀 Como fazer o Deploy no EasyPanel

1. Crie um novo serviço no EasyPanel (projeto `web-sites`):
   - **Nome:** `site-jpstudio-tech`
   - **Source:** Git Repository (`git@github.com:Jeipidevs/jpstudio-tech.git`, branch `main`)
   - **Build Type:** `Dockerfile`
   - **Porta:** `80`
   - **Domínios:** `jpstudio.tech` e `www.jpstudio.tech`
2. No painel de DNS (Hostinger/Cloudflare), aponte o registro A de `jpstudio.tech` e `www` para o IP do servidor EasyPanel.
