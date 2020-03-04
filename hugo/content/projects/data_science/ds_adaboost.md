{
  "title": "Adaboost with numpy",
  "date": "2018-07-10T12:41:05-05:00",
  "image": "/img/adaboost.png",
  "link": "https://github.com/SergioSJS/adaboost-python",
  "description": "Adaboost for categorical data implemented with numpy only.",
  "tags": ["python","analysis", "Machine Learning", "adaboost", "jupyter notebook", "numpy"],
  "fact": "",
  "featured":true
}

This simple model has only one hyperparameter, the number of weak models, therefore, the greater the quantity, better the nidek or better rule. The algorithm automatically checks and selects the best rules with the best accuracy. After that, it performs the evaluation of the alpha, fallowed by change the weights of the data, increasing the weights of wrong classified data. This process repeat until the hyperparameter value. A important observation, how after each rule the data distribuction change, the algorithm can be select the same rules but with different values of alpha and weights.


![test](/img/adaboost.png#center)