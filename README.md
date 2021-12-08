from random import randint
import random
import math

print ('''

-----------------------
      Class 10d
-----------------------


------------------------------------''')
for i in range(10): #10d
    name = ['David', 'Nikita' , 'Anton', 'Vladslaves', 'batman', 'dima', 'Semion']
    surname = ['Nikolay', 'Vadimich', 'Denisovich', 'Viktorich', 'Mazertti', 'Parmezan', 'DOOMDOOMOVICH']
    score1 = randint(1,10)
    score2 = randint(1, 10)
    score3 = randint(1, 10)
    average1 = (score1 + score2 + score3) /3
    score1 = str(score1)
    score2 = str(score2)
    score3 = str(score3)
    average1 = round(average1)
    average1 = str(average1)
    print(('Name: ') + (random.choice(name)) + (random.choice(surname)))
    print (('Class: 10d'))
    print (('score1: ') + (score1))
    print (('score2: ') + (score2))
    print (('score3: ') + (score3))
    print (('Average score: ') +(average1))
    print('------------------------------------')

