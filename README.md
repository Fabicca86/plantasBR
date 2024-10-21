# plantasBR
Esta ideia surgiu para contribuir com a preservação ambiental. Está em fase de construção portanto, requer melhorias. Sinta-se livre para contribuir mesmo que seja apenas com aporte de ideias.


# BRPlant_Classifier

Este projeto busca criar um modelo de Deep Learning para reconhecer e classificar plantas pertencentes à flora brasileira. Utilizando visão computacional e técnicas de deep learning, o objetivo é fornecer uma ferramenta precisa e eficiente para identificação de plantas.

## Descrição do Projeto

O MyPlant Classifier será um aplicativo que utilizará um modelo de deep learning para classificar plantas nativas do Brasil. Voce poderá notar que há diretrizes em portugues e ingles, isto se deve a que tenho feito uma compilação de tutorias e em alguns momentos digitar no ingles era mais rápido. Também irá notar muitos erros de digitação, desculpas antecipadas! É por causa de defeito em meu teclado. Tudo será aperfeiçoado e corrigido. O dataset ainda não existe e nenhum debbug foi realizado.
No conceito inicial iria adquirir o dataset do SiBBr. Mas não consegui visualizar as imagens e labels dos conjuntos que achei mais interessantes.

## Conjuntos de Dados Sugerido

Para acessar os conjuntos de dados utilizados neste projeto, visite a página do [SiBBr](https://collectory.sibbr.gov.br/collectory/datasets).


O PROJETO ESTÁ EM DESENVOLVIMENTO assim como meu aprendizado, forte razão de necessitar da ajuda de quem se sentir motivad@ a contribuir.

Atualmente inclui as seguintes etapas:

**Etapas**
- Preparação do ambiente de Deep Learning
- Criação de dataset do zero ou usar um modelo aprendizado não supervisionado (sem labels)
- Treinamento do modelo
- Avaliação e validação do modelo

## Tecnologias Inicialmente Utilizadas

- Python
- TensorFlow
- NumPy
- Matplotlib

## Estrutura do Projeto (esboço)

```plaintext
BRPlant_Classifier/
│
├── data/
│   ├── raw/                # Dados brutos
│   ├── processed/          # Dados processados
│
├── notebooks/
│   ├── MyPlant_classifier.ipynb  # Notebook principal
│
├── models/
│   ├── model.h5            # Modelo treinado
│
├── src/
│   ├── data_preparation.py # Script de preparação de dados
│   ├── model_training.py   # Script de treinamento do modelo
│
├── README.md
├── requirements.txt        # Dependências do projeto
└── setup.py                # Script de instalação
```

## Como Usar

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/MyPlant_Classifier.git
    cd MyPlant_Classifier
    ```

2. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

3. Prepare os dados:
    ```bash
    python src/data_preparation.py
    ```

4. Treine o modelo:
    ```bash
    python src/model_training.py
    ```

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e enviar pull requests. Ou me contatar via linkedin.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

---

