# Operadores Lógicos

| Nº | Variáveis                      | Sentença                                | **Resultado** |
|----|--------------------------------|-----------------------------------------|---------------|
| 1  | nota = 10                      | nota <= 10                              | **True**      |
| 2  | nota = 6 faltas = 4            | (nota <= 6) and (faltas <= 3)           | **False**     |
| 3  | convidados = 3 fumante = False | (convidados > 4) or (fumante == True)   | **False**     |
| 4  | dia = “qua”                    | (dia == “sab”) or (dia == “dom”)        | **False**     |
| 5  | feriado = True                 | not(feriado == False)                   | **True**      |
| 6  | dia = “ter” feriado = False    | (dia == “seg”) or not(feriado == False) | **False**     |
