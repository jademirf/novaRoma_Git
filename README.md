# novaRoma_Git
Repositório criado para ao workshop sobre git da semana de tecnologia da Nova Roma - Recife

## Clonar repositório
```bash
git clone https://github.com/jademirf/novaRoma_Git.git
```

## Adicionar alterações (stage)
```bash
git add .
```
## Criar um commit (identifica um conjunto de alterações)
```bash
git commit -m "mensagem que identifica o que foi feito nesse commit"
```
## Enviar as alterações feitas para o repositório (origin)
```bash
git push
```
## Enviar as alterações criando uma nova branch no repositório (origin)
Caso tenha sido criada uma nova branch localmente, basta informar no push que precisa ser adicionada uma nova branch no repositório remoto (remote origin)
```bash
git push -u nomeDaNovaBranch
```
ou
```bash
git push --set-upstream origin nomeDaNovaBranch
```
## Mudar de branch
```bash
git checkout nomeDaBranch
```
## Criar uma nova branch
podemos criar uma branch nova usando o comando checkout e adiconando -b para informar que vamos criar a branch para a qual estamos tentando mudar.
```bash
git checkout -b nomeDaNovaBranch
```
## Merge entre duas branchs
Faça checkout para a branch que deseja RECEBER as alterações e em seguida:
```bash
git merge nomeDaBranchQueContemAsInformacoes
```