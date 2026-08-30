# Shelved 📚 — Shared Library (Standalone HTML)

Uma aplicação web completa e autónoma num único ficheiro **`index.html`**, sem dependências de Node.js, npm ou processos de compilação. Basta dar **duplo clique** no ficheiro `index.html` para abrir diretamente no teu navegador!

---

## ✨ Funcionalidades

- **Paleta "Old Library"**: Cores vintage baseadas na imagem (`#1D1617`, `#262630`, `#2A374D`, `#444A41`, `#9F6932`, `#522623`), tipografia clássica (*Cinzel*, *Playfair Display*) e estética de biblioteca antiga.
- **Pesquisa Automática com API (Google Books API)**: Ao adicionar um livro, basta pesquisar pelo título, autor ou ISBN (ex: *"Dune"*, *"Ensaio sobre a Cegueira"*, *"The Hobbit"*) para preencher automaticamente capa, autores, ano, editora, categoria, sinopse, faixa etária e ISBN.
- **Suporte Bilingue**: Campos dedicados para Título em Inglês e Título em Português (*Título em Português*).
- **Base de Dados no GitHub & Sincronização**: Podes guardar a coleção em `localStorage` ou ligar ao teu repositório GitHub através de um Personal Access Token (PAT) nas Definições ⚙️ para sincronizar livros entre várias pessoas automaticamente sem custos de servidor.
- **3 Modos de Visualização**:
  - 🏛️ **Modo Biblioteca / Estante**: Capas com títulos, autores e etiquetas de categoria.
  - 📜 **Modo Lista Detalhada**: Cartões ricos com sinopse, estrelas, dono e localização.
  - 📋 **Modo Tabela**: Tabela compacta para consulta rápida.
- **Filtros e Pesquisa Avançada**: Filtros por *Formato* (Físico / Digital), *Faixa Etária*, *Categorias*, *Localizações/Estantes*, *Curador/Dono* e *Estado de Leitura*.
- **Onde Encontrar**: Organizador por divisões da casa, estantes e resumo de quem é o dono de cada livro.
- **Popup de Detalhes**: Capa emoldurada, títulos EN/PT, autor, ano, géneros, idades, sinopse completa, links para Google/Goodreads e opções de editar/remover.
- **Exportação & Importação**: Botões de 1-clique para descarregar ou importar backups em JSON.

---

## 🚀 Como Executar

Basta abrir o ficheiro **`index.html`** no teu navegador favorito (Chrome, Edge, Firefox, Safari).

---

## 🌐 Publicar no GitHub Pages

1. Envia esta pasta para um repositório no GitHub.
2. Vai a **Settings** → **Pages** no teu repositório.
3. Em **Source**, seleciona **GitHub Actions** (ou **Deploy from a branch: main**).
4. O teu site estará imediatamente online no link do GitHub Pages!
