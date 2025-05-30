🏷️ Leilão-Java
Sistema de leilões desenvolvido em Java, com persistência de dados utilizando MySQL. Este projeto foi criado com o objetivo de simular um ambiente de leilões, permitindo o cadastro de itens, realização de lances e gerenciamento de usuários.

📌 Funcionalidades
Cadastro de usuários

Registro de itens para leilão

Realização de lances em tempo real

Histórico de lances por item

Determinação automática do vencedor ao final do leilão

🛠️ Tecnologias Utilizadas
Linguagem: Java

Banco de Dados: MySQL

IDE: NetBeans

Controle de Versão: Git

🚀 Como Executar o Projeto
Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/gabszv/Leilao-Java.git
Importe o projeto no NetBeans:

Abra o NetBeans.

Vá em Arquivo > Abrir Projeto.

Selecione a pasta clonada do repositório.

Configure o banco de dados:

Crie um banco de dados no MySQL com o nome leilao_db.

Execute o script SQL fornecido na pasta sql para criar as tabelas necessárias.

Atualize as configurações de conexão:

No arquivo src/util/ConnectionFactory.java, atualize as informações de conexão com o banco de dados (usuário, senha, URL) conforme sua configuração local.

Execute o projeto:

No NetBeans, clique com o botão direito no projeto e selecione Executar.

📂 Estrutura do Projeto
pgsql
Copiar
Editar
Leilao-Java/
├── src/
│   ├── model/
│   ├── view/
│   └── controller/
├── lib/
├── nbproject/
├── build.xml
└── README.md
👨‍💻 Autor
Gabriel Vidal Oliveira
LinkedIn: https://www.linkedin.com/in/gabriel-vidal-oliveira/

📄 Licença
Este projeto está licenciado sob a MIT License.
