**Integra��o via API - Processos**

Autua��o e tramita��o de Processos Administrativos seguindo a formalidade da legisla��o vigente.

O Processo possui um custodiante que pode ser:
- Uma Organia��o (�rg�o), neste caso o respons�vel pela organiza��o poder� realizar os atos processuais, podendo delegar tais compet�ncias.
- Uma Unidade (setor), neste caso o respons�vel pela unidade poder� realizar os atos processuais, podendo delegar tais compet�ncias.
- Um Grupo, neste caso todos os membros do Grupo poder�o realizar os atos processuais.
- Um Papel (servidor p�bico ocupando um cargo ou fun��o), neste caso somente o detentor do Papel poder� realizar os atos processuais.

**A��es dispon�veis:**
- [Autuar](#Autuar)
- [Despachar](#Despachar)
- [Entranhar Documentos](#Entranhar Documentos)
- [Desentranhar Documentos](#desentranhar-documentos)
- [Encerrar](#Encerrar)
- [Consultar](#Consultar)

##**Autuar**
Um Processo Administrativo passa a existir no momento de sua autua��o.

A documenta��o deste m�todo pode ser vista [aqui](https://api.e-docs.es.gov.br/swagger/index.html#/Processos/Processos_Autuar).

No momento da autua��o poder� ser informados quais documentos j� ser�o entranhados ao processo.

Todo Processo � autuado na Unidade onde o Papel que fez a autua��o est� lotado.

**#Despachar**
O Despacho � usado para movimentar o Processo Administrativo, fazendo com que o Processo mude de custodiante.

A documenta��o deste m�todo pode ser vista [aqui](https://api.e-docs.es.gov.br/swagger/index.html#/Processos/Processos_Despachar).

No momento do despacho poder� ser informados quais documentos ser�o entranhados ao processo.

**Entranhar Documento**
Atrav�s desse m�todo � poss�vel entranhar um Documento ao Processo sem que ele sofra uma movimenta��o.

A documenta��o deste m�todo pode ser vista [aqui](https://api.e-docs.es.gov.br/swagger/index.html#/Processos/Processos_Entranhar).

##**Desentranhar Documentos**
Atrav�s desse m�todo � poss�vel desentranhar um Documento que tenha sido entranhado anteriormente ao Processo. Este ato n�o movimenta o Processo.

A documenta��o deste m�todo pode ser vista [aqui](https://api.e-docs.es.gov.br/swagger/index.html#/Processos/Processos_Desentranhar).

[**Encerrar**]
Ap�s concluidos os tramites do Processo e tendo ele atingido o seu objetivo, encerra-se o Processo.

O Encerramento far� com que o processo seja movimentado para a Unidade que esteja vinculado ao atual custodiante.

A documenta��o deste m�todo pode ser vista [aqui](https://api.e-docs.es.gov.br/swagger/index.html#/Processos/Processos_Encerrar).

