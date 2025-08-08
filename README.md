# Site Pessoal — Carlos Ribeiro

Este repositório contém o código-fonte do site pessoal publicado em **https://chmribeiro.eu** através do **GitHub Pages**.

## Estrutura de ficheiros

- `index.html` — Página inicial
- `sobre.html` — Página "Sobre mim"
- `trabalhos.html` — Página "Trabalhos e Documentos"
- `favicon.ico` — Ícone do site
- `apple-touch-icon.png` — Ícone para dispositivos móveis Apple
- `logo.png` — Logotipo exibido no topo das páginas
- `avatar-512.jpg` — Fotografia (se aplicável)
- `docs/` — Pasta sugerida para guardar PDFs ou outros documentos para download

## Publicação no GitHub Pages

O site é hospedado diretamente a partir da branch `main` deste repositório.  
Qualquer alteração enviada para o `main` será publicada automaticamente em **https://chmribeiro.eu** após alguns segundos/minutos.

## Como atualizar o site

1. **Editar ficheiros** no seu computador (HTML, imagens, PDFs).
2. Entrar no repositório no GitHub: `https://github.com/solribeiro/chmribeiro.eu`
3. Clicar em **Add file → Upload files**.
4. Arrastar os ficheiros atualizados ou novos para a área de upload.
5. Escrever uma mensagem de commit descritiva.
6. Clicar em **Commit changes**.

## Como adicionar PDFs na página Trabalhos

1. Criar uma pasta chamada `docs/` no repositório (se não existir).
2. Fazer upload do ficheiro PDF para `docs/`.
3. Editar `trabalhos.html` e alterar o link para apontar para o novo ficheiro, por exemplo:
   ```html
   <a href="/docs/relatorio-exemplo.pdf">Abrir PDF</a>
   ```

## Notas

- O site suporta apenas HTML, CSS e JavaScript estáticos.
- Não há suporte para PHP, bases de dados ou outro back-end no GitHub Pages.
- Recomenda-se otimizar imagens e PDFs antes de enviar, para manter o carregamento rápido.
