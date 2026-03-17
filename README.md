# 🏢 Salas de Reunião

Dada uma lista de intervalos representando reuniões `[start, end]`, retorne o **número mínimo de salas** necessárias para acomodar todas sem conflitos.

## Regras

- Intervalos são **semi-abertos**: se uma reunião termina às `10`, outra pode começar às `10` na mesma sala.
- A lista pode estar **fora de ordem**.

## Exemplo

```
Input:  [[0, 30], [5, 10], [15, 20]]
Output: 2
```

A reunião `[0,30]` ocupa uma sala o tempo todo.
`[5,10]` conflita → precisa de outra sala.
`[15,20]` cabe na sala de `[5,10]` (começa depois que termina).

---

# meeting-rooms-challenge
