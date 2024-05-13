## Sobre JavaScript (oq eu acho q aprendi):
- Linguagem de alto nível;
- Tipagem dinâmica e fraca;
- A linguagem nativa da web;
- Cada browser tem seu motor (uma espécie de interpretador) JavaScript (Chrome: V8, Firefox: Spidermonkey e por aí vai);
- Multiparadigma, podendo ser OO para construção de aplicativos robustos, tais como aplicações android; imperativo, para controle de eventos do DOM. Em geral, O JS também pode seguir outros paradigmas;
- Ao acessar o DOM (objeto document), o JS pode modificar as tags e o estilo de uma página, através da inserção de classes IDs ou até mesmo inserção ou remoção de um atributo das tags;

### Sobre a objeto 'window':
O objeto window representa a janela atual do navegador e fornece acesso a várias funcionalidades e objetos importantes, como o DOM (Modelo de Objeto de Documento), objetos globais, métodos para manipulação da janela, manipulação de eventos, e muito mais.

Em termos de hierarquia, window é considerada a propriedade pai de todo o ambiente de execução JavaScript no navegador. Todos os objetos globais, funções e variáveis que são definidos no escopo global em um documento HTML são, na verdade, propriedades do objeto window. Isso inclui não apenas objetos e funções padrão do JavaScript, mas também objetos e funções específicos do navegador.

Em relação ao DOM, o objeto window também possui uma propriedade chamada document, que representa o DOM do documento atualmente carregado na janela do navegador. Por exemplo, window.document é uma referência para o DOM, permitindo que você manipule elementos HTML e outros aspectos do documento.

Em resumo, window é o objeto global no navegador JavaScript e atua como o ponto de entrada para acessar muitas funcionalidades essenciais do navegador, incluindo o DOM e muitas outras APIs do navegador.

#### Alguns comandos (funções) deste objeto:
    window.alert();

Wuando você usa window.alert(), você está chamando o método alert() que é uma propriedade do objeto window. O alert() é usado para exibir uma caixa de diálogo com uma mensagem para o usuário, você pode omitir o prefixo window caso queira, mas por questões didáticas, eu irei manter este prefixo para facilitar a compreensão do JavaScript.

    window.confirm();

Assim como o alert(), o confirm() executa um evento exibindo uma caixa de diálogo na janela atual e, intuitivamente, a depender do botão que foi clicado, retorna true ou false.

    window.prompt();

Este evento carrega uma caixa de diálogo que exibe um campo de entrada de uma string onde o usuário deve digitar o texto.

