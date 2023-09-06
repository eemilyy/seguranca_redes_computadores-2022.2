# Como preparar-se para uma festa de assinatura de chaves GPG

Uma festa de assinatura de chaves GPG, também conhecida como "Key Signing Party" em inglês, é um evento organizado por membros da comunidade de segurança de informações, desenvolvedores de software ou entusiastas de criptografia para verificar e assinar as chaves públicas usadas no sistema de criptografia GPG (GNU Privacy Guard) ou PGP (Pretty Good Privacy). O objetivo principal de uma festa de assinatura de chaves é estabelecer uma rede de confiança entre os usuários, permitindo que eles confirmem a autenticidade das chaves públicas uns dos outros.

## Como criar uma chave GPG

Primeiro, é preciso instalar a ferramenta [gpg4win](https://www.gpg4win.org/). Realize a instalação e crie seu usuário selecionando o seu nome e um email.

Ao criar o usuário, importe sua chave publica e em seguida insira a chave em um servidor de chaves, como por exemplo [pgp.mit.edu](http://pgp.mit.edu/)

## Revogar chave

Para revogar a chave, dentro da própria plataforma, deve-se revogar o certificado da chave, em seguida importe sua chave publica novamente e submeta sua nova chave no servidor. Uma mensagem de chave atualizada deve ser mostrada.

 

# Exercício

Após a criação da chave GPG, deve-se submeter a chave em um servidor e em seguida compartilhar o link.

**Link da chave revogada:** 

- [https://keyserver.ubuntu.com/pks/lookup?search=EmilySouza&fingerprint=on&op=index](https://keyserver.ubuntu.com/pks/lookup?search=EmilySouza&fingerprint=on&op=index)
- [http://pgp.mit.edu/pks/lookup?search=EmilySouza&op=index&fingerprint=on](http://pgp.mit.edu/pks/lookup?search=EmilySouza&op=index&fingerprint=on)