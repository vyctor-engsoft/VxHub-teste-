print('=====[ Bem-Vindo(a) ao Vxhub]=====')

X1 = str(input('Digite o seu nome: '))
X2 = int(input('Digite a sua idade: '))
X3 = int(input('Digite seu CEP: '))
X4 = int(input('Digite o seu CPF: '))
X5 = int(input('Digite o seu numero de telefone: '))

dados = {
    'nome': X1,
    'idade': X2,
    'cep': X3,
    'cpf': X4,
    'telefone': X5,
}

print('LISTA:')
print(f"Nome = {dados['nome']}")
print(f"Idade = {dados['idade']}")
print(f"CEP = {dados['cep']}")
print(f"CPF = {dados['cpf']}")
print(f"Telefone = {dados['telefone']}")

print("Dicionário completo:")
print(dados.items())