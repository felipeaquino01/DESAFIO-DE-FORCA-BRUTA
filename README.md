# DESAFIO-DE-FORCA-BRUTA
repositório para documentação do desafio de ataques de força bruta com Medusa e Kali Linux


##Ambiente e Ferramentas.
Kali Linux, Metasploitable2, VirtualBox

#Execução do Ataque

  ip a
   ( verificar o ip da maquina Metasploitabe2 )
<img width="720" height="400" alt="print 0" src="https://github.com/user-attachments/assets/dc56d7e0-58c0-4b06-add3-e80c5fee0481" />

nmap -sn 192.168.56.0/24
   ( verificar os ips da rede VirtualBox (Metasploitabe2) )
<img width="1920" height="954" alt="print 1" src="https://github.com/user-attachments/assets/6d208bb8-fc6c-4183-b75e-675bef2279e7" />

nmap 192.168.56.102
   ( verificar as portas abertas )
<img width="1920" height="954" alt="print 2" src="https://github.com/user-attachments/assets/af8bc1d1-c96f-42eb-b6b2-a7e418cd506e" />

medusa -h 192.168.56.102 -U users.txt -P pass.txt -M http -t 6
   ( fazer o ataque de força bruta )
<img width="1920" height="954" alt="print 3" src="https://github.com/user-attachments/assets/8c5ac836-a0a4-4a31-9ab7-65ce977e78f2" />

Testando o login e senha captrado pelo MEDUSA
<img width="1920" height="954" alt="print 4" src="https://github.com/user-attachments/assets/3fdf2d12-a238-4aa6-a08a-683d41a9884f" />

ATAQUE REALIZADO COM SUCESSO
<img width="1920" height="954" alt="print 5" src="https://github.com/user-attachments/assets/183a9174-e1dc-486e-9efd-808c3ceeb630" />
