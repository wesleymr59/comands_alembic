<h1>Comandos Alembic:</h1>

<!--ts-->
* [Comandos basicos Alembic](#comandos)
    * [Init](#init)
    * [Revision](#revision)
    * [Revision AutoGenerate](#revision-autogen)
    * [Upgrade +1](#upgrade+1)
    * [Upgrade Id](#upgradeId)
    * [Upgrade Head](#upgradeHead)
    * [Downgrade -1](#downgrade-1)
    * [Downgrade Id](#downgradeId)
    * [Downgrade Base](#downgradeBase)
    * [History](#history)
    * [History -Current](#historyCurrent)
    * [Downgrade Base](#downgradeBase)

<h1 id="comandos">Comandos:</h1>

• <span id="init"> alembic init <NOME> -> Comando inicial para começar a montar as migrations.</span> <br>
<p style="padding-left:5em;">alembic init migration <br>
</p><br>

• <span id="revision"> alembic revision -m "nome da revisão" <NOME> -> Comando para criar o arquivo de migration na pasta versions dentro do arquivo criado no INIT. </span> <br>
<p style="padding-left:5em;">alembic revision -m "nome da revisão"   pasta: migration>version <br>
</p><br>

• <span id="revision-autogen"> alembic revision --autogenerate -m "nome da revisão" <NOME> -> Comando para criar automaticamente o script de migration. </span> <br>
<p style="padding-left:5em;">alembic revision --autogenerate -m "nome da revisão"   pasta: migration>version <br>
</p><br>


• <span id="upgrade+1"> alembic upgrade <NOME> -> Comando para para atualizar para o ultimo script. </span> <br>
<p style="padding-left:5em;">lembic upgrade +1<br>
</p><br>

• <span id="upgradeId"> alembic upgrade ID <NOME> -> Comando para para atualizar para script informado no campo ID.</span> <br>
<p style="padding-left:5em;">alembic upgrade ID <br>
</p><br>

• <span id="upgradeHead"> alembic upgrade head <NOME> -> Comando para para atualizar todos os scripts até o HEAD. </span> <br>
<p style="padding-left:5em;">alembic upgrade head <br>
</p><br>

• <span id="downgrade-1"> alembic downgrade -1 <NOME> -> Comando para fazer o downgrade do ultimo script executado.</span> <br>
<p style="padding-left:5em;">alembic downgrade -1 <br>
</p><br>

• <span id="downgradeId"> alembic downgrade ID <NOME> -> Comando para fazer o downgrade da migration informando o id do script executado.</span> <br>
<p style="padding-left:5em;">alembic downgrade ID<br>
</p><br>

• <span id="downgradeBase"> alembic downgrade base <NOME> -> Comando para fazer o downgrade da migration diretamente na base. </span> <br>
<p style="padding-left:5em;">alembic downgrade base <br>
</p><br>

• <span id="history"> alembic history <NOME> -> Comando para visualização do historico de migrations.</span> <br>
<p style="padding-left:5em;">alembic history <br>
</p><br>

• <span id="historyCurrent"> alembic history --indicate-current<NOME> -> Comando para visualização do historio de migrations especifica.</span> <br>
<p style="padding-left:5em;">alembic history --indicate-current <br>
</p><br>

