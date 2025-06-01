# Laboratório 3 - Microsoft Azure 50 Anos - Configuração de Instância de Banco de Dados no Microsoft Azure

Este laboratório tem como objetivo praticar o processo de configuração de uma instância de Banco de Dados na plataforma Microsoft Azure. O entregável proposto é a criação de um repositório contendo resumos, anotações e dicas sobre o uso da Azure, servindo como material de apoio para estudos e futuras implementações.

O processo de criação de um banco de dados SQL na Plataforma Azure se dá por algumas etapas. Inicialmente, devemos procurar na aba lateral do ambiente Azure o campo _Banco de Dados SQL_ e acessá-lo. Em seguida, é necessário clicar em _Criar_ que será iniciado o procedimento de criação de um banco de dados relacional. Esse procedimento é descrito/realizado através das seguintes etapas: **Básico → Rede → Segurança → Configurações Adicionais → Rótulos → Revisar + Criar.**

## 1. Básico
Nesta seção inicial, especificamos informações fundamentais e de desempenho para a instância do banco de dados SQL.

### Detalhes do Projeto:
- Assinatura: Qual assinatura do Azure será utilizada para provisionar e cobrar o recurso (ex: "Pay-as-you-go").
- Grupo de Recursos: O grupo de recursos ao qual o banco de dados e seus componentes associados (como o servidor lógico) pertencerão.
### Detalhes do Banco de Dados:
- Nome do Banco de Dados: O nome exclusivo para o seu banco de dados.
- Servidor: É necessário criar um novo servidor lógico SQL ou selecionar um existente que hospedará o banco de dados. A criação de um novo servidor inclui definir um nome de servidor globalmente exclusivo, login de administrador e senha, e a região.
- Deseja usar o pool elástico SQL? Opção para usar um pool elástico para compartilhar recursos entre múltiplos bancos de dados.
- Ambiente de carga de trabalho (opcional): Pode-se especificar se o ambiente é de Desenvolvimento ou Produção, o que pode influenciar recomendações.
### Computação + armazenamento:
- Configurar banco de dados (Nível de Serviço): Escolha do modelo de compra (ex: vCore ou DTU), o nível de serviço (ex: Fins Gerais, Comercialmente Crítico, Hyperscale, Básico, Standard, Premium), e a configuração de hardware (número de vCores, quantidade de memória). Esta escolha impacta diretamente o desempenho, funcionalidades disponíveis e o custo.
- Tamanho máximo dos dados: Define o limite de armazenamento para o banco de dados.
- Redundância de armazenamento de backup: Opções para redundância do armazenamento dos backups (ex: localmente redundante, com redundância geográfica).
