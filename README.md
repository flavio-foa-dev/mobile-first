# mobile-first

- Acessar e visualizar o projeto no Figma;
- Captar informações como as cores dos elementos no Figma;
- Começar a construir um projeto HTML;
- Criar variáveis CSS;
- Aplicar o reset.css.
- Baixar imagens no Figma;
- Construir um header;
- Transformar elementos em flex-containers e flex-items com FlexBox;
- Associar arquivos CSS através do @import;
- Desenvolver um menu hambúrguer interativo com HTML e CSS;
- Position relative e absolute;
- Importar e usar fontes do google fonts;
- Criar sections;
- Editar input e seu placeholder.
- Aplicar plugins externos através de CDN;
- Utilizar o plugin SwiperJS para criar um carrossel;
- flexbox;
- Reutilizar elementos e estilos;
- ul e li;
- Editar input e seu placeholder.
- Usar media queries;
- Aplicar diferentes estilos para diferentes tamanhos de tela;
- Retirar elementos da tela;
- Aplicar elementos na tela de acordo com o tamanho do dispositivo.
- Aplicar estilos com media queries diferentes;
- Usar estilos diferentes no mesmo elemento com pseudo-classes.
- Construir um repositório com o código do curso;
- Escrever commits;
- deploy;
- projeto em outros dispositivos.


projeto nos esbarramos nas pseudo-classes :hover e :checked
-  Pseudo-classe  Descrição	                                                        Exemplo
- :active	        Link que está ativo.	                                            Um link sendo clicado.
- :disabled	      Elemento desativado.	                                            Um input que não pode ser preenchido.
- :focus	        Elemento recebendo foco ao ser selecionado por mouse ou teclado.	Campo de um formulário.
- :link	          Cor dos links.	                                                  Tag <a> em geral.
- :visited	      Cor dos links que já foram visitados.	                            É utilizado em tags <a> mas só aparecem quando já foram clicadas.


Também ao editar os inputs da página usamos outra coisa com estrutura semelhante: o ::placeholder. Mesmo que comece com dois pontos (e dessa vez repetidos) ele é um pseudo-elemento, uma palavra-chave adicionada a um seletor que especifica uma parte do elemento selecionado



### Combinador	Descrição	Exemplo de uso
- +	Seleciona elementos que estão logo após o elemento especificado antes do símbolo.	.container__botao + container__rotulo
- ~	Seleciona elementos que estão após (mas não necessariamente em seguida) o elemento especificado antes do símbolo.	container__botao ~ .container__rotulo
- >	Seleciona elementos que estão dentro do elemento especificado antes do símbolo.	.container__rotulo>.cabeçalho__menu-hamburguer