# 1
# num_str = input("Введите числа через пробел: ")
# num_list = num_str.split()
# num = [int(num) for num in num_list]
# sum_of_num = sum(num)
# print("Сумма чисел:", sum_of_num)

# 2
# def front_x(words):
#     x_words = []
#     other_words = []
#     for word in words:
#         if word.startswith("x"):
#             x_words.append(word)
#         else:
#             other_words.append(word)
#     x_words.sort()
#     other_words.sort()
#     sorted_words = x_words + other_words 
#     return sorted_words
# words = ['mix', 'extra', '', 'x-files', 'xyz', 'xapple', 'apple']
# sorted_words = front_x(words)
# print(sorted_words)

# 3
# def count_donuts(num_donuts):
#     if num_donuts <= 9:
#         return f"Всего пончиков: {num_donuts}"
#     else:
#         return "Всего пончиков: много"
# num_donuts = int(input("Введите количество пончиков: "))
# result = count_donuts(num_donuts)
# print(result)

# 4
# n = int(input("Введите натуральное число n: "))
# sum_num = 0
# for num in range(n + 1):
#     if num % 5 == 0 and num % 3 != 0:
#         sum_num += num
# print("Сумма чисел от 0 до", n, "включительно, которые делятся на 5 без остатка, но на 3 делятся с остатком:", sum_num)

5
def get_substring(str):
    if len(str) < 2:
        return ""
    else:
        return str[:2] + str[-2:]
input_str = input("Введите строку: ")
result = get_substring(input_str)
print(result)
 
