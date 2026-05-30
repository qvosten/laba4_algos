# Лабораторная работа 4 (Подсчёт слов в тексте)

## Описание задачи
### Необходимо реализовать программу, которая анализирует текст и считает, сколько раз встречается каждое слово.

## Создание и заполнение словаря, где ключом является само слово, а значением — количество его повторений в тексте

```python

words = text.split()

cnt_word = {}

for word in words:
    if word in cnt_word:
        cnt_word[word] += 1
    else:
        cnt_word[word] = 1

```

## Вывод результата в отсортированном виде(по алфавиту)
```python
sorted_words = sorted(cnt_word.keys())
for i in sorted_words:
    print(f'{i} -> {cnt_word[i]}')
```
## Пример работы 

<img width="723" height="161" alt="image" src="https://github.com/user-attachments/assets/38b3a083-d522-47da-90d5-4aa237b78fb4" />
