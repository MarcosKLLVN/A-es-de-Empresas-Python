import random
import time

valor_acao_a = 76.40
valor_acao_b = 55.78
valor_acao_c = 68.28

print("Valor das Ações:")
print(f"A - Empresa A (R$ {valor_acao_a:.2f})")
print(f"B - Empresa B (R$ {valor_acao_b:.2f})")
print(f"C - Empresa C (R$ {valor_acao_c:.2f})")

print("Dia 1", end="", flush=True)
for i in range(10):
    time.sleep(0.3)
    print("...", end="", flush=True)

percentual_variacao = random.uniform(-5, 5)
variacao = valor_acao_a * (percentual_variacao / 100)
valor_acao_a += variacao

percentual_variacao = random.uniform(-5, 5)
variacao = valor_acao_b * (percentual_variacao / 100)
valor_acao_b += variacao

porcentual_variacao = random.uniform(-5, 5)
variacao = valor_acao_c * (porcentual_variacao / 100)
valor_acao_c += variacao

print("Valor das Ações:")
print(f"A - Ações Empresa A (R$ {valor_acao_a:.2f})")
print(f"B - Ações Empresa B (R$ {valor_acao_b:.2f})")
print(f"C - Ações Empresa C (R$ {valor_acao_c:.2f})")

print("Dia 2", end="", flush=True)
for i in range(10):
    time.sleep(0.3)
    print("...", end="", flush=True)


percentual_variacao = random.uniform(-5, 5)
variacao = valor_acao_a * (percentual_variacao / 100)
valor_acao_a += variacao

percentual_variacao = random.uniform(-5, 5)
variacao = valor_acao_b * (percentual_variacao / 100)
valor_acao_b += variacao

porcentual_variacao = random.uniform(-5, 5)
variacao = valor_acao_c * (porcentual_variacao / 100)
valor_acao_c += variacao

print("Valor das Ações:")
print(f"A - Ações Empresa A (R$ {valor_acao_a:.2f})")
print(f"B - Ações Empresa B (R$ {valor_acao_b:.2f})")
print(f"C - Ações Empresa C (R$ {valor_acao_c:.2f})")


print("Dia 3", end="", flush=True)
for i in range(10):
    time.sleep(0.3)
    print("...", end="", flush=True)

percentual_variacao = random.uniform(-5, 5)
variacao = valor_acao_a * (percentual_variacao / 100)
valor_acao_a += variacao

percentual_variacao = random.uniform(-5, 5)
variacao = valor_acao_b * (percentual_variacao / 100)
valor_acao_b += variacao

porcentual_variacao = random.uniform(-5, 5)
variacao = valor_acao_c * (porcentual_variacao / 100)
valor_acao_c += variacao


