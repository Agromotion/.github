# Agromotion: Sistema Automatizado de Alimentação Animal

O **Agromotion** é um ecossistema IoT (Internet of Things) desenvolvido como **Projetos Finais de Curso** da Licenciatura em **Engenharia de Sistemas Informáticos** (IPCA). A solução permite o agendamento, gestão e monitorização remota de um alimentador animal inteligente, unindo hardware robusto a uma interface intuitiva.

*Nota: Apesar de ser o mesmo ecossistema, o projeto é dividido em **dois projetos diferentes** que se complementam numa solução final.*

<p align="center">
  <img src="logo_w_512.png" alt="Agromotion logo" width="175" style =  >
</p>

---

## Estrutura do Ecossistema

O projeto divide-se em três pilares fundamentais, cada um com o seu repositório dedicado:

### 1. [Agromotion Robot](https://github.com/Agromotion/agromotion-robot)
O hardware do projeto. Um sistema embebido capaz de processar comandos e executar a alimentação a animais.
* **Hardware:** Baseado em Arduino e Raspberry Pi.
* **Funcionalidades:** Ativação de motores de precisão, câmara e comunicação em tempo real.

### 2. [Agromotion App](https://github.com/Agromotion/agromotion-app)
A central de comando do utilizador, desenvolvida para ser verdadeiramente multiplataforma.
* **Gestão:** Agendamento de horários e controlo manual do alimentador.
* **Cloud:** Integração com Firebase para sincronização de dados e notificações push (FCM).
* **Suporte:** Android, iOS, Windows.

### 3. [Agromotion Website](https://github.com/Agromotion/agromotion-web)
A montra digital do projeto. Um portal informativo que detalha a visão, os objetivos e os resultados alcançados pelo Agromotion.

---

## Equipa e Responsabilidades

O projeto foi concebido por dois estudantes, dividindo o trabalho entre duas camadas: Hardware (Firmware) e Software (Application/Cloud):

| Desenvolvedor | Foco Principal | Responsabilidades |
| :--- | :--- | :--- |
| **Júlio Faria** | **Firmware & Hardware** | Construção física do robô, eletrónica, lógica de controlo em Arduino/Raspberry Pi. |
| **Miguel Areal** | **Software & Backend** | Desenvolvimento da App, arquitetura Firebase e integração App-Robô. |

*Ambos colaboraram no desenvolvimento e design do **Website Informativo**.*

---

## Tecnologias

* **Linguagens:** Dart, C++, Python, Javascript.
* **Infraestrutura:** Firebase (Auth, Firestore, Messaging).
* **Hardware:** Sensores IoT, Motores, Microcontroladores, Câmara.

---

## Contexto Académico
* **Instituição:** [IPCA](https://www.ipca.pt) - Instituto Politécnico do Cávado e do Ave
* **Curso:** Engenharia de Sistemas Informáticos (Regime Pós-Laboral)
* **Unidade Curricular:** Projeto Final de Curso
* **Ano Letivo:** 2025-2026
