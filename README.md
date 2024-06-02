# Stress Test

Desafio Fullcycle Stress-test

## Comando para execução

1. [docker build -t fullcycle_stress_test .] para construir a imagem docker
2. [docker run fullcycle_stress_test stressTest -u -r -c ] para executar o teste
    - -u = url que será testada
    - -r = contagem de requisições que serão feitas
    - -c = contagem de solicitações que serão feitas ao mesmo tempo
3. Exemplo: 
    - [docker run fullcycle_stress_test stressTest -u=https://www.google.com -r=1000 -c=10]
