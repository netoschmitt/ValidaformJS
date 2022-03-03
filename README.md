# ValidaformJS
###  Validação de formulario em Javascript puro.
  Criado form em HTML, a validação será em main.js, no evento de 'submit' com um método 'eventos(),
- metodo handlesubmit que recebe este evento, crio o método para verificar se os campos são validos;
-  metodo camposSaoValidos(), crio uma classe validar no html, assim tenho o controle de quais campos
estão sendo validados, checagem, se os campos estão vazios;
- metodo criaErro() - recebe o campo e passa a msgs de erro na div "depois do campo(metodo insetAdjacentElement('afterend');"
- metodo validaCPF() - checa se o cpf é válido de acordo com a class validaCPF https://github.com/netoschmitt/ValidaCPF_JS
- metodo validaUsuario() - verifica a condição de caracteres atravez de expressões regulares *if(!usuario.match(/^[a-zA-Z0-9]+$/g))*
- metodo senhasValidas() - verificação com um metodo aparte senhasSãoValidas(),checa a condição senha e lança seus erros.
- finalizando em *handleSubmit(e)* a verificação se campos e senhas são validos,(flag valid = true),executa o submit do formulario.


Formulário de cadastro
- Nenhum Campo pode estar vazio
- Usuário só poderá conter letras e /ou números
- Usuário deverá ter entre 3 e 12 caracteres
- Senha precisa ter entre 6 e 12 caracteres
