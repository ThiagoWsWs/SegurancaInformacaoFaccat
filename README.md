# Segurança Informação Faccat
Dentro deste repositorio tem todos os trabalhos desenvolvidos e anotações referentes a disciplina de Segurança da Informação.

# O que é Segurança da Informação

- É um conjunto de praticas que tem como objetivo impedir que os dados de uma empresa caiam nas mãos de pessoas não autorizadas...

# Importância de Investir em Segurança da Informação

- A empresa lida com grandes volumes de informações diariamente, não apenas organizacionais mas também de clientes, acionistas e *stakeholder* (mais informações abaixo). Em determinado momento a empresa sofre em ataque hacker e os todas essas informações são afetadas, além de prejudicar os envolvidos a empresa ainda perde credibilidade por não garantir a segurança das informações de seus meios...

(STAKEHOLDERS) -> são partes interessadas em uma organização, projeto ou iniciativa que têm influência direta ou indireta sobre ela, ou que são afetadas por suas ações e decisões.
Eles podem incluir indivíduos, grupos, comunidades, instituições ou qualquer entidade que tenha um interesse legítimo no que uma empresa ou projeto realiza.

# Pilares da Segurança Cibernetica

CID - Triade dos pilares...

- Confidencialidade -> de dados e privacidade.
- Integridade -> de dados e de sistemas.
- Disponibilidade -> Tem que estar disponivel quando usuario precisar...

Ativos = (hardware, software, firmware, informações/dados e telecomunicações)

Registros de incidentes envolvendo a segurança de dados no Brasil
https://stats.cert.br/incidentes/

# Confidencialidade
- Preserva restrições autorizadas ao acesso e revelação de informações, incluindo meios para proteger a privacidade pessoal e as informações proprietárias.
- A perda de confidencialidade consiste na revelação não autorizada de informações.
- *Relativa a Dados*: Tem como propósito garantir que informações privadas ou confidenciais não fiquem disponíveis nem sejam reveladas a indivíduos não autorizados.
- *Relativa a privacidade*: Garante controlar ou influenciar quais informações podem ser coletadas e armazenadas, e por quem e para quem tais informações podem ser reveladas.

A *Confidencialidade* está atrelado a privacidade das informações. Ou seja, a garantia de que os dados da empresa não estarão disponíveis nem serão divulgados a indivíduos sem autorização.

Para garantir a confidencialidade, a sua empresa precisa adortar medidadas preventivas, por exemplo, definir o acesso as informações somente para pessoas autorizadas. Também conscientizar toda a equipe para não violar as regras de segurança, e proteger os computadores contra ciberataques, vírus e espionagem...

### Principais ataques que prejudicam a Confidencialidade

  * *Phishin* - Ataques que enganam usuarios por meio de e-mails ou sites falsos para obter credeciais como senhas e dados pessoais.

  * *Eavesdropping* (escuta) - Interceptação não autorizada de comunicações em rede, permitindo que atacantes aacessem informações em trânsito.

  * *Man in the Middle(MITM)* - O atacante insere entre duas partes de uma comunicação, monitorando ou alterando os dados trocados sem que os envolvidos percebam.

  * *Pass the hash* - Técnica que o criminoso utiliza um hash de senha (em vez da senha real) para se autenticar em sistemas, obtendo acesso sem precisar decifar a senha.

  * *Spyware* - Software malicioso que coleta informações pessoais, como senhas e dados de navegação, sem o conhecimento do usuário.

  * *Fator Humano* - Ações inadvertidas de coloboradores, como clicar em links maliciosos ou compartilhar credenciais que expoem dados confidenciais.

Esses ataques exploram falhas técnicas ou comportamentais para violar o sigilo de informações. A proteção envolve criptografia, politicas de segurança robustas, treinamentos continuos e o uso de ferramentas como firewall, antivirus e VPN.

# Integridade
- Garante que informações não sejam eliminadas ou modificadas de forma imprópria
- Garante a autenticidade da informações, tanto para *dados* quanto para *sistemas*

