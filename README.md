<h2> #cupp_wordlist</h2>

<h3>Introdução ao CUPP - Common User Passwords Profiler</h3>

Sendo uma ferramenta usada para a criação de wordlists, pode ser de grande ajuda para o estudo em rede de computadores, principalmente como um instrumento de auxílio na prática de Brute Force, como por exemplo na quebra de redes wifi com WPA2.

Se você usa o Kali Linux, principalmente em máquina virtual entregue pelos desenvolvedores, o cupp já está instalado.

Para você que não tem o Kali Linux instalado e não quer dedicar um tempo para instalar, posso recomendar o acesso ao seguinte endereço:

https://www.kali.org/get-kali/#kali-virtual-machines

Para você que não tem o Kali Linux instalado, mas nesse pequeno momento deseja instalar:

https://www.kali.org/get-kali/

Agora voltando ao cupp, uma recomendação para instalação pode ser pela descrição do repositório oficial aqui no github:

https://github.com/Mebus/cupp


Para a criação de uma senha, algumas pessoas tomam por base critérios que auxiliem a memória como: nomes de pessoas, datas, números que remetem ao telefone, lugares entre outros exemplos. O CUPP entre outras opções, pode ajuda no repertório de quem estuda ou trabalha e que em determinado cenário precisa quebrar uma senha, levando em consideração o alvo em potencial possui chances de ter senhas frágeis.

```
python3 cupp.py -i
```

ou em situação de está no uso da VM 

```
cupp -i
```




