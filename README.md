<h1 align="center">Ano 1 - Semestre 2 - Challenge - 1ESPR</h1>

<hr/>

<p align="center">
  <a href="#pushpin-Introdução">Introdução</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#bulb-Desafio">Desafio</a>
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

## :pushpin: Introdução
Este checkpoint teve como objetivo avaliar a compreensão acerca da interação com o [Node-RED](https://nodered.org/).

## :bulb: Desafio
O desafio proposto pela Global Solutions para aprimorar a experiência hospitalar envolve o desenvolvimento de estratégias inovadoras para tornar a visita ao hospital mais agradável, divertida e eficiente. O foco principal é proporcionar benefícios aos pacientes, acompanhantes, visando a redução do tempo de espera, a comunicação eficaz e a diminuição do desconforto durante procedimentos médicos.

Identificar desafios específicos enfrentados pelos pacientes durante suas visitas ao hospital, propondo soluções para tornar a experiência mais positiva, ágil e agradável. Considerar fatores como entretenimento, comunicação e eficiência nos processos.

## :hammer_and_wrench: Tecnologias e Ferramentas
Este projeto utilizou as seguintes tecnologias e ferramentas:
* [Wokwi](https://docs.wokwi.com/pt-BR/)
* [Node-RED](https://nodered.org/)
* [C++](https://pt.wikipedia.org/wiki/C%2B%2B)
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

<img src="https://github.com/danillosales/sprint3-challenge-icr/blob/main/circuit.PNG" alt="circuit" width="500" />
   


### Fluxo
<img src="https://github.com/danillosales/sprint3-challenge-icr/blob/main/flow.PNG" width="500" />
<h6>Acesse o JSON para importação no Node-RED clicando <a href="https://github.com/danillosales/sprint3-challenge-icr/blob/main/flows.json">aqui</a>.</h6>

### Dashboard no TagoIO
<img src="https://github.com/danillosales/sprint3-challenge-icr/blob/main/dashboard.PNG" alt="dashboard" width="500" />

## :gear: Como Utilizar
1. Instalar o [Node-RED](https://nodered.org/);
2. Baixar o [código](https://github.com/studies2023-FIAP-ES-553521-ano1-05-EDG/sem2-checkpoint1/blob/main/code.ino) da solução e instalar as bibliotecas ArduinoJson e DHT sensor library;
3. Montar o circuito;
4. Conectar o Arduino no computador e fazer upload do código para o Arduino;
5. Iniciar o [Node-RED](https://nodered.org/) no computador;
6. Importar o [fluxo](https://github.com/studies2023-FIAP-ES-553521-ano1-05-EDG/sem2-checkpoint1/blob/main/flows.json) no [Node-RED](https://nodered.org/) no computador e fazer o deploy.

## :technologist: Integrantes
* RM 552980 - Danilo Vieira
* RM 553377 - Enzo de Oliveira Rodrigues
* RM 552939 - Jonata Rafael
* RM 553403 - Matheus Felippe
* RM 553521 - Rafael Cristofali
