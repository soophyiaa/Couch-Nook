# Couch-Nook
Couch&Nook é um app de aprendizado integrado de idiomas, com foco no estudo da cultura e linguagem.

# 🕹️ Couch & Nook

Protótipo frontend de uma plataforma gamificada para aprendizado de idiomas, projetada para transformar o estudo de novas línguas em uma jornada leve, visual e nostálgica, inspirada nos videogames arcade de 16-bits dos anos 90.

---

## 💡 Sobre o Projeto e Objetivo

O nome **Couch & Nook** vem da união entre *couch* (sofá) e *nook* (canto aconchegante). A proposta nasceu de uma dor real enfrentada por estudantes de idiomas: o cansaço de plataformas tradicionais e a necessidade constante de sair do aplicativo para pesquisar curiosidades históricas, expressões locais e contexto cultural em sites externos.

O objetivo do **Couch & Nook** é unir **prática linguística** e **imersão cultural** em um único ambiente confortável e intuitivo, onde cada detalhe visual — das fontes pixeladas às paletas de cores temáticas — ajuda o usuário a mergulhar no universo do país que está estudando.

---

## ⚙️ Funcionalidades e Fluxo Completo do App

### 1. Tela de Login (Porta de Entrada)
* Funciona como a página inicial e ponto de partida para toda a navegação do aplicativo.
* Conta com validação visual obrigatória nos campos de entrada (`input`), orientando o usuário antes de liberar o acesso à plataforma.

### 2. Seleção de Mundos e Idiomas (Identidade Visual por País)
* Inspirada nos mapas de progressão de jogos clássicos (com layout em formato de zigue-zague), a seleção divide os idiomas em **quatro mundos culturais**, cada um com sua própria paleta de cores e identidade temática para simbolizar o país correspondente:
  * **Mundo Londres (Inglês):** Estética e tons inspirados na cultura britânica.
  * **Mundo Andaluzia (Espanhol):** Paleta quente e vibrante remetendo à cultura hispânica.
  * **Mundo Paris (Francês):** Identidade visual clássica inspirada na cultura francesa.
  * **Mundo Joseon (Coreano):** Cores e referências inspiradas na história e tradição da Coreia.

### 3. Home Personalizada e Navegação
* Ao escolher um mundo, o usuário entra na **Home exclusiva daquele idioma**, onde toda a interface acompanha as cores temáticas daquela nação.
* Inclui menus integrados para alternar entre idiomas, acompanhar o progresso e acessar as configurações visuais do protótipo, sempre com botões de avançar e voltar bem posicionados para garantir uma boa experiência de navegação (UX).

### 4. Trilha de Fases e Pedagogia Adaptada
* **Fases Introdutórias:** Cada idioma apresenta lições estruturadas para iniciantes, abordando conteúdos essenciais como verbo *ser/estar*, números e vocabulário prático do dia a dia.
* **Fase Extra de Alfabetização (Coreano):** Para o idioma coreano — que utiliza um sistema de escrita diferente do alfabeto romano (*Hangul*) —, o aplicativo conta com uma etapa introdutória adicional dedicada exclusivamente a ensinar os caracteres e a pronúncia antes de avançar para os exercícios práticos.

### 5. Exercícios Interativos Diversificados
* As lições não se limitam a um único formato de resposta, alternando entre:
  * **Questões de múltipla escolha**, ideais para reconhecimento de vocabulário e associação rápida.
  * **Campos de digitação direta (`input`)**, estimulando a escrita ativa e a fixação das palavras no idioma estudado.

### 6. Páginas de Imersão Cultural
* Integradas diretamente no fluxo de cada mundo, oferecem conteúdos extras sobre a história, curiosidades, costumes e influências culturais de cada país, eliminando a necessidade de buscar referências fora da plataforma.

---

## 🛠️ Tecnologias e Arquitetura Técnica

* **HTML5 Semântico:** Estruturação clara das telas, formulários, listas de navegação e áreas de conteúdo.
* **CSS3 Temático:** Estilização retro 16-bits utilizando tipografia pixelada (*Press Start 2P*), bordas sólidas, sombras marcadas e organização de layout com Flexbox e posicionamento.
* **Arquitetura Estrita por IDs:** Todo o projeto foi desenvolvido sem o uso de classes (`class`), aplicando estilização exclusivamente através de seletores de identificação única (`#id`). Essa abordagem garante controle absoluto sobre a especificidade de cada componente visual e mantém o isolamento de estilos entre as diferentes telas e paletas de países.
* **Modularização por Telas:** Os arquivos HTML e CSS são organizados diretamente pelas telas e fluxos do sistema, partindo da página de login para os demais módulos sem dependência de bibliotecas externas ou frameworks.

---

## 🚀 Como Executar o Projeto

1. Clone ou baixe este repositório na sua máquina:
   ```bash
   https://github.com/soophyiaa/Couch-Nook.git
