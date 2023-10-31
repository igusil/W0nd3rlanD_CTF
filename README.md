# W0nd3rlanD_CTF

*************************************************************************************************************************************
Iniciei realizando um scan de diretorios com dirb e também passei um nmap pra encontrar portas.
a pagina dá uma dica muito importante, "follow the white rabbit"
![Screenshot from 2023-10-29 22-08-05](https://github.com/igusil/W0nd3rlanD_CTF/assets/89313216/9e6a7ae5-fb85-4da5-82fd-13a24fabefe0)
conseguimos ver que tem uma porta ssh aberta.
------------------------------------------------------------------------------------------------------------------------------------

ao encontrar essa pagina, verifique o codigo. podemos identificar um possivel user e pass, o prox passo é tentar conectar no ssh

![Screenshot from 2023-10-29 22-11-06](https://github.com/igusil/W0nd3rlanD_CTF/assets/89313216/630ab768-0648-4789-86e5-c6dcecb66ca3)

------------------------------------------------------------------------------------------------------------------------------------

conseguimos os acesso com user e pass encontrados no html, e encontramos a nossa primeira flag.  -->  thm{}
![Screenshot from 2023-10-29 22-30-20](https://github.com/igusil/W0nd3rlanD_CTF/assets/89313216/6eb1c8a9-8b8d-4a58-8f42-d569801bd930)

temos um script python no diretório, ele possui uma coleção de linhas diferentes que são impressas aleatoriamente.
![Screenshot from 2023-10-30 22-08-52](https://github.com/igusil/W0nd3rlanD_CTF/assets/89313216/952dfc84-450d-422a-a8b4-54b0151083ba)

verificamos a permissão sudo para tentar encontrar binarios ou arquivos que o usuário atual pode executar com privilégios elevados.
podemos executar walrus_and_the_carpenter.py com python3.6

![Screenshot from 2023-10-30 22-13-41](https://github.com/igusil/W0nd3rlanD_CTF/assets/89313216/81cb26a0-74a2-40c9-ad39-937505a406db)


