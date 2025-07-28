# Policies

Este diretório contém algumas policies que achei interessante destacar. Avalie cada um dos arquivo listados acima.

## Restringi o Acesso ao Root, via IAM

É possível e pode ser muito útil em alguns cenários [1].

![2](Restrict%20even%20root%20access.png)

[1] Dizer que não se pode restringir o acesso do root user é uma simplificação. O root user é o proprietário da conta e
pode administrá-la, mas, via SCP o root pode ser limitado dentro da organização e, via policies, você também consegue
proteger recursos de "erros" de um usuário root.
