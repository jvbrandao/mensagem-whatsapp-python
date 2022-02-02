# Mensagem whatsapp via python

Script para envio de mensagens no whatsapp via python 
## Instalação
Necessita usar a biblioteca pywhatkit.
```bash
pip install pywhatkit
```

## Uso

```python
import pywhatkit

numero = "+55 **********" #insira o numero para quem deseja enviar a mensagem

mensagem = "mensagem pelo pywhatkit!:)" #insira sua mensagem aqui

pywhatkit.sendwhatmsg_instantly(numero, mensagem)
```
Após isso basta rodar a main, e escanear o codigo QR que vai aparecer
