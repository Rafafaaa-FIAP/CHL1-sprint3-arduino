<h1 align="center">Challenge 1 - Arduino - Sprint 3</h1>

<hr/>

<p align="center">
  <a href="#bulb-Desafio">Desafio</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-Aplicação">Aplicação</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#hammer_and_wrench-Tecnologias-e-Ferramentas">Tecnologias e Ferramentas</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#floppy_disk-Solução">Solução</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#gear-Como-Utilizar">Como Utilizar</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#technologist-Integrantes">Integrantes</a>
</p>

<hr/>


## :bulb: Desafio
O desafio proposto pela Challenge para aprimorar a experiência hospitalar envolve o desenvolvimento de estratégias inovadoras para tornar a visita ao hospital mais agradável, divertida e eficiente. O foco principal é proporcionar benefícios aos pacientes, acompanhantes, visando a redução do tempo de espera, a comunicação eficaz e a diminuição do desconforto durante procedimentos médicos.

Identificar desafios específicos enfrentados pelos pacientes durante suas visitas ao hospital, propondo soluções para tornar a experiência mais positiva, ágil e agradável. Considerar fatores como entretenimento, comunicação e eficiência nos processos.

## :computer: Aplicação
A finalidade da aplicação desenvolvida é a simulação do monitoramento do leito hospitalar, facilitando o acompanhamento de variáveis vitais do ambiente, tais como temperatura, umidade e níveis de luz. Adicionalmente, a plataforma permite que os pacientes a requisitem assistência médica acionando um botão específico. Essas informações são centralizadas e acessíveis à equipe de saúde através de um painel de controle intuitivo na plataforma TagoIO, otimizando o gerenciamento dos cuidados ao paciente.

## :hammer_and_wrench: Tecnologias e Ferramentas
Este projeto utilizou as seguintes tecnologias e ferramentas:
* [Wokwi](https://docs.wokwi.com/pt-BR/)
* [C++](https://pt.wikipedia.org/wiki/C%2B%2B)
* [Node-RED](https://nodered.org/)
* [TagoIO](https://tago.io/)

## :floppy_disk: Solução
### Circuito
<h4>Componentes</h4>
<ul>
  <li><b>ESP32</b>: uma placa microcontroladora de código aberto com Wi-Fi e Bluetooth.</li>
  <li><b>Botão</b>: dispositivo eletromecânico utilizado para fechar ou abrir um circuito elétrico.</li>
  <li><b>LDR</b>: um resistor cuja resistência varia conforme a intensidade da luz que incide sobre ele.</li>
  <li><b>DHT22</b>: um sensor desenvolvido para medir temperaturas da faixa de -40°C a +80°C e umidade de 0% a 100%.</li>
</ul>

<img src="https://github.com/Rafafaaa-FIAP/CHL1-arduino-sprint3/blob/main/circuit.PNG" alt="circuit" width="500" />
<h6>Acesse o projeto clicando <a href="https://wokwi.com/projects/406323357735494657">aqui</a>.</h6>
   


### Fluxo
<img src="https://github.com/Rafafaaa-FIAP/CHL1-arduino-sprint3/blob/main/flow.PNG" width="500" />
<h6>Acesse o JSON para importação no Node-RED clicando <a href="https://github.com/Rafafaaa-FIAP/CHL1-arduino-sprint3/blob/main/flows.json">aqui</a>.</h6>

### Dashboard no TagoIO
<img src="https://github.com/Rafafaaa-FIAP/CHL1-arduino-sprint3/blob/main/dashboard.PNG" alt="dashboard" width="500" />
<h6>Acesse o vídeo de demonstração do funcionamento clicando <a href="https://youtu.be/tl2RWaOU1Pw">aqui</a>.</h6>


## :gear: Como Utilizar

1. Acessar o circuito montado no Wokwi;
2. Instalar o Node-RED;
3. Iniciar o Node-RED no computador;
4. Importar o fluxo no Node-RED no computador e fazer o deploy;
5. Acessar a plataforma TagoIO e acessar a dashboard.

## :technologist: Integrantes
* RM 552980 - Danilo Vieira
* RM 553377 - Enzo de Oliveira Rodrigues
* RM 552939 - Jonata Rafael
* RM 553403 - Matheus Felippe
* RM 553521 - Rafael Cristofali
