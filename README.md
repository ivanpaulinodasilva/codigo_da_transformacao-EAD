# 🎲 Código da Transformação - EAD 🐍☁️💻
Nosso primeiro repositório do Código da Transformação.

## 👥 Participantes Organizados

### 🌅 Manhã (Segunda e Terça)
* Anthony Bezerra
* Beatriz Borges
* C. Adriano
* Cauã José
* Diego Farias
* Gabriel Lima
* Gabriele Campos
* Henrique Souza
* Juan Pablo
* Laís Renata
* Luan Seiji
* Marcos Nobre
* Maria Matos
* Pedro Henrique
* Rafael Araújo
* Rychard Rodrigues
* Samuel Paiva
* Vinicius Batista

### 🌆 Tarde (Segunda e Terça)
* Alicya Duarte
* Allan Costa
* Ana Nascimento
* Claudomiro Santos
* Davi Lima
* Fellipe Lima
* Gustavo Jesus
* Igor Batista
* João Teles
* Julio Ilidio
* Lana Reis
* Larissa Silva
* Leandro Xavier
* Lorenzo Carmo
* Luis Gentil
* Luiz Silva
* Miguel Alves
* Milena Oliveira
* Nicolly Gonçalves
* Paulo Nascimento
* Richard Pimenta
* Thalya Alcantara
* Thierry Duarte
* Yuri Santana

---

## 📂 Projetos por Tema

### 🍔 Hamburgueria / Burguer
* **Grupo 1:** Marcos Nobre, Samuel Paiva, Diego Farias.
* **Grupo 2:** Gabriel Lima, Gabriele Campos, Maria Matos, Vinicius Batista.
* **Grupo 3:** Gabriela Leite, Henrique Souza, Laís Renata, Rychard Rodrigues.
* **Grupo 4:** Beatriz Oliveira, Clara, João, Maria Ferreira.
* **Grupo 5:** Claudomiro Santos, Richard Pimenta.
* **Grupo 6:** Julio Ilidio, Miguel Alves.

### 🍧 Açaí
* **Grupo 1:** Anthony Bezerra, C. Adriano, Luan Seiji.
* **Grupo 2:** Cauã José, Juan Pablo, Pedro Henrique.
* **Grupo 3:** Guilherme Firmino, Gustavo Rodrigues, Leonardo Santana, Wilson.
* **Grupo 4:** Lorenzo Carmo, Luis Gentil, Maxuel Xavier.

### 🥖 Padaria
* **Grupo 1:** Kauã, Miguel Marcondes.
* **Grupo 2:** Fellipe Lima, Gustavo Jesus, Juliana Lima, Lana Reis.

### 🍽️ Restaurante
* **Grupo 1:** Alicya Duarte, Ana Nascimento, Larissa Silva, Nicolly Gonçalves, Thalya Alcantara, Thierry Duarte.

### ✂️ Barbearia
* **Grupo 1:** Allan Costa, Igor Batista, Milena Oliveira, Yuri Santana.

### 💄 Salão de Beleza
* **Grupo 1:** Michelle Andrade, Rafaela, Stefani Santos.

---

## 📚 Método Educativo: Estrutura de Dados
Na programação, o que acabamos de fazer foi transformar uma **Lista Desordenada** em uma **Lista Estruturada**.

* **Agrupamento:** Em linguagens como Python, poderíamos usar um **Dicionário** para salvar esses dados, onde a "Chave" é o **Tema** e o "Valor" é a **Lista de Alunos**.
* **Markdown:** É a linguagem que estamos usando para formatar este texto. Ela é essencial para programadores documentarem seus projetos no GitHub de forma clara e profissional.

---

💻 Exemplo de Código: Sistema com Carrinho de Compras
Markdown
# 🛒 Exemplo de Código: Sistema de Pedidos em Python

Este código permite que o cliente selecione múltiplos itens e calcula o valor total automaticamente.

```python
# --- DOCUMENTAÇÃO ---
# Objetivo: Permitir múltiplos pedidos e somar o total.
# Conceitos: While (Loop), Acumuladores e Operadores Matemáticos.

nome_cliente = input("Qual o seu nome? ")
total_conta = 0.0  # Variável que vai guardar a soma de tudo
continuar = True   # Controle do nosso Loop (Laço)

print(f"\nOlá {nome_cliente}! Monte seu pedido (Digite 0 para finalizar):")

while continuar:
    print("\n--- MENU DE SELEÇÃO ---")
    print("1. Item A (Hambúrguer/Açaí/Corte) - R$ 20.00")
    print("2. Item B (Batata/Adicional/Barba) - R$ 10.00")
    print("3. Item C (Bebida/Suco/Sobrancelha) - R$ 7.00")
    print("0. FINALIZAR PEDIDO")
    
    escolha = input("\nEscolha o número do item: ")

    if escolha == "1":
        total_conta += 20.00
        print("Item A adicionado!")
    elif escolha == "2":
        total_conta += 10.00
        print("Item B adicionado!")
    elif escolha == "3":
        total_conta += 7.00
        print("Item C adicionado!")
    elif escolha == "0":
        continuar = False # Altera a condição para encerrar o loop
    else:
        print("Opção inválida! Tente de novo.")

# --- FINALIZAÇÃO (Sessão fora do loop) ---
print("\n" + "="*30)
print(f"RESUMO DO PEDIDO - CLIENTE: {nome_cliente}")
print(f"TOTAL A PAGAR: R$ {total_conta:.2f}")
print("Obrigado e volte sempre!")
print("="*30)

´´´

### 📖 O que pode aprender como esse código?

1.  **Variáveis Acumuladoras:** A `total_conta` começa em zero e vai "ganhando" valor conforme o uso do operador `+=`.
2.  **O Laço `while`:** Diferente do `if` que só testa uma vez, o `while` cria uma repetição. O programa só sai desse bloco quando a variável `continuar` vira `False`.

3.  **Boas Práticas de UX (Experiência do Usuário):** Usar o `input` para capturar a escolha e dar um feedback imediato (ex: "Item adicionado!").

**Gostaria que eu criasse um "Desafio de Programação" baseado nesse código para os grupos