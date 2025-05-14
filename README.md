# Detecção de Personagens da Turma da Mônica — YOLOv8

## Este repositório contém o peso treinado (`best.pt`) de um modelo YOLOv8 para detectar os personagens **Mônica**, **Cebolinha** e **Cascão** da Turma da Mônica.

---

### 👾 Sobre o Projeto

O modelo foi treinado com um **dataset próprio**, contendo imagens rotuladas manualmente com os três personagens.  
O objetivo é realizar **detecção de objetos** com a arquitetura YOLOv8.

---

### 🔍 Personagens Detectados

- Mônica  
- Cebolinha  
- Cascão  

---

### 🧠 Modelo

- Arquitetura: **YOLOv8** (Ultralytics)  
- Arquivo de peso disponível: [`best.pt`](./best.pt)

---

### 🚀 Como Usar

1. Instale a biblioteca **Ultralytics**:

   ```bash
   pip install ultralytics
   ```

Faça a detecção com o peso treinado:

bash
Copiar
Editar
yolo task=detect mode=predict model=best.pt source=CAMINHO_PARA_IMAGEM_OU_VIDEO
Exemplo de uso:

bash
Copiar
Editar
yolo predict model=best.pt source="imagens/teste.jpg"
📦 Dataset
O dataset utilizado para o treinamento é próprio e não está incluído neste repositório.

📈 Resultados
O modelo apresenta boa performance na detecção dos três personagens em imagens variadas.

Treinado por [Seu Nome] utilizando YOLOv8 da Ultralytics.

⚠️ Aviso Legal
Os personagens utilizados neste projeto são de propriedade de Mauricio de Sousa Produções.
Este projeto é apenas para fins educacionais e não possui fins comerciais.
