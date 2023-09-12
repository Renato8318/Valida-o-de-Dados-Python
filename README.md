# Valida-o-de-Dados-Python
Validação de Dados no Padrão Nacional.


Durante o Prjeto teste  foi  criado diversas classes com funções diferentes; primeiro, um Documento que será uma factory, um padrão de projeto responsável por decidir se instanciará a DocCpf ou DocCnpj, de acordo com o documento que passaremos para a classe. Depois faremos validação e formatação de número de telefone utilizando expressões regulares,
Em seguida, usaremos a biblioteca datetime e timedelta do Python para fazermos com que as informações de cadastro de usuário sejam salvas e exibidas da forma com que estamos acostumados a ver aqui no Brasil.Também usaremos uma formatação específica da timedelta chamada strftime e alguns métodos para conseguirmos mostrar o dia da semana e meses do ano dentro dos padrões nacionais.Por fim, criaremos a classe BuscaEndereco responsável por formatar e validar CEP, além de acessar uma API ou WebService online em tempo real que enviará o CEP e receberá uma informação serializada do endereço de usuário, contendo informações de ruas, bairros, estados e etc. que possibilitará o envio de boletos aos clientes.
