# provaparte1
# **Ordenação de dados**

* Algoritmo de ordenação em ciência da computação é um algoritmo, de manipulação de dados, que coloca os elementos de uma dada sequência em uma certa ordem em outras palavras, efetua sua ordenação completa ou parcial. As ordens mais usadas são a numérica e a lexicográfica.
* Existem várias razões para se ordenar uma sequência. Uma delas é a possibilidade se acessar seus dados de modo mais eficiente.
![Exemplo1 ](http://www.arnerobotics.com.br/eletronica/new_pictures/metodos_pes_ord_fig1.png)

# Bubble Sort

Bubble sort é o algoritmo mais simples, mas o menos eficientes. Neste algoritmo cada elemento da posição i será comparado com o elemento da posição i + 1, ou seja, um elemento da posição 2 será comparado com o elemento da posição 3. Caso o elemento da posição 2 for maior que o da posição 3, eles trocam de lugar e assim sucessivamente. Por causa dessa forma de execução, o vetor terá que ser percorrido quantas vezes que for necessária, tornando o algoritmo ineficiente para listas muito grandes.
![Exemplo2 ](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTcVU1hSmgIPq2g8_DWgpkLURhb9TyAmaYjUwZaJeJW8m921noRvXSzW-yGijTN9AQVNbb_hAq3gDM&usqp=CAU)

# Selection Sort

* Este algoritmo é baseado em se passar sempre o menor valor do vetor para a primeira posição (ou o maior dependendo da ordem requerida), depois o segundo menor valor para a segunda posição e assim sucessivamente, até os últimos dois elementos.

* Neste algoritmo de ordenação é escolhido um número a partir do primeiro, este número escolhido é comparado com os números a partir da sua direita, quando encontrado um número menor, o número escolhido ocupa a posição do menor número encontrado. Este número encontrado será o próximo número escolhido, caso não for encontrado nenhum número menor que este escolhido, ele é colocado na posição do primeiro número escolhido, e o próximo número à sua direita vai ser o escolhido para fazer as comparações. É repetido esse processo até que a lista esteja ordenada.
![Exemplo3](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAO8AAADTCAMAAABeFrRdAAAAxlBMVEX///9qtf9aV/vt9f5ms//y+P77/f+rq6tdsP/x9/6Xyf9ttv95u/+Sxv9ksv+v1f/IyMj09PSIwv/T6P+22f/R0dFVUvtVUfvBwcH0/f6Ihvz6+v9eW/tsa/tKRfuOkPzS2v7T3/6mof1PSvu0y/59fPzM5P/r6+uk0P/c3NxSrP+01//i8P9+vv/f7v+5uP3R0P5mY/u3t7ff3/7A3v/o6P7BwP3JyP2qqf1BPfvv7/84NPp4dvyopv01MPrI1v6Yl/zh5+4Omea+AAALPElEQVR4nO2dC0ObSBeGT2SA4RIwkIs1rbamxZiEqDGu1a/9av//n9oZkrQyXOakRBvd8+42KhzOzMNcQpSXASCRSCQSiUQikUgkEkkoaaMUxcdYfcJlFFqOkYHhEhfnzrS4nKHE4/6gj9LoEzIl49MoQAUGboitpqHhjVgLpSA+QGrwKcClbAXdNq505obYanb/Y7xT4iVeTKJXwhsSL/FiEhHvm+ANOJdbOOfK9iLvaCRe+qOTkY6XZSnXmWt5g03h+dJLeUW+4ondlpctDSMMmD83Y6+et9+/uhFwxzcPV+/reblriOoGS2fm5vcUeHlouKzlG7OZ4et4g6ymDXl5DLEBLrMgASO3R+XtXz8AHPS/wcMV3I7qeOVb4jLgCcSmUprKGyQAY8bGYBizXIoSXhE7N0R0M142TyYRJGMIJ0uBXcM7ehg+QH9w9vDhf7dQxyuqPxO8HhiTFOJcP1V4xbXvTBAES5hMtP2Zz2KRL1EbeNv+zANxxDiBKBhD92myQvt+e38L/YPBqD8YDk9q+7MbwZJH8pMYOHW8La89Frx8DqYxzp+zkv4sRu8Ypk15WywVlYohDVzRKDW8B/0TyXtwcHIHp4Na3qAteMW/gFlmblfJ+JX9uRsvLUif7imdr5hvmcVRve185YPlc0T7ih6d8Z78A1/zE3SBl7XX7RuAUdu+srZiRIrZWWm5Ml6Ba/lNeeU5CyaiuO4kgXbd+D3oy3E7ELjf/39SzytYu5MWOHJm0LcvZ2026eZnojJezzI9ZZhvz+tZYIGYVQwwYJ5vC3X8nt5YcHN8mSW5ruMN4hk4Me+CA+Dn9yi8TMy4xtIDMW0ZuvEbgKzpXAXektdPpERfWs67SldTeY+v7u6uvny9E7qq513KnAEfx0mq5FR5YxHY5VESK4WX8HoyNuk2na+CTPLiRZ10Cv15JNQfyFfN+F2nZDzQXV+tIlmh8NLrjXXaZryVeqvXz5WJiJd4ibc+J/GWi3grUxJvXmHhErQi0evgFR/tamWZLkdpkpwgdf9jgkvJJ2GEjIzGuJxsalkaXtPByTCxMpAZRc6dR5qmjtd4U3K0vM7fruJOpectaWBz8RN7FhY7rW1zmUMNr5UNOdHxndUX8WL+tBdm9vNmg/yX+289WN717MN3zioo27D+Ljvmd0JndcTvhM7qf2eTevODk69LLuGmmLKEqxwyWDNdSWBrOBxaUsP1y3CxsC/W32Z7h+LrcLgOkN9vgk17YZ9vjh2uQobr49Zx64Pk8cNNQmuT0FITDp8elkv4dM+vejwpabjG0OBmxBn1L3y4sBeLhRKTi4XNAYeC92j9g6UErTPKr9YqgbV+3fy8iYXfCTd76xJCVUIEa5k6tuC1e4jIcxFp2xd/VszeqHN+YR+dn6Mie3YPFbnf6tiHyMiLV9+6UsRbJeJ9jSLeKhHva5TktTB6M7x4vQVeODxCq/O360oikUgkEolEIpFIpD9T6KHEElyc0I/Be5wGn9stVMaWG+IC/USH20Xev8EVv0rNzRYfR/qbPDKNPuPv30DeE8J1Bm/8/TlY3taz8L683/l18O7OD0u8FSLeF+Td3f2ExFsh4iXeveHlXkt6ZwJPMScXeVlmrwkKkUXewUAaDUfiq443S5k9GEbPy0UNGvP6c4CEBW0TjLw5qsAb+IYp81tqZIH35CtcDg7ef4Sh4jRUeZlvWOJ0dy3Lmmn9oV5W04a84vKzOxcfIcAMwconUnhZWxwsKgKzLpj5a3CFd3AHcDkaXcHljeIkVXhZJFJ6LT63kjjPV+b/nUM3bu6HXU6lqzGE8aSr+p0Vf7tpGJI39iczyJea5+2fgkAdXcPN/TVcjWp4ueMYktdMEH7nIOnuwu8cBFyASj+sq/phlf7sccErB7GnuFwL7fv+i+D9Av+MBsOHOl6RciZ4maiV1da176qmTf3smTl5Pin1O6vzVcYrdszVHOr4HRwL3uOM16jlbWW83jQUg0k7fltBBLPG/kGBOwv4Etp8DCGGV+C6ykdolbcveb/B3WgAtyd63hYPxAnXP58hAoM1na/ELGSkqedCMpnnLeUFXjYxgDMmZjdfNz+L/nw/GA4Hj6KNa+dnUah4J+x6LQd07SsmN1FTX9m6tf832zYX5VqQKH5nZX4ey9tR3dXvT/LFKryjWxH5cP8o4pz8kzrU+dmVucbj7FU3fllW8Kyh31mOnTB0WTBeqs8GUds3EqHT1JXx0/wudb46+/r96/fB6Nvl94N+HW8rlSmjIOp203zhZX7nrKaN56vMRMw2F091vK21N7noOi7MV1JiGKuXV8XxuyqcBWrhlX7npuO3Wm/1+rkyEfFWiXiJl3jrRLyV1fyv8ep+/4z/e1kLWST7eIJ7kHB/938vY3yu8w9OfZwSZJzv/7j+gNP1ZxeZ0g1xcWmi9zsj5eAj32GFTrlF6eR3zvM28jv/fIbIRtLyNmlg56eNPFtm7+hlOpLO7wzWEDlSyrYv7B5yArDtn4gy/li/EupwcT6USnfKwu6gIg/txaJBSVtIg7uh3nL7audisahyKlm5bzrSUdzQyWIpX7XV27kOM7szxv67kLz2a7eyWNATtJhz3IEj0fGfvULPrh6qdaWO7DeAS7yVIt7XKOKtEvG+RvXsi3Oc3govXm+Bt9ND6034wEkkEolEIpFIJNIb18v8naOphjjpadvIZ48nyEePi0j888xTZGT78R73MPVjHTH+efVov3P8DM+rP1PvNa26BeZMw7v7+3P+Km//C/ESL6ZuxFtVOeKtykm8FSmJl3j/iJfx1BdXXEErVbwuJX5nJrcEXqqakwu83POyzJ66MKHKu0qZPSpHy9sffbgu3ni8JS9LLYCZXMcTIG+4Kvqd2wCtbInivHG2yMtjuTZsaoJqXy2sdxxJ/2+wFCnzluIS3v4HcaV825SXm+AuoeuDEZmQAyz46eQpkYsZJ20L8pVTeP1Ztr6zIc13+du2FV4mnXTS7+yEU9UPW+AdPcDpP9I33qw/j10ewXIKLp/mPXwFv/Msln7nqOtNZrW8zIUlLHkKc+4pfj+Fl8/n0h/KrTj1VL9zgXdw9ngiPadNxy/jCbRXfud6/6/0h2a+u1ShUNuXsSfrHdeu/8tWflhZrVA5Z8XxO5Br8Z42bV85dJNJgvc7M89R7KGF8YvmXft/25EYTLr+nH30KzTv1rxcDMgJX4r+HOYHWwWvxE2VzlfKK9cqZ7r1nTd+Z17wOxd5R49wddJvyBuMYeaOowjmnpEvsrQ/BxI3HI8187PkDUQ36OYfCVDsz2IqaAV+nKaW6mcvjt9HuD19/KICb8m78jvPJvItYVr7fpTNzzBeLX+X1vHyLITLh03MlPf0kvkZwsz1rJ2fD7Kstw3nK68tFYlrAzfV+J19GelH2QG5XYX5KspSMs9tK787Utt3lTLwXFfx/pTxHkt9a9i+q2e5SL9zwThdcn21Ciw8/KUwftchxZzF66vywNLrq0wNx2+13uj1c3XdiLeqcsRblZN4K1ISL/ESb5kSzlCSfmecghiZkvFpFOBSumejAUr3d/W4lpW4KLVjXJxQ3EYGtpchMjK8PMXpamd+5y3Wd8bbHLHGScdEO6jJ75znfb3rO5dZqLW8w5cBdnbv7zYXvULndLb3Oz+P3h1d4KcKlKwL2y4Of70B+GVurzm3d+53ztZaLmzV4b6QkCsob6Ge9BTv69rDcons3fqdpWW8sOz2vmi1RPbRjrPuPOHO1Omc20edXfvZ95dXzIrPULl95u0Qb2MR7/6IeJuLePdHHfn+u2PtN+8zaE+vJjP1Dnevff20QCKRSCQSiUQikUj7qH8BLucLUPNtfXAAAAAASUVORK5CYII=)

# Insertion Sort

* O Insertion sort é um algoritmo simples e eficiente quando aplicado em pequenas listas. Neste algoritmo a lista é percorrida da esquerda para a direita, à medida que avança vai deixando os elementos mais à esquerda ordenados.

* O algoritmo funciona da mesma forma que as pessoas usam para ordenar cartas em um jogo de baralho como o pôquer.
![Exemplo4](https://miro.medium.com/max/2280/1*Tyd9a7fjF-zPUTModbU3VA.png)

# Quick sort

O Quick sort é o algoritmo mais eficiente na ordenação por comparação. Nele se escolhe um elemento chamado de pivô, a partir disto é organizada a lista para que todos os números anteriores a ele sejam menores que ele, e todos os números posteriores a ele sejam maiores que ele. Ao final desse processo o número pivô já está em sua posição final. Os dois grupos desordenados recursivamente sofreram o mesmo processo até que a lista esteja ordenada.
![Exemplo5](https://miro.medium.com/max/600/1*DtH6fEdBhoUGnjBWudJ8pA.png)

# Tempo de execução e performance 
* obs: Não contém bubble sort no comparativo
* Elementos em ordem aleatória
![Exemplo6](https://lh3.googleusercontent.com/jiiMPZTsVN81088jaSJNShBWerlrI9-fkYt0cEUAvhtB1cXNp6xfFrVu4VqujTtlahgi2q8=s160)

* Elementos em ordem crescente
![Exemplo7](https://lh3.googleusercontent.com/Sk9o19T_75_fpcIk112vKgNwXOm3avEGrPJDwcz-hA-LhMCbnZLPBsfvqEC056KWkJh8-w=s161)
* Elementos em ordem decrescente
![Exemplo8](https://lh3.googleusercontent.com/RB50e_25OOI1YLaMWB0eGAbkrDXsqCU7WGNh4viVaDLfj-U3BOBSKsvhXr5QHZtVEHJpOjM=s160)

# Qual o método de ordenação mais rápido
* O algoritmo de ordenação mais rápido é o Quick sort por que:
* É o algoritmo mais eficiente que existe para uma grande variedade de situações
* O algoritmo é recursivo, o que demanda uma pequena quantidade de memória adicional
* É um algoritmo de comparação que emprega a estratégia de “divisão e conquista”. A estratégia consiste em rearranjar as chaves de modo que as chaves "menores" precedam as chaves "maiores". Em seguida o quicksort ordena as duas sublistas de chaves menores e maiores recursivamente até que a lista completa se encontre ordenada.
