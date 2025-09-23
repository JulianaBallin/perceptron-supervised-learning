# ✅ Checklist – Projeto Prático 2.1 (Perceptron)

Este documento serve como guia de acompanhamento da equipe para garantir que **todos os requisitos do projeto** foram cumpridos conforme instruções do PDF.

---

## 👥 Organização do Grupo
- [✅] Equipe com 5 integrantes cadastrados.  
- [✅] Nome, matrícula e GitHub de todos no notebook.  
- [✅] Identificador da equipe calculado (últimos dígitos das matrículas % 4).  

---

## 📂 Estrutura do Repositório
- [✅] Repositório GitHub criado (privado até a entrega).  
- [✅] Todos os membros adicionados como colaboradores.  
- [✅] Pasta `data/` com arquivos fornecidos pela professora.  
- [✅] Notebook `.ipynb` com células organizadas e executadas.  
- [✅] Prints e gráficos salvos como evidências no notebook.  

---

## 🟢 Parte I – Linearmente Separable
- [✅] Usar `dataAll.txt`.  
- [✅] Função de ativação **degrau (θ = 0)**.  
- [✅] Taxa de aprendizado **η = 0.1**.  
- [✅] Pesos iniciais ~ U(-0.5, +0.5) **e impressos no início**.  
- [✅] Treino até a **convergência**.  
- [✅] Imprimir ao final:  
  - [✅] Número de ajustes.  
  - [✅] Número de épocas até convergência.  
  - [✅] Pesos finais.  
- [✅] Gerar gráfico com:  
  - [✅] Pontos de dados (`x1, x2`).  
  - [✅] Classe 0 = vermelho, Classe 1 = azul.  
  - [✅] Reta de decisão aprendida.  
  - [✅] Labels nos eixos e título.  

---

## 🟢 Parte II – Experimentação
- [ ✅] Usar `data<ID>.txt` onde `<ID>` é o identificador da equipe.  
- [✅] Executar **10 repetições** em cada configuração:  
  - η ∈ {0.4, 0.1, 0.01}  
  - Intervalos de pesos ∈ {(-100,+100), (-0.5,+0.5)}  
- [✅] Coletar para cada configuração:  
  - [✅] Média ± desvio padrão de ajustes.  
  - [✅] Menor nº de épocas até convergência.  
- [✅] Montar **tabela comparativa** (ex: `prettytable`).  
- [✅] Escrever discussão: melhor/pior configuração ou equivalência.  

---

## 🔴 Parte III – Validação Holdout
- [ ] Usar `dataHoldout.txt`.  
- [ ] Mostrar gráfico inicial evidenciando que **não é linearmente separável**.  
- [ ] Dividir dataset em:  
  - [ ] 70% treino, 30% teste.  
  - [ ] Usar seed = identificador da equipe.  
- [ ] Treinar por 100 épocas com:  
  - Função degrau (θ = 0).  
  - η recomendado.  
  - Pesos iniciais ~ U(-0.5, +0.5).  
  - Amostras embaralhadas a cada época.  
- [ ] Avaliar no conjunto de teste:  
  - [ ] Matriz de confusão.  
  - [ ] Acurácia.  
  - [ ] Precisão, Revocação e F1-score.  
- [ ] Discutir qualidade da solução baseada nas métricas.  
- [ ] Gerar gráficos finais:  
  - [ ] Treino + fronteira.  
  - [ ] Teste + fronteira.  
  - [ ] Mostrar lado a lado.  

---

## 🛠️ Tecnologias
- [✅] Python 3.6+.  
- [✅] Bibliotecas obrigatórias: `numpy`, `matplotlib`, `random`, `math`.  
- [✅] Permitido: `scikit-learn` (métricas), `prettytable`  
