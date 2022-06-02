# Curso  Frot-end

# GIT 
## Coceitos de Versionamento
-Histórico
-controle de versão
-Quem alterou
-O quê alterou
-Quando alterou
-Todos os arquivos
-Evolução continua

Aquivo A | Versão 1 | Versão 2
Aquivo B | Versão 1 | Versão 2

## Intalação do  git 

## Criar conta no GIT

## Clonar projeto
git clone https://github.com/Edusax77/Curso-Frontend.git

## Comits
Irfomação de alteração 
após testa seu código
git add *
git commit -m "mensagem "
git push (enviar  alteração para o repositório GitHub )
git pull ( puxa / traz alteraçoes do gitHub para sua máquina)

## GitFLOW
Fluxo do GIT
### Branchs
são ramificações /versão paralelas

main /master (vai para produção, quando o prejeto é publicado)
develop
DDO Difinition of Done: critérios de aceite
versionamento 1.0.0

git checkout -b dev (cria uma branch)
git checkout master (muda de branch)

### Merge
Mescla sde Branch
Você pode precisar de resolver conflitos manualmente 

git merge main

### Pull Request
Mesclas de branch no repositório
Permite código review
O repositório resolve conflito automaticamente

### configura o GitFlow
git flow init