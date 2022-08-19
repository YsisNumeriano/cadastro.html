# cadastro.html
Foi solicitado pelo professor a criação de uma página para gerenciamento dos seus usuários. Crie uma Página de cadastro (cadastro.html) com um formulário contendo: Nome; E-mail; Data de nascimento; Residência (Casa ou Prédio - checkbox) (Todos com seus input types em html5)  Subsequentemente, foi solicitado que nesta página de cadastro fossem adicionados dois botões:  -> Salvar (na cor verde);  -> Limpar (na cor vermelha)  Por conta das cores da empresa, foi pedido que os input types de textos (input[type=text]) criados tivessem uma borda de 2px solid azul e o background da página cinza (#f3f3f3).


# Discorra sobre o que é doctype e porque o adicionamos em páginas html?
Diferente do que algumas pessoas acham Doctype não é uma tag HTML e sim uma declaração para informar ao navegador qual é a versão do HTML utilizada no documento. Essa declaração vem antes das tags HTML, portanto, geralmente é apresentada na primeira linha de um código. Hoje em dia, todos os navegadores suportam a versão mais nova do HTML que é a versão 5. Sendo assim basta iniciar a declaração usando <!doctype html>.
Porém, a presença do DTD garante que o navegador se comportará adequadamente e de maneira precisa. Quando não informamos o Doctype HTML, o navegador utiliza um recurso chamado de quirks mode, decidindo um padrão a ser seguido. Já quando é feita a declaração, o navegador entra no modo standard. Dessa forma, o navegador seguirá todos as especificações do HTML e do CSS adequadamente.

Além disso, a falta do Doctype HTML, assim como o modo quirks do navegador, pode gerar falhas de vulnerabilidade. A falta desta declaração, mesmo em navegadores mais novos, torna as páginas vulneráveis a ataques como o RPO (Relative path Overwrite), que atua na injeção em folhas de estilos.

Portando, é errado afirmar que o doctype não é obrigatório, pois a própria W3C orienta seu uso. O uso do Doctype HTML é essencial para qualquer documento. Sendo assim, seu uso é obrigatório perante as boas práticas e também para garantir o perfeito funcionamento e a segurança do documento.
