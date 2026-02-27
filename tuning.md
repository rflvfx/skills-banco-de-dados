# Tuning Guide

1. medir primeiro: slow query log / pg_stat_statements
2. indice certo na coluna certa (cardinalidade alta primeiro)
3. reescrever a query antes de jogar hardware
4. revisar plano de execucao: scans vs seeks
