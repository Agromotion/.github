# Agromotion - Sistema Automatizado de Alimentação Animal

Este projeto foi desenvolvido como **Projeto Final de Curso** no âmbito da Licenciatura em **Engenharia de Sistemas Informáticos (Regime Pós-Laboral)** no **IPCA (Instituto Politécnico do Cávado e do Ave)**.

**Agromotion** é uma solução IoT (Internet of Things) integrada que permite o agendamento, gestão e monitorização remota de um sistema de alimentação automatizado para animais.

---

## Estrutura do Ecossistema

O projeto é composto por:

### 1. Sistema Embebido (Robô)

  
### 2. Aplicação
Interface de utilizador para controlo total do sistema.
* **Gestão de Horários:** Interface para criar, editar e alternar estados de alimentação.
* **Notificações Push:** Sistema de alertas via Firebase Cloud Messaging (FCM) para manter o utilizador informado sobre a atividade do robô.
* **Plataformas Suportadas:** Android, IOS, MacOS, Linux, Windows.

### 3. Website

---

## Stack Tecnológica

* **Linguagens:** Dart (Flutter), C++ (Arduino/ESP32).
* **Frameworks:** Flutter, Firebase SDK.
* **Protocolos:** WebSockets (Realtime DB), HTTPS, OAuth2.
* **Segurança:** Gestão de Service Accounts para envio de notificações e proteção de chaves VAPID.

---

## Funcionalidades Principais

* **Sincronização em Tempo Real:** Alterações na App refletem-se no robô instantaneamente.
* **Sistema de Notificações:** Notificações disparadas automaticamente quando um horário é alterado ou uma tarefa concluída.
* **Interface Adaptativa:** Suporte para diferentes temas e design responsivo para diferentes dispositivos.
* **Segurança de Acesso:** Login social via Google, e-mail e palavra-passe.

---

## Compilação e Execução

### App (Flutter)
1. Instalar dependências: `flutter pub get`
2. Configurar assets: Adicionar `service-account.json` em `assets/`.
3. Configurar .env: Adicionar `env.dart` em `lib/config`.
4. Executar: `flutter run`


---

## Autores e Instituição

* **Instituição:** IPCA - Instituto Politécnico do Cávado e do Ave
* **Curso:** Engenharia de Sistemas Informáticos (Pós-Laboral)
* **Projeto:** Projeto Final de Curso
* **Desenvolvido por:** Miguel Areal, Júlio Faria
