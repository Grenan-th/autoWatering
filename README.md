# autoWatering
Rega automática, auto-dosada

Lista de HW e funcionamento básico:
1) btOn: botão tipo ALAVANCA, é o principal, necessário para habilitação dos demais;
2) btConfig/Reset: botão tipo CHAVE, seleciona entre: calibração ou uso - se acionado imediatamente zera o valor anteriormente parametrizado, funcionando somente no modo livre;
3) btMode: botão tipo CHAVE seleção de modos: auto, livre;
4) btMeas: botão tipo PUSH, para medição da quantidade desejada (parametrização do volume, liberado se btConfig == calibração);
5) btRega: botão tipo PUSH, quando acionado libera a entrada de agua parametrizada em 3;
6) oWatPump: bomba d'agua (manter agua pressurizada por um tempo determinado após a rega, com desligamento automatico) - necessário ligar a bomba antes de liberar a valvula para garantir a pressurização;
7) oWatValv: valvula solenoide (abertura/fechamento do sistema) - QCRV22749 - 12V | 180º | 1/2 x 1/2;
8) sWatFlw: sensor de vazão d'agua, informa a quantidade de agua já disponibilizada - YF-S201 | até 30L/min | até 17bar;

### IDEIAS DUVIDAS FUTURO ###
1) O QUE POSICIONAR PRIMEIRO: VALVULA OU SENSOR???
2) QUAL DISTANCIA MÁXIMA ENTRE A BOMBA E O REGADOR? - É RELEVANTE???
3) BOMBA PRÓXIMA DO TANQUE OU DO REGADOR??? - NECESSÁRIO TESTAR

