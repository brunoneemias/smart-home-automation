# 📱 APP Mobile — Smart Home

> Aplicativo Android para controle da iluminação residencial via Bluetooth, parte do projeto **Smart Home Automation**.

---

## 📖 Sobre

Aplicativo mobile desenvolvido em **Delphi (FireMonkey)** para Android, responsável por enviar comandos ao Arduino via **Bluetooth (HC-05)** e controlar os 10 pontos de iluminação da residência.

---

## 🛠️ Tecnologias

| Ferramenta | Descrição |
|---|---|
| Delphi / RAD Studio | IDE e linguagem de desenvolvimento |
| FireMonkey (FMX) | Framework de UI multiplataforma |
| Object Pascal | Linguagem de programação |
| Bluetooth clássico | Comunicação com o módulo HC-05 |
| Android | Plataforma alvo |

---

## 📁 Estrutura dos Arquivos

| Arquivo | Descrição |
|---|---|
| `Unit1.pas` / `Unit1.fmx` | Tela principal e lógica do app |
| `BTConfig.pas` | Configuração e gerenciamento do Bluetooth |
| `Remote.dpr` / `Remote.dproj` | Projeto principal Delphi |
| `AndroidManifest.template.xml` | Permissões e configurações Android |
| `Remote.res` | Recursos do projeto |

---

## ⚙️ Funcionalidades

- [x] Conexão com módulo Bluetooth HC-05
- [x] Envio de comandos para controle de até 10 luzes
- [x] Interface mobile para acionamento por ambiente
- [x] Integração direta com o Arduino do projeto Smart Home

---

## 🔗 Integração com o Arduino

O app se comunica com o módulo **HC-05** conectado ao Arduino. Cada botão no app envia um comando que o Arduino interpreta para ligar ou desligar o LED do ambiente correspondente.

> Consulte o módulo [`/Arduino`](../Arduino) para entender a lógica de recepção dos comandos.

---

## 👨‍💻 Autor

**Bruno Neemias**  
Projeto desenvolvido para fins educacionais.

[![GitHub](https://img.shields.io/badge/GitHub-brunoneemias-181717?style=flat&logo=github)](https://github.com/brunoneemias)
