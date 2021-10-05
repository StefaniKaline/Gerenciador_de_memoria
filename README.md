# Implementação de um Gerenciador de memória

>*Descrição:* Projeto proposto pelo professor Rodrigo Moreira na disciplina de Sistemas Operacionais - SIN351 da *Universidade Federal de Viçosa - Campus Rio Paranaíba (UFV-CRP)*. Seu objetivo é o desenvolvimento de algoritmos de substituição de páginas, complementando assim o Gerenciador de Memória disponibilizado pelo mesmo e por fim comparar a eficiência destes algoritmos.

### Desenvolvido por:
* `Stefani Kaline:` https://github.com/StefaniKaline
* `Matrícula: 4702`

### Repositório no GitHub:
* https://github.com/StefaniKaline/Gerenciador_de_memoria

### Como utilizar:
* O projeto foi desenvolvido na linguagem C usando o padrão C99 e a IDE Code::Blocks
* Compilação do arquivo .c:
~~~C
gcc -Wall vmm.c -o vmm
~~~

* Execução do Gerenciador de Memória passando como parâmetro o arquivo dos acessos para os algoritmos fifo, second chance, nru, aging e random respectivamente:
~~~C
./vmm fifo 10 < anomaly.dat
~~~

~~~C
./vmm second_chance 10 < anomaly.dat
~~~

~~~C
./vmm nru 10 < anomaly.dat
~~~

~~~C
./vmm aging 10 < anomaly.dat
~~~

~~~C
./vmm random 10 < anomaly.dat
~~~

### Bugs conhecidos ou problemas:
* Não foi identificado nenhum problema que impedisse a execução dos algoritmos.
