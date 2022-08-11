# C4A-Andon
User manual Call4Action - Andon

## 1. Introdução

 Andon é uma ferramenta de controle de qualidade, podendo mostrar relatórios detalhadados de tempo de parada, sem contar com a possibilidade de sinalizações visuais via **colunas luminosas, beacons, telas, mobile e smart watches** . C4A (Call4Action) é um sistema Andon que é moldado de acordo com a necessidade da aplicação, com as possibilidades de ser implementadas em quais quer tipo de industria.
 
## 2. Topologias

C4A pode é um sistema que usa equipamentos de comunicação sem fio. Podendo ser acionados por botoeiras sem fio que não usam bateria e se moldando a plantas que não tem a possibilidade de pontos de alimentações.  

As colunas luminosas e beacons sem fio da C4A podem ser usadas para mostrar o estagio de uma linha de produção com sinais luminosos e sonoros. 

Todas as ativações das botoeiras ou beacons/colunas luminosas são monitoradas pelo sistema C4A. Esses dados de ativações são disponibilidadas para tratamento de dados.

A plataforma [C4A](https://c4a.com.br/) foi pensada em ser utilizada em Nuvem ou em um servidor interno. A diferença crussial é poder acompanhar o sistema de qualquer lugar (Nuvem) ou se os dados são sigilosos que não podem sair da empresa (servidor local).

## 3. Lista de hardwares compativeis:
- C4A Applience 
- Eltako FAM14 (gateway)
- Eltako FRP14 (repetidor)
- Schlegel DFA16 (bloco de contato)
- Schlegel DFA22 (bloco de contato)
- Schlegel EK-FA-KRHV (fim de curso)
- QLight GW768 (gateway)
- QLight QMCL125-WIZ-BZ-24-SWP125 (beacon)
- QLight QTG70LF-WIZ-BZ-3 (coluna luminosa, 3 cores)
- QLight QTG70LF-WIZ-BZ-4 (coluna luminosa, 4 cores)
- QLight QTG70LF-WIZ-BZ-5 (coluna luminosa, 5 cores)

## 4. Setups do funcionamento da solução:
### Aplience:
Dispositivo responsavel pela aquisição e tratamento dos dados.
- A fonte que vai junto, tem que ser ligada na tomada e no dispositivo
- O cabo de rede deve ser ligado no applience e na rede em que terá internet ou na rede em que os demais disposivos estarão ligados.

### Eltako FAM14:
Gateway que faz funcionar as botoeiras sem fio.
- Alimentação: rede eletétrica (120VA ou 220VA)
- Comunicação: ligada no applience com cabo MINI USB.

### QLight GW768:
Gateway que faz a comunicação dos Beacons e Colunas Luminosas.
- Alimentação: 24V ou Cabo MINI USB.
- Comunicação: ligada no applience com cabo MINI USB ou via cabo de rede (os equipamentos tem que estarem na mesma rede que o applience).

### Schleggel EK-FA-KRGV:
Repetidor de sinal das botoeiras.
- Alimentação: rede eletétrica (120VA ou 220VA)
- Comunicação: Tem que estar no alcance do FAM14.

### Schlegel DFA16 DFA22:
Bloco de contato das botoeiras sem fio e sem bateria.
- Comunicação: alcance do FAM14 ou EK-FA-KRGV.
- Configurações: 2 estagios (on, off) ou pulso.

### Qlight QMCL125-WIZ-BZ:
Sinalisadores visuais e sonoros. 3 cores primarioas que podem se misturar. 5 tipos de sinalizações sonoras.
- Comunicação: alcence do GW768.
- Alimentação: 24Vcc

### Qlight  QTG70LF-WIZ-BZ:
Coluna luminosa que tem ate 5 cores diferentes. 5 tipos de sinalizações sonoras.
- Comunicação: alcence do GW768.
- Alimentação: 24Vcc

## 5. Versão:
### Aplience:
- versão 3.2.0.2
- Hardware: RICH-61D0

#### Features
- Plug-in-play com Eltako FAM14.
- Plug-in-play com Qlight GW768.

### Plataforma C4A
- versão: 2.8.7.4.3 (6-frontend; 7-backend; 4-mobile; 3-applience)
- Aplicação web: Todas as aplicações da Call4Action estão com o dominio [c4a.com.br](https://c4a.com.br/) com o subdomino da aplicação por ex. [bundycwb.c4a.com.br](https://bundycwb.c4a.com.br); [bundypba.c4a.com.br](https://bundypba.c4a.com.br)
- Mobile: o aplicativo Android esta disponivel ao entrar no endereço android correspondente da aplicação.

#### Features
##### Tela principal: 
- Piso Principal: Mostra o desenho da planta, posicionando cada linha fabril no chao de fabrica. 
- 
