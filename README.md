# Wabill

Envie mensagens exclusivas do WhatsApp para vários números de uma só vez.

Clique [neste link](https://youtu.be/iQz-v9CCngE) para ver o vídeo do guia de instalação e uso.

![aplicativo de captura de tela](client/assets/ss-app.png)

## Guia rápido
1. Baixe do Github
2. Execute o aplicativo
3. Abra a página do servidor
4. Digitalize o código QR
5. Crie dados no Planilhas/Excel
6. Abra a página do cliente
7. Copie e cole os dados anteriormente
8. Crie modelos
9. Clique em visualizar
10. Envie!

## Como usar
1. Execute o servidor de aplicativos, existem duas maneiras de executar este aplicativo, use este executável ou clone repo e execute-o com `node index.js`.
Para rodar com o executável, baixe este aplicativo na seção Release à direita, de acordo com seu sistema operacional. Depois disso, clique duas vezes (para Windows) e um prompt de comando será aberto. Aí vai sair a url, abra a url no seu navegador (eu uso o google chrome). Então escaneie o código qr, uma vez ativo, abra a página do cliente em `url/client` por exemplo `http://localhost:8000/client`.
2. Crie dados no Google Sheet/Microsoft Excel

![exemplo de dados do excel](client/assets/ss1.png)

3. Copie e cole os dados, **Certifique-se de que a primeira linha seja o cabeçalho da coluna e a primeira coluna seja o número do WhatsApp do destinatário (com o formato 62xxxxxxxx).**

![primeira linha e coluna](client/assets/ss2.png)

4. Crie um modelo, envolva os títulos das colunas com símbolos **{}**, um modelo de exemplo (de acordo com os dados acima):
>Prezado Cliente,

>Informamos você sobre sua conta Wabill {number} em nome de {name}, o mês de cobrança 08-2021 no valor de {billing} será devido em 09-05-2021.

>Faça um pagamento imediatamente para que seu Wabill não fique isolado.

>Ignore esta notificação se você já fez um pagamento.

>obrigado
5. Verifique a visualização primeiro
6. Envie!

## Atualizações
Este aplicativo usa a biblioteca Baileys, que pode exigir atualização posterior. Você pode apoiar este aplicativo doando via:
[Trakteer.id](https://trakteer.id/afarhansib) ou [Saweria](https://saweria.co/afarhansib) ou entre em contato pelo meu whatsapp em [wa.me/6281233745324](https://wa. eu/6281233745324)

Seu apoio significará muito para mim e para a continuação deste aplicativo :)

**Este aplicativo/ferramenta é gratuito. por favor, não está à venda! **

**Não gravo/coleto dados deste aplicativo.**
