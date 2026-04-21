# UNA-BLAZOR-LISTA12
## 📌 Identificação

**Nome:** Luis Gustavo Coelho de Melo 

**RA:** 32616684

**Curso:** Ciências da Computação

**Disciplina:** Interação Humano-Computador e UX

---

## 🧠 Heurísticas de Nielsen Aplicadas

### 1. Visibilidade do status do sistema

O usuário é informado constantemente sobre o status do programa atráves do contador atualizado sempre que uma nova ação seja finalizada, como por exemplo a mensagem de meta atingida quando o contador alcança o valor 100.

### 2. Feedback imediato

Cada novo clique que o usuário dá gera uma resposta visual, como por exemplo quando a cor da borda muda para verde ao atingir 50 pontos.

---

## 💡 Guia de execução

Foi preciso criar, via terminal, um arquivo tipo blazor, que já retorna uma pasta contendo diversas outras pré criadas. Em seguida, a pasta é aberta no Visual Studio Code para que sejam feitas alterações no código. 

No caso, houve a criação de um novo arquivo tipo blazor no guia componente da pasta e as alterações foram feitas nele e no arquivo "Home".  

1) No arquivo Home: utilizando comandos HTML, houve a criação de 3 seções, referenciadas nos parâmetros criados no arquivo "EcoStatus" e suas respectivas características.
2) No arquivo EcoStatus: foram criados os parâmetros, contadores, as formatações das 3 instâncias e as condições para que houvessem alterações a partir de determinados pontos.

---

## 🔁 Uso dos Parâmetros

Os parâmetros são definidos no arquivo EcoStatus e retornam no arquivo Home para cada sistuação específica:

1) No arquivo EcoStatus são declarados:

[Parameter]

public required string NomeAcao { get; set; }

[Parameter]

public int Peso { get; set; }

2) No arquivo Home retornam para cada caso específico com o nome e com o peso respectivos:

```razor
<EcoStatus NomeAcao="Reciclagem de Plástico" Peso="1" />
<EcoStatus NomeAcao="Plantio de Árvores" Peso="10" />
<EcoStatus NomeAcao="Descarte de Eletrônicos" Peso="5" />
```

---

## 📷 Print do programa funcionando

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/2449cce8-43b8-45eb-93cf-fd233e5ca9ad" />
