# bike-rentals ![Azure](https://img.shields.io/badge/Azure-blue?style=for-the-badge&logo=microsoft%20azure&logoColor=blue&labelColor=FFFFFF&link=https%3A%2F%2Fimages.app.goo.gl%2FK7PN1jYJd57x4q7A8)
## Aprendizado de máquina automatizado para previsão de aluguel de bicicletas

Uma descrição detalhada do processo de criação de um modelo de regressão no Azure ML para previsão da demanda de aluguel de bicicletas. 
 Será aplicado o recurso de aprendizado de máquina automatizado no Aprendizado de Máquina do Azure para treinar e avaliar um modelo de aprendizado de máquina.

Confira os passos a seguir para a realização desta tarefa com sucesso:

### 1. Criar um espaço de trabalho do Aprendizado de Máquina do Azure

Para começar a trabalhar é necessário criar um __espaço de trabalho__ do Aprendizado de Máquina do Azure em sua assinatura do Azure. Em seguida, você poderá usar o __estúdio__ do Aprendizado de Máquina do Azure para trabalhar com os recursos em seu espaço de trabalho.

Confira como fazer isso clicando [aqui](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html#create-an-azure-machine-learning-workspace)


### 2. Usar o aprendizado de máquina automatizado para treinar um modelo

O aprendizado de máquina automatizado permite que você experimente vários algoritmos e parâmetros para treinar vários modelos e identificar o melhor para seus dados. Neste exercício, você usará um conjunto de dados de detalhes históricos de aluguel de bicicletas para treinar um modelo que prevê o número de aluguéis de bicicletas que devem ser esperados em um determinado dia, com base em características sazonais e meteorológicas.

Confira como fazer isso clicando [aqui](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html#use-automated-machine-learning-to-train-a-model)


### 3. Reveja o melhor modelo

Após o treinamento do modelo é possível verificar as características do modelo com melhor desempenho na previsão do número de biciletas alugadas com base nas variáveis como pro exêmplo temperatura, humidade ou dia da semana.

Confira como fazer isso clicando [aqui](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html#review-the-best-model)


### 4. Implantar o modelo

Para uitlizar o modelo é necessário que ele seja implantado no espaço do trabalho de aprendizado de máquina automatizado.

Confira como fazer isso clicando [aqui](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html#deploy-and-test-the-model)


### 5. Testar o modelo implantado

Para a realização de testes será necessário ciar __Pontos de extremidade__ no estúdio do Aprendizado de Máquina do Azure.
Pontos de extremidade podem ser entendidos como um recurso utilizado para solicitar ou passar parâmetros para que o modelo possa utilizá-los para fazer suas inferências ou previsões.

A imagem a seguir mostra um texto em formato json onde podemos inserir os parâmetros que queremos que nosso modelo. Neste caso foram colocados os parâmetrso sugeridos pela documentação do Azure.

![imagem do json](/assets/tela_json.png)

Confira como fazer isso clicando [aqui](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html#test-the-deployed-service)


Para finalizar, além de seguir esse passos para treinar, testar e implantar um modelo de machine learning sugerimos que você faça seus próprios testes, alteranto o texto json com outros valores para testar seu modelo para diversas condições.