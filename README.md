# Rubeus_teste_tecnico

Segue minhas observações sobre os dois sites propostos no teste técnico:

1. Certificação: [https://qualidade.apprbs.com.br/certificacao](https://qualidade.apprbs.com.br/certificacao)
2. Site: [https://qualidade.apprbs.com.br/site](https://qualidade.apprbs.com.br/site)

Resolvi criar esse repositório mesmo não realizando testes automatizados, pois o formulário de envio no site atingiu o limite máximo de caracteres. Fico à disposição para um bate-papo, segue minhas observações:

#Link 1 - Certificação: [https://qualidade.apprbs.com.br/certificacao](https://qualidade.apprbs.com.br/certificacao):

Item 01 - Botão "Saiba mais" inacessível.
Tipo: Correção.
Classificação: Utilidade.
Prioridade: Média.
Descrição: Na página inicial (1 bloco - Faculdade Exemplo), não foi possível clicar no botão saiba mais para o usuário obter mais informações.

Item 02 -  Texto dos parágrafos e títulos desalinhados e fora de formação.
Tipo: Melhoria.
Classificação: Desejabilidade.
Prioridade: Baixa.
Descrição: Na página inicial (2 bloco - Lorem Ipsum), os parágrafos ao lado do formulário estão formatados incorretamente (desalinhados e com espaçamento incorreto). Os títulos também estão com um "padding" muito grande e desalinhados em relação ao restante dos parágrafos.

Item 03 - Imagem com "aspect ratio" incorreto.
Tipo: Melhoria.
Classificação: Desejabilidade.
Prioridade: Baixa.
Descrição: Na página inicial (2 bloco - Lorem Ipsum), a imagem exibida do "consultor" está com as propriedades (aspect ratio) incorretas, o que torna a experiência do usuário desagradável

Item 04 - Formulário não tem o funcionamento esperado.
Tipo: Correção.
Classificação: Utilidade.
Prioridade: Alta.
Descrição: Na página inicial (2 bloco -Lorem Ipsum), mesmo após inserir dados reais e válidos, o formulário não é enviado ao sistema. E a mensagem de erro exibida  ( "É necessário informar a base legal") não explica onde está o erro e torna o feedback e a experiência do usuário desagradável.

Item 05 - Textos e colunas desalinhadas e com espaçamentos diferentes.
Tipo: Melhoria.
Classificação: Desejabilidade.
Prioridade: Baixa.
Descrição: Na página inicial (3 bloco), vemos que os textos estão desalinhados, descentralizados, com conteúdos desiguais, margens incorretas e altura de texto incorreta. Importante revisar: margin-top, line-height e justify.

Item 06 - Containers iguais de larguras diferentes.
Tipo: Melhoria.
Classificação: Desejabilidade.
Prioridade: Baixa.
Descrição: Na página inicial (5 bloco - Lorem Ipsum), nota-se que os containers estão com larguras diferentes. O 5 container (2 da 2 linha) está com a quebra de linha de forma diferente e a imagem está "achatada".

Item 07 - Imagens "cortadas" nos cards "saiba mais"
Tipo: Melhoria.
Classificação: Desejabilidade.
Prioridade: Baixa.
Descrição: Na página inicial (6 bloco - "Outros cursos"), as imagens dos containers (2 e 3) estão cortadas - possivelmente problema no "object-fit". 

Item 08 - Textos dos containers de saiba mais estão com erros de ortografia.
Tipo: Melhoria.
Classificação: Desejabilidade.
Prioridade: Baixa.
Descrição: Na página inicial (6 bloco - "Outros cursos", os containers 1 e 3 estão com erros de ortografia no botão "saiba mais". Faltando palavras e palavras escritas de forma errada.

Item 09 - Botão de saiba mais não é clicável e não redireciona o usuário.
Tipo: Correção.
Classificação: Usabilidade.
Prioridade: Média.
Descrição: Na página inicial (6 bloco - "Outros cursos"), os botões de "saiba mais", não são clicáveis e não redirecionam o usuário para nenhum endereço para obter mais informações. Possivelmente faltando o atributo "href" e estilização do botão.

Item 10 - Botão de quero me certificar redirecionando para o endereço incorreto
Tipo: Correção.
Classificação: Usabilidade.
Prioridade: Alta.
Descrição: Na página inicial (7 bloco - "Quero me certificar"), o botão "quero me certificar" redireciona o usuário para o endereço incorreto: "https://www.google.com/". Gentileza verificar atributo "href" do botão.

Item 11 - Botão da rede social Youtube redireciona para o Tiktok.
Tipo: Correção.
Classificação: Usabilidade.
Prioridade: Alta.
Descrição: Na página inicial (Footer), o botão que deveria redirecionar para o youtube (https://www.youtube.com/@Rubeus), redireciona para outra rede social - tiktok (https://www.tiktok.com/@rubeusoficial). Gentileza verificar o atributo "href" do botão que possivelmente está com endereço incorreto.

#Link 2 - Site: [https://qualidade.apprbs.com.br/site](https://qualidade.apprbs.com.br/site):

Item 01 - Botão Atendimento redirecionando para o whatsapp ao invés de atendimento por telefone.
Tipo: Correção
Classificação: Usabilidade.
Prioridade: Alta.
Descrição: Na página inicial (header), o botão que deveria redirecionar para o antendimento, redireciona para o whatsapp (sendo que já estive um botão dedicado a isso)

Item 02 - Botão do whatsapp redireciona apenas para o aplicativo, sem redirecionar diretamente para o contato do atendente.
Tipo: Correção
Classificação: Usabilidade
Prioridade: Média.
Descrição: Na página inicial (header), o botão que deveria redirecionar a conversa do whatsapp direto no contato, redireciona apenas para o aplicativo do whatsapp. Faltando parametro informando o numero para redirecionamento correto.

Item 03 - Textos com alinhamento incorreto nos cards.
Tipo: Melhoria.
Classificação: Desejabilidade.
Prioridade: Baixa.
Descrição: O texto nos cards está sendo exibido de uma maneira bem descentralizada. Possível ajuste no atributo "justify" ou "text-align".

Item 04 - Parágrafo desalinhado (próximos eventos).
Tipo: Melhoria.
Classificação: Desejabilidade.
Prioridade: Baixa.
Descrição: Na parte de "próximos eventos", o parágrafo está com uma formatação incorreta e desalinhado. Gentileza revisar as propriedades "text-align/justify".

Item 05 - Formulário não tem o funcionamento esperado.
Tipo: Correção.
Classificação: Utilidade.
Prioridade: Alta.
Descrição: Na página inicial (area "não fique de fora"), mesmo após inserir dados reais e válidos, o formulário não é enviado ao sistema. E a mensagem de erro exibida ("É necessário informar a base legal") não explica onde está o erro e torna o feedback e a experiência do usuário desagradável.

Item 06 - Textos desalinhados (parágrafo próximos eventos)
Tipo: Melhoria.
Classificação: Desejabilidade.
Prioridade: Baixa.
Descrição: Na página inicial (Próximos eventos) o parágrafo se encontra

Item 07 - Textos desalinhados no footer (Todos os direitos reservados)
Tipo: Melhoria.
Classificação: Desejabilidade.
Prioridade: Baixa.
Descrição: Na página inicial (footer), os textos de rodapé estão desalinhados. Possívelmente, propriedade justify está incorreta.
