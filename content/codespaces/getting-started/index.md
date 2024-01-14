import hashlib

roulette_hash = "DF1A65C1A4357A70489B3BEB4352906D"

# Преобразуем хеш в число
hash_number = int(roulette_hash, 16)

# Получаем последние 2 символа хеша
last_two_digits = hash_number % 100

print("Случайное число: {}".format(last_two_digits))
