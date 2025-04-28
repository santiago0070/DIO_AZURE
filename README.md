# DIO_AZURE
Aprendizado adequirido no curso da DIO_AZURE
INTRODUÇÃO
----------------------------------------------------------------------------------------------------------------------------------------
FASE 01
D01 
Como funciona o Azure Microsoft?
R:Serve como armazenamento na nuvem.

D02 Quais são as vantagens do Azure?
R: Paga somente pelo recurso usado e a escalabilidade destes recursos
são mais fáceis.

D03 
Em que ano foi fundado o Azure?
R: 1 de fevereiro de 2010

D04 
Entendendo as nomenclaturas do Azure:
R: Recursos - são ferramentas gerenciáveis  como: banco de dados em nuvem, máquinas virtuais, redes virtuais e armazenamento de contas.
R:Assinatura - funciona como um contêiner, parecido com dockeserver para criar os recursos (precisa pagar).
R:Conta do Azure - precisar cadastrar com gmail.com  ou hotmail.com, para configurar a modalidade da conta(estudante) ou (profissional).
R:Administrador da conta- é o responsável por criar e pagar os recursos da conta Azure.
R: Azure Active Directory(AD do Azure) - faz o controle de acesso aos recursos da nuvem.
R: Locatário do Azure AD - Ele vai vincular a sua conta do Azure ao e-mail que você cadastrou, se ele pertencer a um conta empresarial, o locatário será para a empresa. 
R: Diretório do AD do Azure - É o local onde a conta está vinculada; ex(uma empresa). Então para este diretório pode ter vários recursos vinculados a ele.
R: Grupos de recursos - antes de criar os recursos é necessário criar um grupo onde ficarão vinculados.
R: Grupos de gerenciamento: responsável por controlar e monitorar os acessos ou desempenho dos grupos de recursos.
R: Região - São  data centers que ficam como backup dos seus recursos, caso eles o servidor caia, outro servidor núvem próximo entra, caso precisem de alta disponibilidade.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
FASE 02  EXEMPLO DE ARQUITETURA SEM SERVIDOR
D01
Quais são as funcionalidades da arquitetura Azure?
R:App de função  - responsável por monitorar alterações nos recursos do azures.
R:Cosmos DB - funcionando com serviço de banco de dados em JSON  independente.
R: Armazenamento de Fila - em caso de erro em algum evento no recursos, ele salva em uma espécie de logs.
R:Azure Monitor - Monitora  o desempenho dos recursos e traz esta visualização em dashboard.
Fase 02 Infraestrutura de Nuvem

D01
 Quais os tipos de nuvem?
R: Pública - Utilizar o mesmo provedor(máquinas), porém em ambientes e acessos diferentes. Exemplo, duas empresas compartilham da mesma máquina, porém,  cada empresa utiliza VMs  diferentes.
R: Híbridas - pode se manter a parte de um recurso na rede interna(por segurança) e outros em rede pública para diminuir os custos.
R: Privada - a empresa contrata o provedor privado de nuvem que nenhuma outra empresa poderá acessar. Porém todas as responsabilidades com a segurança e infraestrutura ficará por conta da empresa.

D02
Quais diferenças entre infraestrutura ONPRISE, IAAS, PAAS, SAAS?
R: ONPRISE - Todos os recursos tanto de hardware, software, luz e segurança é da própria empresa.
R:IAAS - Configurar e administrar os recursos do SO, SOFTWARE e APP em nuvem;
Ex: Contratei uma VM com Windows 2012 server com o banco de dados, porém, tenho acesso às informações do SO e do Banco de dados.

R:Paas -Permite aos desenvolvedores criar, implantar e gerenciar aplicações sem se preocuparem com a infraestrutura subjacente.
Ex: Contratei um recurso de banco de dados ORACLE, neste caso não preciso me preocupar com o armazenamento, pois ficará na nuvem.

R:Saas - A empresa contrata um recurso 100% pronto, não configura nada e nem instalar como MICROSOFT 360.

—------------------------------------------------------------------------------------------------------------------------

FASE 03
INTERFACE DO AZURE
D01
Sempre que for criar um grupo de recurso devo:
R: Pesquisar pela nomenclaturas do azure, para criar um padrão.

