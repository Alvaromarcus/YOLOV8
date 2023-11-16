YOLOv8 Polygon Coordinates Converter
Este repositório contém dois scripts em Python para converter coordenadas de polígonos em formato YOLOv8. Os scripts são projetados para trabalhar com dados de treinamento em formato CSV e JSON.

Uso
Script 1 (CSV):
python convert_csv_to_yolo.py
Este script lê um arquivo CSV contendo coordenadas de polígonos e gera arquivos .txt no mesmo diretório.

Script 2 (JSON):
python convert_json_to_yolo.py
Este script lê um arquivo JSON contendo coordenadas de polígonos e também gera arquivos .txt no mesmo diretório.

Configuração
Certifique-se de fornecer as dimensões corretas da imagem (largura e altura) no script antes de executar.

Estrutura de Diretórios
/
|-- placas/
|   |-- train/
|   |   |-- placas_treino.json
|   |-- val/
|   |   |-- placas_validacao_csv.csv
|-- convert_csv_to_yolo.py
|-- convert_json_to_yolo.py
