## 1. Cadastrar novo curso

 Ator Principal: Administrador
 Pré-condição: O administrador precisa estar autenticado no sistema.
 Cenário Principal:
   1. O administrador acessa a área de administração.
   2. Seleciona a opção 'Cadastrar curso'.
   3. Preenche os dados do curso (nome, carga horária, etc).
   4. Clica em 'Salvar'.
   5. O sistema confirma o cadastro com uma mensagem.
 Cenário Alternativo 1: 3a. Se o nome do curso já existir, o sistema exibe uma mensagem de erro.
 Cenário Alternativo 2: 4a. Se algum campo obrigatório não for preenchido, o sistema solicita o
 preenchimento.
 Pós-condição: O curso estará disponível para os alunos visualizarem e se matricularem.


## 2. Realizar matrícula em curso

 Ator Principal: Aluno
 Pré-condição: O aluno deve estar logado na plataforma.
 Cenário Principal:
   1. O aluno navega até a lista de cursos disponíveis.
   2. Seleciona um curso.
   3. Clica em 'Matricular-se'.
   4. O sistema confirma a matrícula.
 Cenário Alternativo 1: 3a. Se o aluno já estiver matriculado, o sistema exibe uma mensagem de
 aviso.
 Cenário Alternativo 2: 3b. Se o curso estiver lotado, o sistema informa a indisponibilidade.
 Pós-condição: O aluno estará matriculado no curso escolhido.


## 3. Realizar login na plataforma

Ator Principal: Qualquer usuário
 Pré-condição: O usuário precisa possuir um cadastro válido.
 Cenário Principal:
   1. O usuário acessa a tela de login.
   2. Insere e-mail e senha.
   3. Clica em 'Entrar'.
   4. O sistema autentica o usuário e redireciona para o painel principal.
 Cenário Alternativo 1: 2a. Se os dados estiverem incorretos, o sistema exibe uma mensagem de
 erro.
 Cenário Alternativo 2: 3a. Se houver erro de conexão, o sistema solicita tentar novamente mais
 tarde.
 Pós-condição: O usuário tem acesso à plataforma com sua conta.


 ## 4. Emitir certificado de conclusão

 Ator Principal: Aluno
 Pré-condição: O aluno deve ter completado todos os módulos do curso.
 Cenário Principal:
   1. O aluno acessa a área do curso concluído.
   2. Clica em 'Emitir certificado'.
   3. O sistema gera o certificado em PDF e disponibiliza o download.
 Cenário Alternativo 1: 2a. Se o aluno não concluiu o curso, o sistema não habilita o botão de
 emissão.
 Cenário Alternativo 2: 3a. Se ocorrer falha na geração, o sistema solicita tentar novamente.
 Pós-condição: O aluno terá acesso ao certificado digital do curso.


## 5. Avaliar curso
 
 Ator Principal: Aluno
 Pré-condição: O aluno deve estar matriculado no curso e ter acessado ao menos um módulo.
Cenário Principal:
   1. O aluno acessa a área de avaliação do curso.
   2. Preenche nota e comentário.
   3. Clica em 'Enviar avaliação'.
   4. O sistema registra a avaliação.
 Cenário Alternativo 1: 2a. Se a nota não for preenchida, o sistema solicita correção.
 Cenário Alternativo 2: 3a. Se a avaliação já foi enviada, o sistema exibe a avaliação anterior.
 Pós-condição: A avaliação será armazenada e visível para outros usuários
