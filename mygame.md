# The codes of my game 'Butterfly Village'
```.py
message= '🦋 Welcome to the butterfly village. In this game you will test your knowledge in crytals, herbs and astrology and compete for the highest place on the butterfly score chart. Wish you the best of luck 🦋'
space='                                                             '
butterfly_line='🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋🦋'
print(message)
print(space)
print(butterfly_line)
user_name=input('🦋 Please enter your name or a name that you want to be referred🦋 ')
label=int(input('🦋 Now please choose a label for yourself. This will stick your name throughout the game🦋 \n 🧚 press 1 for fairy \n 🧙‍ press 2 for witch  \n 🧛 press 3 for vampire'))
if label<4:
   if label == 1:
       print('🦋Your username will be 🧚fairy' + user_name)
   if label == 2:
       print('🦋Your username will be 🧙witch' + user_name)
   if label == 3:
       print('🦋Your username will be 🧛vampire' + user_name)
else:
   print('🦋Please select a title .')

print(space)
choose_forest=int(input('🦋Now we will move on to our knowledge-test part! In this part we will ask you to choose a forest to test your knowledge .🦋 \n 🌸 press 1 for Crsytal Forest \n 🌸 press 2 for Herbs Forest \n 🌸 press 3 for Astrology Forest  '))
if choose_forest<4:
  if choose_forest==1:
      print('🦋 You have chosen the Crystal Forest . You will receive five questions listed from easy to hard.Here comes your first question.🦋' )
      print(space)
      cq_1=int(input('🦋Which crystal you are not supposed to put in the water? \n 1)Clear quartz \n 2)Ruby \n 3)Aventurine \n 4)Tiger’s Eye '))
      answerc1=0
      if cq_1<5:
          if cq_1==1:
              print('🦋Your answer was not right ')
              answerc1+=0
          if cq_1==2:
              print('🦋Your answer was right ')
              answerc1+=1
          if cq_1==3:
              print('🦋Your answer was not right ')
              answerc1+=0
          if cq_1==4:
              print('🦋Your answer was not right ')
              answerc1+=0
      cq_2=int(input('🦋What is the type of crystal that is mostly found on Earth? \n 1)Amethyst \n 2)Calcite \n 3)Opal \n 4)Quartz '))
      answerc2=0
      if cq_2<5:
          if cq_2==1:
              print('🦋Your answer was not right ')
              answerc2+=0
          if cq_2==2:
              print('🦋Your answer was not right ')
              answerc2+=0
          if cq_2==3:
              print('🦋Your answer was not right ')
              answerc2+=0
          if cq_2==4:
              print('🦋Your answer was right ')
              answerc2+=1
      cq_3 = int(input('🦋What is the rarest type of crystal in the world?  \n 1)Red Beryl \n 2)Benitoite \n 3)Taaffeite \n 4)Painite '))
      answerc3=0
      if cq_3<5:
          if cq_3==1:
              print('🦋Your answer was not right ')
              answerc3+=0
          if cq_3==2:
              print('🦋Your answer was not right ')
              answerc3+=0
          if cq_3==3:
              print('🦋Your answer was  right ')
              answerc3+=0
          if cq_3==4:
              print('🦋Your answer was not  right ')
              answerc3+=1
      cq_4 = int(input('🦋Which crystal is the one that you can place under sun? \n 1)Hiddenite \n 2)Calcite \n 3)Prasiolite \n 4)Malachite '))
      answerc4=0
      if cq_4 == 1:
          print('🦋Your answer was not right ')
          answerc4 += 0
      if cq_4 == 2:
          print('🦋Your answer was not right ')
          answerc4 += 0
      if cq_4 == 3:
          print('🦋Your answer was not right ')
          answerc4 += 0
      if cq_4 == 4:
          print('🦋Your answer was  right ')
          answerc4 += 1
      cq_5 = int(input('🦋Which crystal is not believed to work with anxiety? \n 1)Amethyst \n 2)Malachite \n 3)Rhodonite \n 4)Moonstone '))
      answerc5=0
      if cq_5 == 1:
          print('🦋Your answer was not right ')
          answerc5 += 0
      if cq_5 == 2:
          print('🦋Your answer was right ')
          answerc5 += 5
      if cq_5 == 3:
          print('🦋Your answer was not right ')
          answerc5 += 0
      if cq_5 == 4:
          print('🦋Your answer was not right ')
          answerc5 += 0
      print('🦋Your total score is :')
      print(answerc1+answerc2+answerc3+answerc4+answerc5)
  if choose_forest==2:
      print('🦋 You have chosen the Herbs Forest . You will receive five questions listed from easy to hard.Here comes your first question.🦋')
      print(space)
      ch_1 = int(input('🦋Which herb is not supposed to be used in a state of anxiety? \n 1)Chamomille \n 2)Lavender \n 3)Lemon \n 4)Passion Flower' ))
      answerh1 = 0
      if ch_1 == 1:
          print('🦋Your answer was not right ')
          answerh1 += 0
      if ch_1 == 2:
          print('🦋Your answer was not right ')
          answerh1 += 0
      if ch_1 == 3:
          print('🦋Your answer was right ')
          answerh1 += 1
      if ch_1 == 4:
          print('🦋Your answer was not right ')
          answerh1 += 0
      ch_2 = int(input('🦋What is the oldest herb? \n 1)Salt \n 2)Gingko  \n 3)Cinnamon \n 4)Pepper'))
      answerh2 = 0
      if ch_2 == 1:
          print('🦋Your answer was not right ')
          answerh2 += 0
      if ch_2 == 2:
          print('🦋Your answer was right ')
          answerh2 += 2
      if ch_2 == 3:
          print('🦋Your answer was not right ')
          answerh2 += 0
      if ch_2 == 4:
          print('🦋Your answer was not right ')
          answerh2 += 0
      ch_3 = int(input('🦋What is most used herb in the world? \n 1)Cumin \n 2)Sugar  \n 3)Basil \n 4)Salt'))
      answerh3 = 0
      if ch_3 == 1:
          print('🦋Your answer was right ')
          answerh3 += 3
      if ch_3 == 2:
          print('🦋Your answer was not right ')
          answerh3 += 0
      if ch_3 == 3:
          print('🦋Your answer was not right ')
          answerh3 += 0
      if ch_3 == 4:
          print('🦋Your answer was not right ')
          answerh3 += 0
      ch_4 = int(input('🦋What is most expensive herb type in the world? \n 1)Caraway seeds \n 2)Asafoetida \n 3)Sumac \n 4)Saffron'))
      answerh4 = 0
      if ch_4 == 1:
          print('🦋Your answer was not right ')
          answerh4 += 0
      if ch_4 == 2:
          print('🦋Your answer was not right ')
          answerh4 += 0
      if ch_4 == 3:
          print('🦋Your answer was not right ')
          answerh4 += 0
      if ch_4 == 4:
          print('🦋Your answer was right ')
          answerh4 += 4
      ch_5 = int(input('🦋Which one actually count as a herb? \n 1)Salt \n 2)Mud \n 3)Leaf \n 4)Banana'))
      answerh5 = 0
      if ch_5 == 1:
          print('🦋Your answer was not right ')
          answerh5 += 0
      if ch_5 == 2:
          print('🦋Your answer was not right ')
          answerh5 += 0
      if ch_5 == 3:
          print('🦋Your answer was not right ')
          answerh5 += 0
      if ch_5 == 4:
          print('🦋Your answer was right ')
          answerh5 += 5
      print('🦋Your total score is :')
      print(answerh1+answerh2+answerh3+answerh4+answerh5)
  if choose_forest==3:
      print('🦋 You have chosen the Astrology Forest . You will receive five questions listed from easy to hard.Here comes your first question.🦋')
      print(space)
      ca_1 = int(input('🦋If someone was born in 12th of January, what is their sign? \n 1)Sagittarius \n 2)Aquarius \n 3)Capricorn \n 4)Pisces' ))
      answera1 = 0
      if ca_1 == 1:
          print('🦋Your answer was not right ')
          answera1 += 0
      if ca_1 == 2:
          print('🦋Your answer was not right ')
          answera1 += 0
      if ca_1 == 3:
          print('🦋Your answer was right ')
          answera1 += 1
      if ca_1 == 4:
          print('🦋Your answer was not right ')
          answera1 += 0
      ca_2 = int(input('🦋Which is not one of the most common signs? \n 1)Leo \n 2)Cancer \n 3)Virgo \n 4)Scorpio '))
      answera2 = 0
      if ca_2 == 1:
          print('🦋Your answer was not right ')
          answera2 += 0
      if ca_2 == 2:
          print('🦋Your answer was not right ')
          answera2 += 0
      if ca_2 == 3:
          print('🦋Your answer was not right ')
          answera2 += 0
      if ca_2 == 4:
          print('🦋Your answer was right ')
          answera2 += 2
      ca_3 = int(input('🦋Which is the rarest sign? \n 1)Capricorn \n 2)Gemini \n 3)Aries \n 4)Aquarius '))
      answera3 = 0
      if ca_3 == 1:
          print('🦋Your answer was right ')
          answera3 += 3
      if ca_3 == 2:
          print('🦋Your answer was not right ')
          answera3 += 0
      if ca_3 == 3:
          print('🦋Your answer was not right ')
          answera3 += 0
      if ca_3 == 4:
          print('🦋Your answer was not right ')
          answera3 += 0
      ca_4 = int(input('🦋Which is not a full moon date in 2021? \n 1)April 27  \n 2)July 24  \n 3)January 17  \n 4)August 22 '))
      answera4 = 0
      if ca_4 == 1:
          print('🦋Your answer was not right ')
          answera4 += 0
      if ca_4 == 2:
          print('🦋Your answer was not right ')
          answera4 += 0
      if ca_4 == 3:
          print('🦋Your answer was right ')
          answera4 += 4
      if ca_4 == 4:
          print('🦋Your answer was not right ')
          answera4 += 0
      ca_5 = int(input('🦋When was the last solar eclipse? \n 1)December 14 2020  \n 2)January 14 1997 \n 3)October 3 2021  \n 4)March 30 1562 '))
      answera5 = 0
      if ca_5 == 1:
          print('🦋Your answer was right ')
          answera5 += 5
      if ca_5 == 2:
          print('🦋Your answer was not right ')
          answera5 += 0
      if ca_5 == 3:
          print('🦋Your answer was not right ')
          answera5 += 0
      if ca_5 == 4:
          print('🦋Your answer was not right ')
          answera5 += 0
      print('🦋Your total score is :')
      print(answera1 + answera2 + answera3 + answera4 + answera5)
  print('🦋Thanks for playing the game. We hope you like it ! Cannot wait to see you again🦋')
  print('🦋You can also try to test your knowledge in other forest.Wish you the best of luck!🦋')
  ```
