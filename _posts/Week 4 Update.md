---
published: false
---
## 4 Weeks (almost) Complete!

Weeks 2-4 have been a blur to say the least.. Second project, six challenge sets, and one investigation down and there's still 2/3 of the course left. A lot of hard work and willpower is needed to power through each day of each week, but so far this immersive program has been amazing.

## Diving into Project Luther

For Project Luther, I decided to predict the market value of the athletes in the National Basketball Association (NBA) using regression models. Before beginning the modeling process, I needed to gather data from online. This process was completed through web scraping through 17 years worth of data from _basketball-reference.com_ and _ESPN.com_. 

Once the data collection was finished, I attempted to engineer features I believed to be relevant from my knowledge of basketball. However, through the modeling process I found that the most important feature was actually the age of the player! In hindsight this makes a lot of sense because an athlete's market value is highly dependent on what stage in his career he is at. No matter how great an athlete may be, if he is past his prime then his value is always decreasing. 

After I was satisfied with the base features I wanted to include in my models, I created a pipeline function that would do more feature engineering and feature selection as well as feed the selected features into a dictionary of models _(e.g. Lasso, Ridge, RandomForest, GradientBoost)_. This function allowed me to also tune the hyperparameters within each model individually using the Grid Search method.

Overall, however, my model performed around ~50%. I went into the project hoping to reach upwards of 80-90%, so at first I believed I had fallen short and underachieved. But, soon, I came to realize that the purpose of the project wasn't necessarily to create the _perfect_ model, but to get me thinking like a data scientist. I was able to feature engineer so that my model _improved_. I was able to create functions to streamline my workflow and test models at a much faster rate. 

## Final Thoughts

This program is challenging and I'm always left feeling like I could have done better. But the focus is not on perfection, but on the process. That's something I'll have to keep reminding myself throughout the program and as I begin my career.

