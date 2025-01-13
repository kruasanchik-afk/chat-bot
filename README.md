# chat-bot
 это мой первый проект к сожалению он мало что умеет

print(
    '''
привет я чат бот 
вот список команд которые я умею 
1 - рекомендации по музыке
2 - рекомендации по фильмам
3 - рекомендации по играм
4 - мини игра угадай число 
help - для вывода списка команд 
stop - для остановки бота
'''
)

ans = input("назовите команду")
while ans != "stop":
    if ans == "1":
        genre = input("введите жанр музыки")
        if genre == "джаз":
            print("можете послушать Луи Армстронг")
        elif genre == "r&b":
            print("можете послушать исполнителя jason derulo")
        elif genre == "metal":
            print("можете послушать группу металика")
        else :
            print("бот пока незнает такого жанра")
    elif ans == "2":
        genre = input("введите жанр фильма")
        if genre == "комедия":
            print("елки")
        elif genre == "боевик":
            print("терминатор")
        elif genre == "фантастика":
            print("звездные войны")
        else :
            print("бот пока незнает такого жанра")
    elif ans == "3":
        genre = input("введите жанр игры")
        if genre == "шутер":
            print("call of duty")
        elif genre == "симулятор":
            print("euro track simulator")
        elif genre == "песочница":
            print("mincraft")
        else :
            print("бот пока незнает такого жанра")
    elif ans == "4":
        from random import randint
        number = randint(1,100)
        tries = 0
        while 10 > tries:
            answer = int(input("введите число"))
            if number == answer:
                print("поздравляю вы победили")
                break
            elif answer > number:
                print("вы написали слишком большое число")
            elif answer < number:
                print("вы написали слишком маленькое число")
            tries += 1
    elif ans == "help":
        
        print(
    '''
привет я чат бот 
вот список команд которые я умею 
1 - рекомендации по музыке
2 - рекомендации по фильмам
3 - рекомендации по играм
4 - мини игра угадай число 
help - для вывода списка команд 
stop - для остановки бота
'''
)
        


                


    ans = input("назовите команду")



