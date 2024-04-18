# A-as-de-Empresas-Python
lista de exercícios 2

import random
import time

valor_acao_a = 76.40
valor_acao_b = 55.78

print("Valor das Ações:")
print(f"A - Empresa A (R$ {valor_acao_a:.2f})")
print(f"B - Empresa B (R$ {valor_acao_b:.2f})")

print("Dia 1")
time.sleep(3)
print("...")

percentual_variacao = random.uniform(-5, 5)
variacao = valor_acao_a * (percentual_variacao / 100)
valor_acao_a += variacao

percentual_variacao = random.uniform(-5, 5)
variacao = valor_acao_b * (percentual_variacao / 100)
valor_acao_b += variacao

print("Valor das Ações:")
print(f"A - Ações Empresa A (R$ {valor_acao_a:.2f})")
print(f"B - Ações Empresa B (R$ {valor_acao_b:.2f})")

print("Dia 2")
time.sleep(3)
print("...")

percentual_variacao = random.uniform(-5, 5)
variacao = valor_acao_a * (percentual_variacao / 100)
valor_acao_a += variacao

percentual_variacao = random.uniform(-5, 5)
variacao = valor_acao_b * (percentual_variacao / 100)
valor_acao_b += variacao
