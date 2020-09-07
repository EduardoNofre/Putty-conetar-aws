# Usando o Putty no windows para acessar a sua maquina na AWS via SSH.

 ## Download e instalação. 
 
  1 - Faça o download do putty e do puttygen.
 
  2 - Instale o putty em sua maquina a instalação é bem simples.
 
 ## amazon AWS EC2
 
  3 - Vamos partir do principio que você ja tenha uma maquina na amazon (instancia) e gerado o arquivo .pem.
 
  4 - Faça o login na sua conta da amazon.
 
  5 - Vá ate a sua maquina(Instancia).
  
  6 - clique com o botão direito do mouse sobre a sua maquina(Instancia) e selecione a opção conectar.
  
  7 - Ao selecionar a opção conectar você será redirecionado para outra tela. Nesta tela selecione a aba cliente SSH.
  
  8 - Faça uma copia do DNS publica. Obs a dns public será utilizada no putty.  
  
  9 - Abra o puttygen.
  
  10 - Selecione a opção load.
  
  11 - Vá ate onde esteja o seu arquivo .pem.
  
  ![Alt text](https://support.cades.ornl.gov/user-documentation/_book/openstack/screenshots/birthright_ssh_puttygen.png)
  
  Observação: O que vc fez ate aqui é converter um arquivo pem para um .ppk que é o formato que o putty lê.
  
  12 - Salve a chave carregada clicando em Salvar chave privada.
  
  ![Alt text](https://support.cades.ornl.gov/user-documentation/_book/openstack/screenshots/birthright_ssh_puttygen_save.png)
  
  9 - Cole a DNS publica no campo do Putty chamado Host Name (or Ip address) 
  
  ![Alt text](https://imajineweb.com/wp-content/uploads/2019/07/access-phpmyadmin-using-ssh1.jpg)
  
  10 -    




