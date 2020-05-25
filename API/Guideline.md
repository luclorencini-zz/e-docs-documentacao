**Integra��o via API - Guideline**

Os m�todos dispon�veis para utiliza��o via api podem ser consultados [aqui](https://api.e-docs.es.gov.br/swagger).

O ambiente de Treinamento deve ser utilizado para os testes.
[E-Docs Web - Treinamento](https://treinamento.e-docs.es.gov.br)
[E-Docs Api - Treinamento](https://api.treinamento.e-docs.es.gov.br/)

O Sistema E-Docs faz integra��o com os seguintes sistemas:

- [Acesso Cidad�o](https://acessocidadao.es.gov.br)

O Acesso Cidad�o � utilizado para tratar as autentica��es e autoriza��es dos usu�rios.

O Acesso Cidad�o possui sua API publicada em [aqui](https://sistemas.es.gov.br/prodest/acessocidadao.webapi/swagger).

- [Organograma](https://organograma.es.gov.br)

O Organograma � utilizado para consultar os �rg�os e Setores nele cadastrados.
Atualmente o Organograma possui uma integra��o com o sistema de Recursos Humanos do Governo do Estado do Esp�rito Santo, onde toda altera��o referente a �rg�o e setor realizada l� � refletida no Orgranograma.

O Organograma possui sua API publicada em [aqui](https://api.organograma.es.gov.br).


**Primeiros passos:**
- Adicionar um sistema no Acesso Cidad�o
  - Adicionar um App com o fluxo Hybrid, as propriedades destes App ser�o necess�rias para configurar a autentica��o dos usu�rios para que ele possa realizar as opera��es no E-Docs.
  - Adicionar um App com o fluxo ClientCredentials, as propriedades destes App ser�o necess�rias para que o sistema fa�a consultas em outros sistemas, por exemplo o organograma.
  - Pode ser que seja necess�rio utilizar m�todos que est�o disponibilizados via [Api](https://sistemas.es.gov.br/prodest/acessocidadao.webapi/swagger) do Acesso Cidad�o.
- Caso seja necess�rio obter informa��es do Organograma ser� necess�rio acrescentar o scope api-organograma ao App de fluxo ClientCredentials que foi criado no Acesso Cidad�o.


**Principais a��es do E-Docs**
- [Documentos](Documentos.md)
  - Capturar
- [Encaminhamentos](Encaminhamentos.md)
  - Adicionar
- [Processos](Processos.md)
  - Autuar
  - Despachar
  - Entranhar Documentos
  - Desentranhar Documentos
  - Encerrar