# Features: #
[Cadastrar Curso](https://creative-sherbet-a51eac.netlify.app/new-course)
[Listar curso](https://creative-sherbet-a51eac.netlify.app/new-course)

***************************************************************************************
*Observações.:*
*- Com base em minha experiência de usuário de sistemas e como Analista de Qualidade de Software, fundamentei algumas regras de negócio com vistas exploratórias da aplicação, assumindo as seguintes observações:*
*************************************************************************************** 
# User Stories #
# US-001: Cadastrar novo curso #
*Como* usuário do sistema de cursos
*Quero* cadastrar um novo curso
*Para* que ele seja salvo no sistema e apareça na listagem de cursos

*Critérios de Aceite:*
*Critério	Descrição*	
CA-1	    Todos os campos obrigatórios devem existir e ser preenchidos	
CA-2	    A data de término (“Data Fim”) deve ser igual ou posterior à data de início	
CA-3	    O número de vagas deve ser um número inteiro positivo	
CA-4	    O tipo de curso só pode ser “Presencial” ou “Online”	
CA-5	    Se for “Presencial”, exibe campo Endereço que é obrigatório	
CA-6	    Se for “Online”, exibe campo Link de Inscrição que é obrigatório	
CA-7	    Após salvar com sucesso, exibe mensagem de sucesso e redireciona para a listagem de cursos	
CA-8	    Validações de erro devem exibir mensagem clara de campo inválido	
# US-002: Listar cursos disponíveis #
*Como* usuário do sistema
*Quero* visualizar todos os cursos cadastrados
*Para* que eu possa ver suas informações (nome, descrição, datas, vagas, tipo, etc)
Critérios de Aceite:
Critério	Descrição
CA-1	    A listagem exibe nome do curso, descrição, data de início e fim, número de vagas, tipo de curso
CA-2	    Para cada curso listado existe botão de exclusão (delete)
CA-3	    Após cadastro bem-sucedido de curso, ele aparece na listagem imediatamente
# US-003: Excluir curso #
*Como* usuário do sistema
*Quero* deletar um curso listado
*Para* que ele desapareça da visualização de listagem
Critérios de Aceite:
Critério	Descrição
CA-1	    Ao clicar no botão de deleção, sistema solicita confirmação antes de remover
CA-2	    Após confirmação, o curso é removido da listagem dinamicamente (sem necessidade de recarregar página)
CA-3	    Mensagem de sucesso ou feedback adequado após deleção

********************************************************************************************
# Casos de testes #

Para os casos de testes foram utilizadas técnicas como, análise de valor limite e testes exploratórios.
Os casos de teste estão documentados em uma planilha do Google Docs.

Link da planilha com os casos de teste

Já as evidências contidas no diretório de teste estão nomeadas seguindo o ID da planilha acima.

Diretório com as evidências de teste

********************************************************************************************
# Relatório de Bugs #

Para o relatório de bugs foi decidido pela inclusão das seções Título, Descrição, Passo a Passo, Resultado Esperado, Resultado Real, Ambiente de teste, Severidade e Evidência do erro.






