## Resumo das funções do Git 

- O Git armazena e vê informações de forma muito diferente do que esses outros sistemas, mesmo que a interface do usuário seja bem semelhante, e entender essas diferenças o ajudará a não ficar confuso. (Perforce )

- Git trata seus dados mais como um conjunto de imagens de um sistema de arquivos em miniatura. Toda vez que você fizer um commit, ou salvar o estado de seu projeto no Git, ele basicamente tira uma foto de todos os seus arquivos e armazena uma referência para esse conjunto de arquivos. Para ser eficiente, se os arquivos não foram alterados, o Git não armazena o arquivo novamente, apenas um link para o arquivo idêntico anterior já armazenado. O Git trata seus dados mais como um fluxo do estado
dos arquivos.

- O mecanismo que o Git utiliza para esta soma de verificação é chamado um hash SHA-1. Esta é uma
sequência de 40 caracteres composta de caracteres hexadecimais (0-9 e-f) e é calculada com base no
conteúdo de uma estrutura de arquivo ou diretório no Git

Link para download do Git (https://git-scm.com/downloads)
