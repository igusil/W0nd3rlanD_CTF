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
conseguimos os acesso com user e pass encontrados no html, e encontramos a nossa primeira flag.
![Screenshot from 2023-10-29 22-27-42](https://github.com/igusil/W0nd3rlanD_CTF/assets/89313216/5a04d6da-3606-4daa-9c3a-46e84dfac1ee)
