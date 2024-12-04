# Resumo

Este repositório contém códigos, análises e perspectivas sobre uma solução para a correção automática de redações. Uma solução completa para essa tarefa envolve, no mínimo, três etapas básicas:

* Detecção de desvios no texto
* Atribuição da nota, seja ela global ou por competência
* Elaboração de um feedback para o aluno

O objetivo deste trabalho é realizar uma análise em NLP (Processamento de Linguagem Natural) para entender como, a partir de um conjunto de dados contendo redações do ENEM (Exame Nacional do Ensino Médio) e suas respectivas notas por competência, é possível desenvolver uma solução de correção automática de redações.

O conjunto de dados utilizado neste estudo contém 4570 redações do gênero textual dissertativo-argumentativo, abordando 86 temas distintos. Entre os temas, destacam-se direitos humanos, problemas políticos, saúde pública, entre outros. As redações foram coletadas entre dezembro de 2015 e abril de 2020. Mais informações sobre a construção do conjunto de dados estão disponíveis https://sol.sbc.org.br/index.php/dsw/article/view/17414.

Como ferramentas de apoio, serão utilizados os códigos e corpus disponíveis em https://github.com/rafaelanchieta/essay.

## Referência

```
@inproceedings{marinho-et-al-21,
  author = {Jeziel Marinho and Rafael Anchiêta and Raimundo Moura},
  title = {Essay-BR: a Brazilian Corpus of Essays},
  booktitle = {Anais do III Dataset Showcase Workshop},
  year = {2021},
  pages = {53--64},
  publisher = {Sociedade Brasileira de Computação},
  address = {Online},
  doi = {10.5753/dsw.2021.17414},
  url = {https://sol.sbc.org.br/index.php/dsw/article/view/17414}
}

