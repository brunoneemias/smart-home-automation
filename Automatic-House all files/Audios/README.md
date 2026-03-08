# 🔊 Áudios — Smart Home Simulation

> Arquivos de áudio utilizados para simular sons de eletrodomésticos e eventos da residência no projeto **hom\<on>**.

---

## 📖 Sobre

Para tornar a simulação mais realista, o projeto utiliza arquivos de áudio que reproduzem sons do cotidiano de uma casa. Cada som é acionado pelo Arduino ou pelo app em resposta a eventos específicos, como abertura da garagem, alarme disparado ou eletrodomésticos em uso.

---

## 🎵 Arquivos de Áudio

### Sons de Ambiente / Eletrodomésticos

| Arquivo | Duração | Simulação |
|---|:---:|---|
| `Chiado TV 4s.mp3` | 4s | Televisão ligada |
| `Tv willian 10s.mp3` | 10s | Televisão em funcionamento |
| `Microondas 10s.mp3` | 10s | Microondas em uso |
| `Maquina 8s.mp3` | 8s | Máquina de lavar |
| `Garagem rápida 1s.mp3` | 1s | Abertura/fechamento da garagem |

### Alarmes

| Arquivo | Duração | Simulação |
|---|:---:|---|
| `Alarme 8s.mp3` | 8s | Alarme de segurança |
| `Alarme 10s.mp3` | 10s | Alarme de segurança (longo) |

### Arquivos .ad4

| Arquivo | Descrição |
|---|---|
| `0001.ad4` ~ `0006.ad4` | Áudios em formato AD4 para reprodução em módulo de som dedicado (DFPlayer Mini ou similar) |

---

## 🔌 Como eram utilizados

Os áudios `.mp3` e `.ad4` eram reproduzidos via **módulo de som conectado ao Arduino**, simulando a presença e atividade de moradores na residência. Exemplos de uso:

- Ao acionar a **garagem** → toca `Garagem rápida 1s.mp3`
- Ao simular **presença em casa** → toca som de TV ou eletrodoméstico
- Ao disparar o **sistema de alarme** → toca `Alarme 10s.mp3`

---

## 📄 Documentos

| Arquivo | Descrição |
|---|---|
| `Artigo - Residencia Automatizada.doc` | Artigo técnico do projeto |
| `Resumo entrega TCC - Residencia Automatizada.docx` | Resumo para entrega do TCC na ETEC |

---

## 👨‍💻 Autor

**Bruno Neemias** — Projeto educacional desenvolvido na **ETEC**.

[![GitHub](https://img.shields.io/badge/GitHub-brunoneemias-181717?style=flat&logo=github)](https://github.com/brunoneemias)
