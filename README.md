# Analisador_expressao

Gramática:
E → TE′
E′ → E
E′ → ε
T → FT′
T′ → +E
T′ → −E
T′ → ε
F → VF′
F′→ ∗E
F′ → /E
F′ → ε 
V → num
num → [0 − 9][0 − 9]∗
id → [a−zA − Z][a−zA − Z0 − 9]∗

Exemplo de execução:
Informe expressões para quantos identificadores desejar (a,b,c...). Quando quiser parar deixe em branco e clique em enter. Então o programa vai pedir: "Informe uma expressão aritmética para verificar:"
Informe uma atribuição (A) : 3+5
Informe uma atribuição (B) : 3*3
Informe uma atribuição (C) : 
Informe uma expressão aritmética para verificar: a+B+10

Output:
Expressão informada: A+B+10
Expressão formatada: 3+5+3*3+10
A expressão é válida. Resultado:  27
