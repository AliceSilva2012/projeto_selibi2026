# 📚 Blog Selibi 2026 - Thalita Rebouças

<img width="1440" height="900" alt="image" src="https://github.com/user-attachments/assets/51974924-518c-4814-8ecc-a4fb9245d79e" />

> Projeto escolar (blog) de desenvolvimento front-end criado para a feira literária [Selibi 2026](https://www.sesisp.org.br/educacao/noticia/selibi-2026-incentiva-protagonismo-estudantil-e-fortalece-a-formacao-de-leitores-na-rede-sesi-sp), com foco na vida e nas obras da escritora brasileira Thalita Rebouças.

> [!NOTE]
> **🚧 Projeto em Fase Final:** O projeto está nos últimos ajustes de layout e conteúdo. **Entrega oficial do projeto: 30 de setembro de 2026**. 

## 🚀 Funcionalidades e Estrutura

*   **Perfil da Autora:** Cabeçalho fixo (`position: fixed`) com compensação de margem e hero section com plano de fundo temático.
*   **Carrossel Infinito:** Animação contínua de capas de livros desenvolvida com CSS puro (`@keyframes` e `transform`).
*   **Linha do Tempo (Timeline):** Componente visual construído semanticamente com `<time>` e `<article>`, utilizando pseudo-elementos (`::before`) para os marcadores cronológicos da carreira da autora.
*   **Vitrine de Livros Interativa:** Layout responsivo em CSS Grid com cartões de livros que revelam a resenha (sinopse) através de um efeito de sobreposição translúcida (`opacity` e `transition`) no hover.
*   **Cartões de Perfil da Equipe:** Exibição estruturada dos integrantes do projeto utilizando Grid Layout e divisórias estilizadas.

## 📊 Status do Projeto

| Tarefa | Status |
| :--- | :---: |
| Estrutura HTML do Cabeçalho e Menu | ✅ Concluído |
| Centralização da Foto e Correção de Z-Index | ✅ Concluído |
| Lógica e Animação do Carrossel de Livros | ✅ Concluído |
| Linha do Tempo da Jornada da Autora | ✅ Concluído |
| Vitrine Interativa de Livros (Hover Overlay) | ✅ Concluído |
| Estrutura da Seção "Adaptações para o Cinema" | ⏳ Pendente |
| Estrutura da Seção "Livros e Coleções" | 🚧 Em andamento |
| Sobre o Grupo (Equipe) | ✅ Concluído |
| Desenvolvimento do Rodapé (Footer) | ✅ Concluído |
| Publicação na Internet (Hospedagem) | ⏳ Pendente |

## 🛠️ Tecnologias Utilizadas

*   **HTML5:** Semântica e estruturação.
*   **CSS3:** Flexbox, Grid Layout, animações avançadas (`@keyframes`) e Media Queries para adaptação em telas menores.
*   **Git / GitHub:** Versionamento do código e colaboração escolar.

---

## 🌎 Teste o preview deste projeto no seu navegador!

> O projeto já conta com adaptações responsivas (`@media queries`) para reorganizar os cartões da equipe e o menu, e segue em aprimoramento contínuo para a versão final, ou seja, a questão da responsividade já está à parte disponível ao publico, porém ainda segue com melhorias.

- **Selibi 2026:** [VEJA O PREVIEW DESTE PROJETO NO SEU NAVEGADOR!](https://projetoselibi.netlify.app)
  
---

## 📂 Arquitetura do Projeto

```mermaid
graph TD;
    A[blog_selibi] --> B(index.html);
    A --> C(style.css);
    A --> D[📁 img];
    D --> E(biblioteca.png);
    D --> F(lupa.png);
    D --> G(livro1.png...livro8.png);
