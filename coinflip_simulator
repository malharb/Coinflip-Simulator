#coin flip simulator
import random
outcome = ['heads','tails']
def coinflipsimulator(x):
    heads_count = 0
    tails_count = 0
    for coins in range(x):
        coinflip = outcome[random.randint(0,1)]
        if coinflip == outcome[0]:
            heads_count = heads_count + 1
        else:
            tails_count = tails_count + 1

    heads_count_percentage = (heads_count/x)*100
    tails_count_percentage = 100 - heads_count_percentage

    print(f'The coin landed with heads up, {heads_count} times')
    print(f'The coin landed with tails up, {tails_count} times')

    print(f'{heads_count_percentage}% of the coinflips, resulted in the coin landing with heads up')
    print(f'{tails_count_percentage}% of the coinflips, resulted in the coin landing with tails up')

x = input('How many times would you like to simulate the coin flip?: ')
x = int(x)

coinflipsimulator(x)
