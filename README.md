# MemoSystem
Based on Forgetting curve. Help remember things.

##Database Design
id | item | state | round | next_call
2: 20min
3: 1hour
4: 9hour
5: 1day
6: 2day
7: 6day
8: 31day


##API
get: /word
return: page

Choose word from database based on round(8 to 1) and time (old to young)

input = word  
output = word, pronunciation, meaning, example, (sound, picture maybe)

Think of the purpose of your memory.
e.g. If you want to be able to read, you'd choose the vocabulary from the things you are most probably to read about. Then get the high frequency word from it. And then remember it.
You set up a goal and go for it. No other way. Be realistic.
