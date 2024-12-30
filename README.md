# ft_printf

**ft_printf** é uma implementação personalizada da função `printf` da biblioteca padrão em C. O objetivo deste projeto é recriar a funcionalidade da função `printf`, oferecendo suporte para vários tipos de dados, formatação e flags.

## Funcionalidades Implementadas

- **Escrita de strings**: Imprime uma string no formato desejado.
- **Inteiros e números longos**: Imprime números inteiros, tanto positivos quanto negativos.
- **Números com sinal**: Suporta números com sinal.
- **Números em base octal, hexadecimal e binária**: Converte e imprime números em diferentes bases.
- **Ponteiros**: Imprime endereços de memória com o formato hexadecimal.
- **Flags de formatação**: Suporta flags como:
  - `-` (alinhamento à esquerda)
  - `+` (mostrar sinal positivo para números positivos)
  - `0` (preencher com zeros)
  - `#` (formatação especial para números hexadecimais e octais)
- **Largura de campo**: Permite que você defina a largura mínima do campo de saída.
- **Precisão**: Define a precisão (número de casas decimais ou largura mínima para strings).

## Como Usar

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/rubens-maldonado/ft_printf.git

2. **Compile a biblioteca:** Dentro da pasta do repositório:
    ```bash
    cd ft_printf
    make

3. **Inclua no seu código:** Adicione o arquivo de cabeçalho ft_printf.h e o arquivo de implementação ft_printf.o ao seu projeto e use a função ft_printf da seguinte forma:
    ```c

   #include "ft_printf.h"
   int main() {
     int num = 42;
     ft_printf("O número é: %d\n", num);
     return 0;
    }

4. **Limpeza dos arquivos compilados:** Para remover os arquivos temporários e binários gerados durante a compilação:
    ```bash
    make clean

5. **Remover todos os arquivos (incluso** ft_printf.a **):**
    ```bash
    make fclean

6. **Recompilar o projeto:** Para recompilar todos os arquivos:
    ```bash
    make re
