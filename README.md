Este projeto foi desenvolvido como forma de praticar e aprimorar meus estudos em desenvolvimento web e design de interfaces. Aqui, busco aplicar na prática conceitos de HTML, CSS e estruturação visual, criando uma experiência agradável, funcional e alinhada à identidade da marca. Cada detalhe foi pensado para melhorar minhas habilidades e entregar um trabalho cada vez mais profissional.

1. Reset Geral
*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}


Isso remove espaçamentos padrão que o navegador coloca automaticamente e deixa a medição dos elementos mais precisa usando box-sizing.

2. Configurações do Body
body {
    background-color: #b6ae9f;
    color: #19183b;
    text-align: center;
}


Define o fundo da página (background-color)

Cor geral do texto (color)

Centraliza textos por padrão (text-align:center)

3. Logo
.seção_logo {
    text-align: left;
}

#imagem_logo {
     width: 50px;
     border-radius: 20px;
}


A logo fica alinhada à esquerda.

A imagem recebe arredondamento e tamanho reduzido.

4. Cabeçalho / Menu
.seção_cabeçalho {
    text-align: center;
    padding-bottom: 20px;
}
.link_cabeçalho {
    padding: 10px;
    margin: 6px;
    text-decoration: none;
    font-size: 16px;
    font-weight: 700;
    color: #000000;
}
.link_cabeçalho:hover {
    color: #f4f4f4;
}


Links são organizados no centro.

Sem sublinhado (text-decoration: none).

Ao passar o mouse, a cor muda.

5. Título Principal
.seção_titulo {
    padding: 15px;
    margin: 10px;
}
h1 {
    font-size: 24px;
    font-weight: 800;
    font-style: italic;
}
.texto_titulo {
    font-size: 20px;
}


Define espaçamento, tamanho e estilo da fonte para título e texto de apresentação.

6. Seção da Capa
.seção_capa {
    background-image: url("./img/capa.jpg.jpeg");
    background-position:  center top; 
    background-repeat: no-repeat;
    background-size: cover;
    border-radius: 20px;
    opacity: 85%;
    height: calc(180vh - 90px);
}


Define uma imagem como fundo ocupando toda a área (cover).

opacity:85% deixa a imagem levemente transparente.

border-radius arredonda as bordas.

7. Seção de Serviços
.catalago_serviços {
    display: inline-flex;
    align-items:center;
    gap: 12px;
}
.moveis {
    width: 400px;
	overflow-x: scroll;
    white-space: nowrap;
}


inline-flex coloca tudo na mesma linha.

gap cria espaço entre os itens.

.moveis define tamanho das imagens.

8. Localização (Google Maps)
iframe{
    width: 800px;
    height: 600px;
    border-radius: 15px;
}


Deixa o mapa grande e com cantos arredondados.

9. Formulário de Contato
.form-contato {
    max-width: 420px;
    margin: 30px auto;
    padding: 20px;
    background: #ffffff;
    border-radius: 12px;
    box-shadow: 0px 0px 15px rgba(0,0,0,0.1);
}


Centraliza o formulário

Fundo branco

Bordas arredondadas

Sombra suave para dar destaque

Inputs:

.form-contato input,
.form-contato textarea {
    width: 100%;
    padding: 12px;
    border-radius: 8px;
    outline: none;
}
.form-contato button {
    background: #0099ff;
    color: #fff;
}


Campos ocupam toda a largura disponível.

Botão azul com efeito hover.

10. Barra de Rolagem Personalizada
::-webkit-scrollbar {
	width: 15px;
	height: 10px;
}
::-webkit-scrollbar-thumb {
	border-radius: 10px;
	background-color: #888888;
}


Isso personaliza o scroll da página (funciona principalmente no Chrome).

✅ Resumo

O CSS está organizado para:

Manter visual moderno

Centralizar conteúdo

Deixar tudo harmonioso

Criar destaque com imagens grandes e sombras suaves

Se quiser, posso:
✔ Melhorar layout da seção de serviços
✔ Deixar o menu fixo no topo
✔ Adaptar para celular (responsividade)
