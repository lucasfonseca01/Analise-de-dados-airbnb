![Airbnb](imagem/Airbnb.png)

#### Dicionário de dados em inglês
About Dataset

This extensive dataset offers a detailed glimpse into the dynamic world of Airbnb accommodations spanning diverse locations worldwide. From cozy apartments in bustling urban centers to serene retreats nestled in picturesque countryside, this collection provides valuable insights into the various types of lodging options available on the Airbnb platform. With comprehensive information on property features, pricing, reviews, and host characteristics, researchers and enthusiasts alike can delve into the intricate ecosystem of shared lodging, uncovering trends, patterns, and preferences that shape the evolving landscape of modern hospitality. Whether analyzing market trends, assessing the impact of tourism on local economies, or simply satisfying a curiosity about global travel trends, this dataset serves as a rich resource for exploring the multifaceted realm of Airbnb accommodations. <BR>

    
- id 
- log_price
- property_type 
- room_type
- amenities 
- accommodates
- bathrooms
- bed_type
- cancellation_policy
- cleaning_fee, city
- description
- first_review
- host_has_profile_pic 
- host_identity_verified
- host_response_rate
- host_since 
- instant_bookable
- last_review
- latitude
- longitude 
- name
- neighbourhood
- number_of_reviews
- review_scores_rating
- thumbnail_url
- zipcode
- bedrooms
- beds
    

#### Dicionário de dados em português

Sobre o Conjunto de Dados

Este extenso conjunto de dados oferece um vislumbre detalhado do mundo dinâmico das acomodações do Airbnb, abrangendo diversas localidades ao redor do mundo. Desde apartamentos aconchegantes em centros urbanos movimentados até retiros serenos escondidos na paisagem pitoresca do campo, esta coleção fornece insights valiosos sobre os diversos tipos de opções de hospedagem disponíveis na plataforma do Airbnb. Com informações abrangentes sobre características da propriedade, preços, avaliações e características dos anfitriões, pesquisadores e entusiastas podem mergulhar no ecossistema intricado da hospedagem compartilhada, descobrindo tendências, padrões e preferências que moldam o cenário em constante evolução da hospitalidade moderna. Seja analisando as tendências de mercado, avaliando o impacto do turismo nas economias locais, ou simplesmente satisfazendo a curiosidade sobre as tendências de viagem globais, este conjunto de dados serve como um recurso rico para explorar o reino multifacetado das acomodações do Airbnb.

- id: Identificação única para cada entrada de dados. <BR>
- preço do registro: Preço da hospedagem por noite. <BR>
- Tipo de Propriedade: Categoria da propriedade (apartamento, casa, quarto compartilhado, etc.).<BR>
- tipo de sala: Tipo de espaço (quarto privado, espaço compartilhado, casa inteira, etc.).<BR>
- Facilidades: Amenidades oferecidas na propriedade.<BR>
- acomoda(cabe x pessoas): Capacidade máxima de hóspedes.<BR>
- banheiros: Número de banheiros na propriedade.<BR>
- tipo de cama: Tipo de cama disponível (cama de casal, sofá-cama, beliche, etc.).<BR>
- política de cancelamento: Tipo de política de cancelamento aplicada.<BR>
- taxa de limpeza: Taxa adicional de limpeza cobrada.<BR>
- cidade: Cidade onde está localizada a propriedade.<BR>
- descrição: Descrição da propriedade.<BR>
- primeira revisão: Data da primeira revisão.<BR>
- anfitrião tem foto de perfil: Indica se o anfitrião possui foto de perfil.<BR>
- identidade do host verificada: Indica se a identidade do anfitrião foi verificada.<BR>
- taxa de resposta do host: Taxa de resposta do anfitrião a consultas de potenciais hóspedes.<BR>
- anfitrião desde: Data de entrada do anfitrião na plataforma.<BR>
- reserva instantânea: Indica se a reserva é instantânea.<BR>
- última revisão: Data da última revisão.<BR>
- latitude: Coordenada geográfica da latitude.<BR>
- longitude: Coordenada geográfica da longitude.<BR>
- nome: Nome da propriedade.<BR>
- vizinhança: Bairro ou área onde está localizada a propriedade.<BR>
- número de comentários: Número total de comentários recebidos.<BR>
- avaliação de pontuações de revisão: Avaliação média baseada nas revisões dos hóspedes.<BR>
- URL da miniatura: URL para uma imagem em miniatura da propriedade.<BR>
- CEP: Código postal da localização.<BR>
- quartos de dormir: Número de quartos disponíveis.<BR>
- camas: Número total de camas na propriedade.<BR>
    
    
URL DataSet: https://www.kaggle.com/datasets/lovishbansal123/airbnb-data

