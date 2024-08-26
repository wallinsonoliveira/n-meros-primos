# Números Primos

Números primos são números naturais maiores que 1 que têm exatamente dois divisores positivos distintos: 1 e eles mesmos. Ou seja, um número primo só pode ser dividido por 1 e por ele mesmo sem deixar resto.

Números primos desempenham um papel fundamental na criptografia moderna, especialmente em sistemas de criptografia de chave pública, como o *RSA*. A segurança desses sistemas depende da dificuldade de fatorar grandes números compostos em seus fatores primos.

### Sumário
- 🎬 [Introdução](#-Introdução)
- 🔎 [Procurando por Padrões](#-procurando-por-padrões)
- 🔢 [Primo de Mersenne](#-primo-de-mersenne)
- 💰 [Hipótese de Riemann](#-hipótese-de-riemann)
- 📟 [Teste de Lucas-Lehmer](#-teste-de-lucas-lehmer)


### 🎬 Introdução

Encontrar um padrão simples e previsível para os números primos é um dos grandes desafios da matemática, e até agora, não existe um padrão óbvio ou fórmula simples que gere todos os números primos. No entanto, existem algumas observações e propriedades importantes que ajudam a entender a distribuição dos números primos:

**Propriedades e Padrões Observados:**
1. Primos e Progressões Aritméticas:

- Os números primos, após o 2, são todos números ímpares. Como o 2 é o único número primo par, todos os outros primos devem estar na forma *2𝑛 + 1*, onde *n* é um número inteiro.
- Nenhum número primo maior que 3 pode ser múltiplo de 3, então, para *𝑛 ≥ 5*, os números primos têm a forma *6𝑘 ± 1* (onde *k* é um número inteiro), mas nem todos os números dessa forma são primos.

2. Teorema dos Números Primos:

- Este teorema descreve a distribuição dos números primos entre os números naturais. Ele afirma que a densidade dos números primos diminui à medida que os números aumentam, mas eles continuam a aparecer indefinidamente.
- Aproximadamente, o número de primos menores que um dado número *n* é cerca de *𝑛/ln(𝑛)*, onde *ln(n)* é o logaritmo natural de *n*.

3. Seqüências e Gaps entre Primos:

- Os números primos não são espaçados uniformemente; os gaps (intervalos) entre números primos aumentam à medida que os números se tornam maiores.
- Às vezes, números primos aparecem em pares próximos, como 11 e 13, 17 e 19, 29 e 31, chamados `primos gêmeos`. A conjectura dos primos gêmeos sugere que existem infinitos tais pares, embora isso ainda não tenha sido provado.

4. Espaçamento Irregular:

- Não há uma fórmula geral para prever onde o próximo número primo estará. Por exemplo, após o número primo 89, o próximo primo é 97, um gap de 8 números, enquanto o próximo após 97 é 101, um gap de apenas 4.

**Conjecturas e Resultados Avançados**

1. Conjectura de Goldbach:
- A conjectura sugere que todo número par maior que 2 pode ser expresso como a soma de dois números primos, mas isso ainda não foi provado para todos os números.

2. Hipótese de Riemann:
- Relacionada à distribuição dos números primos, a hipótese de Riemann sugere que todos os zeros não triviais da função zeta de Riemann têm uma parte real de *1/2*. A sua solução pode trazer um entendimento mais profundo sobre a distribuição dos primos.

**Conclusão**
Embora existam padrões e propriedades que descrevem como os números primos se comportam, não há uma fórmula simples que gere todos os números primos. Eles permanecem distribuídos de forma complexa e imprevisível, o que os torna fascinantes tanto para a matemática teórica quanto para a criptografia.

### 🔎 Procurando Por Padrões

### 🔢 Primo de Mersenne

### 💰 Hipótese de Riemann

### 📟 Teste de Lucas-Lehmer
