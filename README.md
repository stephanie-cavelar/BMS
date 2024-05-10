# BMS 

As principais funções de um BMS incluem:

- Monitoramento da Tensão: O BMS monitora a tensão de cada célula da bateria para garantir que elas estejam balanceadas e operando dentro de limites seguros.
- Monitoramento da Corrente: Ele mede a corrente de carga e descarga da bateria para garantir que ela não seja sobrecarregada ou descarregada em excesso, o que pode causar danos ou reduzir a vida útil da bateria.
- Proteção contra Sobrecarga e Sobredescarga: O BMS controla o carregamento da bateria para evitar que ela seja carregada acima de sua capacidade máxima ou descarregada abaixo de um nível seguro.
- Proteção contra Sobreaquecimento: Ele monitora a temperatura da bateria e pode desligar a carga ou descarga se a temperatura atingir níveis perigosos.
- Balanceamento de Células: Em baterias compostas por múltiplas células, como as de íon-lítio, o BMS pode equalizar a carga entre as células para evitar que algumas delas sejam sobrecarregadas enquanto outras permanecem subcarregadas.
- Comunicação e Diagnóstico: Muitos BMSs possuem capacidades de comunicação para enviar dados sobre o estado da bateria, como nível de carga, temperatura e histórico de uso. Isso permite o diagnóstico remoto e a manutenção preventiva.


Os passos básicos para projetar um BMS são:

### Definição de Requisitos:
Identifique as especificações e requisitos do sistema, incluindo o tipo de bateria a ser gerenciado (íon-lítio, chumbo-ácido, etc.), capacidade da bateria, número de células, faixa de tensão de operação, corrente máxima de carga e descarga, entre outros.
### Escolha dos Componentes:
Selecione os componentes adequados para o BMS, incluindo sensores de tensão, sensores de corrente, circuitos de proteção, microcontroladores ou processadores de sinais digitais (DSP), circuitos de balanceamento de células, circuitos de comunicação, entre outros.
### Cálculo de Parâmetros:
Calcule os parâmetros necessários para o funcionamento do BMS, como limites de tensão de cada célula da bateria, correntes de carga e descarga máximas permitidas, faixa de temperatura de operação, entre outros.
### Simulação:
Simule o sistema utilizando o Simulink e Simscape da MathWork, implementando os diagramas de blocos e algoritmos.
### Projeto de Hardware:
Projete o hardware do BMS, incluindo o esquemático do circuito eletrônico, layout da placa de circuito impresso (PCB) e seleção dos componentes. Certifique-se de considerar aspectos como dissipação de calor, isolamento elétrico e proteção contra interferências eletromagnéticas (EMI).
### Desenvolvimento de Firmware/Software:
Desenvolva o firmware ou software necessário para o funcionamento do BMS, incluindo algoritmos de monitoramento, controle de carga e descarga, balanceamento de células, comunicação com o usuário ou outros sistemas, e diagnóstico de falhas.
### Testes e Validação:
Realize testes de laboratório e validação do BMS para garantir que ele atenda aos requisitos especificados. Isso inclui testes de funcionamento normal, testes de sobrecarga e sobredescarga, testes de temperatura, testes de comunicação, entre outros.
## Projeto
### Definição de Requisitos:
O pack de baterias a ser utilizado deve ser tal que supra as necessidades energéticas de um cubeSat. 
Usualmente, para este caso, os requisitosde tensão e corrente são de 3,7V nominais, 4,2V máx. Corrente nominal de X mA e máxima de XY mA.
### Escolha dos Componentes:

Caracteização das células de bateria

Circuito de balanceamento
  
![image](https://github.com/stephanie-cavelar/BMS/assets/80367957/8721433b-1b63-469c-8029-bf0329c258ae)

![image](https://github.com/stephanie-cavelar/BMS/assets/80367957/51926c54-f114-4783-a2ac-d930f2cbc680)



# Referências

https://www.sta-eletronica.com.br/artigos/baterias-recarregaveis/baterias-de-litio/como-balancear-baterias-de-li-ion-em-packs-de-baterias#:~:text=Os%20circuitos%20de%20balanceamento%20de,na%20carga%20como%20na%20descarga.
