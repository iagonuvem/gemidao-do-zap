# Gemidão do Zap

> O brasileiro precisa ser estudado

## O que é isso?

O _Gemidão do Zap_ é uma aplicação escrita sobre o NodeJS que permite que você
envie o gemidão do zap para seus amigos via chamada telefônica e simulando o
número telefônico de pessoas conhecidas.

Por exemplo, eu posso enviar o gemidão do zap para meu amigo simulando uma
ligação da mãe dele e, quando ele atender, _AAAWN OOOWN NHAAA AWWWWN AAAAAH_
(inclusive, você acabou de cair no gemidão do zap escrito).

## Como funciona?

Utilizamos a API de chamadas da *TotalVoice*. Você precisa criar uma conta
para poder utilizar. Quando você cria uma conta, você obtém, gratuitamente, para
fins de testes, R$ 3,00 para utilizar. Cada envio do gemidão debita R$ 0,30.

Você receberá um token de acesso, que poderá passar para a nossa API para
fazer as chamadas. Fique tranquilo, todo o código é aberto e não a salvaremos.

## Instalação

`sudo npm install -g gemidao-do-zap`

Você terá disponível globalmente o comando `gemidao-do-zap`.

### Parâmetros

| Parâmetro | Obrigatório        | Descrição                                                 |
|-----------|--------------------|-----------------------------------------------------------|
| `--token` | :white_check_mark: | Seu token de acesso do TotalVoice                         |
| `--de`    |                    | Quem está enviando o gemidão? Qualquer número telefônico! |
| `--para`  | :white_check_mark: | Quem é a vítima do gemidão do zap?                        |
| `--mode`  |                    | `sms` ou `call`. Se for SMS, o gemidão vai por escrito    |

### Exemplo

`gemidao-do-zap --de=+5547998569631 --para=+5547996326548 --key=a15d23ae`

A vítima receberá uma ligação e, quando atender, ouvirá o delicioso gemido do zap!

### Cadê o áudio?

O arquivo encontra-se [neste link](http://prtnsrc.com/2545.mp3). Abra por sua conta e risco!

## Por quê!?

Porque somos brasileiros!
