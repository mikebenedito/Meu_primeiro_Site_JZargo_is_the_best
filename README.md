Meu primeiro site - Aula de Desenvolvimento Web 1 - Prof. Márcio
Aluno: Michael Nunes Benedito
Curso: DSM primeiro semestre FATEC-Franca.

Esse site eu fiz de acordo com as expecificações da tarefa, sendo elas:
- Ter os codigos no GitHub
- Criar uma documentação no GitHub (README)
- Explicar a estrutura do HTML
- Explicar a estrutura do CSS
- Usar imagens/videos
- E ter o site hospedado online (COM O LINK DO README)


Explicação HTML:

-Page index.html:
    Usei a tag HEADER para identificar o cabeçalho da pagina, igual nos exemplos que eu tinha visto na aula.
    Criei uma DIV dentro do HEADER pra criar a CLASS container nela, pois por algum motivo que eu não sei explicar, se eu coloca a CLASS direto no HEADER o CSS não funciona direito.
    Usei o IMG para colocar a Imagem de "capa" do site e coloquei no ALT a descrição da imagem, criei a CLASS imagemcapa para trabalhar com ela no CSS.
    No H1 criei a CLASS container para poder colcoar ela em cima da imagem de "capa" usando o CSS. E dentro do H1 usei a tag BR pra quebrar a linha do texto.
    Após o HEADER acabar comecei uma nova DIV para o conteúdo do site. Nessa DIV criei a CLASS principal-texto para trabalhar essa DIV no CSS.
    Dentro da DIV usei varios P para paragrafos, IMGs para imagens que tive que criar a CLASS imagensdisplay para editalas no CSS, e usei varios BRs para quebrar as linhas.
    No ultimo P usei a tag A para criar um link para a proxima página do meu site, que no caso é a info.html.
    Ao final dessa DIV dos conteúdos eu criei um FOOTER e dentro dele um paragrafo com meu nome, e usei a tag B para deixar meu nome me nêgrito.
    E assim finalizo a pagina index.html.

-Page info.html:
    Usei a tag HEADER da mesma forma da pagina index.html, e fiz a mesma DIV com as mesmas CLASSs para usar o mesmo CSS.
    Após o HEADER criei outra DIV com a mesma CLASS "principal-texto" da pagina index.html, e fiz praticamente a mesma coisa da seção equivalente da outra pagina, a unica tag nova que usei
o Q para mostrar que aquelas frases são quotes e para poder trabalhar com essas quotes no CSS.
    Nos dois ultimos paragrafos dessa DIV fiz dois links, um para a pagina da wiki do personagem em que se baseia a pagina e outro para voltar pra "home page" que é o index.html.
    E no final usei exatamente o mesmo FOOTER com as mesmas tags e tudo.
    E assim finaliza a página info.html.

Explicação CSS:

Body
    Usei o Seletor da TAG body para modificar todo o body do html.
    Usei a Propriedade border-style para definir uma borda pro body, e usei o Valor solid, para que essa borda fosse solida.
    Usei a Propriedade border-width para definir a grossura da borda, e usei o valor de 5 pixels.

.imagemcapa
    Usei o Seletor da CLASS imagemcapa para modificar ela lá no html.
    Usei a Propriedade Display com o Valor Block, mas não entendi direito o porque, eu tive que usar eles para que eu conseguisse colocar o texto em cima da imagem.
    

