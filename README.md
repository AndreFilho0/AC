# Atividade 👥 

Aluno : André De Oliveira Machado Filho , IGOR PIMENTA ARAÚJO  , JAMILLY VITORYA DA SILVA BARBOSA 

## 1. Métricas de Desempenho 📊 

 - Throughput
 - Latência
 - Tempo de Execução
 - Utilização da CPU
 - Memória (Uso e Latência)
 - Velocidade de Clock

## 2. Busca e Registro das Métricas

### Throughput (Vazão):

- André De Oliveira Machado Filho: Download Mbps 38.85 Upload Mbps 36.88
- JAMILLY VITORYA DA SILVA BARBOSA : Download Mbps 24.99 Upload Mbps 37.41
- IGOR PIMENTA ARAÚJO: Igor Pimenta Araújo: Download Mbps 48.23, Upload Mbps 42.00 
### Latência:

- André De Oliveira Machado Filho : ping melivra.com 135.267ms
- JAMILLY VITORYA DA SILVA BARBOSA : ping google.com 50.720 ms
- Igor Pimenta Araújo: ping google.com 40.012 ms
### Tempo de Execução de um Programa: 🕒
- André De Oliveira Machado Filho:
real	0m0,398s
user	0m0,168s
sys	0m0,162s

- JAMILLY VITORYA DA SILVA BARBOSA:
real	0m0,026s
user	0m0,007s
sys	0m0,017s
- IGOR PIMENTA ARAÚJO: real 0m0,350s, user 0m0,190s, sys 0m0,160s 
### Utilização da CPU:
```bash
sar -u 1 60
```

- André De Oliveira Machado Filho : Uso da CPU=100%−%idle=100%−92,49%=7,51%
- Igor Pimenta Araújo: Uso da CPU = 100% − %idle = 100% − 92.75% = 7.25%

- Jamilly Vitorya da Silva Barbosa: Uso da CPU = 100% − %idle = 100% − 88.00% = 12.00%
 

### Memória (Uso e Latência):
```bash
free -h
```
- André De Oliveira Machado Filho :  uso da RAM : 5.8Gi ,  latência : real  0m1.234s
- Igor Pimenta Araújo: Uso da RAM: 5.5Gi, Latência: real 0m1.300s
- Jamilly Vitorya da Silva Barbosa: Uso da RAM: 4.8Gi, Latência: real 0m0.950s

### Velocidade de Clock:
- André De Oliveira Machado Filho:  CPU MHz máx.: 4400,0000 MHz (4,4 GHz) –> Clock máximo , CPU MHz mín.: 400,0000 MHz (0,4 GHz) –> Clock mínimo
- Igor Pimenta Araújo: CPU máx.: 4.2 GHz, CPU mín.: 0.9 GHz
- Jamilly Vitorya da Silva Barbosa: CPU máx.: 3.6 GHz, CPU mín.: 0.6 GHz
## 3. Relatório 📝 

 com base nas métricas fornecidas, podemos observar o seguinte:
Throughput (Vazão):

    André De Oliveira Machado Filho: Download de 38.85 Mbps e Upload de 36.88 Mbps
    Jamilly Vitorya da Silva Barbosa: Download de 24.99 Mbps e Upload de 37.41 Mbps
    Igor Pimenta Araújo: Download de 48.23 Mbps e Upload de 42.00 Mbps

Máquina com melhor desempenho (Throughput): A máquina de Igor Pimenta Araújo apresenta o melhor desempenho, com maiores velocidades de download e upload (48.23 Mbps e 42.00 Mbps, respectivamente).
Latência:

    André De Oliveira Machado Filho: 135.267 ms
    Jamilly Vitorya da Silva Barbosa: 50.720 ms
    Igor Pimenta Araújo: 40.012 ms

