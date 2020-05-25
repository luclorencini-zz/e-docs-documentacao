**[Integra��o via API](Guideline.md) - Encaminhamentos**

O Encaminhamento � a forma de Documentos tramitarem sem estarem entranhados a um processo, de forma avulsa.

**A��es dispon�veis:**
- [Encmainhar](#encaminhar)
- [Consultar](#consultar)

### Encaminhar
Um Encaminhamento pode ser inserido sem referenciar um Encaminhamento Anterior, neste caso ele ser� o raiz.

Um Encaminhamento pode ser inserido referenciando um Encaminhamento Anterior, conforme descrito abaixo:
- Complementar, quando remetente deseja complementar com alguma informa��o o Encaminhamento que foi feito anteriormente
- Responder, quando o destinat�rio deseja responder ao rementente do Encaminhamento Anterior
- Reencaminhar, quando o destinat�rio deseja encaminhar o Encaminhamento Anterior para um outro destinat�rio

A documenta��o deste m�todo pode ser vista [aqui](https://api.e-docs.es.gov.br/swagger/index.html#/Encaminhamentos/Encaminhamentos_Post).

O Access Token obtido atrav�s da **Autentica��o de Usu�rio** no Acesso Cidad�o utilizando o scope 'api-sigades-encaminhamento' � requerido no cabe�alho das requisi��es aos endpoints de Encaminhar usando o padr�o Bearer Token. [Especifica��o de uso do Bearer Token](https://tools.ietf.org/html/rfc6750#page-5)

### Consultar
Ap�s um Encaminhamento ser inserido ele poder� ser consultado.

A documenta��o deste m�todo pode ser vista [aqui](https://api.e-docs.es.gov.br/swagger/index.html#/Encaminhamentos/Encaminhamentos_Get).

O Access Token obtido atrav�s da autentica��o no Acesso Cidad�o utilizando o scope 'api-sigades-consultar' ou 'api-sigades-encaminhamento' � requerido no cabe�alho das requisi��es aos endpoints de Consulta usando o padr�o Bearer Token. [Especifica��o de uso do Bearer Token](https://tools.ietf.org/html/rfc6750#page-5)