# Cálculos Preliminares

## 1. Configuração estrutural

Para o desenvolvimento inicial da ponte, foi adotada uma estrutura do tipo **Treliça Warren**, construída predominantemente com **palitos de madeira** e unida exclusivamente por colagem.

A proposta considera uma ponte com dois apoios nas extremidades e vão livre de 80 cm, conforme especificado no problema.

Para os cálculos preliminares, foram adotadas as seguintes dimensões e condições de carregamento:

| Parâmetro                    | Valor adotado |
| ---------------------------- | ------------: |
| Vão livre                    |         80 cm |
| Comprimento preliminar       |         80 cm |
| Largura preliminar           |         15 cm |
| Altura preliminar da treliça |         15 cm |
| Número de módulos            |             8 |
| Massa do suporte de ensaio   |          1 kg |
| Carga mínima adicional       |          5 kg |
| Massa total considerada      |          6 kg |
| Aceleração da gravidade      |     9,81 m/s² |

**Observação:** as dimensões utilizadas nesta etapa são preliminares e poderão ser modificadas após os testes dos materiais, das uniões e a análise estrutural.

---

## 2. Conversão da carga

A carga mínima de ensaio é composta pelo suporte de aproximadamente 1 kg e pela carga adicional de 5 kg.

Assim:

$$
m = 1 + 5 = 6\,kg
$$

A força correspondente à massa é calculada por:

$$
P=m\cdot g
$$

Substituindo:

$$
P=6\cdot9,81
$$

$$
\boxed{P=58,86\,N}
$$

Portanto, para a análise preliminar, será considerada uma carga vertical de aproximadamente **58,86 N**.

---

## 3. Reações nos apoios

Como a ponte é considerada simétrica e a carga está aplicada no centro do vão, as reações nos dois apoios são iguais.

Pelo equilíbrio vertical:

$$
R_A+R_B=P
$$

Como:

$$
R_A=R_B
$$

temos:

$$
R_A=R_B=\frac{P}{2}
$$

Substituindo a carga:

$$
R_A=R_B=\frac{58,86}{2}
$$

$$
\boxed{R_A=R_B=29,43\,N}
$$

Assim, cada apoio deverá resistir inicialmente a aproximadamente **29,43 N** de reação vertical.

---

## 4. Comportamento esperado da Treliça Warren

A Treliça Warren é formada por elementos diagonais organizados de maneira alternada, formando triângulos.

Quando a carga é aplicada, os elementos da estrutura passam a trabalhar predominantemente sob esforços axiais de:

* tração;
* compressão.

Os elementos submetidos à compressão deverão receber atenção especial devido à possibilidade de **flambagem**, principalmente quando forem utilizados palitos de madeira relativamente esbeltos.

As regiões de ligação também serão consideradas críticas, pois a união entre os palitos será realizada exclusivamente por colagem.


---



## 5. Previsão inicial

Considerando a carga mínima de aproximadamente **58,86 N**, espera-se que a estrutura seja capaz de suportar o carregamento sem colapso durante o período mínimo de 60 segundos.

A análise preliminar indica que o desempenho da ponte dependerá não somente da resistência dos palitos, mas também:

* da geometria da treliça;
* do comprimento dos elementos;
* da quantidade de material utilizada;
* da qualidade das uniões;
* do alinhamento durante a fabricação;
* da resistência à flambagem dos elementos comprimidos.

Por esse motivo, os cálculos serão complementados pelos testes experimentais dos materiais e das uniões.

---

### Referências 
https://eaulas.usp.br/portal/video.action?idItem=30284

https://engineeringstatics.org/

https://engineeringstatics.org/method-of-sections.html

https://lcf.esalq.usp.br/disciplina/detalhe?sgldis=LCF0623&tipo=GR

https://producaocientifica.eesc.usp.br/producao/2016DO_ArefKaliloLimaKzam.pdf

https://teses.usp.br/teses/disponiveis/18/18134/tde-22042010-082927/pt-br.html
