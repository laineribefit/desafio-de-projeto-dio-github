## Resumo das funções do Git 

- O Git armazena e vê informações de forma muito diferente do que esses outros sistemas, mesmo que a interface do usuário seja bem semelhante, e entender essas diferenças o ajudará a não ficar confuso. (Perforce )

- Git trata seus dados mais como um conjunto de imagens de um sistema de arquivos em miniatura. Toda vez que você fizer um commit, ou salvar o estado de seu projeto no Git, ele basicamente tira uma foto de todos os seus arquivos e armazena uma referência para esse conjunto de arquivos. Para ser eficiente, se os arquivos não foram alterados, o Git não armazena o arquivo novamente, apenas um link para o arquivo idêntico anterior já armazenado. O Git trata seus dados mais como um fluxo do estado
dos arquivos.

- O mecanismo que o Git utiliza para esta soma de verificação é chamado um hash SHA-1. Esta é uma sequência de 40 caracteres composta de caracteres hexadecimais (0-9 e-f) e é calculada com base no conteúdo de uma estrutura de arquivo ou diretório no Git.

- Quando você faz algo no Git, quase sempre dados são adicionados no banco de dados do Git - e não removidos. É difícil fazer algo no sistema que não seja reversível ou fazê-lo apagar dados de forma alguma. Como em qualquer VCS, você pode perder alterações que ainda não tenham sido adicionadas em um commit; mas depois de fazer o commit no Git do estado atual das alterações, é muito difícil que haja alguma perda, especialmente se você enviar regularmente o seu banco de dados para outro repositório.

- O Git tem três estados principais que seus arquivos podem estar: committed, modificado (modified) e preparado (staged). Committed significa que os dados estão armazenados de forma segura em seu banco de dados local. Modificado significa que você alterou o arquivo, mas ainda não fez o commit no seu banco de dados. Preparado
significa que você marcou a versão atual de um arquivo modificado para fazer parte de seu próximo commit.

Link para download do Git (https://git-scm.com/downloads)

## Instalar o GIT no Windows:

Acesse o site oficial e faça o download do instalador do GIT para Windows.
Depois de baixado, clique duas vezes no arquivo para iniciar o assistente de instalação. Basta seguir as instruções na tela, clicando em Next. Ao término, clique em Finish para concluir com êxito a instalação.
Abra o prompt de comando e digite os seguintes comandos no terminal:
git config --global user.name "João Silva"
git config --global user.email "exemplo@seuemail.com.br"

><cite>Nota: Lembre-se de substituir João Silva e exemplo@seuemail.com.br com seus dados. Qualquer commit criado posteriormente será associado à esses dados.</cite>