A *integridade* garante a veracidade da informação durante todo seu ciclo de vida. O princípio básico é que informações parmaneçam imutáveis quando estão em repouso ou durante sua transmissão...

 ### Principais ataques que prejudicam a Integridade

 * *Ataques de Falsificação (Spoofing)* - O invasor se passa por um sistema ou usuário legítimo para alterar ou transmitir dados falsos, comprometendo a autenticidade da informação.

 *  *Envenenamento de dados (data poisoning)* - Em sistemas de aprendizado de máquina, invasores introduzem dados maliciosos em conjuntos de treinamento fazendo com que os modelos aprendam padrões errados, criem *backdoors* ocultos ou produzam resultados com viés.

 *  *Ataques de negação de serviço(DoS/DDoS)* - Embora principalmente afetem a disponibilidade, esses ataques podem também impactar a integridade ao sobrecarregar sistemas e causar falhas que levam à corrupção de dados durante o processamento.

 *  *Modificação de Dados* - O atacante altera informações sem autorização, como registros financeiros, dados de saúde ou arquivos críticos, comprometando a confiabilidade da informação.

Quando armazenada sem um local seguro o atacante poderia modificar a informação sem o conhecimento do proprietario. 

# Disponibilidade
- Sistemas devem funcionar prontamente quando necessários por usuarios autorizados
- Tanto o acesso quanto a utilização das informações precisa ser confiável e realizado em tempo adequado

A Disponibilidade está focada no fornecimento da informção, o principio garante que a informação (dados, valores, arquivos e etc) estejam disponiveis 24/7.

### Principais ataques que prejudicam a Disponibilidade

 * *Ataques DDoS (Distributed Denial of Service)* - São os mais comuns e impactantes. Envolve o envio de um volume massivo de requisições simultâneas de múltiplos dispositivos comprometidos(botnets) contra um servidor, rede ou aplicativo, esgotando sua capacidade de processamento e tornando-o inacessível. O Brasil é um dos países com maior número de ataques DDoS globalmente, devido á sua infraestrutura digital ampla e distribuida.

 * *Ataque DoS (Denial of Service)* - Semelhantes ao DDoS, mas originam-se de uma única fonte. O objetivo é sobrecarregar um serviço ou sistema até que ele pare de funcionar, impedindo o acesso legítimo.

 * *Ataques de Sobrecarga de Rede* - Técnicas que inundam a rede com tráfego malicioso, causando congestionamento e indisponibilidade de serviços críticos, como bancos, provedores de internet ou plataformas governamentais.

 * *Sabotagem Cibernética* - Ações intencionais para interromper os destruis serviços essenciais, podendo afetar infraestruturas estratégicas, como sistemas de defesa, logística ou comunicação, com impactos em segurança nacional.

## RFC 2828
 * O que é? - O RFC 2828, intitulado "Internet Security Glossary (Glosário de Segurança da Internet)" é um documento oficial da IETF (Internet Engineering Task Force) que define e padroniza a terminologia na segurança da informação em sistemas de computação em redes.

 - Baicamente -> Documento que padroniza o significado de varias palavras utilizadas por profissionais da area. (padrões em protocos, conceitos e boas praticas).

* Dentro disso temos os conceitos mais comuns utilizados ->

  - *Adversário* - Agente que ataca ou é ameaça para um ativo.
 
  - *Ameaça* - Potencial para violação de segurança. Possivel perigo que poderia explorar alguma volnerabilidade.
 
  - *Ataque* - Tentativa deliberada de violação da política de segurança existente.
 
  - *Contramedida* - Procedimento técnico que visa reduzir uma ameaça, vulnerabilidade ou ataque.
 
  - *Politica de Segurança* - Regras e práticas que regulamentam como um sistema ou entidade fornece serviços de segurança, de modo a garantir a segurança dos ativos sensíveis e/ou críticos.
 
  - *Ativo* - Recurso de sistema. Dados existentes em um sistema de informação. Hardware, software, instalações de redes, equipamentos.
 
  - *Risco* - Chance de perda de segurança. Geralmente expressada pela probabilidade de que uma ameaça explorará uma vulnerabilidade.
 
  - *Vulnerabilidade* - Defeito ou falha em projeto, operação ou gerenciamento de um sustema que poderia ser explorado para violar ativos ou a policita de segurança.
 
    * Categorias de Vulnerabilidade
   
      - *Corrupção* - Ativo pode operar de forma inadequada.
    
      - *Vazamento* - Informaçãoes podem estar sendo acessadas por pessoas não autorizadas.
    
      - *Indisponibilidade* - Impossibilidade de acesso à informação, ou problema com lentidão.
