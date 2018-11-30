<img src="https://i.imgur.com/2dM8xDC.png" />


# GCIV Custom Server

Bem vindo à página do GCIV Custom Server, um servidor para Grand Chase versão Eternal. Esse servidor sempre será uma versão experimental de codar funções do jogo. E acredito que alguém tentará trabalhar nesses arquivos ao invés de ficar esperando por releases.

# O que funciona?

É possivel logar, comprar itens na loja e jogar PVP no momento.

# Como compilar?

Projeto criado com o Delphi XE7, porém pode ser compilado com qualquer versão mais recente.

# Links:
Database: https://pastebin.com/uQ4KDAx9/ 
Arquivos Necessários: https://www.sendspace.com/file/kz93eh/

# GCDLL Lib

GCDLL Anexada ao tópico.

# GCDLL Informações:

* _Encrypt = Deve receber o packet totalmente montado e irá retormar o packet pré pronto para envio, faltando apenas a size.
* _Decrypt = Deve receber o packet do jeito que é recebido pelo cliente.
* _GenerateIV = Recebe apenas o IV e o tipo de IV a ser criado e retorna o IV completo.
* _ClearPacket Deve receber o packet após ter passado pela rotina _Encrypt e irá retornar o packet pronto para envio.
