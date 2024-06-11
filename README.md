## Descrição do Projeto
Este projeto implementa a técnica de estudo Pomodoro com o uso de um Raspberry Pi 4. A técnica Pomodoro divide o trabalho em intervalos de 25 minutos, chamados de "Pomodoros", seguidos por pausas curtas de 5 minutos. Após quatro Pomodoros, é feita uma pausa mais longa. LEDs indicam os ciclos de trabalho e pausas, um botão inicia os ciclos e um buzzer fornece feedback sonoro.

## Esquema de Ligação
Conecte os LEDs vermelhos aos pinos GPIO 17, 27, 22 e 23 do Raspberry Pi, cada um com um resistor.
Conecte o LED verde ao pino GPIO 24 com um resistor.
Conecte o LED azul ao pino GPIO 25 com um resistor.
Conecte o botão ao pino GPIO 18, utilizando o resistor pull-up interno.
Conecte o buzzer ao pino GPIO 3.
Conecte todos os terminais negativos dos LEDs, do botão e do buzzer ao GND do Raspberry Pi.
Modelo de Teste Utilizado no Projeto


## Tutorial de Execução
Conectando os Componentes
Siga as instruções do esquema de ligação acima para conectar todos os componentes ao Raspberry Pi.

## Executando o Código
Abra um terminal no Raspberry Pi.
Navegue até o diretório onde o arquivo pomodoro.py está salvo.
Execute o código com o comando:
python3 pomodoro.py
## Uso do Sistema
Pressione Enter no terminal para iniciar cada ciclo de trabalho.
Ao final de cada ciclo de trabalho de 25 minutos, um LED vermelho acende.
Após quatro ciclos de trabalho, todos os LEDs vermelhos se apagam, e o LED azul acende por 10 segundos, indicando a conclusão de um ciclo completo do Pomodoro.

![0c329425-8afe-4067-89f0-18484229d905](https://github.com/viniciusandrade22/projeto/assets/169168042/7db8dc4e-4bca-48c7-babc-4e76363b6304)

![ab37506b-07ad-4a71-9eac-c4d716292e2b](https://github.com/viniciusandrade22/projeto/assets/169168042/ad6377d8-25e0-4077-915e-6a6954508db6)
