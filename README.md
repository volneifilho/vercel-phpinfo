# Vercel PHP Info

Este repositório hospeda uma aplicação PHP mínima com uma página `phpinfo()`, pronta para ser implantada na camada gratuita da Vercel. A função principal desta aplicação é fornecer informações úteis sobre o ambiente Vercel para programadores PHP que utilizam esta plataforma. Além disso, serve como um exemplo simples e prático de como executar código PHP na Vercel, funcionando como uma espécie de boilerplate para projetos PHP.

![Demo](https://phpinfo.vercel.app/)

## Demonstração

Uma demonstração ao vivo pode ser encontrada em: [https://phpinfo.vercel.app/](https://phpinfo.vercel.app/)

## Como Usar

1. Clique no botão abaixo para clonar este repositório e implantá-lo na Vercel:

   [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fvolneifilho%2Fvercel-phpinfo)

2. Ou clone o repositório manualmente e implante-o com o CLI da Vercel:

   ```bash
   git clone https://github.com/volneifilho/vercel-phpinfo.git
   cd vercel-phpinfo
   vercel
   ```
## Estrutura do Projeto

Este projeto consiste em dois arquivos principais:

- `/api/phpinfo.php`: Este arquivo contém um script PHP simples que chama a função `phpinfo()`, gerando uma página com informações sobre a configuração do PHP no ambiente Vercel.
- `vercel.json`: Este arquivo de configuração dirige o Vercel sobre como tratar as requisições e executar arquivos PHP neste projeto.

## Contribuindo

Sinta-se à vontade para clonar, modificar e reutilizar este projeto. Se você encontrar algum problema ou tiver alguma melhoria, sinta-se à vontade para abrir uma Issue ou um Pull Request.

## Licença

[MIT](LICENSE)

