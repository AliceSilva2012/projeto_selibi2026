# 📚 Blog Selibi 2026 - Thalita Rebouças

<img width="1440" height="900" alt="image" src="https://github.com/user-attachments/assets/7a113a35-dd2a-42bd-8322-96aa2de6ef49">

> Projeto (escolar) de desenvolvimento frontend criado para a feira literária [Selibi 2026](https://www.sesisp.org.br/educacao/noticia/selibi-2026-incentiva-protagonismo-estudantil-e-fortalece-a-formacao-de-leitores-na-rede-sesi-sp), com foco na vida e nas obras da escritora brasileira Thalita Rebouças.

> [!NOTE]
> **🚧 Projeto em Desenvolvimento:** Esta não é a versão final do projeto. Novas funcionalidades, novas `section`, melhorias de design e ajustes de informações estão sendo implementados continuamente. **Entrega do projeto: 28 de setembro de 2026**. 

## 🚀 Funcionalidades e Estrutura

*   **Perfil da Autora:** Cabeçalho fixo (`position: fixed`) com compensação de margem e imagem circular centralizada.
*   **Carrossel Infinito:** Animação contínua de capas de livros desenvolvida com CSS puro (`@keyframes` e `transform`).
*   **Linha do Tempo (Timeline):** Componente visual construído semanticamente com `<time>` e `<article>`, utilizando pseudo-elementos (`::before`) para os marcadores cronológicos.
  
## 📊 Status do Projeto

| Tarefa | Status |
| :--- | :---: |
| Estrutura HTML do Cabeçalho e Menu | ✅ Concluído |
| Centralização da Foto e Correção de Z-Index | ✅ Concluído |
| Lógica e Animação do Carrossel de Livros | ✅ Concluído |
| Linha do Tempo da Jornada da Autora | ✅ Concluído |
| Estrutura da Seção "Adaptações para o Cinema" | ⏳ Pendente |
| Sobre o Grupo | ⏳ Pendente |
| Desenvolvimento do Rodapé (Footer) | ⏳ Pendente |
| Publicação na Internet (Hospedagem) | ⏳ Pendente |

## 🛠️ Tecnologias Utilizadas

*   **HTML5:** Semântica e estruturação.
*   **CSS3:** Flexbox, animações e responsividade.
*   **Git / GitHub:** Versionamento do código e colaboração escolar.

---

> [!NOTE]
> **❗️ERROR 404:** Projeto não disponível para teste!

## 📂 Arquitetura do Projeto

```mermaid
graph TD;
    A[blog_selibi] --> B(index.html);
    A --> C(style.css);
    A --> D[📁 img];
    D --> E(pfp.png);
    D --> F(livro1.png);
    D --> G(livro2.png...);
