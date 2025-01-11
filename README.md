# fazer-isso-todo-dia-no-PowerShell
sempre quando terminar o projeto colocar Set-ExecutionPolicy Restricted

#### Executar este para carregar a pagina web do react 
```
npm start
```

# Alterar a política de execução do PowerShell: depois de colocar para `Set-ExecutionPolicy RemoteSigned` você irá conseguir executar os scripsts
# depois de terminar a programação se lembrar de colocar a politica estritiva para evitar executar scripts de virus `Set-ExecutionPolicy Restricted`

# para saber qual politica esta ativa
```
Get-ExecutionPolicy
```
# Mudar para poder executar o script do react
```
Set-ExecutionPolicy RemoteSigned
```
# Mudar para não poder executar o script do react VOLTAR O QUE ERA ANTES
```
Set-ExecutionPolicy Restricted
```



