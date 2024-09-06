# POO-Desafio
Essa aplicação e referente ao desafio do Bootcamp Claro - Java com Spring Boot da Dio.

classDiagram
    Iphone <|-- ReprodutorMusical
    Iphone <|-- AparelhoTelefônico
    Iphone <|-- NavegadorDeInternet
    Iphone : +String numero
    Iphone : +String musica
    Iphone : +String url
    class ReprodutorMusical{
      +tocar()
      +pausar()
      +selecionarMusica(String musica)
    }
    class AparelhoTelefônico{
        +ligar(String numero)
        +atender()
        iniciarCorreioVoz()
      
    }
    class NavegadorDeInternet{
      +exibirPagina(String url)
      +adicionarNovaAba()
      +atualizarPagina()
    }
