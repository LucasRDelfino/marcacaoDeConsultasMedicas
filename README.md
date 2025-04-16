# App de Agendamento de Consultas

**Nome completo:** Lucas Rodrigues Delfino 
**RM:** 550196

## 📱 Descrição do Projeto

Este aplicativo permite ao usuário visualizar e agendar consultas médicas, com persistência de dados local no dispositivo. O projeto foi desenvolvido em React Native com foco na experiência do usuário e na organização do código.

---

## ✅ Funcionalidades Implementadas

- **Exibição de Consultas na Tela Inicial**  
  As consultas previamente salvas são carregadas e exibidas automaticamente ao abrir o aplicativo.

- **Persistência de Dados com AsyncStorage**  
  As informações das consultas são armazenadas localmente utilizando `@react-native-async-storage/async-storage`, garantindo que os dados permaneçam salvos mesmo após o fechamento do app.

- **Seletor de Data e Hora**  
  Foi utilizado `@react-native-community/datetimepicker` para facilitar a seleção de datas e horários no momento do agendamento.

- **Refatoração dos Tipos do Projeto**  
  Os tipos TypeScript foram reorganizados em arquivos separados por domínio dentro da pasta `src/types`, aplicando o princípio da segregação de responsabilidades. Isso melhora a manutenibilidade, legibilidade e escalabilidade do código.
