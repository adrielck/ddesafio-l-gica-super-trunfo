# Super Trunfo - Países

Programa em C que implementa o jogo “Super Trunfo” para comparação de cartas de cidades. Possui três níveis de desafio:

1. **Novato**  
   - Compara automaticamente o atributo **População**.

2. **Aventureiro**  
   - Menu interativo para o usuário escolher um atributo:  
     - 1) População  
     - 2) Área  
     - 3) PIB  
     - 4) Pontos Turísticos  
     - 5) Densidade Populacional  

3. **Mestre**  
   - Permite a escolha de **dois atributos** (dos listados acima) e determina:
     - Se uma carta vence ambos, é declarado vencedor.
     - Se ambas empatam, exibe empate.
     - Se há divisão (cada carta vence um atributo ou empates), detalha o resultado.

### Como compilar

```bash
gcc super_trunfo.c -o super_trunfo
