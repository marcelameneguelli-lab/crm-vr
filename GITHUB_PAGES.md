# Como publicar o CRM no GitHub Pages

## Arquivos para fazer upload (todos os 6)
- `index.html`
- `manifest.json`
- `sw.js`
- `icon-192.png`
- `icon-512.png`

---

## Passo a passo

### 1. Criar conta e repositório
1. Acesse https://github.com e crie uma conta gratuita
2. Clique em **+** (canto superior direito) → **New repository**
3. Nome: `crm-vr`
4. Marque **Public**
5. Clique em **Create repository**

### 2. Fazer upload dos arquivos
1. Na página do repositório, clique em **Add file → Upload files**
2. Arraste os 6 arquivos acima para a área de upload
3. Clique em **Commit changes**

### 3. Ativar GitHub Pages
1. Clique em **Settings** (menu do repositório)
2. No menu lateral: **Pages**
3. Em "Source": selecione **Deploy from a branch**
4. Branch: **main** | Pasta: **/ (root)**
5. Clique em **Save**

### 4. Acessar o app
Aguarde ~2 minutos e acesse:
```
https://SEU-USUARIO.github.io/crm-vr/
```
Substitua SEU-USUARIO pelo seu nome de usuário do GitHub.

---

## Instalar como app

### No celular (Android + Chrome)
1. Abra o link no Chrome
2. Toque no menu ⋮ → **Adicionar à tela inicial**
3. Confirme → ícone "CRM VR" aparece na tela inicial

### No computador (Chrome)
1. Abra o link no Chrome
2. Na barra de endereços, clique no ícone ⊕ (instalar)
3. Clique em **Instalar**
4. O app abre como janela independente

---

## Atualizar quando houver nova versão
1. Volte ao repositório no GitHub
2. Clique no arquivo `index.html`
3. Clique no ícone de lápis ✏️ → **Upload file** → substitua
4. **Commit changes** — atualiza automaticamente para todos
