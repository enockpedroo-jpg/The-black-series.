# THE BLACK SERIES - APLICATIVO E GUIA DE PUBLICAÇÃO

Parabéns, Enoch! Aqui está o aplicativo completo de **THE BLACK SERIES**, configurado especificamente para:
1. **Publicar seus próprios vídeos** do celular ou computador.
2. **Permitir que os seus espectadores baixem e instalem o aplicativo diretamente** no telemóvel (Android ou iPhone) sem precisar pagar taxas à Google Play Store ou Apple Store.
3. **Monetizar com e-Mola / M-Pesa (876882323)** e **PayPal (enockpedroo@gmail.com)**.

---

## 1. Como as Pessoas Vão Baixar o Seu Aplicativo no Celular

Este app foi construído com a tecnologia **PWA (Progressive Web App)**, que é o padrão moderno usado por grandes plataformas:
- **No telemóvel Android (Google Chrome):**
  Ao abrir a página, aparece uma barra automática: **"Instalar The Black Series"** ou **"Baixar App"**. Quando a pessoa clica, o aplicativo é baixado para a tela de aplicativos do telefone com o seu logotipo oficial dourado!
- **No iPhone (Safari):**
  A pessoa clica no botão de partilha e seleciona **"Adicionar à Tela de Início"**. O app abre em tela cheia, sem barra de navegação, exatamente como um aplicativo da App Store.

---

## 2. Como Você Publica Novos Vídeos

Você não precisa programar nada para colocar episódios novos:
1. Abra o aplicativo e clique no botão superior: **"➕ Publicar Vídeo"**.
2. Escolha a série (ex: *A História de Amadeu*, *A História de Celina*, etc.).
3. Digite o número do episódio e o título.
4. **Envie o vídeo:** Você pode clicar em **"Arquivo de Vídeo"** e escolher um vídeo da galeria do seu celular, ou colar o link de um vídeo da internet (.mp4).
5. Escolha se ele é **Grátis** (como o Episódio 1) ou se custa **15 MT**.
6. Clique em **"Publicar no Aplicativo"**. O episódio entra imediatamente na lista para todos assistirem!

---

## 3. Como Colocar o Aplicativo no Ar Grátis na Internet

Para todo Moçambique e o mundo poderem acessar o link:
1. **Netlify (Mais fácil - 2 minutos):**
   - Acesse [netlify.com](https://www.netlify.com)
   - Arraste a pasta descompactada deste arquivo ZIP para a tela do Netlify.
   - O seu site/app ganha um link instantâneo gratuito (ex: `theblackseries.netlify.app`).
2. **Vercel ou GitHub Pages:**
   - Também pode enviar os arquivos gratuitamente.

---

## 4. Estrutura dos Arquivos Inclusos no ZIP
- `index.html`: O aplicativo completo com o reprodutor de vídeo, lista de episódios, modal de pagamento e painel de publicação.
- `manifest.json`: Arquivo que transforma o site em um aplicativo instalável no telemóvel.
- `sw.js`: Service Worker que permite carregar o aplicativo de forma ultra-rápida.
- `README.md`: Este guia completo de instruções.