#### Perguntas abaixo que deverão ser respondidas
- Quais são as características mais comuns das propriedades listadas no Airbnb em diferentes cidades?
- Qual é a média de preços de hospedagem em diferentes tipos de propriedades (apartamentos, casas, quartos compartilhados, etc.) e em diferentes cidades?
- Existe alguma correlação entre o número de comodidades oferecidas e o preço da hospedagem?
- Qual é a média de avaliação dos hóspedes em relação à taxa de limpeza cobrada?
- Quais são as áreas mais populares (baseadas no número de reservas) em cada cidade?
- Quais são os bairros mais caros e mais baratos para se hospedar em cada cidade?

## Conclusão

Após uma análise abrangente dos dados do Airbnb, podemos destacar algumas características comuns das propriedades listadas em diferentes cidades. Em geral, os tipos de propriedade mais comuns são: Apartamentos, House e bed and breakfasts
Quanto aos tipos de quarto, observamos uma predominância de listagens para Casa/apartamento inteiro  e quartos privados. 
A maioria das propriedades oferece camas do tipo "Real bed", e a quantidade de quartos e cama em grande maioria é entre 1 e 2.

Quanto à correlação entre o número de comodidades oferecidas e o preço da hospedagem, descobrimos que essa relação é forte, com uma correlação média de 0.59. Isso sugere que o número de comodidades tem um impacto significativo nos preços das hospedagens.

Ao analisar a média de avaliação dos hóspedes em relação à taxa de limpeza cobrada, observamos uma diferença quase insignificante. Para valores de limpeza não cobrada, a média de avaliação foi de 96.76%, enquanto para Cobrados foi de 95.60%.

Em relação às áreas mais populares em cada cidade, encontramos alguns bairros destacados. Por exemplo, em Boston, a área mais popular foi Allston-Brighton, enquanto em São Francisco foi o Mission District, em Nova York, Williamsburg e Chicago, DC e LA ficaram os mais bairros mais populares ficaram como desconhecido.

Por fim, ao examinar as tendências de crescimento do número de propriedades e reservas ao longo dos anos em diferentes cidades, pudemos identificar áreas tanto em crescimento quanto em declínio. Cada cidade apresenta suas próprias tendências distintas de mercado imobiliário, com áreas mais caras e mais baratas para se hospedar. 
No geral ficou da seguinte maneira:
Cidades mais caras de Boston: Cambridge, Chicago: Magnificent Mile, DC: Chevy Chase MD, LA: Wilmington, NYC: Mill Basin e SF: Sea Cliff.
Cidades mais baratas de Boston: Somerville, Chicago: South Chicago, DC: Suitland-Silver Hill MD, LA: La Puente, NYC: Morris Park e SF: Daly City."


## Ações

- Com base nas áreas mais populares em cada cidade, os anfitriões localizados nessa área podem considerar estratégias de investimento em marketing para atrair pessoas interessadas em viajar, principalmente a geração millennials, podendo até mesmo promover descontos em datas estratégicas.

- Os anfitriões devem certificar-se de que o perfil e a listagem da propriedade estejam completos e bem otimizados. Isso inclui fotos de alta qualidade, descrições detalhadas e informações precisas sobre comodidades, regras da casa e políticas de cancelamento.

- Otimizar a precificação das hospedagens. Isso pode incluir a implementação de modelos de precificação dinâmica, levando em consideração fatores como sazonalidade, demanda do mercado, características da propriedade e concorrência.