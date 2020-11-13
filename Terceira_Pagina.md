# AZ 900 - Resumo dos Estudos  
<img src="https://github.com/tbarcelar/Resumo-AZ900/blob/main/cloud.jpg" width="1200" height="250">




## O que é rede virtual do Azure

Redes virtuais do Azure permite que os recursos do Azure - como máquinas virtuais, aplicativos da Web e bancos de dados - se comuniquem entre si, com usuários na Internet e com seus computadores clientes locais. 
É  possivel criar várias redes virtuais isoladas. Ao configurar uma rede virtual, define um espaço de endereço de protocolo de Internet (IP) privado, usando intervalos de endereços IP públicos ou privados. 
Uma VM no Azure pode se conectar à Internet por padrão, definindo um endereço IP público ou um balanceador de carga público. Para gerenciamento de VM, pode se conectar por meio da interface de linha de comando do Azure (CLI), protocolo de área de trabalho remota (RDP) ou Secure Shell (SSH).pode usar o serviço de resolução de nomes integrado ao Azure ou configurar a rede virtual para usar um servidor DNS (Sistema de Nomes de Domínio) interno ou externo.


**VPN**
o computador cliente inicia uma conexão VPN criptografada com o Azure, conectando esse computador à rede virtual do Azure.
**VPN site to site**
 vincula dispositivo ou gateway VPN local ao gateway VPN do Azure em uma rede virtual. Na verdade, os dispositivos no Azure podem aparecer como estando na rede local. A conexão é criptografada e funciona pela Internet.
**VPN expressroute** 
serve para  ambientes em que precisa de mais largura de banda e níveis ainda mais altos de segurança,  fornece conectividade privada dedicada ao Azure que não viaja pela Internet. 
**O peering**
 permite que os recursos em cada rede virtual se comuniquem entre si. Essas redes virtuais podem estar em regiões separadas, permitindo que você crie uma rede global interconectada por meio do Azure.

 
 ## Link
  - Repository:https://docs.microsoft.com/pt-br/learn/certifications/exams/az-900
  - Dicionário: https://github.com/tbarcelar/Resumo-AZ900/blob/main/dicionario_dos_servicos.docx
  -  Teste do Resumo P1 e P2 :https://docs.google.com/forms/d/1jyGvla7uYX5ySZtTdu8_sgCxEFe_rB9bth7RwXVhAiw/edit