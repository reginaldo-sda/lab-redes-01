![GitHub License](https://img.shields.io/github/license/reginaldo-sda/lab-red-01)

# Laboratório de redes 01 - Projeto de Rede local

Aluno: Reginaldo Soares

Professor: José de Assis

Data: 09/003/2026

---

## 1. Objetivo
Implantar uma rede local simples conectando 3 notebooks a um roteador
wireless com switch e uma impressora de rede.

O projeto será dividido em duas etapas:

1. simulação da rede no cisco packet Tracer
2. Implementação de rede no laboratório real

---

## 2. Equipamentos utilizados neste laboratório:

- 3 /notebooks
- 1 roteador wireless com 1 porta WAN e 4 portas LAN
- 1 impressora de rede
- cabos de rede

---

## 3. Topologia da Rede

Diagrama lógico da rede usada neste laboratório.
```mermaid
graph TD

WAN[internet / WAN do Provedor]

Router[Roteador Wireless<br>1 Porta WAN<br>4 Portas LAN]

PC1[Notebook 1]
PC2[Notebook 2]
PC3[Notebook 3]

Printer[Impressora de Rede]

WAN --> |Porta WAN| Router

Router --> |LAN 1| PC1
Router --> |LAN 2| PC2
Router --> |LAN 3| PC3
Router --> |LAN 4| Printer
```


## Imagem da topologia usada neste laboratória:

<img width="1158" height="653" alt="topologia" src="https://github.com/user-attachments/assets/45158dec-54b2-4374-a9ee-f9b3ed253831" />

---

