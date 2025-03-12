# Calculadora de IMC

Este é um aplicativo Android simples que calcula o Índice de Massa Corporal (IMC) com base no peso e na altura informados pelo usuário. Ele fornece o diagnóstico correspondente ao IMC calculado.

## Funcionalidades

- **Entrada de Dados**: Permite que o usuário insira o peso (em kg) e a altura (em metros).
- **Cálculo do IMC**: Calcula o IMC usando a fórmula: `IMC = peso / (altura * altura)`.
- **Classificação do IMC**:
  - Abaixo de 18.5: **Abaixo do peso**.
  - Entre 18.5 e 24.9: **Peso normal**.
  - Entre 25.0 e 29.9: **Sobrepeso**.
  - Acima de 30.0: **Obesidade**.

## Estrutura do Projeto

### Atividades

- **`MainActivity`**: Tela principal para entrada dos dados de peso e altura.
- **`ResultadoActivity`**: Tela de resultados que exibe o IMC calculado e o diagnóstico.

### Layouts

- **`activity_main.xml`**: Layout da tela principal com campos de entrada e botão de cálculo.
- **`activity_resultado.xml`**: Layout da tela de resultados, mostrando o IMC e o diagnóstico.
<img src="https://github.com/user-attachments/assets/39cc90b0-3c4a-4051-ab8a-f5aff36fc68f" width="200"/>
<img src="https://github.com/user-attachments/assets/c1bd06c9-6d1a-4682-9ec8-19431e8d4085" width="200"/>



## Como Rodar

1. Clone o repositório.
2. Abra o projeto no Android Studio.
3. Compile e execute no emulador ou dispositivo físico.
4. Insira os valores de peso e altura, clique no botão **Calcular IMC** e visualize o resultado.

## Exemplos de Uso

1. Digite um peso, como `70.0` kg, e uma altura, como `1.75` m.
2. Clique em **Calcular IMC**.
3. O aplicativo exibirá:
   - Peso informado: `70.0 kg`
   - Altura informada: `1.75 m`
   - Diagnóstico: **Peso normal**

## Tecnologias Usadas

- Linguagem: Kotlin.
- Interface do Usuário: ConstraintLayout, Material Design.
- Ambiente de Desenvolvimento: Android Studio.
