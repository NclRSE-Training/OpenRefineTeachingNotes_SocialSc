Perform the same clean up steps and customized text faceting for the ```months_lack_food column```. Which month(s) were farmers more likely to lack food?

**Solution**

All four cleaning steps can be performed by combining ```.replace statements```. The command is: ```value.replace("[", "").replace("]", "").replace(" ", "").replace("'", "")``` This can also be done in four separate steps if preferred. November was the most common month for respondents to lack food.

[Episode 2 Exercise 5](episode2_ex5.md)
