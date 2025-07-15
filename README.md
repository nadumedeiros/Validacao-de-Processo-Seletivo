# 📞 Projeto: Processo Seletivo em Java

Este projeto simula um processo seletivo simplificado com candidatos a uma vaga de emprego. O sistema utiliza estruturas de controle de fluxo, geração aleatória de valores, e simula chamadas telefônicas para os candidatos.

---

## 📂 Estrutura do Projeto

- **Pacote:** `Candidatura`
- **Classe principal:** `Processo_Seletivo.java`

---

## 🚀 Funcionalidades

### ✅ Simulação de contato com candidatos
- Para cada candidato, o sistema tenta fazer até **3 tentativas de ligação**.
- O sucesso da chamada é determinado aleatoriamente.
- Exibe mensagens diferentes se o contato foi realizado ou não.

### ✅ Seleção de candidatos
- Avalia uma lista de 10 candidatos.
- Compara o **salário pretendido** com o **salário base** de R$2000,00.
- Seleciona até **5 candidatos** com pretensão salarial compatível.

### ✅ Impressão de candidatos selecionados
- Exibe todos os candidatos com base no índice da lista.

### ✅ Análise de salário pretendido
- Analisa se deve entrar em contato com o candidato, fazer uma contraoferta ou aguardar outros candidatos, com base no salário pretendido.

---

## 🧪 Métodos principais

| Método | Descrição |
|--------|-----------|
| `main(String[] args)` | Inicia a execução e tenta contato com cada candidato. |
| `entrandoEmContato(String candidato)` | Simula até 3 tentativas de contato com o candidato. |
| `atender()` | Retorna aleatoriamente se o candidato atendeu ou não (1 chance em 3). |
| `imprimirSelecionados()` | Imprime os nomes e posições dos candidatos. |
| `selecaoCandidatos()` | Seleciona candidatos com base no salário pretendido (até 5). |
| `valorPretendido()` | Gera um valor aleatório de salário entre R$1800 e R$2200. |
| `analisarCandidato(double salarioPretendido)` | Analisa se o salário é aceitável. |

---

## 💡 Tecnologias Utilizadas

- Java 8+
- `java.util.Random`
- `java.util.concurrent.ThreadLocalRandom`

---

## 📌 Como executar

1. Compile o arquivo:

```bash
javac Processo_Seletivo.java
