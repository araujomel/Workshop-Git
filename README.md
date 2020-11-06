"# Workshop-Git" 
Criar um repositorio git -> git init NOME
Entrar no repositorio
verificar se existe algo na pasta .git/objects

crie um arquivo de texto
escreva algo no arquivo
Escreva o hash do arquivo no git (git hash-object -w NOME.txt)
Verifique o conteúdo do hash (git cat-file -p HASH)
Verifique o TIPO do conteúdo (git cat-file -t HASH)
APAGUE o arquivo
Recupere ele utilizando o cat-file (Dica: salve a saida do cat-file usando > NOME.txt)

