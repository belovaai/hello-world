1.
a=int(input())
if a>7:
    print("Привет")
2.
a=str(input())
if a=="Вячеслав":
    print("Привет, Вячеслав")
else:
    print("Нет такого имени")
3.
Massiv_V=[int(x) for x in input().split()]
for x in Massiv_V:
    if x%3==0:
        print(x)
4.	Дана скобочная последовательность: [((())()(())]]
- Можно ли считать эту последовательность правильной?
- Если ответ на предыдущий вопрос “нет” - то что необходимо в ней изменить, чтоб она стала правильной?
Предпоследняя скобка должна быть круглой.
