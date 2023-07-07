### SEGURANÇA DE REDES DE COMPUTADORES | 2022.2
Emily Souza de Almeida Santos

1. O que é a arquitetura de segurança OSI?

Arquitetura de padrão internacional, fornecedores de computadores e de comunicação podem estabelecer seus próprios modelos, implementando medidas de segurança em seus produtos e serviços, desde que estejam em conformidade com essa definição estruturada de serviços e mecanismos.
De acordo com o autor, a arquitetura de segurança OSI oferece uma visão geral útil, abstrata, de muitos dos conceitos de que este livro trata, focalizando em “ataque à segurança, mecanismo de segurança e serviço de segurança”.

2. Qual é a diferença entre ameaças à segurança passivas e ativas?

Em resumo, um ataque passivo tenta descobrir ou utilizar informações do sistema, mas não afeta os seus recursos, enquanto um ataque ativo tenta alterar recursos do sistema ou afetar sua operação.
Os ataques passivos estão na natureza de bisbilhotar ou monitorar transmissões. O objetivo é obter informações que estão sendo transmitidas.
Ataques ativos envolvem alguma modificação do fluxo de dados ou a criação de um fluxo falso.

3. Liste e defina resumidamente as categorias de ataques passivos e ativos à segurança.

	Em um ataque passivo, existem 2 categorias: 
O vazamento de conteúdo de mensagens, mensagens essas que podem ser uma conversa telefônica, uma mensagem de correio eletrônico e um arquivo transferido, que contém informações sensíveis ou confidenciais e que não podem ser descobertas por terceiros não envolvidos.
A análise de tráfego, consiste em terceiros conseguirem acesso às mensagens ou conteúdo sensível, mesmo que encriptografadas, pudessem compreender o que está sendo transmitido.
	Em um ataque ativo, existem 4 categorias:
O disfarce ocorre quando uma entidade finge ser outra diferente.
Repasse é obtenção de uma unidade de dados, como um pacote de rede, sem modificar seu conteúdo ou interferir na sua transmissão com o objetivo de causar um efeito não autorizado ou indesejado.
Modificação de mensagens significa que alguma parte de uma mensagem é alterada, ou que as mensagens são adiadas ou reordenadas, para produzir um efeito não autorizado.
Negação do serviço objetivo principal é tornar a comunicação indisponível para usuários legítimos, negando-lhes o acesso ou a utilização normal. Esse tipo de ataque busca sobrecarregar os recursos do sistema alvo, impedindo que ele funcione corretamente ou fique inacessível.

4. Liste e defina resumidamente as categorias dos serviços de segurança.

Autenticação é a certeza de que a entidade se comunicando é aquela que ela afirma ser.
Controle de acesso é a capacidade de limitar e prevenir o acesso não autorizado de um recurso, e para conseguir acesso, ele precisa primeiro ser autenticado ou identificado para que os direitos de acessos possam ser ajustados ao indivíduo. 
Confidencialidade dos Dados é a proteção dos dados transmitidos contra ataques passivos, ou seja, divulgação não autorizada dos dados.
Integridade de Dados é a certeza de que os dados recebidos são exatamente as mesmas enviadas por uma entidade autorizada, não contendo modificação, inserção ou exclusão.
Irretratabilidade é a  proteção total do fluxo, impedindo que o emissor ou o receptor neguem uma mensagem transmitida.Assim, quando uma mensagem é enviada, o receptor pode provar que o emissor alegado de fato a transmitiu.

5. Liste e defina resumidamente as categorias dos mecanismos de segurança.

	Mecanismos De Segurança Específicos
