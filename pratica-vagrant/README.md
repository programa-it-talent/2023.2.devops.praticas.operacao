Nesta aula, aprenderemos como criar ambientes de desenvolvimento utilizando o Vagrant. Para isso, usaremos principalmente o seguinte tutorial como guia, mas você também tem a liberdade de consultar outros materiais:

1- Instale o Vagrant

Install | Vagrant | HashiCorp Developer


2- Instale o python

Download Python | Python.org

3- Depois de instalar o python instalar o pacote python core win32 api
 3.1 - Abra o CMD do Windows e digite: py -m pip install pywin32
 3.2 - Abra Terminal do Linux e digite: pip install pywin32

4- Instale o Virtual Box

Oracle VM VirtualBox

5- Crie uma conta no site do Vagrant para ter acesso aos boxes de images
My Vagrant Boxes - Vagrant Cloud (vagrantup.com)

6- Depois de Criar a conta acesse seu perfil, vá na aba de segurança, coloque uma descrição qualquer para o token, gera um token e guarde o valor dele.



Imagine um time de desenvolvimento no qual cada novo engenheiro que se integra à equipe precisa baixar as principais ferramentas adotadas pelo time em sua própria máquina, em alguns casos em versões específicas. Para atender a essa necessidade, o time de DevOps elabora um arquivo "Vagrantfile", o qual é disponibilizado em um repositório compartilhado. Os desenvolvedores têm a opção de utilizar uma máquina virtual com todos os softwares já instalados, permitindo assim uma integração rápida à equipe, além de facilitar o desenvolvimento em ambientes que se assemelham o máximo possível aos ambientes de produção.


Atividades para praticar/treinar:

1 - Siga os passos do tutorial para realizar a instalação do Vagrant. Inicie uma máquina utilizando-o e acesse-a por meio do comando "vagrant ssh". Depois de acessar a máquina pode destruí-la

2 - Utilizando o mesmo Vagrant Box, inicie a máquina virtual com os pacotes do NGINX ou do Apache instalados. Configure um redirecionamento de porta (forward port) entre a máquina hospedeira e a máquina virtual (guest) na porta 8080 para a porta 80. Tente acessar o site padrão a partir do navegador usando o endereço apropriado. Depois de acessar a máquina pode destruí-la

Desafio

Utilizando o que aprendemos na aula desenvolva um VagrantFile que atenda as seguintes características: 


Instalar os pacotes: Apache ou Nginx, htop, Docker, nano, python3.
Realizar redirecionamento da porta 80 da máquina virtual para a porta 8080 da máquina física.
criar um de compartilhamento de arquivos entre a máquina local e a virtual.
Subir 2 interfaces de rede com IP’s de redes diferentes.


No final, se tudo estiver funcionando, crie um repositório no seu GitHub e suba o arquivo VagrantFile. O link do repositório deverá ser enviado no Google ClassRoom, para receberem a confirmação da atividade. 
