# Atividade Aula 8 - Análise de Dados com PySpark

## Big Data - California Housing Dataset

### Questão 1: As casas mais antigas são necessariamente mais baratas?

**Resposta:** Não, as casas mais antigas não são necessariamente mais baratas. A análise demonstrou que, embora todas as casas com 52 anos de idade compartilhem a mesma idade máxima, seus valores variam significativamente, de $47.500 até $300.000. Isso indica que outros aspectos, como localização, renda da região e características específicas do imóvel, exercem maior influência no valor das casas do que apenas a idade da construção.

---

### Questão 2: As diferenças entre o valor médio das casas em cada localização refletem uma distribuição desigual?

**Resposta:** Sim, a distribuição é geograficamente desigual. A análise revelou diferenças superiores a $80.000 entre diferentes regiões da Califórnia. Observou-se que:

- O Sul da Califórnia (latitude ~33-34) apresenta valores médios mais elevados
- A região de São Francisco (latitude ~37-38) também possui valores mais altos
- A média é uma métrica confiável quando há muitos registros (25-30 casas), mas pode ser enganosa em localizações com poucos dados (1-3 casas)

---

### Questão 3: Como o número de quartos, latitude e longitude se relacionam com o valor das casas?

**Resposta:** O número total de quartos apresenta correlação positiva fraca (0.130) com o valor das casas, indicando que mais quartos tendem a resultar em preços ligeiramente mais altos. Já latitude e longitude apresentam correlações negativas muito fracas (-0.144 e -0.045, respectivamente), sugerindo que regiões ao sul da Califórnia, como Los Angeles e San Diego, têm casas mais caras, e áreas mais próximas à costa apresentam valores ligeiramente superiores. Entretanto, essas correlações geográficas são tão fracas que indicam que a localização específica dentro dessas regiões é muito mais determinante para o valor das casas do que as coordenadas geográficas gerais.

---

## Tecnologias Utilizadas

- Apache Spark
- PySpark
- Google Colab
- Python


