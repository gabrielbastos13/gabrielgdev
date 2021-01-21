---
title: Serviços Web
date: '2021-01-21T11:15:55-03:00'
autoThumbnailImage: false
thumbnailImagePosition: top
coverImage: /images/uploads/webservicesoverview.jpg
---
Serviços web são soluções para diferentes sistemas se comunicarem, usando linguagem comum, seja XML ou JSON, por meio de protocolos genéricos universais, o mais comum HTTP.

Estrutura SOAP é composta por SOAP Envelope, SOAP Header e SOAP body. SOAP Envelope empacota todo o conteúdo da mensagem. SOAP Header, é onde carrega todas as informações de atributos e metadados de requisição ( IP origem, DNS, Token, Credenciais ). SOAP BODY é onde fica o conteúdo da mensagem. 

<soap:Envelope>

\    <soap:Header>

\    </soap:Header>

\    <soap:Body>

\    </soap:Body>\
</soap:Envelope>



WSDL - Web Services Description Language

É um contrato onde é descrito em um documento XML onde é descrito o serviço, especificações de acesso, operação e métodos.

XSD - XML Schema Definition

é um schema no formato XML usado para definir estrutura de dados que será validada no XML. O XSD define quais parâmetros e restrições o SOAP Message deve ter para ser enviado pelo Web Service.
