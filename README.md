# 💻 Configurações do VSCode

Este repositório contém minhas configurações do VSCode para melhorar a produtividade e personalizar a IDE. 🎨

---

## ⚙️ Configurações
```json
"workbench.editor.enablePreview": false, 
"workbench.colorTheme": "Min Dark", // Extensão Min Theme (Download)
"workbench.iconTheme": "symbols", // Extensão Symbols (Download)
"git.confirmSync": false,
"git.autofetch": true,
"git.enableSmartCommit": true,
"workbench.editorAssociations": {
    "*.exe": "default"
},
"editor.fontFamily": "JetBrains Mono", // Fonte JetBrainsMono (Download)
"editor.fontSize": 14,
"editor.lineHeight": 1.8, 
"editor.rulers": [80,120], // Abrir VS Code com tela em branco 
"editor.fontLigatures": true, // Unir o igual (=) com o (>) (Unir símbolos)
"workbench.editor.labelFormat": "short",
"workbench.activityBar.location": "top", 
"editor.scrollbar.horizontal": "hidden",
"editor.scrollbar.vertical": "hidden",
"window.commandCenter": false,
"workbench.layoutControl.enabled": false,
"explorer.fileNesting.enabled": true,
"explorer.fileNesting.patterns": {
  "package.json": ".eslint*, prettier*, tsconfig*, vite*, pnpm-*, bun.lockb, nest*, package-lock*",
  "tailwind.config.*": "tailwind.config*, postcss.config*",
  ".env.local": ".env*",
  ".env": ".env*"
},
"terminal.integrated.fontSize": 14,
"terminal.integrated.fontFamily": "JetBrainsMono Nerd Font", // *Fonte JetBrainsMono Nerd Font (Download)
"workbench.startupEditor": "none",
```

---
## 🛠️ Recursos Utilizados

Aqui estão as extensões, fontes e temas que você precisa instalar para usar minhas configurações:

1. 🎨 **Min Theme**  
   Um tema minimalista e elegante para o VSCode.  
   [🔗 Download Min Theme!](https://vscodethemes.com/e/miguelsolorio.min-theme/min-dark)

2. 🖋️ **JetBrains Mono**  
   Uma fonte projetada para desenvolvedores com ligaduras estilizadas.  
   [🔗 Download JetBrains Mono!](https://www.jetbrains.com/pt-br/lp/mono/)

3. 🖋️ **JetBrainsMono Nerd Font**  
   Uma versão da JetBrains Mono com suporte a Nerd Font para terminais personalizados.  
   [🔗 Download JetBrainsMono Nerd Font!](https://www.nerdfonts.com/font-downloads)

4. 📂 **Symbols Icon Theme**  
   Um conjunto de ícones para facilitar a navegação entre os arquivos.  
   🔎 *Procure por **Symbols Icon Theme** na aba de extensões do VSCode.*

---

## ✨ Outras Configurações
- **Nesting de arquivos no Explorer**: Facilita a organização de arquivos como `package.json` e `.env`.
- **Atalhos no Terminal**: Configuração para fonte e tamanho personalizáveis.
- **Personalização no editor**: Ativa ligaduras, configurações de barras de rolagem e posicionamento de ícones.

---

## 📄 Como Usar  

1. **Baixe os arquivos necessários:**  
   Certifique-se de baixar as fontes e extensões mencionadas na seção **Recursos Utilizados** acima.  

2. **Abra o VSCode e pressione** `CTRL + P`:  
   Este comando abrirá o campo de busca do VSCode.  

3. **Digite no campo:**  
   `>settings `
   (sem as aspas). Isso abrirá suas configurações no formato JSON.  

4. **Copie e cole o código apresentado acima:**  
   Substitua as configurações atuais pelo código fornecido neste repositório.  

5. **Reinicie o VSCode**:  
   Para aplicar as novas configurações, feche e abra o VSCode novamente. 🚀  

---

### ⚠️ Importante  

**Algumas configurações são baseadas no meu gosto pessoal. Se você não gostar de alguma, sinta-se à vontade para modificá-las!**

📦 **Dica:** *Faça um backup das suas configurações antes de realizar qualquer alteração. Isso garante que você possa restaurá-las caso necessário.* 

--- 

Contribuições e sugestões são bem-vindas! 🌟
