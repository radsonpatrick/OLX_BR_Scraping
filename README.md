<h1 align="center"> 
	🚧  OLX Brasil Scraping 🚀
  Em construção...  🚧
</h1>

## Introdução
Projeto começou com o intuito de aprender  e melhorar as habilidades em  Python,git,jupyter,ETL e analise de dados. ultilizando esse projeto que sempre foi um objetivo para mim faze-lo.

## Objetivo
Visualização e notificação de novos anuncios na plataforma https://olx.com.br  podendo ser filtrado por nome,descrição,palavra-chave,categoria,cidade e entre outras. 
-Notificação por Email e Telegram  podendo ser implementado para mais meios.

## **BUGS**
- Codigo ainda com um bug em escolher a div que contem os estados.intermitente ao encontrar a div

## O que funciona
### Seleção de estado
Seleciona o estado desejado, é possivel selecionar a opção TODOS e assim você buscará em todo o brazil ( não recomendamos pois a diponibilização de anuncios é muito grande)

### Seleção de cidade/região 
Seleciona a cidade/região do estado como é no site original,podendo inserir todas as regiões do estado selecionado 

### Seleção de tipo de anuncio 
Seleciona o tipo de anuncio como particular,proficional ou todos

### Busca por palavra chave
A busca por palavra chave usando o campo busca do site

### Varredura em loop 
A varredura usando o for da pagina 5 a 1 do site,na primeira rodada mostrara todos da pagina 1 como novos, mas nas rodadas seguintes apenas quem inseriu,cada rodada tem que ser feita manualmente.

## O que será implementado
- Correção do Bug da div de estados.
- Pular seleção de cidade/região quando o estado selecionado for TODOS.
- implementar loop para rodar  o tempo ficará a criterio.
- Envio de anuncios pelo Telegram. 
