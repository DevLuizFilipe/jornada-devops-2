# jornada-devops-2
Este projeto tem por objetivo criar os manifestos do kubernetes para a aplicação da atividade anterior e para uma nova.
Foi criado Deployments para ambas aplicações e são gerenciados pelo Kustomization, que também gera Secrets para dados 
sensiveis comos as variaveis do banco de dados. Os Services foram configurados para ser Load Balancer de modo que
distribuam a carga recebida entre os pods.
