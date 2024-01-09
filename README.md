import itertools

# Caractères possibles pour le mot de passe
chars = 'abcdefghijklmnopqrstuvwxyz0123456789'

# Longueur du mot de passe
n = 6

# Génère toutes les combinaisons possibles de caractères
for password in itertools.product(chars, repeat=n):
    print(''.join(password))
