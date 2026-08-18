# Steelmast Branding

Este repositório centraliza os logotipos, banners e elementos visuais oficiais da Steelmast. O objetivo é garantir a consistência da marca em todos os canais digitais (e-mails, sistemas e sites).

---

## Como usar as imagens

**NUNCA** copie o link da página do GitHub para usar no HTML do site ou assinatura de e-mail. Esse link não carrega a imagem diretamente. Sempre utilize o endereço da **CDN (jsDelivr)**, que garante carregamento rápido e evita bloqueios.

### Padrão da URL:

`https://cdn.jsdelivr.net/gh/SteelMast-Labs/branding@main/images/[CAMINHO_DA_IMAGEM]`

_Exemplo prático para assinatura de e-mail:_

```html
<img
  src="https://cdn.jsdelivr.net/gh/SteelMast-Labs/branding@main/images/email/exposibram-2026.png"
  alt="Steelmast"
/>
```

---

## Estrutura do repositório

```text
└── images
    ├── brand/ # Identidade visual institucional (Logos e Ícones)
    └── email/ # Campanhas, eventos e assinaturas de e-mail temporárias
```

---

## Regras

1. **Nunca delete ou renomeie arquivos antigos:** Se você remover a imagem `exemplo.png`, todos os e-mails enviados no passado que usavam esse link ficarão com a imagem quebrada.
2. **Nomes de arquivos:** Use apenas letras minúsculas, hifens e números. Nunca use espaços ou caracteres especiais (ex: `ç`, `ã`).
3. **Formatos:**
   - Use `.svg` para aplicações em sites e sistemas web (não pixelam).
   - Use `.png` para imagens com fundo transparente voltadas para e-mail.

---

_Dúvidas ou atualizações de marca? Procure o setor de Tecnologia da Informação e Comunicação._
