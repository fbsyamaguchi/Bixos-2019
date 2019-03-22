# Tarefa de Embarcados

Olá. Venho aqui dar uma pequena explicação sobre o que será esperado que seja feito para a tarefa de embarcados do processo seletivo.

## Objetivo

O principal objetivo da tarefa é familiarizar você com a programação em C, o visual dos arquivos contidos na pasta dos programas da equipe e como fazer o uso de ADC, PWM e GPIO para interagir com elementos físicos.

Você deverá escrever um código que faz com que um led varie de intensidade ao girar um potênciometro. Também deve implementar um botão que irá inverter a lógica da vriação da intensidade do led. 

## Funções principais

1. __mcu_init():__
    Função essencial do programa. Nela serão inicializadados elementos como os pinos do botão e o clock do sistema.

2. **ADC_init():**
    Função que inicia o ADC do programa.

3. **PWM_init():**
    Função que inicia e configura a PWM do programa.

4. **button_init():**
    Função que inicia o botão existente na placa.

##  Interrupção

A interrupção é uma pequena função que é chamada sempre que ocorre algum evento específico, como o aperto de um botão. No caso deste exercício, a interrupção acontece quando o botão da placa é apertado. Para isso, voce deve usar a função:

    void HAL_GPIO_EXTI_Callback(uint16_t    GPIO_Pin){}

Assim, quando o botão é apertado tudo que você escrever dentro da função acontecerá. Esse ferramenta poderosa possibilita a equipe de poder operar robôs de sumô a distância, mudando estratégias com o siples aperto de um botão (mais especificamente um botão em um app que envia o comanado por bluetooth)
## Para você fazer

Crie um programa que faça uso da leitura ADC, de interrupção e de PWM para alterar a intensidade do led. Escreva seu código não só na main como nos arquivos *.c nescessários.

