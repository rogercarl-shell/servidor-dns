🧠 Projeto: Servidor DNS com BIND9 - Debian GNU/Linux
Este repositório faz parte do meu portfólio de infraestrutura Linux e contém a configuração de um servidor DNS autoritativo utilizando o BIND9 em um ambiente Debian.

O foco do projeto é demonstrar, na prática, como estruturar zonas de resolução direta e reversa, com arquivos devidamente organizados e comentados, simulando um ambiente funcional de rede local.

✅ Funcionalidades do projeto:
Instalação e ativação do serviço bind9

Criação da zona direta (meureino.local)

Criação da zona reversa (192.168.122.x)

Testes com:

ping para nomes locais

dig e host para verificar resolução direta e reversa

named-checkzone para validação das zonas

named-checkconf para validação da configuração geral

Imagem ilustrativa da topologia de rede e estrutura das zonas (DNS-BIND-REVERSO.png)

