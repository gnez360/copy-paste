# 📋 Copy & Paste — Página simples (Vercel + GitHub)

Uma página HTML estática e responsiva que permite **copiar e colar texto** diretamente da área de transferência — ideal para testes rápidos ou utilitários mobile.

---

## 🚀 Recursos

* Interface limpa e mobile-first
* Botões para **colar**, **exibir** e **copiar** conteúdo
* Feedback visual rápido (toast messages)
* Compatível com **Clipboard API** moderna
* Pode ser hospedada **gratuitamente na Vercel**

---

## 🧩 Estrutura do Projeto

```
📁 copy-paste-vercel/
 ├── index.html   # Página principal (HTML + JS + CSS inline)
 └── README.md    # Este arquivo
```

Não há dependências externas. Tudo é feito com HTML, CSS e JavaScript puro.

---

## 💻 Pré-requisitos

* Conta no **GitHub**
* Conta gratuita na **Vercel**

---

## 🧱 Como publicar no Vercel

1. Crie um novo repositório no GitHub (ex: `copy-paste-vercel`)
2. Envie o arquivo `index.html` para o repositório:

   ```bash
   git init
   git add index.html README.md
   git commit -m "Add copy-paste page"
   git branch -M main
   git remote add origin https://github.com/<seu-usuario>/copy-paste-vercel.git
   git push -u origin main
   ```
3. Vá até [vercel.com/new](https://vercel.com/new)
4. Clique em **Import Project → Import Git Repository**
5. Selecione seu repositório e configure:

   * **Framework Preset:** `Other`
   * **Build Command:** *(deixe em branco)*
   * **Output Directory:** *(deixe em branco)*
6. Clique em **Deploy** 🎉

Sua página estará disponível em:

```
https://<seu-projeto>.vercel.app
```

---

## 📱 Dica para mobile

* A página é otimizada para telas pequenas.
* O botão **Colar da Área de Transferência** pode exigir permissão do navegador (especialmente no iOS/Safari).

---

## 🧠 Próximos passos (opcional)

* Adicionar botão de limpar
* Suporte a tema claro/escuro
* Copiar automaticamente após exibir
* Adicionar PWA (para usar offline)

---

## 🪪 Licença

MIT © 2025

Sinta-se livre para modificar e reutilizar.
