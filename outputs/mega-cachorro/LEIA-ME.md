# Mega Cachorro

Landing page estática, sem dependências, fontes externas, cookies, analítica ou JavaScript de execução. A pasta `dist` contém o website completo e pode ser publicada em qualquer alojamento estático.

## Editar informação

Abra `dist/index.html` num editor de texto. Procure `EDITAR TELEFONE`, `EDITAR EMAIL` e `EDITAR HORÁRIO`. Os comentários indicam onde colocar os dados confirmados. Nenhum contacto, horário, preço ou menu foi inventado. Ao confirmar contactos e horário, pode também acrescentá-los aos dados estruturados JSON-LD.

O botão Maps pesquisa o nome e a morada fornecidos; o endereço partilhado do Google não pôde ser validado. Não foram usadas fotografias de terceiros.

## Publicar num domínio próprio

1. Escolha um alojamento estático e envie o conteúdo de `dist` para a raiz pública.
2. Ligue o domínio que possui ao alojamento, seguindo os registos DNS indicados pelo fornecedor.
3. Ative o certificado TLS/HTTPS e o redirecionamento de HTTP para HTTPS. O certificado é emitido pelo alojamento; não está incluído nos ficheiros HTML.
4. Em `index.html`, no comentário DOMÍNIO, adicione `<link rel="canonical" href="https://SEU-DOMINIO/">` e `<meta property="og:url" content="https://SEU-DOMINIO/">`, substituindo pelo domínio definitivo. Acrescente o mesmo URL à propriedade `url` do JSON-LD, se desejar.
5. Verifique o acesso público sem sessão iniciada, o certificado, o botão Maps e os dados da empresa.

O site inclui título, descrição, idioma português, Open Graph, dados estruturados Restaurant e robots.txt. Não existe sitemap porque há apenas uma página. O monograma MC é tipográfico, não um logótipo oficial fornecido.

Não foi indicado nem configurado um domínio próprio. Uma eventual pré-visualização privada Sites não substitui a publicação pública no domínio da empresa. A aceitação na verificação da organização depende dos requisitos da entidade verificadora.
