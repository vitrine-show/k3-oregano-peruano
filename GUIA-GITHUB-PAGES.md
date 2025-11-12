# 🚀 GUIA COMPLETO - Como Publicar o Site K3 Orégano no GitHub

## 📋 PASSO 1: Criar o Repositório no GitHub

1. Acesse https://github.com e faça login
2. Clique no **+** (canto superior direito) e selecione **New repository**
3. Preencha:
   - **Repository name**: `k3-oregano-peruano`
   - **Description**: "Landing page do K3 Orégano Peruano"
   - Marque como **Public** (público)
   - ✅ Marque **Add a README file**
4. Clique em **Create repository**

---

## 📤 PASSO 2: Fazer Upload dos Arquivos

### Opção A: Via Interface do GitHub (Mais fácil)

1. No seu novo repositório, clique em **Add file** > **Upload files**
2. Arraste ou selecione os arquivos:
   - `index.html`
   - `README.md`
   - `.gitignore`
3. No campo de commit, escreva: "Adiciona página principal"
4. Clique em **Commit changes**

### Opção B: Via Git (Linha de comando)

```bash
# Clone o repositório
git clone https://github.com/SEU-USUARIO/k3-oregano-peruano.git

# Entre na pasta
cd k3-oregano-peruano

# Copie os arquivos para esta pasta
# (index.html, README.md, .gitignore e pasta images/)

# Adicione os arquivos
git add .

# Faça o commit
git commit -m "Adiciona página principal"

# Envie para o GitHub
git push origin main
```

---

## 🖼️ PASSO 3: Adicionar as Imagens

1. No repositório do GitHub, clique na pasta **images/**
2. Clique em **Add file** > **Upload files**
3. Faça upload das imagens:
   - `logo-k3.png`
   - `oregano-destaque.jpg`
   - `produto-k3.jpg` (opcional)
   - `tabela-nutricional.jpg` (opcional)
4. Escreva no commit: "Adiciona imagens do produto"
5. Clique em **Commit changes**

---

## 🌐 PASSO 4: Ativar o GitHub Pages

1. No seu repositório, clique em **Settings** (Configurações)
2. No menu lateral esquerdo, procure e clique em **Pages**
3. Em **Source** (Fonte/Branch):
   - Selecione: **Deploy from a branch**
   - Branch: **main**
   - Pasta: **/ (root)**
4. Clique em **Save**
5. 🎉 Aguarde 2-3 minutos!

---

## 🔗 PASSO 5: Acessar seu Site

Após alguns minutos, volte em **Settings** > **Pages**

Você verá uma mensagem:
> ✅ Your site is live at https://SEU-USUARIO.github.io/k3-oregano-peruano/

**Este é o link do seu site!** Você pode:
- Compartilhar nas redes sociais
- Criar QR Code para este link
- Enviar para clientes
- Usar em campanhas de marketing

---

## 📱 DICAS EXTRAS

### Como criar um QR Code para o site:

1. Acesse: https://br.qr-code-generator.com/
2. Cole o link: `https://SEU-USUARIO.github.io/k3-oregano-peruano/`
3. Personalize as cores (use o verde da K3: #2e4a3d)
4. Baixe o QR Code em alta resolução
5. Use em embalagens, cartões, materiais impressos!

### Como atualizar o site depois:

1. Acesse o arquivo que quer editar no GitHub
2. Clique no ícone de lápis (✏️) para editar
3. Faça suas alterações
4. Clique em **Commit changes**
5. O site atualiza automaticamente em 1-2 minutos!

### Testar em diferentes dispositivos:

- Desktop: Abra normalmente no navegador
- Mobile: Abra no celular ou use o Chrome DevTools (F12 > Toggle device toolbar)
- Tablet: Teste a responsividade em diferentes tamanhos

---

## ❓ PROBLEMAS COMUNS

**Site não aparece após ativar Pages?**
- Aguarde 5-10 minutos
- Verifique se a branch está como "main"
- Limpe o cache do navegador (Ctrl+F5)

**Imagens não aparecem?**
- Verifique se os nomes estão corretos
- Certifique-se que estão na pasta `images/`
- Nomes devem ser exatamente: `logo-k3.png`, `oregano-destaque.jpg`

**Erro 404?**
- Verifique se o arquivo `index.html` está na raiz do repositório
- Confirme que o nome está correto (em minúsculas)

---

## 📞 PRECISA DE AJUDA?

Se tiver dúvidas sobre qualquer passo, pode me chamar! 😊

---

**Boa sorte com o lançamento do K3 Orégano Peruano! 🌿**
