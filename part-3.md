Part 3

-> **PT-BR**

### Tipos de serviços de nuvem na azure

- IaaS
- Paas
- Saas

- **Iaas (infraestrutura como serviço)**
    - O usuário tem uma atuação maior nas configurações do recurso criado.
    - Maior acesso no contexto de personalização do recurso.

- **Paas (plataforma como serviço)**
    - Engloba o Iaas
        - Servidores e armazemaneto
        - Firewalls/ segurança de rede
    - Além de:  
        - Sistema operacionais
        - Ferramentas para desenvolvedores
        - Análise de negócios de gerenciamento de database (banco de dados)

    - Fornece um ambiente para a criação, teste e a implementação de aplicativos de software, sem focar gerenciamento da infraestrutura subjacente.

- **SaaS (software como serviço)**
    - Exemplo de plataformas Saas (Teams e Office 365)
    - Conforme o modelo de licença, tendo opções de visualização e uso diferentes.
    - Os usuários se conectam e usam aplicativos com base em nuvem como serviço.
    - Menos responsabilidade de manutenção.


### Modelo de responsabilidade compartilhada

<img src="assets/shared-responsibility.svg" alt="Division of responsibility">

 ***Fonte: Microsoft***

- **Categorias que são responsabilidade do servidor (Microsoft)**
    - Hosts Físicos
    - Rede física
    - Datacenter Físico
    - O cliente não tem ação nesse cenário

- **Responsabilidades que podem ser dividas com o servidor**
    ***A responsabilidade varia conforme o tipo***
        - Infraestrutura de identidade e diretório
        - Aplicativos
        - Controles de rede
        - Sistema operacional (exceto para Iaas)

    ***Iaas***
        - Toda a responsabilidade permanece por parte do clinte
    
    ***Paas***
        - A responsabilidade é dividade entre o cliente e a Microsoft
    
    ***Saas***
        - A infraestrutura de identidade e diretório é único ponto onde ocorre a divisão de responsabilidade entre cliente e Microsoft (Cloud provider).


- **Responsabilidade é sempre retida pelo cliente**
    - Informações e dados
    - Dispositivos (moveis e PCs)
    - Contas e identidade de diretório
    - A responsabilidade para manutenção e monitoramente é total do cliente.


- **Comparação dos tipos de serviço na nuvem**

    ***Iaas***
        - Serviço de nuvem mais flexível
        - O cliente configura e administra o hardware utilizado pelo recurso.

    ***Paas***
        - Focado no desenvolvimento de aplicativos
        - Manutenção e gerencia do aplicativo/plataforma é feito pela Microsoft.

    ***Saas***
        - Modelo de preço de pagamento conforme o uso.
        - Menor controle e acesso.
        - Usuários pagam pelo software que utilizam através do modelo de assinatura.

-----------------------------------------------------------------------------------------------

-> **En**

### Cloud Service types on Azure

- Iaas
- Paas
- Saas

- **Iaas (Infrastructure as service)**
    - User can configuration on resource with out restriction.
    - Bigger access about personalite resource context.

- **Pass(plataform as service)**
    - Include all resources in Iaas
    - Firewall
    - Operating system
    - Business analystic for database manegeament.
    - Dedicated envirnoment for create, testing, and implementing apps without worrying about infrastructure.

- **Saas (sofware as service)**
    - Plataform Saas examples: Teams, and Office 365.
    - Depending on the type of license, there are different views and use.
    - The users can connect and use apps on the cloud as service.
    - Less responsibility for maintenance.

### Shared model responsibility

<img src="assets/shared-responsibility.svg" alt="Division of responsibility">

 ***Font: Microsoft***

- **Category that is the responsibility of microsoft server**
    - Phisical hosts 
    - Phisical datacenter
    - Phisical WAN
    - Client has no action in this envirnoment

- **Responsabilities that can be shared with the server** 

    ***The responsibility can vary based on type***
        - Identity infraestructure and directory.
        - Apps
        - Wan controls.
        - Operating system (except for Iaas)

    ***Iaas***
        - All responsibility remains with the client.

    ***Paas***
        - The responability is shared with the client.
    
    ***Saas***
        - Indetity and directory infraestructure are the unique points where responsibility is divided between cliente and Microsft (Cloud provider).

- **Responsabilities of clients**
    - Data and information
    - Devices (smartphones and computers)
    - Accounts and directory identity
    - Maintenance and monitoring responsibility is entirely on the client.

- **Comparation about cloud services types**
    
    ***Iaas***
        - Most flexible cloud service.
        - Client can configure and manage hardware resource.

    ***Paas***
        - Focus on app development.
        - Maintenance and management are done by Microsoft.

    ***Saas***
        - Pay-as-you-use model.
        - Less control and access.
        - User can only use what the pay for, following the license model.


-----------------------------------------------------------------------------------------------
