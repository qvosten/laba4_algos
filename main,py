text = input("Введите текст ")

words = text.split()

cnt_word = {}

for word in words:
    if word in cnt_word:
        cnt_word[word] += 1
    else:
        cnt_word[word] = 1

sorted_words = sorted(cnt_word.keys())
for i in sorted_words:
    print(f'{i} -> {cnt_word[i]}')
    

