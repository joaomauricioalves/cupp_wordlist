<h2> #cupp_wordlist</h2>

<h3>Introdução ao CUPP - Common User Passwords Profiler</h3>

<h4>Atenção</h4>

Antes de tudo, faço questão de frisar quanto a responsabilidade dos ensinamentos. O uso incorreto dos conteúdos deste texto, podem gerar consequências, pois há uma linha muito tênue entre o mundo educacional e a ilegalidade. 

Não é raro que pessoas usem essas informações para atividades maliciosas, dentro da prática de invasão de privacidade, roubo de informações entre outros exemplos, todos com resultados que podem carretar em problemas jurídicos e danos a terceiros, tanto no Brasil e como no mundo. 

Dessa forma, tenho o voltado o perfil para atividade acadêmica e profissional, trazendo uma das formas mais fáceis de criar uma wordlist. 
Por favor, o que você fizer é por sua conta e risco, sendo assim, cuidado!

<h4>Sobre o material</h4>

Como ferramenta usada para a criação de wordlists, o cupp pode ser de grande ajuda para o estudo na computação, principalmente no auxílio do método de Brute Force, dentro do exemplo da quebra de redes wifi com WPA2 ou para acesso a um simples formulário de uma página de login.

Para o uso do cupp tenho as seguintes recomendações:

Se você usa o Kali Linux, principalmente em máquina virtual entregue pelos desenvolvedores, o cupp já está instalado.

Para você que não tem o Kali Linux instalado e não quer dedicar um tempo para instalar, posso recomendar o acesso ao seguinte endereço:

https://www.kali.org/get-kali/#kali-virtual-machines

Para você que não tem o Kali Linux instalado e está curioso para instalar:

https://www.kali.org/get-kali/

Agora para instalação do cupp em outros sistemas operacionais baseados no GNU/Linux, posso sugerir que leia descrição do repositório oficial aqui no github:

https://github.com/Mebus/cupp


Para a criação de uma senha, algumas pessoas tomam por base critérios que auxiliem na memória, como: nomes de pessoas, datas, números de telefone, lugares entre outros exemplos. O cupp pode ajudar no repertório de quem estuda ou trabalha, pois na vida podem acontecer cenários onde você não tenha a chave para abrir algo, então precisa quebrar a fechadura ou chamar um chaveiro.

<h2>Uma forma de criar uma wordlist</h2>

Uma das principais características apresentadas aqui tem a ver com a máxima coleta de dados sobre o alvo,  algo recomendável quando pensamos em eficiência. O CUPP pode criar uma wordlist personalizada dentro do contexto dos dados coletados, justamente aqueles ligados com a facilidade da memorização. 

Se o alvo realmente utilizar de poucos cuidados com a sua senha, o que para exemplificar descrevo como algo em torno de números, letras repetidas ou até com relação ao nome de alguém importante na sua vida e um tamanho de até 8 digitos por exemplo, com a coleta de dados efetuada e nela em posse de tais pistas, o cupp pode auxiliar para que tenha uma maior chance de encontrar o resultado almejado. 

Agora, nem tudo é tão belo quanto parece, pois uma wordlist com mais palavras, consequentemente maior será o tamanho do arquivo, logo afetará diretamente na agilidade do processo. Imagine uma wordlist com um arquivo de texto na escala dos GB de tamanho, sendo usado em brute force, a título de exemplo, quanto maior o arquivo, maior poder computacional, maior o tempo para tentar quebrar possível senha, pense nisso.

<h4>Processo</h4>

Em mãos dos dados do alvo, posso simplesmente digitar no terminal o seguinte comando:

```
python3 cupp.py -i
```

ou em situação de está usando a versão instalada da VM

```
cupp -i
```


Ao digitar você verá algo semelhante a figura abaixo, algo que você deve preencher com os dados que você sabe sobre o alvo:

![cupp1](https://user-images.githubusercontent.com/39026922/175141784-f18f81e2-b112-44f3-8718-0f780d0db01c.png)

Em efeito de exemplo usei dados fictícios. 

Para o cupp, quanto mais detalhes sobre dados você acrescentar, maior o tamanho da wordlist, dessa forma, para este exemplo, não acrescentei tudo, apenas para efeito de conhecimento.

![image](https://user-images.githubusercontent.com/39026922/175144006-2047e036-c9a7-46c8-b4b5-c04c5c181ebf.png)


Ao final ele salva em um arquivo .txt e a partir daí isso pode facilitar a vida para muitas coisas.



