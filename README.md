# HTML5

É uma linguagem de marcação que tem as seguintes responsabilidades:

- Conteúdo;
- Semântica (tags);
- Estrutura;

## Elementos HTML

Esta página lista todos os elementos HTML. Eles são agrupados por função para ajuda-lo a achar o que quer fácilmente.

### Elementos básicos

Elementos básicos são o que constituem a base de todo documento HTML. Esses elementos estão presentes no código fonte de todas as páginas da web, logo em seguida da declaração de doctype, que está na primeira linha da página.

- `<!DOCTYPE>`

Ela não é um tag, é uma instrução para o navegador saber em que versão do HTML está o arquivo. Essa instrução deve vir primeiro lugar, antes de qualquer tag.

```
<!DOCTYPE html>
<html lang="pt-BR">
   //código html aqui
</html>
```

Se utilizarmos dessa forma estamos usando a última versão do HTML, que no momento é a 5.

- `<html>`

Representa a raiz do nosso HTML. Todos os outros elementos devem ser descentes desse elemento.

### Metadados

Os metadados são onde guardamos várias informações sobre a página, incluindo informações sobre estilos, scripts e dados para auxiliar software (ferramentas de pesquisa, navegadores, etc) usar e renderizar a página.

- `<head>`

Representa a coleção de metadados para o documento, incluindo seu título e links para scripts e folhas de estilos.

```
 <head>
    <meta charset="UTF-8" />
    <title>Loja Fone</title>
  </head>
```

- `<link>`

Especifica as relações entre o documento e um recurso externo. Este elemento é mais usado para vincular as folhas de estilo.

- `<meta>`

Define qualquer informação de metadados que não podem ser definidos por outros elementos HTML, ( `<link>`, `<script>`, `<style>` ou `<title>`).

- `<style>`

Contém infomações de estilo para um documento ou parte do documento. As informações de estilo específico são contidas dentro deste elemento.

- `<title>`

Define o título do documento, mostrado na barra de título do navegador ou na aba da página, lembrando que cada navegador decide o local e forma de como será exibido.

### Separação de Conteúdo

- `<header>` - Cabeçalho

Pode conter alguns elementos de cabeçalho mas também outros elementos como um logo, seções de cabeçalho, formulário de pesquisa, e outros.

```
<header>
    <nav>
    <h1>Logo</h1>
    <a href="http://collabcode.training">Produtos</a>
    <a href="http://collabcode.training">Serviços</a>
    <a href="http://collabcode.training">Carrinho (10)</a>
    </nav>
</header>
```

- `<h1>, <h2>, <h3>, <h4>, <h5> e <h6>`

Representam seis níves de título de seção, `<h1>` é o mais importante e `<h6>` é o de menor importância.

- `<nav>` - Navegação
  Representa um seção da página que aponta para outras páginas ou para outras áreas da própria página.

```
<nav>
    <h1>Logo</h1>
    <a href="http://collabcode.training">Produtos</a>
    <a href="http://collabcode.training">Serviços</a>
    <a href="http://collabcode.training">Carrinho (10)</a>
</nav>
```

### Semânticas textuais inline

- `<a>` - Link ou Âncora

Define uma hiperligação (hyperlink), o destino de uma hiperligação, ou ambos.
Você pode utilizar essa tag em conjunto com alguns atributos.

```
<a href="http://www.collabcode.training">CollabCode.Training</a>
```

# CSS

CSS (Cascading Style Sheets ou Folhas de Estilo em Cascata) é uma linguagem de estilo usada para descrever a apresentação de um documento escrito em HTML. O CSS descreve como elementos são mostrados na tela.

Ela possui as seguintes responsabilidades:

- Visual;
