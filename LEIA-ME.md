# AutoTaxa Cargo — Landing page

Site estático (sem build). Suba para o GitHub e importe na Vercel (Framework: Other).

## Ficheiros a substituir
```
assets/vsl.mp4                  ← vídeo 9:16 (hoje é um provisório de 10 s)
assets/provas/prova-1..5.png    ← prints do WhatsApp (hoje são provisórios)
favicon.png                     ← usar o MESMO da Pro (na raiz); o atual é provisório
```

## O que ajustar depois
- `main.js` → `UNLOCK_AT` (segundos em que abre a secção de depoimentos; o CTA final aparece no último depoimento).
- `index.html` → comentário "UTMify (passo final)": colar o script de UTMs do Cargo.
- `termos.html` → cláusula 5 (reembolso 7 dias, igual à Pro): confirmar para o Cargo.

## Regras de pixel
Só `PageView` na página (ID 2337044630374395). Compra/InitiateCheckout vêm da OkandaPay (Pixel + API de Conversões).
Sem upsell/downsell. Páginas: `/`, `/termos`, `/privacidade`.
