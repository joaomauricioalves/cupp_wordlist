<h2> #cupp_wordlist</h2>

<h3>Introdução ao CUPP - Common User Passwords Profiler</h3>

<h4>Atenção</h4>

Antes de tudo, faço questão de frisar quanto a responsabilidade dos ensinamentos aqui. O uso incorreto dos conteúdos deste texto, podem gerar consequências, pois há uma linha muito tênue entre o mundo educacional e a ilegalidade. Não é raro dentro de atividades maliciosas se usem dessas informações para a prática de invasão de privacidade, algo que pode acarretar a conclusões de nível jurídico, no Brasil e no mundo. Desta forma aqui neste texto, tenho o voltado o perfil para atividade acadêmica e profissional, sendo totalmente contra o uso indiscriminado da técnica para agir contra pessoas, sendo assim, cuidado!


Sendo uma ferramenta usada para a criação de wordlists, pode ser de grande ajuda para o estudo em rede de computadores, principalmente como um instrumento de auxílio na prática de Brute Force, como por exemplo na quebra de redes wifi com WPA2 ou para acesso a um simples formulário de uma página.

Se você usa o Kali Linux, principalmente em máquina virtual entregue pelos desenvolvedores, o cupp já está instalado.

Para você que não tem o Kali Linux instalado e não quer dedicar um tempo para instalar, posso recomendar o acesso ao seguinte endereço:

https://www.kali.org/get-kali/#kali-virtual-machines

Para você que não tem o Kali Linux instalado, mas nesse pequeno momento deseja instalar:

https://www.kali.org/get-kali/

Agora voltando ao cupp, uma recomendação para instalação, caso não use o Kali Linux que já vem com ele instalado e escolha a opção de instalar do zero, posso sugerir que leia descrição do repositório oficial aqui no github:

https://github.com/Mebus/cupp


Para a criação de uma senha, algumas pessoas tomam por base critérios que auxiliem a memória como: nomes de pessoas, datas, números que remetem ao telefone, lugares entre outros exemplos. O CUPP entre outras opções, pode ajuda no repertório de quem estuda ou trabalha e que em determinado cenário precisa quebrar uma senha, levando em consideração o alvo em potencial possui chances de ter senhas frágeis.

<h2>Uma forma de criar uma wordlist</h2>

Uma das principais características apresentadas aqui, tem a ver com a máxima coleta de dados sobre o alvo, que 

```
python3 cupp.py -i
```

ou em situação de está no uso da VM 

```
cupp -i
```




