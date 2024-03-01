Neural Network Model Analysis for Alphabet Soup
Overview
The aim of this project was to help Alphabet Soup, a philanthropic organization, direct their funds more effectively. By analyzing data on past projects they've supported, we aimed to build a neural network that could predict which future projects would be successful. It's like trying to create a crystal ball to see which projects will make the biggest impact.
How I Cracked the Data
Sorting the Data
What I Were Looking For: We focused on whether projects were successful or not, using the IS_SUCCESSFUL column as our guide.
What I Examined: We looked at various details about the projects, like their type, their financial background, and what they aimed to achieve.
What I Ignored: We didn't pay attention to EIN and NAME because these are just identifiers and don't tell us anything about the project's likelihood of success.
Building the Brain
Our Model's Ingredients: We used a mix of 80 neurons at the start and then a smaller group of 30, all stirred together with the ReLU activation function. For the final touch, we added an output layer with a single neuron using the sigmoid function, turning our outputs into predictions.
Did It Work?: Our goal was a model that could predict success over 75% of the time. We got close, with our best model reaching about 73.15% accuracy.
Tweaks and Adjustments: We tried adding more layers, changing the number of neurons, and playing with the model's learning settings. We also got creative with the data itself, trying to present it to the model in the most informative way.
Wrapping Up
Our neural network learned quite a bit from the data and got pretty good at predicting project success, but it didn't quite hit our goal. It's like it's on the edge of greatness but needs a little nudge to get there.

Looking Ahead: Maybe it's time to try a new approach. Ensemble methods, like a team of decision trees (Random Forest) or Gradient Boosting, could bring new insights. They're like a group project where everyone brings their own strengths to the table, potentially leading to better predictions. Plus, they're great at figuring out which features of the projects really matter, which could help fine-tune our predictions even further.

In the end, this journey showed us that while we're on the right path, there's still room to grow and learn. With a few adjustments and maybe a different perspective, we could help Alphabet Soup find the projects that will truly make a difference.
