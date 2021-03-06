# Best11-Fantasycricket

Project made by: Royston(lucasace),Shreyas (SRP457), Sammith(SammithSB)</br>


# Description 

In the past year or so fantasy cricket has been getting a lot of traction and with recent deal struck by Dream11 with IPL, more people are playing fantasy cricket than ever, but the problem is lot of people do not make right choices in choosing the team and end up thinking winning is all about luck and nothing else. With our project we want to break that myth by making a model which when given with players predicts the best 11 that will have the most points in the fantasy league. We have gathered statistics of players throughput their career and the model takes in the scores last 5 games a player has played and it tries to predict his score in the next game using a linear model. The model also makes sure that best 11 follows all the rules of selecting a team given by the fantasy league which includes given number of batsman and bowlers, maintaining spent credits within 100. A flask model has been used to create the GUI to show the predicted 11.

## Requirements

1. Flask
2. sklearn

Install using </br>
```bash
pip3 install Flask
pip3 install sklearn
```

## I want to run your project

To run our project follow these steps

1. Clone our repo into your system using 
 ```bash
  git clone https://github.com/lucasace/Best11-Fantasycricket.git
  ```
  OR
 
 ```bash
 gh repo clone lucasace/Best11-Fantasycricket
 
 ```
2. Change your directory to 'Best11-Fantasycricket' using
```bash
cd Best11-Fantasycricket
``` 

3. Run the files : 
```bash
python3 'Final Project'/Flask.py

```
5. Open http://127.0.0.1:5000/  and voila!! 

## How do you verify your model??

We use six matches from the World Cup 2019 for our verification as of now,namely

* England vs Australia League Stage
* England vs Australia SemiFinal
* India vs New Zealand SemiFinal
* India vs Australia
* India vs Bangladesh QuarterFinal
* England vs India

During the ICC World Cup the winners of the fantasy cricket league was shown and their respective scores were also showed.
</br>We use those scores to match our models score.

We predict the team and calculate the dream 11 score of each player for that match and match it with the winning score and calculate loss.   
</br>

To check how our model worked in our test data run : 

```bash
python3 'Final project'/check.py 

```
## Dataset

Confused by the dataset, Dont Worry I would be too if I were you, dont worry I'll walk you through it in detail

Click on this [link](https://github.com/lucasace/Best11-Fantasycricket/blob/master/Dataset.md) to understand the dataset, the scoring system and any other doubts u might have

## How do I contribute to this project????

We have created two issues for you in the Issues section namely Web Scraping and The algorithm </br></br>
To contribute to this project, first fork the repo then , You can complete the problems presented in each issue and set up a Pull Request, If we think it helps the project or if you have fulfilled the requirements , we will merge it and CONGRATULATIONS, you are a contributor</br></br>
Note: You dont need to complete all the points in the issues to become a contributor , if you complete any one point in any issue you can set up a pull request, except for the web scraping points 1 and 2 which has to be submitted together
</br></br>
If you have any suggestions for our project , do raise a issue and we will look into it and if we think it helps our project we will keep it open until its implemented by us or by anyone else 
</br></br>
If you have any questions regarding our project , you can contact any of the maintainers(info on respective profile pages) or raise a issue and we'll answer you as soon as possible.  

## Thank You 

We would like to thank [Howstat](http://www.howstat.com/cricket/home.asp) for their amazing website with daily updates and availabilty to scrape 

If you liked our project we would really appreciate you starring this repo.

Thank you
