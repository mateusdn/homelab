# HomeLab Setup

<a name="logo" href="https://www.artstation.com/matd2d"><img src="w-server.png" /></a>

Esses componentes formam a base sólida para a infraestrutura de rede, proporcionando gerenciamento centralizado, distribuição dinâmica de endereços IP, virtualização e resoluções eficientes.

* [Hyper-V](#Virtualização-com-Hyper-V)
* [Windows Server](#Instalação-e-Configuração-do-Windows-Server)
* Active Directory
*  DHCP
*  DNS

## Virtualização com Hyper-V:
* Você pode baixar o Hyper-V através do PowerShell com permissões administrativas usando o comando:
  
  * `Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V -All`
 
* Trocando o nome do servidor:
  * Meu Computador -> Propriedades -> Renomear este Computador -> Reinicie a máquina
  * print-
 
### Comutadores Virtuais (Virtual Switches):
* Eles permitem a comunicação entre maquinas virtuais e/ou com redes físicas, facilitando a criação e gerenciamento de redes virtuais em ambientes de virtualização.
  
* Tipos de Comutadores:
  
  * External Switch -
  * Internal Switch -
  * Private Switch - 

### Criando a Primeira Máquina Virtual

* ISO Windows Server 2022  -link.




## Instalação e Configuração do Windows Server:



## Configuração do Active Directory:

## Implantação do Serviço DHCP:
