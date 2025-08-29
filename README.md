# PlantUML Examples: Digital Wallet Full Cycle

Este repositório contém **exemplos de diagramas de arquitetura** utilizando PlantUML, aplicados a uma **Digital Wallet**.  
Os diagramas seguem a notação **C4** (Context e Container) para facilitar a visualização de microserviços.

---

## Diagramas incluídos

- **Context Diagram**: visão geral do sistema, mostrando como ele interage com usuários e sistemas externos.  
- **Container Diagram**: detalha os microserviços internos, APIs, bancos de dados e comunicação assíncrona.

Os arquivos `.puml` estão dentro da pasta `c4-model/`.

---

## Como visualizar os diagramas

Você pode gerar os diagramas a partir dos arquivos `.puml` usando:

- [PlantUML Online](https://plantuml.com/pt/online)  
- Extensões para VS Code, como **PlantUML**  
- Linha de comando:

```bash
java -jar plantuml.jar diagrams/seu-diagrama.puml
