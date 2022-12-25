# PyPIX

Este é um script em Python que permite a criação de um QR Code para chave Pix.

Este script é apenas ilustrativo e não está integrado a nenhum sistema de pagamentos. Ele foi criado com o objetivo de exercer a lógica de geração de QR Code para chave Pix, e não para ser usado em aplicações reais.

Por isso, é importante lembrar que o QR Code gerado pelo script não pode ser utilizado para efetuar transações ou qualquer outra operação com o Pix. Ele serve apenas como exemplo para entender o funcionamento da geração de QR Code para chave Pix.

Se você deseja integrar um sistema de pagamentos com o Pix, é necessário utilizar as APIs e ferramentas disponibilizadas pelos bancos e instituições financeiras. Mais informações podem ser encontradas no site do Banco Central do Brasil (https://www.bcb.gov.br/).


Para usar o script, é necessário ter o módulo qrcode instalado. Você pode instalá-lo usando o seguinte comando:

```
pip install qrcode
```


O script possui uma função chamada gerar_qr_code_pix(), que recebe dois parâmetros: valor e destinatario. O parâmetro valor representa o valor da transação, enquanto o parâmetro destinatario representa o nome ou razão social do destinatário.

A função cria uma chave Pix a partir dos parâmetros passados, e gera um QR Code a partir dessa chave. O QR Code é então salvo em um arquivo de imagem chamado "pix.png", e exibido na tela.

Para usar a função, basta chamá-la passando os valores desejados para os parâmetros. Por exemplo:

```
gerar_qr_code_pix(100.0, "João da Silva")
```

Isso irá gerar um QR Code para uma transação no valor de R$ 100,00 para o destinatário "João da Silva".
