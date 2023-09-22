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

Seletor: Body
    Usei o Seletor da TAG body para modificar todo o body do html.
    Usei a Propriedade border-style para definir uma borda pro body, e usei o Valor solid, para que essa borda fosse solida.
    Usei a Propriedade border-width para definir a grossura da borda, e usei o valor de 5 pixels.

Seletor: .imagemcapa
    Usei o Seletor da CLASS imagemcapa para modificar ela lá no html.
    Usei a Propriedade Display com o Valor Block, mas não entendi direito o porque, eu tive que usar eles para que eu conseguisse colocar o texto em cima da imagem.
    Usei as Propriedades margin-left e margin-right com o Valor Auto, para que as imagens fiquem centralizadas na pagina.
    E usei a Propriedade Width no valor 100% para que a imagem fique do tamanho inteiro da pagina.

Seletor: .container
    Usei para conseguir colocar o texto em cima da imagem mas não entendi direito o porque.

Seletor: .text-block
    Usei a Propriedade position com o Valor absolute para o texto ficar em cima da imagem mas eu não entendi porque.
    Usei a Propriedade Color com o Valor White para que o texto da CLASS fique branco.
    Usei a Propriedade font-size com o Valor de 40 pixels para que o tamanho da forte fique em 40 pixels.
    Usei as Propriedades left e bottom com seus valores para que o texto fique na parte esquerda inferior da imagem.
*Obs: ainda não entendi direito essa Propriedade position, usei mas copiei da internt pois não conseguia de jeito nenhum fazer o texto ficar em cima da imagem.

Seletor: .principal-texto
    Usei a Propriedade background-color com o Valor RGB de 182, 182, 182 para que o fundo/background fique dessa cor selecionada.
    Usei a Propriedade border-style com o Valor solid para fazer uma borda solida em volta dessa CLASS.
    Usei a Propriedade border-width com o Valor de 2.5 pixels para que a grossura da borda fique de 2.5 pixels.
    Usei a Propriedade color com o Valor Black para que o texto dessa CLASS fique preto.
    Usei a Propriedade font-size com o Valor de 30 pixels para que o texto fique com 30 pixels de tamanho.
    usei a Propriedade text-align com o Valor center para que o texto fique alinhado com o centro da pagina.

Seletor: .imagensdisplay 
    Usei a Propriedade display com o Valor block para a imagem ficar no centro, só nao sei porque.
    Usei as Propriedades margin-left e margin-right com o Valor auto para alinhar a imagem com o centro da pagina. (Eu acho.)
    Usei a Propriedade widht com o Valor de 70% para que as imagens dessa CLASS fiquem com 70% da largura da pagina.
    Usei a Propriedade border-style com o Valor solid para criar uma borda solida em volta das imagens.
    Usei a Propriedade border-radius com o Valor de 2 pixels para que a borda tenha um alcance de 2 pixels.

Seletor: q 
    Usei a Propriedade font-style com o Valor italic para que o texto da TAG q fique em italico.
    Usei a Propriedade font-size com o Valor de 33 pixels para que o texto dessa TAG fique com o tamanho de 33 pixels.
    Usei a Propriedade color com o Valor RGB de 43, 43, 43 para que o texto dessa TAG fique com uma cor diferente dos outros textos.

Seletor: footer
    Usei a Propriedade backgound-color com o Valor RGB de 121, 121, 121 para que o fundo/background fique com uma cor diferente do restante do body.
    Usei a Propriedade text-align com o Valor center para que o texto da TAG footer fique alinhado com o centro da pagina.
    Usei a Propriedade border-style com o Valor solid para criar uma borda na TAG foot e dar continuidade na borda que vem da CLASS principal-texto.
    Usei a Propriedade border-widht com o Valor de 2.5 pixels para que a grossura da borda seja de 2.5 pixels e dar continuidade a borda da CLASS principal-texto.


    Essas foram as explicações de como eu usei o HTML e o CSS para fazer o meu primeiro site do zero. Fiquei com muita dúvida no CSS principalmente para entender como
colocar o texto em cima da imagem, eu sinceramente não entendi direito e só copiei o código da W3school, tenho que pesquisar mais. E uma outra dúvida que me surgiu enquanto 
escrevia o README foi na questão dos valores em porcentagem, por exemplo na CLASS imagensdisplay eu usei widht 70% mas eu não tenho certeza se esse 70% é da largura
da página ou se é do elemento pai da CLASS.

