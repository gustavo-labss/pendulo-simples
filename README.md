# Pêndulo simples: medindo a gravidade com cálculo e simulação

Trabalho de **Física Geral e Experimental – Mecânica**, do curso de **Engenharia da Computação**.

**Autores:** Gustavo Oliveira de Moura e Vinícius Oliveira da Silva

**Abrir o programa:** https://gustavo-labss.github.io/pendulo-simples/

## O que é
O programa é uma página só (`index.html`), em JavaScript puro, que roda no navegador sem instalar nada. Ele tem duas abas:

- **1 · Calcular:** você digita o comprimento do fio (L) e o tempo de 10 oscilações. O programa calcula o período (T) e a gravidade (g = 4π²·L / T²), faz a média, mostra o erro em relação a 9,78 m/s² (Cuiabá) e desenha o gráfico T² × L, de onde também sai o g (g = 4π² ÷ inclinação).
- **2 · Simular:** o pêndulo animado resolve a equação completa θ″ = −(g/L)·sen θ com o método RK4, em passos de 1 ms. Ele compara o período simulado com a fórmula T = 2π√(L/g) e mostra que ela só vale para ângulos pequenos: em 60°, o período fica cerca de 7% maior. Também dá para trocar a gravidade (Terra, Lua e Marte).

**Atalhos:** as teclas `1` e `2` trocam de aba. Na aba Simular, `espaço` inicia e pausa, e `R` reinicia.

## Relatório
O relatório de 2 páginas está em [`docs/relatorio.pdf`](docs/relatorio.pdf).
