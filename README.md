# AWS_Robo_Adviser
Lex bot created using AWS Lex and Lambda functions to deliver an automated chat service detailing risk on an investment.

---

## Technologies

Language: Python 

[Amazon Lex](https://aws.amazon.com/lex/) - AWS service for creating automated chat bots

[Amazon Lambda](https://aws.amazon.com/lambda/) - AWS service for creating complex functions for use in other AWS services such as Lex



---

## Installation Guide

There is nothing to install as Amazon Web Services are accessed through **[aws.amazon.com](aws.amazon.com)**


---

## Usage

I have not published this bot so there is no public usage at this point. There are GIFs below showing how it works.

Ultimately the user inputs their first name, age, amount for investment and their risk level.

The bot stores this information and recommends a split of bonds (AGG) and/or stocks (SPY)


---

## Overview of Project

### Bot Set Up

Slots:
<div style="text-align: left"><img src="./images/slots.png" width="600" /></div>

Utterances:
<div style="text-align: left"><img src="./images/utterances.png" width="600" /></div>


### Helper Functions
<div style="text-align: left"><img src="./images/validation_function.png" width="600" /></div>
<div style="text-align: left"><img src="./images/recommendation_function.png" width="600" /></div>

### Lambda Function
<div style="text-align: left"><img src="./images/full_function.png" width="600" /></div>

### Test Cases

Incorrect Amount: <div style="text-align: left"><img src="./images/incorrect_amount.png" width="500" /></div>

Negative Age: <div style="text-align: left"><img src="./images/neg_age.png" width="500" /></div>

Too High of an Age: <div style="text-align: left"><img src="./images/age_error.png" width="500" /></div>

Correct Info: <div style="text-align: left"><img src="./images/correct_dialogue.png" width="500" /></div>


### Recommendation Display
<div style="text-align: left"><img src="./images/final_rec.png" width="300" /></div>

---

## Gifs of Bot Working

### Test

![Gif_Test](videos/Lex_Bot_Tst.gif)

### Full Build

![Gif_Full](videos/Lex_Bot_Full_Gif.gif)

> if the gifs are not in high enough resolution just go to:
>[test video](videos/Lex_Bot_Test.mp4) | 
>[full video](videos/Lex_Bot_Full.mp4)

---

## Contributors

Created by Silvano Ross while in the UW FinTech Bootcamp
> Contact Info:
> email: silvanoross3@gmail.com |
> [GitHub](https://github.com/silvanoross) |
> [LinkedIn](https://www.linkedin.com/in/silvano-ross-b6a15a93/)


---

## License

- [MIT](LICENSE)