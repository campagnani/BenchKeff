# BMC - Benchmark Monte Carlo

Esse repositório visa estabelecer um teste de Benchmark de processadores utilizando código Monte Carlo OpenMC.

## Metodologia

- Sistema operacional: GNU.
- Kernel: Linux.
- Distribuição: Arch Linux Rolling.
- Código Monte Carlo: OpenMC 
- Biblioteca: endf-viii
- Input: Reator Chicago DEN-R1 com 100.000 particulas e 440 ciclos.

### Resultados

Os resultado da tabela abaixo são os que aparecem no campo `Total time in simulation`:

Processador | Configuração | Tempo OMP (s) | Tempo MPI (s)
-|-|-|-
Broadcom BCM2711 | 4/4 @ 2.0Ghz | | 
Intel Core i7-860 | 4/8 @ 2.8GHz | | 
Intel Core i7-3770 | 4/8 @ 3.9GHz | | 
Intel Core i7-8700 | 6/12 @ 4.6GHz | | 
Intel Core i7-10700 | 8/16 @ 4.8GHz | | 
Intel Core i7-10700F | 8/16 @ 4.8GHz | | 
Intel Core i7-11700F | 8/16 @ 4.9GHz | | 
Intel Core i7-QQLT | 6/12 @ 4.4GHz | | 374.35
Intel Xeon E5 2665 | 8/16 @ 3.1GHz | | 
Intel Xeon E5 2665 (x2) | 16/32 @ 3.1GHz | | 295.64
Intel Xeon E5 2670 | 8/16 @ 3.3GHz | | 
Intel Xeon E5 2697v2 | 12/24 @ 3.5GHz | | 349.01
Intel Xeon E5 2697v2 (x2) | 24/48 @ 3.5GHz | | 
Intel Xeon E5-1603v3 | 4/4 @ 2.8GHz | | 
Intel Xeon E5-2640v3 Unlock TB | 8/16 @ 3.4GHz | | 
Intel Xeon W-2123 | 4/8 @ 3.9GHz | | 