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
   * <img src="p-nome.png" />
 
### Comutadores Virtuais (Virtual Switches):
* Eles permitem a comunicação entre maquinas virtuais e/ou com redes físicas, facilitando a criação e gerenciamento de redes virtuais em ambientes de virtualização.
  
* Tipos de Comutadores:
  
  * External Switch - permite que máquinas virtuais se comuniquem com redes físicas e outros dispositivos fora do ambiente virtual.
  * Internal Switch - é utilizado para comunicação exclusiva entre máquinas virtuais em um host específico, mas não têm acesso direto à rede física externa.
  * Private Switch - é semelhante ao interno, mas não permite qualquer comunicação com a rede física externa. Ele cria uma rede isolada apenas para as VMs no host.

### Criando e Configurando a Primeira Máquina Virtual

*  [ISO Windows Server](https://www.microsoft.com/en-us/software-download/windowsinsiderpreviewserver?wa=wsignin1.0)

* <img src="p-vm.png" />

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
