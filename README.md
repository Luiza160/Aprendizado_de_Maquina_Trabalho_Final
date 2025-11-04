# <h1 align="center">😔 Máquinas Tristes 😔</h1>

Projeto realizado para a diciplina de Aprendizado de Máquina, no segundo semestre de 2025 do curso de Ciência e Tecnologia, Ilum Escola de Ciência.

## 🔎 Sumário 🔎
- [Título](#😔-Máquinas-Tristes-😔)
- [O Projeto](#O-Projeto)
- [Ferramentas Utilizadas](#🛠️-Ferramentas-Utilizadas-🛠️)
- [Instalação e Instruções](#💻-Instalação-e-Instruções-💻)
  - [Instalação do Código](#Instalação-do-Código)
  - [Instalação das Bibliotecas](#Instalação-das-Bibliotecas)
- [Desenvolvedores do Projeto](#👥-Desenvolvedores-do-Projeto-👥)
- [Referências](#Referências)

# O Projeto

## Problemática: Tecnologia e bem-estar psicológico em jovens
  Diversos estudos investigaram a relação entre o uso de tecnologia digital e o bem-estar psicológico de adolescentes, revelando um quadro complexo, com efeitos geralmente pequenos e dependentes do tipo de uso, contexto e características individuais[1].
  
  Nesse sentido uso passivo ou procrastinatório está mais relacionado a efeitos negativos, enquanto o uso ativo e social pode ter efeitos positivos, como aumento da sensação de conexão social [2]. Alguns estudos sugerem que meninas podem ser mais vulneráveis aos efeitos negativos das redes sociais, com associações mais fortes entre uso de mídias sociais e problemas de saúde mental [3]. Jovens de famílias economicamente desfavorecidas também relatam mais experiências negativas online [4].
  
  A relação entre tecnologia e bem-estar psicológico em jovens é multifacetada: os efeitos negativos existem, mas são geralmente pequenos e dependem do tipo de uso, contexto social e características individuais. O uso moderado e ativo pode trazer benefícios, enquanto o uso excessivo ou passivo pode estar associado a riscos, especialmente em grupos vulneráveis [4].

## Os Códigos
  o objetivo do projeto é predizer os níveis de saúde mental de jovens estudantes, com base tanto no ambiente de convívio quanto em hábitos relacionados ao uso das redes sociais. Esse tipo de análise pode ajudar a identificar hábitos e prever o aumento da probabilidade do desenvolvimento de doenças mentais - como depressão, ansiedade, etc. Ao determinar quais são esses parâmetros, é possível diagnosticar precocemente o desenvolvimento de transtornos mentais. 

# 🛠️ Ferramentas Utilizadas 🛠️

- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Numpy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [Scikit-Learn](https://scikit-learn.org/stable/index.html)
- [Optuna](https://optuna.org/)

#### Versão do Python
- Python 3.12.7

# 💻 Instalação e Instruções 💻

### Instalação do Código
O código principal para a execução deste projeto se encontra neste repositório do GitHub, na pasta [Principal](https://github.com/Luiza160/Aprendizado_de_Maquina_Trabalho_Final/tree/main/Principal). É recomendado que o usuário baixe a **pasta completa** e rode todos os notebooks instalados, começando com o *tratamento_de_dados.ipynb* e terminando com o *Comparacao_geral.ipynb*, para garantir que todos os modelos de predição sejam executados corretamente.

Ao realizar o download, é possível perceber que o arquivo é um Jupyter Notebook, ou seja, deve ser rodado em programas que possuam um Jupyter Kernel. Durante a realização do projeto, foram utilizados o JupyterLab e o Visual Studio Code, sendo os mais recomendados para a execução, uma vez que os testes já foram realizados neles. Além disso, é preciso que o usuário tenha instalado todas as bibliotecas citadas anteriormente em seu computador.

### Instalação das Bibliotecas
Outro ponto que exige atenção antes da execução do código tem relação com as bibliotecas que serão utilizadas. Em tópicos anteriores, tais ferramentas já foram citadas, incluindo também, o link para a página de cada uma delas na internet. Para que o código seja executado corretamente, o usuário deve verificar se já possui todas essas bibliotecas instaladas em seu dispositivo. Caso alguma delas não esteja, o usuário deverá criar uma nova célula, digitar **pip install** *(nome da biblioteca)* e executar. Por exemplo, para instalar a biblioteca Seaborn, digita-se *pip install seaborn*

# 👥 Desenvolvedores do Projeto 👥

[<img loading="lazy" src="https://avatars.githubusercontent.com/u/195492158?v=4" width=115><br><sub>🗿Luiza Davoli🗿</sub>](https://github.com/Luiza160)


[<img loading="lazy" src="https://avatars.githubusercontent.com/u/67320923?v=4" width=115><br><sub>👻Samarah Luiza de Medeiros Ramos👻</sub>](https://github.com/SamarahRamos)


[<img loading="lazy" src="https://avatars.githubusercontent.com/u/208799529?v=4" width=115><br><sub>📎Sarah Santos Silva📎</sub>](https://github.com/SarahSantosSilva)

Agradecimento especial ao professor da matéria de Aprendizado de Máquina, por todo o aprendizado durante o semestre e a colaboração para a realização desse projeto:

📍Professor Daniel Roberto Cassar

# Referências

[1] Orben, A., & Przybylski, A. (2019). The association between adolescent well-being and digital technology use. Nature Human Behaviour, 3, 173 - 182. https://doi.org/10.1038/s41562-018-0506-1

[2] Dienlin, T., & Johannes, N. (2020). The impact of digital technology use on adolescent well-being . Dialogues in Clinical Neuroscience, 22, 135 - 142. https://doi.org/10.31887/dcns.2020.22.2/tdienlin

[3] Twenge, J., Haidt, J., Lozano, J., & Cummins, K. (2022). Specification curve analysis shows that social media use is linked to poor mental health, especially among girls.. Acta psychologica, 224, 103512. https://doi.org/10.1016/j.actpsy.2022.103512

[4] George, M., Jensen, M., Russell, M., Gassman‐Pines, A., Copeland, W., Hoyle, R., & Odgers, C. (2020). Young Adolescents' Digital Technology Use, Perceived Impairments, and Well-Being in a Representative Sample.. The Journal of pediatrics. https://doi.org/10.1016/j.jpeds.2019.12.002
