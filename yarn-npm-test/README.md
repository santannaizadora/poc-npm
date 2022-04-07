# yarn-npm-test

Bash script para comparar o NPM e o Yarn

Teste feito por: https://github.com/vcavalcante/yarn-npm-test


## Execute o test

Execute o script dentro do seu diretório com um arquivo package.json.

```
bash yarn-npm-test.sh
```

O script gerará um arquivo de log para cada cenário, assim você pode verificar o que foi feito e também um arquivo test-yarn-npm.log.

Esse último arquivo tem um resumo dos tempos por cenário, ele é cumulativo cada vez que você executar ele irá incrementer esse arquivo.
