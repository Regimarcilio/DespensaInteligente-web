# 🧊 DespensaInteligente Web — v2.0

App web (PWA instalável) que guarda sua despensa com validade, **avisa antes de vencer**, gera a **lista de reposição sozinha** e mostra o **desperdício evitado em R$**. 100% offline-first: sem conta, sem rastreio, dados no navegador.

> Evolução web do [app Android original](https://github.com/Regimarcilio/Projeto_ListaCompras) (irmão do ListaCompras). Criado no Google AI Studio, refinado com auditoria minuciosa de estilo.

## ✨ Funcionalidades
- 📦 Estoque com busca, filtros por local **e por status** (Fresco/Atenção/Vencido com contadores)
- 🚦 Semáforo de validade + pílula de status no header
- 👆 Baixa em 1 gesto, foto do item, backup JSON local
- 🛒 Reposição automática + export no formato ListaCompras (WhatsApp/SMS)
- 💰 Economia do mês (salvos vs perdidos) · 🌗 claro/escuro/sistema · 📲 PWA + modal de instalação (APK via workflow)

## 🛠️ Stack
React 19 + TypeScript + Vite + Tailwind CSS 4 · PWA (Workbox) · `localStorage` como banco · ícones Lucide.

## 🚀 Rodar
```bash
npm install
npm run dev      # http://localhost:3000
npm run build    # gera dist/ + service worker
```

## 🤝 Contribuir
Toda demanda vira **issue** antes de virar código. Se ajuda você, deixe uma ⭐.
