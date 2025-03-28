# 💡 Iluminação Inteligente com MongoDB

Este projeto simula um sistema de gerenciamento de iluminação pública em uma cidade inteligente, utilizando o banco de dados **MongoDB** para armazenar e manipular dados de forma flexível e escalável.

O sistema contempla postes inteligentes com sensores, monitoramento de consumo, alertas de manutenção, histórico de operações e mapeamento por bairros.

---

## 🛠️ Tecnologias Utilizadas

- **MongoDB**
- **MongoDB Compass**
- **NoSQL**
- JSON para estrutura dos documentos

---

## 📁 Estrutura do Projeto

- `README.md` – Descrição do projeto e instruções gerais
- `scripts/` – Comandos CRUD utilizados (inserção, leitura, atualização, exclusão)
- `imagens/` – Prints de tela das operações realizadas no MongoDB Compass

---

## 🗃️ Collections Utilizadas

1. `iluminacao_publica` – Informações sobre os postes inteligentes
2. `bairros` – Dados dos bairros da cidade
3. `alertas_manutencao` – Registros de falhas e manutenções
4. `consumo_energia` – Medições de consumo por poste
5. `historico_operacoes` – Log de eventos dos postes (ligar, desligar, ajustar, etc.)

---

## 🔁 Operações Realizadas (CRUD)

- **Create:** Inserção de 10 documentos em cada collection
- **Read:** Consultas filtrando por status, consumo, tipo de operação, etc.
- **Update:** Alterações no status de postes, consumo e outros atributos
- **Delete:** Remoções de documentos com base em condições específicas

---

