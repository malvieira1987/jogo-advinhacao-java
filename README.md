🎯 Jogo de Adivinhação em Java
Este é um simples jogo de adivinhação implementado em Java. O programa escolhe um número aleatório entre 0 e 100, e o jogador tenta adivinhar qual é esse número. A cada tentativa, o programa informa se o palpite foi muito baixo, muito alto ou correto.

🧠 Como funciona
O programa gera um número aleatório entre 0 e 100.

O jogador é solicitado a digitar um número.

O programa compara o número digitado com o número secreto:

Se for menor: mostra "Muito Baixo!"

Se for maior: mostra "Muito Alto!"

Se for igual: mostra "Parabéns!" e encerra o jogo.

O número de tentativas é exibido após cada palpite.

📦 Requisitos
Java JDK 8 ou superior

▶️ Como executar
Compile e execute o programa via terminal ou sua IDE favorita:

bash
Copiar
Editar
javac Main.java
java Main
🧾 Exemplo de uso
text
Copiar
Editar
Digite o numero que estou pensando entre 0 e 100: 
50
Muito Baixo! Voce ja tentou: 1 vezes!
Digite o numero que estou pensando entre 0 e 100: 
75
Muito Alto! Voce ja tentou: 2 vezes!
Digite o numero que estou pensando entre 0 e 100: 
62
Parabens! Voce acertou em 3 tentativas
💡 Extras
O programa valida a entrada para garantir que o usuário digite apenas números.

Utiliza Scanner para leitura da entrada e Random para gerar o número secreto.

📁 Arquivo principal
Main.java – Contém toda a lógica do jogo.
