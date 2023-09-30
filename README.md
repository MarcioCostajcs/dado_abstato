# dado_abstato
# Criando conjuntos
conjunto_A = {1, 2, 3}
conjunto_B = {3, 4, 5}

# Inserção
conjunto_A.add(6)

# Remoção
conjunto_A.remove(2)

# Consulta
if 3 in conjunto_A:
    print("3 pertence ao conjunto A")

# União
uniao = conjunto_A.union(conjunto_B)  # Também pode ser feito com o operador "|"
print("União:", uniao)

# Interseção
intersecao = conjunto_A.intersection(conjunto_B)  # Também pode ser feito com o operador "&"
print("Interseção:", intersecao)

# Diferença
diferenca = conjunto_A.difference(conjunto_B)  # Também pode ser feito com o operador "-"
print("Diferença:", diferenca)
