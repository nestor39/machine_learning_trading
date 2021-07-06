# Machine Learning Trading

This code was created with the purpose of implementing an algorithmic trading bot, which is going to manage and automatically trade assets in a highly dynamic environment. Using my skills in financial Python programming and machine learning I created a bot that learns and adapts to new data and evolving markets. I adjusted the input parameters to optimize the trading algorithm and at the end I used a new machine learning mode and compared its performance to that of a baseline model.


## Technologies
```
pandas
numpy
pathlib
hvplot.pandas
matplotlib.pyplot
sklearn 
sklearn.preprocessing
pandas.tseries.offsets
sklearn.metrics
sklearn.tree
```

## Installation

In order to open and run this program you have to follow these steps:

* Go to my repository in GitHub and open the repository called ```machine_learning_trading_14```

* Copy the repository's link.

![machine_learning_trading_ssh_jpeg](https://user-images.githubusercontent.com/80844686/124669870-f9455380-de67-11eb-8400-eba74483f4df.jpg)



* Open Git Bash in your computer.

![git_bash](https://user-images.githubusercontent.com/80844686/115638940-40d82c80-a2c8-11eb-816a-e991b245cd88.jpg)

* Clone the repository by typing ```git clone``` and paste the link ```git@github.com:nestor39/machine_learning_trading_14.git```.

![git_clone_machine_learning_trading](https://user-images.githubusercontent.com/80844686/124669839-e9c60a80-de67-11eb-9f80-99299db1ccaf.jpg)


After doing the steps above you are going to have the files in your computer, now we are going to need to open it:

 * Open Git Bash in your computer.
  
  * Activate  the Conda development environment, by typing ```conda activate dev```.

  
 * Type  ```jupyter lab"``` in your Git Bash(it will open a tab in your explorer).
  
 * Open the file ```machine_learning_trading_bot.ipynb``` and you are going to be able to see the code.
  
  * Run the code.
  

## Results
* Baseline performance

![svc_model_predictions](https://user-images.githubusercontent.com/80844686/124673012-f305a600-de6c-11eb-95ee-419152dea37a.jpg)
![baseline_machine_learning](https://user-images.githubusercontent.com/80844686/124673169-3bbd5f00-de6d-11eb-8d84-178e0902f6a0.png)



* New machine learning performance (DecisionTreeClassifier)
![new_machine_learning_trading](https://user-images.githubusercontent.com/80844686/124673019-f6992d00-de6c-11eb-9fe8-d83741b6f8b3.jpg)
![second_machine_learning](https://user-images.githubusercontent.com/80844686/124673176-3e1fb900-de6d-11eb-9610-f83e81652114.png)


When I compared both models I could see that the first model performed much better than the second model. There was no point of comparison in the second model with the tuned trading algorithm. The accuracy score for the second model was 0.45 while the first one was 0.55. So, we can see how well the first model performs when you compare it with the second one.

## Inside the repository

![machine_learning_trading_14_excalidraw](https://user-images.githubusercontent.com/80844686/124670576-0747a400-de69-11eb-97f2-8916e3ca93bf.jpg)

## Contributors

This project was made with helpful contribuitions from Berkeley Fintech Bootcamp members. 

This code was written by Nestor Ramirez.

email: nestorramirez3994@gmail.com

Linkedin: (https://www.linkedin.com/in/nestor-ramirez-cuadro-375654209/)


## License
MIT
