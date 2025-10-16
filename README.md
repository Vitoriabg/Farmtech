# Farmtech
# 👁️ FarmTech Solutions - Sistema de Segurança com Visão Computacional

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![YOLOv5](https://img.shields.io/badge/YOLOv5-v7.0%2B-green)](https://github.com/ultralytics/yolov5)
[![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-orange)](https://colab.research.google.com/)

## 👨‍🎓 Integrantes: 
- <a href="https://www.linkedin.com/in/juliano-romeiro-rodrigues/">Juliano Romeiro Rodrigues</a>
- <a href="https://www.linkedin.com/in/nicolas--araujo/">Nicolas Antonio Silva Araujo</a> 
- <a href="https://www.linkedin.com/in/vitoria-bagatin-31ba88266/">Vitória Pereira Bagatin</a> 
<br><br>
## 📋 Sobre o Projeto
Este projeto implementa um sistema de Visão Computacional para a FarmTech Solutions, expandindo seus serviços para a área de segurança patrimonial em fazendas. O objetivo é demonstrar a capacidade de uma rede neural em identificar e diferenciar automaticamente **Pessoas** e **Tratores** em ambientes agrícolas. Desenvolvido como parte da Fase 6 do programa de Graduação em Inteligência Artificial, com foco em Redes Neurais e Visão Computacional.  
<br><br>
## 🎯 Objetivos Específicos da Fase 6
- ✅ **Organização do Dataset**: Criar e organizar um dataset customizado com no mínimo 80 imagens (40 de 'pessoa' e 40 de 'trator'), divididas para treino, validação e teste.
- ✅ **Rotulação de Imagens**: Realizar a rotulação precisa das imagens de treino utilizando o Make Sense AI, no formato YOLO.
- ✅ **Desenvolvimento no Colab**: Montar um ambiente de desenvolvimento no Google Colab para as etapas de treinamento, validação e teste.
- ✅ **Treinamento YOLOv5**: Treinar um modelo YOLOv5 com o dataset customizado, realizando ao menos duas simulações com diferentes quantidades de épocas (e.g., 30 e 60 épocas).
- ✅ **Análise Comparativa**: Comparar os resultados de acurácia, erro e desempenho entre os diferentes treinamentos.
- ✅ **Conclusões e Demonstração**: Apresentar conclusões sobre os resultados obtidos na validação e nos testes, incluindo prints das imagens processadas pelo modelo.
<br><br>
## 🛠️ Tecnologias e Bibliotecas Principais
```python```  
* **YOLOv5 (Ultralytics)**: Framework de detecção de objetos para o treinamento do modelo.
* **PyTorch**: Biblioteca de aprendizado de máquina que serve de base para o YOLOv5.
* **Google Colab**: Ambiente de desenvolvimento em nuvem com aceleração de GPU.
* **Make Sense AI**: Ferramenta online para rotulação de imagens.

## 📁 Estrutura de Pastas (Google Drive - Conectado ao Colab)
Este projeto utiliza uma estrutura de pastas organizada no Google Drive para armazenamento das imagens e rótulos, acessada diretamente pelo Google Colab:

### <br>FarmTech_Seguranca_YOLO/<br>
A pasta raiz do projeto de Visão Computacional no Google Drive.

* <b>`datasets/images/train/`</b>: Contém as 64 imagens de treino (32 de pessoa, 32 de trator).
* <b>`datasets/images/val/`</b>: Contém as 8 imagens de validação (4 de pessoa, 4 de trator).
* <b>`datasets/images/test/`</b>: Contém as 8 imagens de teste (4 de pessoa, 4 de trator).
* <b>`datasets/labels/train/`</b>: Armazena os 64 arquivos `.txt` (rótulos no formato YOLO) correspondentes às imagens de treino.
<br><br>
## 🚀 Metodologia
1.  **Coleta e Organização de Dados**: Obtenção de 40 imagens de 'pessoa' e 40 de 'trator', e sua divisão em conjuntos de treino, validação e teste.
2.  **Rotulação**: Anotação manual de todos os objetos nas imagens de treino utilizando a ferramenta Make Sense AI, gerando arquivos de rótulo no formato YOLO.
3.  **Configuração do Ambiente**: Utilização do Google Colab com aceleração GPU para clonagem do repositório YOLOv5 e instalação de dependências.
4.  **Treinamento do Modelo**: Execução de treinamentos com 30 e 60 épocas para observar o impacto da duração do treino na performance.
5.  **Validação e Teste**: Avaliação do modelo em imagens não vistas para verificar sua capacidade de generalização e identificar acertos e erros.
6.  **Análise de Resultados**: Comparação das métricas de desempenho e análise visual das detecções para extrair conclusões sobre o potencial e as limitações do sistema.
<br><br>
## 🔗 Notebook do Projeto
Acesse o notebook completo no Google Colab, que detalha todas as etapas do projeto, códigos, e a análise de resultados:

* **[Clique aqui para acessar o Notebook do Projeto no Google Colab](https://colab.research.google.com/drive/1ej8q-2pIt8EDoVe-M20vaia2Z4yPyrq4?usp=sharing)**
<br><br>
## 🎥 Vídeo de Demonstração
Assista ao vídeo demonstrativo que apresenta o funcionamento do sistema, o notebook em execução e os resultados visuais da detecção:

* **[Clique aqui para assistir ao vídeo no YouTube]([LINK DO SEU VÍDEO NO YOUTUBE])**
<br><br>
## 📋 Conclusões
Este projeto valida o uso da Visão Computacional com YOLOv5 como uma solução eficaz para a segurança patrimonial da FarmTech Solutions. A capacidade de identificar automaticamente objetos de interesse abre portas para sistemas de monitoramento proativos e inteligentes, capazes de aumentar a segurança e a eficiência operacional em ambientes agrícolas. O relatório detalhado no notebook discute as métricas obtidas, os desafios encontrados e os próximos passos para aprimorar a solução.
