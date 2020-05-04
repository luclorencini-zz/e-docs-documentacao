**Integra��o via API - Guideline**

O Sistema E-Docs faz integra��o com os seguintes sistemas:
-[Acesso Cidad�o](https://acessocidadao.es.gov.br)
O Acesso Cidad�o � utilizado para tratar as autentica��es e autoriza��es dos usu�rios.

O Acesso Cidad�o possui sua API publicada em [aqui](https://sistemas.es.gov.br/prodest/acessocidadao.webapi/swagger).

-[Organograma](https://organograma.es.gov.br)
O Organograma � utilizado para consultar os �rg�os e Setores nele cadastrados.
Atualmente o Organograma possui uma integra��o com o sistema de Recursos Humanos do Governo do Estado do Esp�rito Santo, onde toda altera��o referente a �rg�o e setor realizada l� � refletida no Orgranograma.

O Organograma possui sua API publicada em [aqui](https://api.organograma.es.gov.br).

**Step by step:**
- Adicionar um sistema no Acesso Cidad�o
-   Adicionar um App com o fluxo Hybrid, as propriedades destes App ser�o necess�rias para configurar a autentica��o dos usu�rios.
- ...