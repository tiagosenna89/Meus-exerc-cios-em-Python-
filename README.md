# Meus-exerc-cios-em-Python-
# Meus Estudos em Python

Este repositório reúne exercícios básicos de Python que venho praticando para aprimorar meus conhecimentos em programação.  
Os códigos incluem:  

- Cálculo de média de notas  
- Contagem de palavras em uma frase  
- Análise simples de uma lista de números (máximo, mínimo e média)  

## Sobre def sao_anagramas(s1, s2):
    return sorted(s1.replace(" ", "").lower()) == sorted(s2.replace(" ", "").lower())

# Exemplos
print(sao_anagramas("Roma", "Amor"))  # True
print(sao_anagramas("Python", "Typhon"))  # True
print(sao_anagramas("ChatGPT", "GPTChat"))  # True
print(sao_anagramas("Teste", "Best"))  # False

ordenacao da def ordenar_lista(lista):
    return sorted(lista, key=lambda x: (len(x), x.lower()))

# Exemplo
palavras = ["uva", "abacaxi", "banana", "kiwi", "pera", "maçã", "abacate"]
print(ordenar_lista(palavras))
# Saída: ['kiwi', 'uva', 'pera', 'maçã', 'banana', 'abacate', 'abacaxi']

encontrando def sao_anagramas(s1, s2):
    return sorted(s1.replace(" ", "").lower()) == sorted(s2.replace(" ", "").lower())

# Exemplos
print(sao_anagramas("Roma", "Amor"))  # True
print(sao_anagramas("Python", "Typhon"))  # True
print(sao_anagramas("ChatGPT", "GPTChat"))  # True
print(sao_anagramas("Teste", "Best"))  # False
Meu nome é Tiago Sena de Oliveira.  

expressões matemáticas 

def validar_parenteses(expressao):
    pilha = []
    pares = {'(': ')', '[': ']', '{': '}'}

    for char in expressao:
        if char in pares:
            pilha.append(char)
        elif char in pares.values():
            if not pilha or pares[pilha.pop()] != char:
                return False
    return not pilha

# Exemplos
print(validar_parenteses("(2+3)*[5/{7-3}]"))  # True
print(validar_parenteses("(2+3]*5"))          # False

## Contato

- LinkedIn: https://www.linkedin.com/in/tiago-sena-8482617a  
- E-mail: tgo.senna@hotmail.com

---

Sinta-se à vontade para explorar os códigos, dar sugestões ou contribuir.  
Obrigado por visitar!
