# Site Dr. Luiz Carlos Ortiz - Cirurgião Plástico

**URL:** https://drortiz.vercel.app

## 📋 Guia de Configuração para o Dr. Ortiz

### Passo 1: Criar conta na Vercel

1. Acesse: https://vercel.com
2. Clique em **"Sign Up"** (Criar conta)
3. Use o email: **lclortizmd@gmail.com**
4. Escolha **"Continue with Email"**
5. Confirme o email que receberá na caixa de entrada
6. Complete o cadastro

### Passo 2: Importar o site

1. Após fazer login na Vercel, clique em **"Add New..."** → **"Project"**
2. Clique em **"Import Git Repository"**
3. Cole este link: `https://github.com/occydefi/dr-luiz-ortiz`
4. Clique em **"Import"**
5. Deixe as configurações padrão e clique em **"Deploy"**
6. Aguarde 1-2 minutos até aparecer "Congratulations!"

### Passo 3: Configurar domínio (opcional)

Se quiser usar um domínio próprio como `www.drortiz.com.br`:

1. No painel da Vercel, vá em **Settings** → **Domains**
2. Adicione seu domínio
3. Siga as instruções para configurar o DNS

---

## ✏️ Como Editar o Site

### Opção 1: Editar online (mais fácil)

1. Acesse: https://github.com/occydefi/dr-luiz-ortiz
2. Faça login no GitHub (se não tiver conta, crie grátis)
3. Clique no arquivo `index.html`
4. Clique no ícone de lápis (✏️) no canto superior direito
5. Faça as alterações desejadas
6. Role até o final, adicione uma descrição e clique em **"Commit changes"**
7. A Vercel vai atualizar o site automaticamente em 1-2 minutos

### Opção 2: Editar localmente (para quem sabe programar)

```bash
git clone https://github.com/occydefi/dr-luiz-ortiz.git
cd dr-luiz-ortiz
# Edite os arquivos
git add .
git commit -m "Descrição da mudança"
git push
```

---

## 📁 Estrutura do Site

- **index.html** - Página principal (todo o conteúdo)
- **style.css** - Estilos visuais
- **imagens/** - Pasta com todas as fotos
  - `foto-perfil.jpg` - Foto do Dr. Ortiz
  - `resultado-*.jpg` - Fotos de antes/depois no carrossel

---

## 🔧 Principais Alterações Que Pode Fazer

### Mudar CRM/RQE

Procure por `CRM 11820` no arquivo `index.html` e substitua pelo número correto.

### Adicionar/Remover Fotos do Carrossel

1. Faça upload das novas imagens na pasta `imagens/`
2. No `index.html`, procure por `<!-- Carrossel -->`
3. Adicione um novo bloco:

```html
<div class="carousel-item">
    <img src="imagens/sua-nova-foto.jpg" alt="Descrição">
</div>
```

4. Adicione também um novo ponto (dot) embaixo do carrossel

### Mudar Textos

Edite diretamente o conteúdo entre as tags HTML no arquivo `index.html`.

### Mudar Cores

Edite o arquivo `style.css` - procure por `:root` no início.

---

## 🆘 Precisa de Ajuda?

- **Occy (AI Assistant):** Disponível via WhatsApp da Roberta
- **Email de suporte:** Contate a Roberta

---

## 📊 Informações Técnicas

- **Tecnologia:** HTML5, CSS3, JavaScript puro (sem frameworks)
- **Hospedagem:** Vercel (grátis)
- **Repositório:** GitHub (público)
- **Deploy:** Automático a cada commit no GitHub

---

**Criado com ❤️ por Occy AI**
