# XML Quest Editor

Este é um editor de quests (missões) para arquivos XML. Ele fornece uma interface gráfica para visualizar, editar e gerenciar dados de quests de forma simples e intuitiva, ideal para projetos que utilizam a estrutura `Quest.xml`.

O editor foi projetado para ser leve e eficiente, facilitando o gerenciamento de conteúdo de jogos arquivo `Quest.xml`.

# Demo

https://github.com/user-attachments/assets/59574f58-25fa-4960-a39f-4f48d9e065b1

---

## Funcionalidades

* **Edição Visual:** Modifique campos como Título, Corpo, Nível e recompensas das quests diretamente na interface.
* **Gestão de Recompensas Dinâmica:** Adicione, edite ou remova recompensas de forma flexível, incluindo EXP, Bits (dinheiro) e itens.
* **Pesquisa Rápida:** Encontre quests facilmente usando a barra de pesquisa, filtrando por ID ou Título.
* **Paginação:** Navegue por grandes listas de quests de forma organizada, com paginação de 50 quests por página.
* **Salvar Alterações:** As modificações são salvas primeiro na memória da aplicação e, em seguida, podem ser escritas no arquivo `Quest.xml` com um único clique.
* **Exclusão de Quests:** Remova quests indesejadas diretamente da interface do usuário.
* **Interface Moderna:** O editor utiliza um tema escuro e um design limpo, proporcionando uma experiência de usuário agradável.
  
---

## Como Usar

1.  Após utilizar o **BIN - XML CONVERTER**, pegue o arquivo `Quest.XML` e coloque na pasta `XML` do Quest Editor.
2.  Execute o `Quest Editor.exe`.
3.  Modifique a quest que deseja. Clique no ícone verde para salvar as alterações (a quest irá fechar) e, em seguida, salve o arquivo XML no botão amarelo no topo.
4.  Pegue o arquivo `Quest.XML` e converta para `.bin` utilizando o **BIN - XML CONVERTER**. Utilize o **DB Importer** para salvar as alterações no banco de dados.
5.  Gere o novo `Pack 03` e coloque na pasta `data` do cliente utilizado.
