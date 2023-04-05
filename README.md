Web Scraping de Fundos Imobiliários
Este script faz web scraping das informações de alguns fundos imobiliários brasileiros e envia essas informações para um grupo do Telegram.
Este código é um web scraper que coleta informações sobre fundos imobiliários em três URLs diferentes do site Fund Explorer. As informações coletadas são dividend yield, liquidez média diária, preço atual, setor, dividendo, variação de preço e patrimônio líquido.

O código utiliza as bibliotecas Requests e BeautifulSoup para fazer a requisição HTTP para as páginas do site Fund Explorer e extrair as informações relevantes.

Após extrair as informações, o código utiliza a biblioteca Telegram para enviar uma mensagem contendo as informações para um grupo especificado através do token do bot do Telegram e do chat ID do grupo.
Como usar
Clone este repositório em sua máquina.
Certifique-se de que as bibliotecas necessárias (Requests, BeautifulSoup e Telegram) estão instaladas em sua máquina. Caso não estejam, você pode instalá-las utilizando o pip.
Edite o código inserindo o seu token do bot do Telegram e o chat ID do grupo para onde deseja enviar as mensagens.
Execute o código.
Exemplo de mensagem enviada:
Dividend Yield: 0,60%
Liquidez Média Diária: R$ 70.454,50
Preço Atual: R$ 123,90
Setor: Shoppings
Dividendo: R$ 0,75
Variação de Preço: -2,78%
Patrimônio Líquido: R$ 632.786.000,00
