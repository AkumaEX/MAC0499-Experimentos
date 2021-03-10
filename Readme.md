# MAC0499 Trabalho de Formatura Supervisionado

Os cadernos **Python** (*Jupyter Notebooks*) representam os experimentos e resultados do trabalho [**Previsão de Pontos Críticos de Crime: Uma modelagem por aprendizado de máquina para prevenção de roubos de celulares em São Paulo**](https://linux.ime.usp.br/~akumaex/mac0499). Estes cadernos estão estruturados da seguinte forma:

1. Aprendizado não supervisionado
2. Aprendizado supervisionado
3. Visualização dos Resultados
4. Aprendizado não supervisionado
5. Aprendizado supervisionado
6. Visualização dos Resultados
7. Comparações
8. Implementação
9. Conceitos

Os cadernos 1, 2 e 3 representam os experimentos e resultados para a abordagem de agrupamentos com o **número de agrupamentos definido**, e os cadernos 4, 5 e 6 representam os experimentos e resultados para a abordagem de agrupamentos com o **número de agrupamentos dinâmico**. O caderno 7 compara os melhores resultados das duas abordagens e o caderno 8 mostra a implementação do modelo e a visualização da previsão. O caderno 9 são os exemplos e conceitos apresentados ao longo do trabalho.

Os cadernos 1 e 4 (aprendizado não supervisionado) abordam os dois tipos agrupamentos; os cadernos 2 e 5 (aprendizado supervisionado) abordam os treinamentos dos modelos de previsão e os cadernos 3 e 6 (visualização dos resultados) abordam os resultados e comparações dos experimentos.
___
## Execução
Para a execução dos cadernos, é necessário um dos seguintes requisitos:

* Docker e Docker Compose
* Python VirtualEnv

### Docker
Com o **Docker** e **Docker Compose** instalados, execute pelo terminal:
```
$ docker-compose up
```
E siga as instruções pelo terminal

### Python VirtualEnv
Com o ambiente virtual Python ativado, execute o seguinte comando para instalar as bibliotecas e a aplicação web **Jupyter Notebook**:
```
$ pip install -r requirements.txt
```
Para iniciar o **Jupyter Notebook**, execute:
```
$ jupyter notebook
```