# Décimo oitavo desafio de codar em js.
Construindo um leitor de código QR com javascript. Este leitor de código qr também usa a API do QR Reader e pode ler os códigos qr que geramos.
* Função `fetchRequest`:
   * Envia uma solicitação POST para a API do serviço QRServer, passando o arquivo de imagem com o código QR.
   * Processa a resposta da API para extrair e exibir o resultado da leitura do código QR na página.
* Event Listeners:
   * Quando um arquivo é selecionado, o código chama a função `fetchRequest` para enviar o arquivo para a API e obter o resultado.
   * Quando o usuário clica no botão de cópia, o resultado é copiado para a área de transferência do sistema.
   * Outros elementos interagem para facilitar a seleção de arquivos e o fechamento do contêiner.
* Tratamento de Erros:O código lida com possíveis erros de conexão ao chamar a API, garantindo a robustez do aplicativo.

## Captura da tela
Aqui a captura da tela com o projeto :

[leitorQRcode.webm](https://github.com/77971904/-Desafio-de-codar-em-javascript18/assets/108705247/2c99175f-0c6f-401a-ba5a-1aed4ebb2d98)

(O intuito desse projeto é apenas praticar os conhecimentos em javascript.)
Acompanhando um desafio de 100 dias condando em js do canal de youtube <a href="youtube.com/channel/UCJqXkOwrq7uBn-sn_Fvce9Q?sub_confirmation=1">AsmrProg</a>

