# Comandos Linux para Newba

<p align="center">
  <img src="https://i.pinimg.com/originals/41/bb/6f/41bb6f7d099e7af93bcdaa6817a87847.gif" width="200">
</p>

## Linux para Noobs

Simplesmente um repositório para guardar as sintaxes de comandos Unix e suas funcionalidades para facilitar meu aprendizado e lembrança desses, como também, ajudar indivíduos que desejam aprender a utilizar Linux. Bons estudos :)
## Básicos
- `echo` -> permite que seja exibido mensagens ou textos na tela. Útil em scripts para gerar saídas, exibir mensagens informativas ou passar valores para outro comandos.
  ```bash
  echo banana      saída: banana
| opções | descrição | sequências de escape |
|---|---|---|
| `-e` | Habilita a interpretação de sequências de escape como `\n`, `\t`, etc | `\n` -> Nova linha |
| `-n` | em nova linha, o comando `echo` por padrão adiciona uma nova | `\t` -> Tabulação |
| `-E` | Desativa a interpretação de caracteres especiais. Isso pode ser útil para exibir strings "cruas" | `\\\` -> Barra invertida literal |

###### Uso em scripts
```bash
#!/bin/bash
echo "Iniciando o script"
echo "Seu nome de user é: $USER"
#!exibição de valores de variavéis
nome="João"
echo "Olá, $nome!"````

####### Passar saída para outros comandos


