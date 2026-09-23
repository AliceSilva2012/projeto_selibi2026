# 📚 Blog Selibi 2026 - Thalita Rebouças

> Projeto (escolar) de desenvolvimento frontend criado para a feira literária Selibi 2026, com foco na vida e nas obras da escritora brasileira Thalita Rebouças.

> [!NOTE]
> **🚧 Projeto em Desenvolvimento:** Esta não é a versão final do projeto. Novas funcionalidades, novas `section`, melhorias de design e ajustes de informações estão sendo implementados continuamente. **Entrega do projeto: 28 de setembro de 2026**. 

## 🚀 Funcionalidades

*   **Perfil da Autora:** Estruturação em bloco com alinhamento visual e imagem circular.
*   **Carrossel Infinito:** Animação contínua e fluida desenvolvida com CSS puro (`@keyframes` e `transform`).
*   **Menu de Navegação:** Cabeçalho fixo com efeitos de transição (hover) interativos.

## 📊 Status do Projeto

| Tarefa | Status |
| :--- | :---: |
| Estrutura HTML do Cabeçalho e Menu | ✅ Concluído |
| Centralização da Foto de Perfil | ✅ Concluído |
| Lógica e Animação do Carrossel de Livros | ✅ Concluído |
| Criação da Seção "Adaptações para o Cinema" | ⏳ Pendente |
| Informações do Grupo | ⏳ Pendente |
| Publicação na Internet (Hospedagem) | ⏳ Pendente |

## 🛠️ Tecnologias Utilizadas

*   **HTML5:** Semântica e estruturação.
*   **CSS3:** Flexbox, animações e responsividade.
*   **Git / GitHub:** Versionamento do código e colaboração escolar.

## 📂 Arquitetura do Projeto

```mermaid
graph TD;
    A[blog_selibi] --> B(index.html);
    A --> C(style.css);
    A --> D[📁 img];
    D --> E(pfp.png);
    D --> F(livro1.png);
    D --> G(livro2.png...);
