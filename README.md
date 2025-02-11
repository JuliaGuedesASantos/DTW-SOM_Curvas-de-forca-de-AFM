# <p align="center"> **DTW SOM - Curvas de força de AFM** 📊💪 </p>
### **Resumo** 🗺️🕰️
<p align="justify">
O Self-Organizing Map (SOM, do português, Mapa Auto-Organizável) é uma rede neural não supervisionada que busca reduzir a dimensionalidade dos dados ao agrupar atributos em clusters que preservam suas principais características. Originalmente, o método utiliza a distância euclidiana para comparar a similaridade entre os dados de entrada e os neurônios. No entanto, o artigo referenciado em [3] propõe uma adaptação desse método ao empregar a técnica de Dynamic Time Warping (DTW), tornando-o mais adequado para a análise de séries temporais. Enquanto a distância euclidiana mede a menor distância entre dois pontos, o DTW avalia a similaridade entre duas séries temporais, permitindo um alinhamento flexível que maximiza a correspondência entre elas. 
</p>

<p align="justify">
Neste contexto, o presente trabalho aplica o método DTW-SOM à clusterização de curvas de força obtidas por meio da caracterização de materiais utilizando Atomic Force Microscopy (AFM). Inicialmente, os pontos significativos das curvas na base de dados serão identificados por meio de motif discovery. Em seguida, o DTW-SOM será empregado para identificar os padrões centrais dos dados de entrada, facilitando, assim, a análise e interpretação das medições realizadas.
</p>

### **Divisão do GitHub** 🗂️
O GitHub se encontra dividido em pastas, sendo essas:
<ul>
  <li>Au-Au 🐶: Possui os primeiros testes realizados com a biblioteca DTW-SOM, com a utilização de dados de feitos com medições de substrato e ponta de ouro. Além dos notebooks, contém uma tabela com o resumo dos resultados e o dataset utilizado. </li>
  <li>Lig-CL 🐛: Possui dois testes (um com escalonamento e outro sem), um notebook com histogramas e gráficos - comparação dos pesos com os dados reais dos clusters mais relevantes - e o dataset utilizado.
  <li>Outros códigos 👩🏻‍💻👩🏻‍💻: Contém outros códigos que foram feitos durante a execução do projeto. </li>
</ul>

### Bibliotecas utilizadas 📚
* matplotlib 3.9.2
* numpy  2.1.3
* pyclustering 0.10.1.2
* matrixprofile-ts 0.0.9
* dtwsom 1.0

### Referências 🗃️
Link para o GitHub do projeto original: https://github.com/misilva73/dtw_som

[1] Gabriel R Schleder et al. “From DFT to machine learning: recent approaches to materials science–a review”, J. Phys. Mater. 2 032001, 2019. Acesso em 14 de janeiro de 2025.

[2] Géron, Aurélien. Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow. 3. ed. Estados Unidos: O'Reilly Media, 2022. ISBN 9781492032649.

[3] D’haeseleer, Patrik. How Does DNA Sequence Motif Discovery Work? Nature Biotechnology, vol. 24, no 8, agosto de 2006, p. 959–61. www.nature.com, https://doi.org/10.1038/nbt0806-959.

[4] “Understanding Dynamic Time Warping”. Databricks, 30 de abril de 2019, https://www.databricks.com/blog/2019/04/30/understanding-dynamic-time-warping.html.

[5]Tavenard, Romain. An introduction to Dynamic Time Warpi, 2021.. https://rtavenar.github.io/blog/dtw.html. Acesso em 28 de janeiro de 2025.

[6] Mayatopani, Hendra, et al. “Implementation of Self-Organizing Map (SOM) Algorithm for Image Classification of Medicinal Weeds”. Jurnal RESTI (Rekayasa Sistem Dan Teknologi Informasi), vol. 7, no 3, junho de 2023, p. 437–44. jurnal.iaii.or.id, https://doi.org/10.29207/resti.v7i3.4755.

[7] Silva, Maria Inês, e Roberto Henriques. Exploring time-series motifs through DTW-SOM. arXiv:2004.08176, arXiv, 17 de abril de 2020. arXiv.org, https://doi.org/10.48550/arXiv.2004.08176.
</p>
