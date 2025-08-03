# XML Quest Editor

Este é um editor de quests para arquivos XML, criado com a biblioteca Flet. Ele oferece uma interface gráfica para visualizar, editar e gerenciar dados de quests de forma simples e intuitiva, sendo ideal para projetos que utilizam a estrutura de arquivo `Quest.xml`.

O editor é projetado para ser leve e eficiente, simplificando o gerenciamento do conteúdo do jogo no arquivo `Quest.xml`.

[🔗 View video demonstration](https://github.com/user-attachments/assets/763422e1-c3c9-456e-85cc-84b5538c3f6a)

---

## Funcionalidades

* **Edição Visual:** Modifique campos como Título, Corpo da quest, Nível, ID do NPC, tipo da quest, e defina metas, recompensas e condições diretamente na interface.
* **Gerenciamento Dinâmico:** Adicione, edite ou remova recompensas (como EXP, Bits e itens) e metas de forma flexível.
* **Criação de Pasta Automática:** Ao iniciar, o editor verifica se a pasta `XML` existe e a cria automaticamente se necessário, evitando erros de arquivo não encontrado.
* **Busca Rápida:** Encontre quests facilmente usando a barra de busca, filtrando por ID ou Título.
* **Paginação:** Navegue por grandes listas de quests de forma organizada, com 50 quests por página.
* **Salvar Alterações:** As modificações em uma quest são salvas primeiro na memória do aplicativo ao clicar no ícone verde de salvar. Depois, todas as alterações podem ser escritas no arquivo `Quest.xml` com um único clique no botão "Save XML".
* **Exclusão de Quests:** Remova quests indesejadas diretamente da interface do usuário.
* **Interface Moderna:** O editor utiliza um tema escuro e um design limpo, proporcionando uma experiência de usuário agradável.

---

## Como Usar

1.  Após usar o **BIN - XML CONVERTER**, pegue o arquivo `Quest.XML` e coloque-o na pasta `XML` do Quest Editor. Se a pasta não existir, ela será criada automaticamente ao executar o editor.
2.  Execute `Quest Editor.exe`.
3.  Modifique a quest desejada. Clique no ícone verde de "Save Changes" para salvar as alterações daquela quest na memória e depois no botão "Save XML" no topo para salvar todas as alterações da memória para o arquivo `Quest.xml`.
4.  Pegue o arquivo `Quest.XML` modificado e converta-o para um arquivo `.bin` usando o **BIN - XML CONVERTER**. Use o **DB Importer** para salvar as alterações no banco de dados.
5.  Gere o novo `Pack 03` e coloque-o na pasta `data` do cliente que você está usando.
