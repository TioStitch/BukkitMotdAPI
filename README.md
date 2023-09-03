# BukkitMotdAPI

Com a recodificação total do BukkitMotdAPI você pode criar seus MOTDs de forma otimizada e organizada agora,
darei alguns passos a baixo de como realizar isto, pode parecer meio irrelevante mas é muito útil.

Inicialização do Objeto:

argumento 1: Linha 1.
argumento 2: Linha 2.

![screenshot](https://imgur.com/J7LLBex.png)

Métodos para criar linhas animadas:

Este é realmente opcional,
é apenas uma dica melhorada.

argumento 1: Lista em String da Linha 1.
argumento 2: Lista em String da Linha 2.

![screenshot](https://imgur.com/KGwWcmk.png)

Como puxar um exemplo de MOTD:

Você deve criar uma classe e implementar
ela em AbstractMOTD e com isso criar um evento
com ServerPingListener e instanciar um novo
objeto da sua classe de MOTD com implemento.

Bom, você pode usar o ExampleMOTD
mas eu recomendo criarem um próprio.

![screenshot](https://imgur.com/QegaN12.png)
