# 📚 Blog Selibi 2026 - Thalita Rebouças

<img width="1440" height="900" alt="image" src="https://github.com/user-attachments/assets/87bc421a-f961-465c-a09f-f3727be4c605">

> Projeto (escolar) de desenvolvimento frontend criado para a feira literária [Selibi 2026](https://www.sesisp.org.br/educacao/noticia/selibi-2026-incentiva-protagonismo-estudantil-e-fortalece-a-formacao-de-leitores-na-rede-sesi-sp), com foco na vida e nas obras da escritora brasileira Thalita Rebouças.

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
