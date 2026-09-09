# 📓 Notas de Referência de modificações


## 🚀 Comandos do Terminal (Local)
* **Limpar cache e iniciar o servidor:**
  ```bash
  rm -rf .jekyll-cache _site && bundle exec jekyll serve
  ```
  
## Trabalhar localmente 
* http://localhost:4000/


* **Atualizar o site no Git:**
  ```bash
  git add .
  git commit -m "Minha mensagem de atualização"
  git push 
  ```

## 🖼️ Tamanho de Imagens e Fotos
* No texto (`.md` ou `.html`), para controlar o tamanho exato:
  ```html
  <img src="/images/foto.jpg" alt="Descrição" style="width: 250px; height: auto;">
  ```

## ✍️ Customização de Texto e Cores
* **Texto menor e cinza (Legendas):**
  ```html
  <span style="font-size: 82%; color: #666; font-style: italic;">Texto aqui</span>
  ```
* **Caixinha de Citação:** Basta colocar o símbolo `>` no início da linha.

## 🔗 Links e Arquivos PDF
* **Link para a USP abrindo em nova aba:**
  ```html
  <a href="https://usp.br" target="_blank" style="font-weight: bold;">USP</a>
  ```
* **Botão para baixar PDF:**
  ```html
  <a href="/assets/pdfs/arquivo.pdf" target="_blank" style="background-color: #0076df; color: white; padding: 8px 16px; text-decoration: none; border-radius: 4px;">Clique aqui para abrir o PDF</a>
  ```