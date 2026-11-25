# 🚀 Landing Fé & Papel — como publicar e configurar

## 1. Publicar no Vercel (2 minutos, grátis)
1. Acesse **vercel.com** e entre com a conta GitHub (ou crie com e-mail)
2. "Add New → Project" → **"Deploy without Git"** não existe pra pasta? Use o caminho rápido abaixo ↓
3. **Caminho mais fácil:** arraste e solte — na tela inicial do painel Vercel, solte a pasta `landing` inteira em "Deploy" (drag & drop). Pronto: `feepapel-xxx.vercel.app`
4. Renomeie: Project Settings → Domain → Edit → **`feepapel`**

## 2. O que trocar no index.html ANTES de publicar (5 substituições)
| O quê | Onde | Trocar por |
|---|---|---|
| `href="#CHECKOUT"` (4 ocorrências) | botões CTA | link do checkout Kiwify |
| `<!-- META PIXEL AQUI` | `<head>` | código do pixel (Ads Manager → Eventos) |

> FAQ e contatos do rodapé foram removidos a pedido — as imagens em `imgs/` são screenshots reais das páginas dos PDFs (geradas do produto de verdade). Se regerar os PDFs, gere as imagens de novo.

## 3. Mockups (a imagem vale ouro)
Com o produto pronto, gere fotos de verdade: imprima 1 folha do kit natal + 1 devocional na gráfica local, fotografe na janela (guia no upsell, cap. 3) e salve como `landing/imgs/mockup-hero.png`. **Landing com foto real converte 2-3× mais que bloco ilustrado.** Enquanto não tiver, o bloco estilizado já funciona.

## 4. Checklist pré-ar
- [ ] Checkout Kiwify testado (compra de R$ 1 pra si mesmo)
- [ ] Pixel instalado e evento Purchase configurado na Kiwify (integração nativa: Kiwify → Integrações → Pixel)
- [ ] Bump (R$ 17) e upsell (R$ 47) ligados no checkout
- [ ] Link do grupo VIP no PDF de boas-vindas
- [ ] Teste de celular: abrir a landing no celular e clicar em tudo
