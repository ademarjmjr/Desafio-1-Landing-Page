# Desafio-1-Landing-Page
Pagina para captação de clientes de arquitetura.

README
Descrição do Projeto

Esta é uma landing page desenvolvida para uma empresa de arquitetura que se especializa em projetos residenciais e comerciais. A página destaca a tradição e experiência da empresa e convida os visitantes a conhecerem mais sobre seus serviços.

Estrutura do Projeto

Arquivos e Diretórios

index.html: Arquivo principal HTML que estrutura a página.
css/estilo.css: Arquivo CSS que contém os estilos para a página.
img/image.png: Imagem usada na seção de conteúdo para ilustrar os projetos da empresa.

Dependências Externas

Google Fonts:
Inter: Utilizada para a tipografia geral.
Raleway: Utilizada para variação de tipografia, fornecendo uma aparência mais moderna e clean.

Estrutura HTML

Cabeçalho (Header)
Título (h1): "Tradição em projetos de arquitetura"
Parágrafo (p): "Arquitetura residencial e comercial."

Corpo Principal (Main)

Seção de Informações
Empreendimentos construídos: 850
Anos de mercado e experiência: 40
Metros quadrados construídos: 2,000,000m²

Seção de Conteúdo
Texto:
Título (h3): "Arquitetos com História e Experiência."
Parágrafo (p): Descrição da trajetória da empresa desde 2002.

Foto: Imagem representando os projetos da empresa.

Seção de Formulário
Título (h4): "Conheça mais sobre nossos serviços:"

Formulário:
Campos para nome e e-mail.
Botão para enviar os dados.

Estilos (CSS)

Reset Básico

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

Configuração do Corpo
body, html {
    font-family: "Inter", sans-serif;
    background-color: #f4f4f4;
    color: #333;
    height: 100%;
    margin: 0;
    padding: 0;
}

Estilo do Cabeçalho
header {
    height: 430px;
    text-align: left;
    padding: 20px;
    background-color: #303030;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

#h1-cabecalho {
    font-size: 60px;
    margin-top: 168px;
    margin-bottom: 30px;
    margin-left: 62px;
    font-weight: 600;
    line-height: 72px;
    letter-spacing: -4.9px;
    color: #FFFFFF;
}

#p-cabecalho {
    font-size: 20px;
    font-weight: 500;
    line-height: 28px;
    color: #FFFFFF; 
    margin-left: 62px;   
}

Estilo do Main
main {
    padding: 0px;
}

Estilo das Informações
.info {
    width: 100%;
    height: auto;
    background-color: #F9F9F9;
    display: flex;
    padding-left: 75px;
    padding-right: 100px;
    margin-bottom: 45px;
}

.info div {
    padding-top: 76px;
    margin-left: 98px;
    text-align: left;
}

.info h2 {
    font-size: 35px;
    font-weight: 600;
    color: #000;
    line-height: 28px;
}

.info span {
    font-size: 20px;
    font-weight: 400;
    line-height: 28px;
    text-align: left;
}

Estilo do Conteúdo
.conteudo {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: center;
    padding-right: 60px;
}

.texto {
    flex: 1 1 400px;
    margin: 75px;
}

.foto {
    width: 410px;
    height: 605px;
}

.texto h3 {
    font-size: 40px;
    font-weight: 500;
    line-height: 35px;
    text-align: left;
    letter-spacing: -2px;
    padding-bottom: 60px;
}

#conteudo-paragrafo {
    font-size: 24px;
    font-weight: 300;
    line-height: 26px;
    text-align: left;    
    color: #000;
}

.foto img {
    max-width: 100%;
    height: auto;
    border: 0;
    border-radius: 8px;
}

Estilo do Formulário
.formulario {
    width: 100%;
    height: 638px;
    background-color: #303030;
}

h4 {
    font-size: 32px;
    font-weight: 700;
    line-height: 48px;
    text-align: center;
    color: #FFFFFF;
    padding-bottom: 72px;
    padding-top: 90px;
}

form {
    text-align: center;
    justify-content: center;
}

input {
    width: 508px;
    height: 72px;
    border-radius: 10px;
    border: 0;
    margin-bottom: 68px;
    padding-left: 20px;
    font-family: "Raleway", sans-serif;
    font-size: 24px;
    font-weight: 700;
    line-height: 30px;
    text-align: left;
}

button {
    width: 286px;
    height: 74px;
    border-radius: 10px;
    border: 0;
    background-color: #C07212;
    cursor: pointer;
    font-family: "Raleway", sans-serif;
    font-size: 30px;
    font-weight: 700;
    line-height: 30px;
    text-align: center;
    color: #FFFFFF;
    margin-top: 10px;
}

Responsividade
Para Dispositivos com Largura Máxima de 1040px
@media (max-width: 1040px) {
    .conteudo {
        flex-direction: column;
        margin-left: 100px;
    }
    
    .texto, .foto {
        flex: 1 1 100%;
        padding-bottom: 40px;
    }
}

Para Dispositivos com Largura Máxima de 920px
@media (max-width: 920px) {
    .info {
        width: 100%; 
        padding: 0;
        margin: 0;
        flex-direction: column;
    }
}

Para Dispositivos com Largura Máxima de 768px
@media (max-width: 768px) {
    .info div {
        flex-direction: column;
        padding-bottom: 2px;
        padding-right: 0;
        padding-left: 0;
        margin: 0;
        text-align: center;
    }
    
    .conteudo {
        padding-top: 50px;
        flex-direction: column;
    }
    
    .texto, .foto {
        width: 90%;
        margin: 0;
        padding: 0;
        padding-bottom: 30px;
    }
    
    #h1-cabecalho {
        font-size: 35px;
        line-height: 35px;
        letter-spacing: 1px;
    }
    
    #p-cabecalho {
        font-size: 20px;
    }

    input {
        width: 90%;
    }
}
Para Dispositivos com Largura Máxima de 480px
@media (max-width: 480px) {
    main {
        padding-top: 30px;
    }

    .info div {
        width: 90%;
        flex: 1 1 100%;
        text-align: center;
        margin: 0;
        padding: 0;
    }

    h2 {
        padding-bottom: 20px;
    }

    .texto h3 {
        font-size: 1.5rem;
    }

    #conteudo-paragrafo {
        font-size: 0.9rem;
        width: 280px;
    }

    .conteudo {
        width: 100%;
        margin: 0;
        flex-direction: column;
        padding-right: 0;
        padding-left: 0;
        padding-top: 40px;
    }

    .foto {
        width: 90%;
    }

    input {
        width: 90%;
    }
}

Como Utilizar
Visualização Local:

Abra o arquivo index.html em um navegador para visualizar a landing page.
Modificações:

Edite o arquivo css/estilo.css para alterar os estilos conforme necessário.
Substitua a imagem em img/image.png por uma imagem adequada aos seus projetos.
Formulário:

O formulário está configurado para enviar dados para uma API ou um serviço de e-mail. Configure o backend conforme necessário.
Autor
Nome: [Ademar José Martins Junior.]
Contato: [martinsdomsn@hotmail.com]
GitHub: [https://github.com/ademarjmjr]

Licença
Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE para obter mais informações.

