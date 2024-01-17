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

### Criando e Configurando a Primeira Máquina Virtual

* ISO Windows Server 2022  -link.

* print-nov-vm

* Após criar uma máquina virtual no Hyper-V, você ainda pode ajustar várias configurações para atender às suas necessidades:
  
  * Processador: Ajustar o número de processadores virtuais alocados à VM.
  * Memória: Modificar a quantidade de RAM atribuída à VM.
  * Dispositivos de Inicialização: Alterar a ordem de inicialização e selecionar discos virtuais ou outros dispositivos.
  * Rede: Modificar a configuração de rede associada à VM, como trocar o switch virtual ao qual a VM está conectada.
  * Armazenamento: Adicionar, remover ou modificar discos virtuais, além de ajustar configurações avançadas, como snapshots.
  * Integração com Serviços: Habilitar ou desabilitar a integração com serviços, como a integração do sistema operacional convidado, cópia e cola, e redirecionamento de área de transferência.
  * Configurações de Segurança: Modificar configurações de segurança, como habilitar ou desabilitar o "Secure Boot" ou configurar políticas de máquinas virtuais protegidas.
  * Geração da Máquina Virtual: Em algumas versões do Hyper-V, você pode converter uma VM de uma geração para outra.
 

* print-tela-config.

* 

## Instalação e Configuração do Windows Server:

### Instalando o Windows Server
*print-

passo a passo

### Configurando o Windows Server

## Configuração do Active Directory:

## Implantação do Serviço DHCP:
