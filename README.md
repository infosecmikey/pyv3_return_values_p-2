# pyv3_return_values_p-2

# return value exercise

def greet(lang) :
    if lang == 'es':
        return 'Hola,'
    elif lang == 'fr':
        return 'Bonjour,'
    elif lang == 'de':
        return 'Hallo,'
    else:
        return 'Hello,'

print(greet('en'), 'Glenn')
print(greet('es'), 'Sally')
print(greet('fr'), 'Michael')
print(greet('de'), 'Finn')
