# Validador de Texto

Este projeto tem como objetivo analisar um texto inserido pelo usuário e verificar se ele segue certas regras de escrita. O programa identifica erros comuns, como:

- Espaços em branco consecutivos.
- Uso indevido de letras maiúsculas ou minúsculas.
- Pontuação incorreta, como vírgulas e pontos no meio de palavras.
- Uso inadequado de aspas duplas.

## Funcionalidades

O script realiza a análise do texto e retorna se o texto está correto ou não. Em caso de erros, ele identifica a natureza de cada problema, com destaque para:

- **Espaços em branco consecutivos**: Identifica se há dois ou mais espaços seguidos sem necessidade.
- **Letras maiúsculas e minúsculas**: Verifica se a primeira letra de uma sentença é maiúscula e se não há letras maiúsculas no meio de palavras.
- **Pontuação**: Verifica se a pontuação está correta, como a presença de pontos e vírgulas no meio de palavras ou entre espaços.
- **Aspas duplas**: Verifica se as aspas duplas estão abertas e fechadas corretamente.

## Como usar

1. **Inserir o texto**: O programa solicita ao usuário que insira o texto a ser analisado.
2. **Processamento**: O programa analisa o texto em busca de erros de acordo com as regras definidas.
3. **Resultado**: Se o texto estiver correto, o programa imprime `SIM`. Caso contrário, ele informa os tipos de erros encontrados e seus índices no texto.


## Como Funciona

O código realiza as seguintes etapas de análise:

1. **Divisão do texto**: O texto é dividido em caracteres individuais para análise detalhada.
2. **Identificação de espaços em branco**: O código verifica se há espaços consecutivos no texto.
3. **Verificação de letras maiúsculas e minúsculas**: O código verifica se a primeira letra de uma sentença é maiúscula e se há letras maiúsculas fora do início de palavras.
4. **Análise de pontuação**: O código verifica se a pontuação está correta e no lugar certo.
5. **Análise de aspas**: O código verifica se as aspas estão abertas e fechadas corretamente, identificando erros.

## Requisitos

- Python 3.x

## Licença

Este projeto está licenciado sob a MIT License - consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
