<h2> #cupp_wordlist</h2>

<h3>Introdução ao CUPP - Common User Passwords Profiler</h3>

<h4>Atenção</h4>

Antes de tudo, faço questão de frisar quanto a responsabilidade dos ensinamentos aqui. O uso incorreto dos conteúdos deste texto, podem gerar consequências, pois há uma linha desse contexto, muito tênue entre o mundo educacional e a ilegalidade. Não é raro dentro de atividades maliciosas que se usem dessas informações para a prática de invasão de privacidade, roubo de informações entre outros exemplos que podem acarretar a conclusões de nível jurídico e dano a terceiros, tanto no Brasil e como no mundo. 

Desta forma aqui neste texto, tenho o voltado o perfil para atividade acadêmica e profissional, trazendo uma das formas mais fáceis de criar uma wordlist. 
Por favor, o que você fizer é por sua conta e risco, sendo assim, cuidado!

<h4>Sobre</h4>

Como ferramenta usada para a criação de wordlists, o CUPP pode ser de grande ajuda para o estudo em rede de computadores, principalmente no auxílio da prática de Brute Force, dentro do exemplo da quebra de redes wifi com WPA2 ou para acesso a um simples formulário de uma página.

Se você usa o Kali Linux, principalmente em máquina virtual entregue pelos desenvolvedores, o cupp já está instalado.

Para você que não tem o Kali Linux instalado e não quer dedicar um tempo para instalar, posso recomendar o acesso ao seguinte endereço:

https://www.kali.org/get-kali/#kali-virtual-machines

Para você que não tem o Kali Linux instalado, mas nesse pequeno momento deseja instalar:

https://www.kali.org/get-kali/

Agora voltando ao cupp, uma recomendação para instalação, caso não use o Kali Linux que já vem com ele instalado e tenha escolhido a opção de instalar do zero, posso sugerir que leia descrição do repositório oficial aqui no github:

https://github.com/Mebus/cupp


Para a criação de uma senha, algumas pessoas tomam por base critérios que auxiliem a memória, como: nomes de pessoas, datas, números de telefone, lugares entre outros exemplos. O CUPP pode ajudar no repertório de quem estuda ou trabalha, pois na vida podem acontecer cenários onde você não tenha a chave para abrir algo, então precisa quebrar a fechadura.

<h2>Uma forma de criar uma wordlist</h2>

Uma das principais características apresentadas aqui, tem a ver com a máxima coleta de dados sobre o alvo, pois o CUPP pode criar uma wordlist personalizada e isso pode ser de grande ajuda, porque na medida que a wordlist precisa de mais palavras, maior será o tamanho do arquivo, que em consequência, afetará diretamente na agilidade do processo.

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


