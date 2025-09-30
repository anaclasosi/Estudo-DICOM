# Estudo_DICOM
  Este repositório contém um notebook Jupyter (Estudo_DICOM.ipynb) desenvolvido para a análise de imagens médicas no formato DICOM. O projeto foi criado para ser uma ferramenta de pesquisa, facilitando a visualização, o processamento e a inspeção de metadados de exames. 

## Funcionalidades
  O notebook oferece um conjunto de funções para trabalhar com imagens médicas, incluindo:
1. Leitura e Conversão: Carrega arquivos DICOM e converte os dados de pixel em arrays NumPy, um formato padrão para processamento de dados em Python.
2. Processamento de Imagem: Aplica janelamento (ajuste de contraste e brilho) para otimizar a visualização de diferentes estruturas de tecido.
3. Visualização Interativa: Inclui um visualizador que permite navegar por fatias de volumes 3D usando um controle deslizante (slider), o que é essencial para analisar exames como tomografias (CT).
4. Análise de Dados: Gera histogramas de intensidade de pixel para ajudar a compreender a distribuição dos valores na imagem.
5. Exportação: Converte e salva volumes 3D no formato NIfTI (.nii.gz), que é amplamente utilizado em pipelines de aprendizado de máquina e softwares de visualização médica.
