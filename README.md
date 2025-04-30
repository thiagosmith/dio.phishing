# Desafio DIO - Criando um Phishing para capturar senhas de login do facebook.

#Phishing para captura de senhas do Facebook
Ferramentas
- Kali Linux
- setoolkit

# Configurando o Phishing no Kali Linux
- Acesso root: sudo su
- Iniciando o setoolkit: setoolkit
- Tipo de ataque: Social-Engineering Attacks
- Vetor de ataque: Web Site Attack Vectors
- Método de ataque: Credential Harvester Attack Method 
- Método de ataque: Site Cloner
- Obtendo o endereço da máquina: $ ip -br a
- URL para clone: http://www.facebook.com

# Resutados:
- Acesso root: sudo su
![RCE](./img/01.png)

- Iniciando o setoolkit: setoolkit
![RCE](./img/02.png)
![RCE](./img/03.png)
![RCE](./img/04.png)
  
- Tipo de ataque: Social-Engineering Attacks
![RCE](./img/05.png)
![RCE](./img/06.png)

- Vetor de ataque: Web Site Attack Vectors
![RCE](./img/07.png)
  
- Método de ataque: Credential Harvester Attack Method
![RCE](./img/08.png)
  
- Método de ataque: Site Cloner
![RCE](./img/09.png)
  
- Obtendo o endereço da máquina: $ ip -br a
![RCE](./img/10.png)
![RCE](./img/11.png)
  
- URL para clone: http://www.facebook.com
![RCE](./img/12.png)
![RCE](./img/13.png)
![RCE](./img/14.png)

-Acessando a página clonada: http://192.168.2.127/
![RCE](./img/15.png)

-Inserindo credenciais: usuario@face.com / senhasecreta123
![RCE](./img/15.png)

- Senhas Capturadas: http://www.facebook.com
![RCE](./img/14.png)