Codificação: refere-se à aplicação de algoritmos matemáticos para transformar os dados em um formato que não seja facilmente compreensível. A recuperação dos dados transformados requer o uso de um algoritmo e, possivelmente, uma ou mais chaves de criptografia.
Assinatura digital: diz respeito aos dados anexados a uma unidade de dados ou uma transformação criptográfica dessa unidade, que permite ao destinatário comprovar a origem e a integridade dos dados, além de protegê-los contra falsificação pelo destinatário.
Controle de acesso: abrange uma série de mecanismos que são usados para impor direitos de acesso aos recursos. Esses mecanismos determinam quais usuários ou entidades têm permissão para acessar determinados recursos.
Integridade dos dados: engloba um conjunto de mecanismos utilizados para garantir a integridade de uma unidade de dados específica ou de um fluxo contínuo de unidades de dados.
Troca de autenticação: refere-se a um mecanismo projetado para garantir a identidade de uma entidade por meio da troca de informações. Esse mecanismo ajuda a verificar se uma entidade é realmente quem afirma ser.
Preenchimento de tráfego: consiste na inserção de bits em lacunas de um fluxo de dados, com o objetivo de dificultar a análise do tráfego por terceiros.
Controle de roteamento: permite a seleção de rotas específicas que sejam fisicamente seguras para determinados dados e alterações de roteamento, especialmente quando há suspeita de uma violação de segurança.
Notarização: envolve o uso de um terceiro confiável para garantir certas propriedades de uma troca de dados, como a autenticidade ou a integridade dos dados transmitidos.
	Mecanismos De Segurança Difusos
Funcionalidade confiada: refere-se ao que é considerado como correto com base em critérios estabelecidos, como uma política de segurança. É aquilo que se espera que atenda a determinadas condições de segurança.
Rótulo de segurança: é a marcação associada a um recurso, que pode ser uma unidade de dados, e que identifica ou descreve os atributos de segurança desse recurso.
Detecção de evento: consiste na identificação de eventos relevantes para a segurança. É o processo de reconhecer e registrar eventos que possam ter impacto na segurança de um sistema ou ambiente.
Trilha de auditoria de segurança: trata-se dos dados coletados e potencialmente utilizados para auxiliar uma auditoria de segurança. Essa auditoria envolve uma revisão e análise independente dos registros e das atividades do sistema, com o objetivo de avaliar a conformidade e a efetividade das medidas de segurança implementadas.
Recuperação de segurança: refere-se às ações tomadas para lidar com solicitações de mecanismos, como funções de tratamento e gerenciamento de eventos, visando à recuperação de uma situação de segurança. É o processo de restauração da segurança após um incidente ou uma violação.

6. Considere um caixa eletrônico, ATM no qual os usuários fornecem um cartão e um número de identificação pessoal (senha). Dê exemplos de requisitos de confidencialidade, integridade disponibilidade associados com esse sistema e, em cada caso, indique o grau de importância desses requisitos.

Confiabilidade
Senha: Não pode ser divulgada para outras pessoas
Importância: O requisito de confidencialidade é extremamente importante, pois a divulgação dessas informações pode levar a acessos não autorizados às contas bancárias e a possíveis fraudes.
Integridade
Transferência de valores: O valor que foi transferido não pode ser alterado, permitindo com que ele chegue ao seu destino final da forma como foi programado.
Importância: A integridade é crucial para garantir a confiança nas transações e nos registros financeiros.
Disponibilidade
Saldo da conta: O saldo da conta do cliente deve estar disponível para que ele possa consultar e realizar ações quando necessário.
Importância: Um sistema com interrupção prolongada pode causar inconveniência e afetar negativamente a confiança dos usuários.

7. Para responder as letras abaixo, por favor, consulte o livro-texto da disciplina:

(a) Desenhe uma matriz similar ao Quadro 1.4 que mostre o relacionamento entre serviços de segurança e ataques.

Para cada serviço da matriz, a sua relação se da por meio do que o ataque impacta no serviço de segurança

| |**Vazamento de conteúdo de mensagens**|**Análise de tráfego**|**Disfarce**|**Repasse**|**Modificação de mensagens**|**Negação do serviço**|
|-|-|-|-|-|-|-|
|**Autenticação**|||x|||
|**Controle de Acesso**||x|x|||
|**Confiabilidade dos dados**|x||x||||
|**Integridade de dados**||||x|x||
|**Irretratabilidade**||||||x|

(b) Desenhe uma matriz similar ao Quadro 1.4 que mostre o relacionamento entre mecanismos de segurança e ataques.
| |**Vazamento de conteúdo de mensagens**|**Análise de tráfego**|**Disfarce**|**Repasse**|**Modificação de mensagens**|**Negação do serviço**|
|-|-|-|-|-|-|-|
|**Codificação**|x|x||||
|**assinatura digital**|||x|||
|**Controle de acesso**|x|x||||x|
|**integridade de dados**|||||x||
|**Troca de autenticação**|||x||||
|**preenchimento de tráfego**||x|||||
|**Controle de roteamento**||x|||||
|**Notarização**|||x|x|||