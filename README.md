# HTML
## HTML é uma linguagem de marcação utilizada na construção de páginas na Web. Essa linguagem deve ser utilizada unicamente para estruturar o conteúdo das páginas, ou seja, não cabe a ela definir características visuais ou comportamentos.

## TAGS HTML
### As tags são usadas para informar ao navegador a estrutura do site, elas vão ser interpretadas e produzirão assim a estrutura e o conteúdo visual da página.
### Elas são divididas em dois tipos: as que precisam de fechamento e as que não precisam de fechamento. As tags que precisam de fechamento possuem a sintaxe "< tag>" "< /tag>", já as que não precisam de fechamento possuem como estrutura <tag/>.

## ESTRUTURA DE UM DOCUMENTO HTML SIMPLES
### <! DOCTYPE html >
### < html lang="pt-br" >
###  < head >
###    < title>Título da página</title >
###    < meta charset="utf-8" >
 ### < /head >
 ### < body >
 ###   Aqui vai o código HTML que fará seu site aparecer.
 ### < /body >
### < /html >"

### Doctype -  instrução para o navegador e outros programas que podem ler seu site, que o código encontrado ali é um código HTML. 
### HEAD - Contém informações que não são transpostas visivelmente para o usuário/leitor do documento. São dados implícitos, de uso e controle do documento: vinculação com outros arquivos, aplicação de lógica de programação de scripts e metadados.
### BODY - Trata-se do documento em si, ou seja, a informação legível para o usuário/leitor do documento. 


## EXEMPLOS DE TAGS HTML
### 1-class=”…“ – Atribui uma classe ao elemento (uma classe pode ser utilizada para um ou mais elementos);
### 2-id=”…“ – Atribui um id ao elemento (um id deve ser único, ou seja atribuído a um único elemento);
### 3-style=”…” – Permite incluir elementos CSS (estilos) dentro da tag;
### 4-lang=”…” – Define o idioma principal do elemento;
### 5-title=”…” – Define o título do elemento;
### 6-alt=”…” – Define um texto alternativo e, por isso, é muito utilizado em imagens, auxilia nas práticas de SEO;
### 7-hidden – Oculta o elemento;
### 8-align=”…” – Permite definir o padrão de alinhamento desse elemento, como por exemplo: right, center, left e justify;
### 9-width=”…” – Define uma largura para o elemento;
### 10-height=”…” – Define uma altura para o elemento.

## ESTILIZAÇÃO DE TAGS HTML 
### A estilização é feita para modificar no arquivo a imagem do site. Normalmente feita com CSS 




# Estilização com  CSS 
##  CSS é um mecanismo para adicionar estilo a um documento web
## Para cor a sintaxe:
### Color : nome da cor;
## Para tamanho da fonte :
### Font – size : tamanhopx;
## Para o alinhamento: 
### Text – align: tipo de alinhamento;

### Exemplo: 
### < style >
### P { 
### Text – align: center; 
### Font – size: 16px;
### Color : pink; 
### }
### </ style >

## Tipos de modelos de CSS 
### CSS interno 
Código CSS interno é colocado na seção <head> de uma determinada página. As classes e IDs podem ser usados para se referir ao código CSS, mas eles só estão ativos nessa página específica. CSS estilos incorporados desta forma são baixados cada vez que a página carrega para que ele possa aumentar a velocidade de carregamento.

### CSS externo 
Provavelmente a maneira mais conveniente de adicionar CSS ao seu site, é vinculá-lo a um arquivo .css externo. Dessa forma, quaisquer alterações feitas em um arquivo CSS externo serão refletidas em seu site globalmente.

### CSS Inline 
O CSS inline é usado para uma tag HTML específica. O atributo <style> é usado para formatar uma tag HTML específica. Usar CSS desta forma não é recomendado, pois cada tag HTML precisa ser denominada individualmente. 
 
 

# FRAMEWORKS CSS 
## O framework é um facilitador no desenvolvimento de diversas aplicações, e sem dúvida, sua utilização poupa tempo e custos para quem utiliza, pois de forma mais básica, são templates que provém diversas funções que podem ser utilizadas em qualquer projeto e com o resultado bem bacana.

## BOOTSTRAP
### O Bootstrap é um framework desenvolvido pelo Twitter, que traz consigo características bem definidas de inicialização rápida, ou seja, possuem estilos predefinidos (prontos). Com a utilização do Bootstrap é possível a criação de sites responsivos, que são aqueles que se adaptam ao tamanho da tela que estará sendo utilizada pelo usuário.

## MaterializeCSS
### A utilização do MaterializeCSS facilita a criação de interfaces dentro do padrão do material design feito pela Google, que tem como intuito de unificar a experiência do usuário na usabilidade dos seus softwares seja em smartphones, desktops ou tablets.

## Foundation
### o Foundation é um framework que possui como forte característica sua responsividade, sem a necessidade de adicionar classes, facilitando assim a criação de sites, aplicativos e muito mais.

## Semantic UI
### O Semantic UI utiliza as tecnologias jQuery e LESS, tornando a criação de aplicações com o HTML conciso, o JavaScript intuitivo e um debug simplificado.
### Utilizando o Semantic UI é possível a criação de layouts agradáveis para o usuário final, além de design responsivo. O uso do framework suporta animações 3D e fornece uma variedade de componentes de interface do usuário, repleto de recursos como a inclusão de um estado “desativado” a imagens e ícones que podem ser formatados com diferentes tamanhos e cores.