Máquina com melhor desempenho (Latência): A máquina de Igor Pimenta Araújo também se destaca, com a menor latência (40.012 ms), seguida por Jamilly (50.720 ms) e André (135.267 ms).
Tempo de Execução de um Programa:

    André De Oliveira Machado Filho: 0m0,398s (real), 0m0,168s (user), 0m0,162s (sys)
    Jamilly Vitorya da Silva Barbosa: 0m0,026s (real), 0m0,007s (user), 0m0,017s (sys)
    Igor Pimenta Araújo: 0m0,350s (real), 0m0,190s (user), 0m0,160s (sys)

Máquina com melhor desempenho (Tempo de Execução): A máquina de Jamilly Vitorya da Silva Barbosa tem o melhor desempenho em termos de tempo de execução, com um tempo muito menor (0m0,026s real) comparado a André (0m0,398s) e Igor (0m0,350s).
Utilização da CPU:

    André De Oliveira Machado Filho: 7.51% de uso da CPU
    Igor Pimenta Araújo: 7.25% de uso da CPU
    Jamilly Vitorya da Silva Barbosa: 12.00% de uso da CPU

Máquina com melhor desempenho (Uso da CPU): Igor Pimenta Araújo apresenta o menor uso de CPU (7.25%), seguido por André (7.51%) e Jamilly (12.00%).
Memória (Uso e Latência):

    André De Oliveira Machado Filho: Uso da RAM = 5.8Gi, Latência = 0m1.234s
    Igor Pimenta Araújo: Uso da RAM = 5.5Gi, Latência = 0m1.300s
    Jamilly Vitorya da Silva Barbosa: Uso da RAM = 4.8Gi, Latência = 0m0.950s

Máquina com melhor desempenho (Memória): Jamilly Vitorya da Silva Barbosa tem o melhor desempenho em termos de latência (0m0,950s) e menor uso de RAM (4.8Gi), o que sugere maior eficiência no uso da memória.
Velocidade de Clock:

    André De Oliveira Machado Filho: Máximo de 4.4 GHz, Mínimo de 0.4 GHz
    Igor Pimenta Araújo: Máximo de 4.2 GHz, Mínimo de 0.9 GHz
    Jamilly Vitorya da Silva Barbosa: Máximo de 3.6 GHz, Mínimo de 0.6 GHz

Máquina com melhor desempenho (Velocidade de Clock): André De Oliveira Machado Filho tem o maior clock máximo (4.4 GHz), o que pode indicar um maior potencial de processamento para tarefas mais exigentes.
2. Impacto das Características de Hardware nas Métricas de Desempenho:

    Throughput (Vazão): Máquinas com maiores velocidades de clock tendem a ter melhor desempenho em throughput. A máquina de Igor, com clock máximo de 4.2 GHz, teve o melhor desempenho em throughput.

    Latência: A latência parece não ser diretamente impactada pela velocidade de clock, mas sim pela qualidade da rede e da configuração de hardware. A máquina de Igor teve a menor latência, seguida pela de Jamilly.

    Tempo de Execução: A velocidade do clock e o uso eficiente da memória influenciam diretamente o tempo de execução. A máquina de Jamilly teve o melhor tempo de execução, o que sugere uma boa combinação de hardware e otimização de software.

    Utilização da CPU: Uma menor utilização da CPU pode indicar um melhor balanceamento de tarefas e uma melhor gestão de recursos. A máquina de Igor teve o menor uso de CPU, o que pode indicar maior eficiência no processamento.

    Memória: Menor uso de memória e latência de memória mais baixa indicam uma gestão eficiente da memória. A máquina de Jamilly teve o menor uso de RAM e a melhor latência de memória, o que indica maior eficiência no gerenciamento de recursos de memória.

Conclusão:

    A máquina de Igor Pimenta Araújo se destaca em várias métricas, incluindo throughput, latência e utilização de CPU.
    A máquina de Jamilly Vitorya da Silva Barbosa se destaca em tempo de execução e eficiência de memória.
    A máquina de André De Oliveira Machado Filho tem o maior clock máximo (4.4 GHz), o que pode indicar maior potencial de desempenho em tarefas que exigem mais poder de processamento.
