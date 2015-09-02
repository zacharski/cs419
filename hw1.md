##cs419 homework 1

#### How to submit

send email to `submit.o.bot@gmail.com` The subject line should be

    419 homework 1

the contents of the message (in plain text) should be:

    avatar name:
    I hereby declare upon my word of honor that I have neither given 
    nor received unauthorized help on this work
    Initial here as digital signature: 
    (no work accepted without signature)
    
    1. answer to question 1
    2. answer to 2, etc.
    
Here are the questions.

1. This question relates to lab 2. When we looked at recommendations for Sarah we noticed a difference between the top recommendation at checkpoint 1 and that at checkpoint 2. Briefly explain the cause of that difference and how we might fix it.
2. Using the dataset below and using Pearson in the lab 2 recommender class, who is Sarah's nearest neighbor and what is the distance?
3. Using the dataset below and using Pearson in the lab 2 recommender class, are any users exactly negatively correlated with Sarah (I can see this by getting the nearest neighbors). If so, who are these users?
4. Using the dataset below and using Pearson and k=1 in the lab 2 recommender class, what do we predict Sarah's rating of Randy Wood to be?
5. Using the dataset below and using Pearson and k=3 in the lab 2 recommender class, what do we predict Sarah's rating of Randy Wood to be?
6. BONUS (will only be awarded if you get the above questions correct): what genre is Randy Wood? How would you describe his music?

sample data:
    
    r = {'Sarah':    {'Taylor Swift': 5, 'Carrie Underwood': 5, 
                      'Jhené Aiko': 2, 'Kelela': 2},
         'Miguel':   {'Taylor Swift': 2, 'Jhené Aiko': 4, 
                      'Kelela': 5, 'Tinashe': 5, 'Randy Wood': 1},
         'Tyler':    {'Taylor Swift': 4, 'Miranda Lambert': 4, 
                      'Carrie Underwood': 5, 'Jhené Aiko': 2, 
                      'Kelela': 2, 'Tinashe': 1, 'Randy Wood': 1},
         'Ann':      {'Taylor Swift': 2, 'Miranda Lambert': 3,  
                      'Jhené Aiko': 5, 'Kelela': 5,  
                      'Randy Wood': 1},
         'Jessica':  {'Taylor Swift': 2, 'Miranda Lambert': 1,  
                      'Jhené Aiko': 5, 'Randy Wood': 1},
         'Franklin': {'Taylor Swift': 4, 'Miranda Lambert': 5, 
                      'Carrie Underwood': 5, 'Jhené Aiko': 2, 
                      'Kelela': 3, 'Tinashe': 2, 'Randy Wood': 2},
         'Jenny':    {'Taylor Swift': 4, 'Miranda Lambert': 4, 
                      'Carrie Underwood': 4, 'Jhené Aiko': 1, 
                      'Kelela': 1, 'Tinashe': 1, 'Randy Wood': 5},
         'Clara':    {'Taylor Swift': 1, 'Miranda Lambert': 1,  
                      'Jhené Aiko': 5, 'Kelela': 5,  'Randy Wood': 5}    
          }