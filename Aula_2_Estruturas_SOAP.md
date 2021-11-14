# Estruturas SOAP

#### SOAP: **Simple Object Access Protocol**
* É um protocolo baseado em XML para acessar serviçoes web principalmente por HTTP
* é basicamente uma definição de como os serviços WEB se comunicam

## Estrutura SOAP
<SOAP Envelop>
    <SOAP Header>
        <SOAP Body>

        </SOAP Body>
    </SOAP Header>
</SOAP Envelop>

* SOAP Envelop = utilizado para encapsular toda a mensagem
* Soap Header = onde possui informações de atributos e metadados da requisição
* SOAP Body = elemento que contem os detalhes da mensagem