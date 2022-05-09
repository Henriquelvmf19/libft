Primeiro Projeto da 42 chamado libft,total de 70 horas para realizacão, vamos listar oque o programa pede junto com suas especificações


=================================================
									LIBFT - Minha primeira Biblioteca
=================================================

O projeto visa codar nossa própria biblioteca em C, com varias funções para usos variados, todas as funções serão desenvolvidas por mim e serão utilizadas nos projetos subsequentes

@ INTRODUCÃO

-> Este projeto visa capacitar sobre a maneira como estas funções funcionam, implementando e aprendendo a utiliza-las, vamos criar nossa própria biblioteca, sempre adicione novas funcoes conforme sua evolucão no cursus

A programação em C pode ser muito tediosa quando não se tem acesso ao altamente útil
funções padrão. Este projeto trata de entender como essas funções funcionam,
implementá-los e aprender a usá-los. Você criará sua própria biblioteca. Será
útil, pois você o usará em suas próximas tarefas da escola C.
Aproveite o tempo para expandir sua libft ao longo do ano. No entanto, ao trabalhar
em um novo projeto, não se esqueça de garantir que as funções usadas em sua biblioteca sejam permitidas em
as diretrizes do projeto.

!!! INSTRUÇÕES COMUNS DO PDF !!!

• Seu projeto deve ser escrito em C.
• Seu projeto deve ser escrito de acordo com a Norma. Se você tem bônus arquivos/funções, eles são incluídos na verificação de norma e você receberá um 0 se houver um erro de norma dentro.
• Suas funções não devem ser encerradas inesperadamente (falha de segmentação, erro de barramento, livre, etc) além de comportamentos indefinidos. Se isso acontecer, seu projeto será considerado não funcional e receberá 0 durante a avaliação.
• Todo o espaço de memória alocado no heap deve ser liberado adequadamente quando necessário. Sem vazamentos será tolerado.
• Se o assunto exigir, você deve enviar um Makefile que compilará seu arquivos de origem para a saída necessária com os sinalizadores -Wall, -Wextra e -Werror, use cc, e seu Makefile não deve revincular.
• Seu Makefile deve conter pelo menos as regras $(NAME), all, clean, fclean e ré.
• Para entregar bônus ao seu projeto, você deve incluir um bônus de regra no seu Makefile, que irá adicionar todos os vários cabeçalhos, bibliotecas ou funções que são proibidas na parte principal do projeto. Os bônus devem estar em um arquivo diferente _bonus.{c/h} se o assunto não especifica mais nada. Avaliação obrigatória e de partes bônus é feito separadamente.
• Se seu projeto permite que você use sua libft, você deve copiar suas fontes e seu Makefile associado em uma pasta libft com seu Makefile associado. O seu projeto Makefile deve compilar a biblioteca usando seu Makefile e, em seguida, compilar o projeto.
• Incentivamos você a criar programas de teste para seu projeto, mesmo que este trabalho não terá que ser enviado e não será avaliado. Vai te dar uma chance
para testar facilmente seu trabalho e o trabalho de seus colegas. Você encontrará esses testes especialmente útil durante a sua defesa. De fato, durante a defesa, você é livre para usar seus testes e/ou os testes do colega que você está avaliando.
• Envie seu trabalho para o repositório git atribuído. Apenas o trabalho no repositório git será avaliado. Se o Deepthought for designado para avaliar seu trabalho, isso será feito após as avaliações dos colegas. Se ocorrer um erro em qualquer seção do seu trabalho durante A classificação do Deepthought, a avaliação será interrompida.


|------------------------------------------------|
|Nome do programa: 	libft.a			 |
|Turn in files:	Makefile, libft.h, ft(all).c 	 |
|Makefile:	NAME, all, clean, fclean, re	 |
|External functs:	Detalhes abaixo		 |
|------------------------------------------------|

# Considerações

• É proibido declarar variáveis ​​globais.
• Se você precisar de funções auxiliares para dividir uma função mais complexa, defina-as como estáticas
funções. Dessa forma, seu escopo será limitado ao arquivo apropriado.
• Coloque todos os seus arquivos na raiz do seu repositório.
• É proibido entregar arquivos não utilizados.
• Todos os arquivos .c devem ser compilados com os sinalizadores -Wall -Wextra -Werror.
• Você deve usar o comando ar para criar sua biblioteca. Usando o comando libtool
é proibido.
• Seu libft.a deve ser criado na raiz do seu repositório.

	vamos pensar e colher links, para a pesquisa sempre útil analisar o MAN da função e seu 'source code', para além de entender como prototipar entender como os tipos de dados são tratados e qual o comportamento padrão da função, PROCURAR MAIN'S PARA TESTAR CASOS E CONFERIR O FUNCIONAMENTO DA ORIGINAL E NOSSO PROTOTIPO

vamos recriar algumas funções da Bibliotaca Libc e desenvolver nossa própria biblioteca em C. elas devem reproduzir o mesmo comportamento com unica variacão no nome, tendo o prefixo **ft_** adicionado à frente

- FUNÇÃO -    feita	revisada	main()

• isalpha	OK	!		!
• isdigit	OK	!		!
• isalnum	OK	!		!
• isascii 	OK	!		!
• isprint 	OK	!		!
• strlen 	OK	!		!
• memset 	INTRA	!		!
• bzero		INTRA	!		!
• memcpy 	INTRA	!		!
• memmove 	INTRA	!		!
• strlcpy 	OK	!		!
• strlcat	OK	!		!
• toupper	OK	!		!
• tolower 	OK	!		!
• strchr 	OK	!		!
• strrchr 	OK	!		!
• strncmp 	OK	!		!
• memchr 	INTRA	!		!
• memcmp 	INTRA	!		!
• strnstr 	OK	!		!
• atoi		!	!		!

funções que irão usar o malloc()

- FUNÇÃO -    feita	revisada	main()

• calloc 	INTRA	!		!
• strdup	INTRA	!		!

tembém existem funções adicionais solicitadas pela 42

- FUNÇÃO -    	feita		revisada	main()

• ft_substr	OK		!		!
• ft_strjoin	OK		!		!
• ft_strtrim	OK		!		!
• ft_split	OK		!		!
• ft_itoa	OK		!		!
• ft_strmapi	!		!		!
• ft_striteri	!		!		!
• ft_putchar_fd	!		!		!
• ft_putstr_fd	!		!		!
• ft_putendl_fd	!		!		!
• ft_putnbr_fd	!		!		!
  
FUNÇÕES BONÛS


- FUNÇÃO -   	 	feita		revisada	main()

• ft_lstnew		!		!		!
• ft_lstadd_front	!		!		!
• ft_lstsize		!		!		!
• ft_lstlast		!		!		!
• ft_lstadd_back	!		!		!
• ft_lstdelone		!		!		!
• ft_lstclear		!		!		!
• ft_lstiter		!		!		!
• ft_lstmap		!		!		!

pdf-https://cdn.intra.42.fr/pdf/pdf/50832/en.subject.pdf

*Uma dica útil é utiizar o opensource.apple, nele você observa o código fonte e consegue reproduzir seu comportamento
