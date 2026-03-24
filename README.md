# Análise do Mercado de Airbnb no Rio de Janeiro

Projeto de análise exploratória de dados utilizando informações públicas da plataforma Airbnb, disponibilizadas pelo projeto Inside Airbnb.

O objetivo deste projeto é analisar o mercado de hospedagem de curto prazo na cidade do Rio de Janeiro, identificando padrões de preço, distribuição geográfica dos imóveis e características estruturais do mercado.

---

# Objetivos da análise

Este projeto busca responder algumas perguntas centrais:

* Quais bairros possuem maior concentração de anúncios?
* Quais regiões possuem os preços médios mais elevados?
* Como o tipo de acomodação influencia o preço?
* Como os anúncios estão distribuídos geograficamente?

---

# Dataset

Os dados utilizados foram obtidos do projeto Inside Airbnb, que disponibiliza datasets públicos com informações detalhadas sobre anúncios da plataforma.

O dataset contém informações como:

* identificação do anúncio
* nome do imóvel
* localização (bairro e coordenadas)
* tipo de acomodação
* preço da diária
* número de avaliações
* disponibilidade anual
* número mínimo de noites

---

# Estrutura do dataset

O conjunto de dados analisado possui:

* 43.068 anúncios
* 18 variáveis

Principais variáveis utilizadas:

price              
neighbourhood      
room_type       
minimum_nights      
number_of_reviews  
availability_365   
reviews_per_month   

---

# Tecnologias utilizadas

* Python
* Pandas
* Matplotlib
* Seaborn
* Folium

---

# Imagens
<img width="1382" height="831" alt="01" src="https://github.com/codelibet/analise-airbnb-rio/blob/main/images/image1.png"/>
<img width="1382" height="831" alt="01" src="https://github.com/codelibet/analise-airbnb-rio/blob/main/images/image2.png"/>
<img width="1382" height="831" alt="01" src="https://github.com/codelibet/analise-airbnb-rio/blob/main/images/image3.png"/>
<img width="1382" height="831" alt="01" src="https://github.com/codelibet/analise-airbnb-rio/blob/main/images/image4.png"/>



---

# Resultados e interpretação dos dados

## Concentração de anúncios

Os dados mostram forte concentração em poucos bairros:

* Copacabana: 11.968 anúncios
* Ipanema: 3.289
* Barra da Tijuca: 3.166

Isso indica um mercado altamente centralizado, com predominância em regiões turísticas. A concentração sugere alta concorrência local e dependência direta da demanda turística.

---

## Estrutura de preços

Estatísticas principais:

* média: R$ 497
* mediana: R$ 313
* desvio padrão: R$ 568

A média superior à mediana indica uma distribuição assimétrica, com presença de valores elevados que distorcem a média.

A maior parte dos imóveis está concentrada aproximadamente entre R$ 200 e R$ 500, enquanto valores acima disso pertencem a um segmento mais restrito.

---

## Bairros mais caros

Principais bairros por preço médio:

* Anchieta: R$ 2.531
* Joá: R$ 1.454
* São Conrado: R$ 952
* Lagoa: R$ 860
* Leblon: R$ 764

Alguns bairros apresentam médias elevadas devido a baixa quantidade de imóveis, o que distorce o resultado. Já bairros como Leblon, Lagoa e São Conrado representam regiões premium consolidadas.

---

## Tipo de acomodação

Preço médio por tipo:

* hotel room: R$ 619
* imóvel inteiro: R$ 545
* quarto privado: R$ 305
* quarto compartilhado: R$ 141

Existe uma relação direta entre preço e nível de privacidade. Imóveis inteiros são significativamente mais caros, enquanto quartos compartilhados representam o segmento econômico.

---

## Distribuição geográfica

A distribuição espacial dos anúncios mostra forte concentração na Zona Sul e regiões próximas ao litoral.

Isso indica que o mercado segue a lógica tradicional do turismo, com maior densidade em áreas com infraestrutura e atratividade.

---

## Impacto dos outliers

Mesmo após a remoção de valores extremos acima de 5000, ainda há grande variação nos preços.

Isso evidencia a existência de um segmento de luxo que influencia significativamente as métricas agregadas.

---

## Estrutura do mercado

Com base nos dados, o mercado pode ser caracterizado como:

* concentrado em poucos bairros
* desigual em termos de preços
* segmentado por tipo de acomodação
* dependente da localização

---

# Conclusão

O mercado de Airbnb no Rio de Janeiro apresenta uma estrutura altamente concentrada e orientada por localização. O preço dos imóveis está diretamente relacionado à região e ao tipo de acomodação, enquanto a oferta acompanha a demanda turística.

A plataforma não altera a lógica urbana existente, mas a reproduz, concentrando valor e oferta nas mesmas regiões já valorizadas da cidade.

---

