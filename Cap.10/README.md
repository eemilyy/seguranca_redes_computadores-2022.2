# Como preparar-se para uma festa de assinatura de chaves GPG

O PGP (Pretty Good Privacy ou Privacidade Muito Boa) é um sistema de criptografia assimétrica e assinatura digital, desenvolvido em 1991 por Philip Zimmermann. No início, o PGP possuia restrições quanto ao uso. Assim sendo, o [Projeto GNU](http://www.gnu.org/) desenvolveu o GnuPG (GNU Privacy Guard), também conhecido como GPG, que é totalmente compatível com o PGP.

## Como criar uma chave GPG

Primeiro, é preciso instalar a ferramenta [pgp4win](https://www.gpg4win.org/). Realize a instalação e crie seu usuário selecionando o seu nome e um email.

Ao criar o usuário, importe sua chave publica e em seguida insira a chave em um servidor de chaves, como por exemplo [pgp.mit.edu](http://pgp.mit.edu/)

## Revogar chave

Para revogar a chave, dentro da própria plataforma, deve-se revogar o certificado da chave, em seguida importe sua chave publica novamente e submeta sua nova chave no servidor. Uma mensagem de chave atualizada deve ser mostrada.

 

# Exercício

Após a criação da chave PGP, deve-se submeter a chave em um servidor e em seguida compartilhar o link.

**Link da chave revogada:** 

- [https://keyserver.ubuntu.com/pks/lookup?search=EmilySouza&fingerprint=on&op=index](https://keyserver.ubuntu.com/pks/lookup?search=EmilySouza&fingerprint=on&op=index)
- [http://pgp.mit.edu/pks/lookup?search=EmilySouza&op=index&fingerprint=on](http://pgp.mit.edu/pks/lookup?search=EmilySouza&op=index&fingerprint=on)