# carevaluation
🚗 Car Evaluation - Classificação com Árvore de Decisão

📚 Sobre o Projeto
Este projeto utiliza Árvores de Decisão para classificar carros em diferentes níveis de aceitabilidade (inaceitável, aceitável, bom, muito bom) com base em atributos como preço, manutenção, número de portas, entre outros.
O objetivo é prever corretamente a aceitabilidade de um carro a partir de seus atributos.

🔥 Tecnologias Usadas
Python
Pandas
Scikit-Learn
Matplotlib
Google Colab

🛠️ Como o projeto foi desenvolvido

Carregamento dos dados
Dataset utilizado: Car Evaluation Dataset

Pré-processamento
Codificação dos atributos categóricos com LabelEncoder.

Divisão de dados
Separação em treino (70%) e teste (30%) com train_test_split.

Treinamento do modelo
Modelo: DecisionTreeClassifier do sklearn.
Visualização da árvore
Utilização do plot_tree para ilustrar as decisões do modelo.

Avaliação de desempenho
Cálculo da acurácia do modelo no conjunto de teste.

📊 Resultados
Acurácia obtida: (coloque aqui o valor que você obteve, ex: 0.92)

Observações:
O modelo apresentou boa performance mesmo sem ajustes de hiperparâmetros.
Testes com profundidade limitada da árvore (max_depth) mostraram que há espaço para otimização.

🚀 Como Executar
Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/seu-usuario/seu-repo.git
Acesse o Google Colab e abra o notebook disponível no projeto.

🔗 Clique aqui para ver o notebook no Colab (coloque o link do seu notebook aqui)

🧠 Próximos passos
Testar diferentes profundidades de árvore (max_depth)
Aplicar técnicas de poda para reduzir overfitting
Comparar com outros algoritmos de classificação (ex: Random Forest)

✨ Contato
Feito com dedicação por Dieiny Gomes!
Se quiser saber mais: [Seu LinkedIn] | [Seu GitHub]

