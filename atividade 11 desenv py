from colorama import init, Fore, Style

init()

niveis = [
    "Muito baixo",
    "Baixo",
    "Médio",
    "Alto",
    "Muito alto"
]

def mostrar_cor(n):
    if n == 0:
        return Fore.RED
    elif n == 1:
        return Fore.YELLOW
    elif n == 2:
        return Fore.GREEN
    elif n == 3:
        return Fore.CYAN
    else:
        return Fore.BLUE

for i in range(len(niveis)):
    print(mostrar_cor(i) + "Nível " + str(i+1) + ": " + niveis[i])

print(Style.RESET_ALL)
