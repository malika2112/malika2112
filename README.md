def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Пример использования функции для вычисления факториала
n = int(input("Введите число: "))
факториал = factorial(n)
print(f"{n}! = {факториал}")
