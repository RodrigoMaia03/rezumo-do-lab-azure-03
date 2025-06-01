# Laboratório 3 - Microsoft Azure 50 Anos - Configuração de Instância de Banco de Dados no Microsoft Azure

Este laboratório tem como objetivo praticar o processo de configuração de uma instância de Banco de Dados na plataforma Microsoft Azure. O entregável proposto é a criação de um repositório contendo resumos, anotações e dicas sobre o uso da Azure, servindo como material de apoio para estudos e futuras implementações.

O processo de criação de um banco de dados SQL na Plataforma Azure se dá por algumas etapas. Inicialmente, devemos procurar na aba lateral do ambiente Azure o campo _Banco de Dados SQL_ e acessá-lo. Em seguida, é necessário clicar em _Criar_ que será iniciado o procedimento de criação de um banco de dados relacional. Esse procedimento é descrito/realizado através das seguintes etapas: **Básico → Rede → Segurança → Configurações Adicionais → Rótulos → Revisar + Criar.**

## 1. Básico
Nesta seção inicial, especificamos informações fundamentais para a instância do banco de dados.

- Assinatura: Qual assinatura do Azure será utilizada para provisionar e cobrar o recurso (ex: "Pay-as-you-go").
- Grupo de Recursos: O grupo de recursos ao qual o banco de dados e seus componentes associados (como o servidor lógico) pertencerão. Isso ajuda na organização e gerenciamento.
- Nome do Banco de Dados: O nome exclusivo para o seu banco de dados.
- Servidor: Para muitos bancos de dados relacionais, é necessário criar ou selecionar um servidor lógico existente que hospedará o banco de dados. Isso inclui definir um nome de servidor, login de administrador e senha, e a região.
- Região: A localização geográfica do data center onde o banco de dados e o servidor serão hospedados.
- Origem dos Dados (opcional): Possibilidade de criar um banco de dados em branco, restaurar de um backup ou usar um banco de dados de exemplo.
