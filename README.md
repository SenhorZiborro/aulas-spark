# Aulas de Apache Spark

Bem-vindo ao repositório oficial da série de vídeos práticos sobre Apache Spark! Este espaço concentra todo o código, configurações Docker, manifestos Kubernetes, notebooks e laboratórios que construímos ao longo das aulas. O objetivo aqui é sujar as mãos: sair da teoria e ver como o Spark se comporta no dia a dia do engenheiro e do analista de dados.

## O que tem neste repositório?

O material está organizado cronologicamente acompanhando as aulas, indo desde a subida da infraestrutura até a execução no Kubernetes, observabilidade e motores acelerados.

Navegando pela estrutura de pastas, você vai encontrar laboratórios cobrindo os seguintes temas práticos:

* **Setup e Arquitetura:** Subida do ambiente, primeiros contatos com o PySpark e arquitetura de execução.
* **Fundamentos e SQL:** DataFrames, tipos de dados, funções, joins, Window Functions, `SELECT` em profundidade e SQL parametrizado.
* **Fontes de Dados e Streaming:** Formatos de arquivo, metastore, particionamento e Structured Streaming.
* **Performance:** Catalyst, planos de execução, shuffle, memória, cache, AQE e data skew.
* **Kubernetes e Ecossistema:** Spark Kubernetes Operator, observabilidade, Data Lakes com MinIO, Kafka, Delta e Iceberg, e motores acelerados.

## Como utilizar o material

A base de todos os nossos laboratórios é um ambiente rápido e isolado rodando em containers. Se você está chegando agora, siga este caminho:

1. Certifique-se de ter o **Docker** instalado na sua máquina (e o **minikube** a partir das aulas de Kubernetes).
2. Acesse o diretório correspondente à aula que você está assistindo para buscar os notebooks, manifestos ou scripts necessários para acompanhar a prática.

Bons estudos e bora botar a mão na massa!