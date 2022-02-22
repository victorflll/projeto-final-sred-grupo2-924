# Projeto final de Infraestrutura e Serviços de Redes
Projeto final da disciplina de Infraestrutura e Serviços de Redes - Grupo 2 - Turma 924 - IFAL Campus Arapiraca.

## Equipe:
Aluno 1: EMANUEL CEZAR DE MELO <br/>
Aluno 2: EMANUELLY VITÓRIA DA SILVA SANTOS <br/>
Aluno 3: LARYSSA MARIA DOS SANTOS <br/>
Aluno 4: VICTOR LUAN DE LIMA LEMOS <br/>

## Definições de rede

* Tabela com as defições de ips e de domínio


```
----------------------------------------------------------------------------
|                Configurações das interfaces de rede                       |
----------------------------------------------------------------------------
| ip da subrede   |     10.9.24.0/24          |       192.168.24.8/29       |
----------------------------------------------------------------------------
| ip de broadcast |     10.9.24.255/24        |       192.168.24.15/29      |
----------------------------------------------------------------------------
| ip do gw        |ens160      |              |ens192     | 192.168.24.9/29 | 
| ip do samba     |ens160      |              |ens192     | 192.168.24.10/29|  
| ip do ns1       |ens160      | 10.9.24.123  |ens192     | 192.168.24.11/29| 
| ip do ns2       |ens160      | 10.9.24.112  |ens192     | 192.168.24.12/29| 
| ip do WEB       |ens160      |              |ens192     | 192.168.24.13/29|
| ip do BD        |ens160      |              |ens192     | 192.168.24.14/29|         
-----------------------------------------------------------------------------

-----------------------------------------------------------------------------
|  Definição de nomes e domínio (<grupoX>.<turma9yz>.ifalara.local.)         |
-----------------------------------------------------------------------------
| vm         |domínio (zona)| grupo2.turma924.ifalara.local.                 |
-----------------------------------------------------------------------------
| aluno      |FQDN do gw       | gw.grupo2.turma924.ifalara.local.           |
| aluno      |FQDN do samba    | smb.grupo2.turma924.ifalara.local.          |  
| aluno 23   |FQDN do ns1      | ns1.grupo2.turma924.ifalara.local.          |
| aluno 12   |FQDN do ns2      | ns2.grupo2.turma924.ifalara.local.          |
| aluno      |FQDN do web      | web.grupo2.turma924.ifalara.local.          |
| aluno      |FQDN do bd       | bd.grupo2.turma924.ifalara.local.           |
-----------------------------------------------------------------------------
 

```      
