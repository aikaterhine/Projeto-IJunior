# PIJunior
Sistema de comentários acerca de disciplinas e professores com o intuito de sintetizar e avaliar o desempenho dos docentes em cada semestre.

# Pré-requisitos
Possuir a aplicação MySql Workbench bem como o Wordpress configurado em servidor local.

# Instruções
1. Importe o arquivo .sql no MySql Workbench
2. Acesse página do projeto
3. Insira dados de usuário e senha que já se encontram no Banco de Dados (Exemplo | usuário: 1 | senha: 123456 | função: administrador)
4. Você será redirecionado e terá acesso às páginas de acordo com o seu nível de acesso definido no Banco de Dados

# Funcionamento do Sistema
O sistema está dividido em abas que correspondem ao nível de acesso de cada usuário, descritas a seguir:

Na aba *Home*, usuários comuns poderão inserir, acessar comentários existentes ou realizar filtragem na tabela1 de acordo com o parâmetro fornecido. A tabela1 apresenta o professor e disciplina correspondente, devendo-se realizar inserção de acordo com as combinações mostradas.
Na aba *Comentários*, usuários administradoes poderão inserir, editar, excluir e acessar comentários. A tabela2 apresenta o professor e disciplina correspondente, devendo-se realizar inserção de acordo com as combinações mostradas, além de mostrar o código do usuário sob o qual o comentário deverá ser registrado.
Na aba *Disciplina*, usuários administradores poderão inserir e acessar disciplinas cadastradas. A tabela3 apresenta o professor e disciplina correspondente, devendo-se realizar inserção de combinações que não estão registradas.
Na aba *Professor*, usuários administradores poderão inserir e acessar professores cadastrados. A tabela4 apresenta o professor e código correspondente, devendo-se realizar inserção de registros que não estão cadastrados.

# Desenvolvido com
* MySql Workbench
* Wordpress
* Trello
* Moqups

# Versionamento
Foi utilizado o GitHub para controle de versionamento do software.

# Autores
* Catarina Enya
