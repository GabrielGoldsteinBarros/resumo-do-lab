# resumo-do-lab
Assunto do modulo é nuvem.
Existem ferramentas diferentes na nuvem, como estou fazendo um curso de full-stack é importante que eu tenha uma noção sobre essa ferramenta

Desafio - criando maquinas virtuais na azure
o SLA garante que a Microsoft forneça um nível específico de serviço e desempenho para os recursos e serviços hospedados no Azure, e estabelece as consequências caso esses níveis não sejam atingidos
Criar uma máquina virtual no Microsoft Azure é como alugar um computador no mundo digital. Aqui está uma descrição simplificada:

Escolha o Sistema Operacional: Decida se você quer usar Windows, Linux ou outro sistema operacional.

Selecione o Tamanho: Escolha a quantidade de CPU, memória e espaço em disco que você precisa.

Configurações Básicas: Forneça um nome para sua máquina virtual, escolha a região onde ela estará localizada e configure as opções de rede.

Configurar Segurança: Defina regras de acesso e configure senhas ou chaves de acesso SSH para proteger a máquina.

Revisar e Criar: Verifique todas as suas configurações e clique em criar. Azure vai provisionar a máquina virtual para você em minutos.

A partir daí, você pode acessar a máquina virtual como se fosse um computador físico, instalar aplicativos, armazenar dados e muito mais.

Desafio - Configurando uma instancia de Banco de dados na Azure
  Vamos explorar os conceitos de IaaS, PaaS e SaaS no contexto do Microsoft Azure:
IaaS (Infrastructure as a Service):

O que é: Fornece recursos de infraestrutura, como servidores, armazenamento e redes, em um modelo de pagamento por uso.
Exemplo no Azure: Máquinas Virtuais. Você aluga a infraestrutura e tem controle total sobre o sistema operacional e as aplicações que deseja executar.

PaaS (Platform as a Service):
O que é: Fornece uma plataforma que permite aos desenvolvedores criar, testar e gerenciar aplicativos sem se preocupar com a infraestrutura subjacente.
Exemplo no Azure: Azure App Service. Você pode desenvolver e implantar aplicativos rapidamente, enquanto o Azure cuida do gerenciamento do servidor e da escalabilidade.

SaaS (Software as a Service):
O que é: Fornece acesso a aplicações prontas para uso, hospedadas na nuvem e acessíveis pela internet. Não há necessidade de instalação ou manutenção de software.
Exemplo no Azure: Microsoft Office 365. Os usuários acessam aplicativos como Word e Excel diretamente do navegador, sem precisar se preocupar com atualizações ou infraestrutura.

Configurar uma instância de banco de dados no Microsoft Azure é um processo simplificado que envolve alguns passos básicos:

Acessar o Portal do Azure:
  Faça login no Portal do Azure.

Criar um Banco de Dados:
  Navegue até Serviços de Banco de Dados (Database Services) e escolha o tipo de banco de dados que você deseja criar (por exemplo, SQL Database, MySQL, PostgreSQL).

Configurar a Instância:
  Defina o nome do banco de dados.
  Escolha uma assinatura e grupo de recursos.
  Selecione a localização (região) onde o banco de dados será hospedado.

Configurar o Servidor:
  Crie um servidor novo ou selecione um existente.
  Configure o nível de performance (basic, standard, premium, etc.), que determinará a capacidade de processamento e o armazenamento.

Autenticação e Segurança:
  Defina usuário e senha para o administrador do banco de dados.
  Configure as regras de firewall para permitir acesso ao banco de dados.

Revisar e Criar:
  Revise todas as configurações e clique em Criar. Azure iniciará a configuração da instância.

Conectar ao Banco de Dados:
  Após a criação, você pode usar strings de conexão fornecidas no portal para conectar sua aplicação ao banco de dados.
