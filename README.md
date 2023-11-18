# p2p-chat

# Цель проекта - разработка однорангового мессенджера с шифрованием сообщений для общения по защищенному каналу связи.

# Функциональные требования:
- [P2P-FR-001](./requirements/functional/P2P-FR-001.md) Экспорт информации участника сети.
- [P2P-FR-002](./requirements/functional/P2P-FR-002.md) Импорт информации участника сети.
- [P2P-FR-003](./requirements/functional/P2P-FR-003.md) Отправка текстовых сообщений.
- [P2P-FR-004](./requirements/functional/P2P-FR-004.md) Отправка файлов.
- [P2P-FR-005](./requirements/functional/P2P-FR-005.md) Сквозное шифрование.
- [P2P-FR-006](./requirements/non-functional/P2P-NFR-006.md) Наличие консольного клиента.

# Нефункциональные требования:
- [P2P-NFR-001](./requirements/non-functional/P2P-NFR-001.md) Архитектура проекта должна быть модульной и содержать минимум: ядро для работы с сетью и консольный клиент.
- [P2P-NFR-002](./requirements/non-functional/P2P-NFR-002.md) Ядро нужно реализовать с возможностью встраивания в другие типы клиентов. 
- [P2P-NFR-003](./requirements/non-functional/P2P-NFR-003.md) Для передачи данных предлагается использовать протокол [GossipSub][1]
- [P2P-NFR-004](./requirements/non-functional/P2P-NFR-004.md) ЯП - [golang 1.21.4][2]
- [P2P-NFR-005](./requirements/non-functional/P2P-NFR-005.md) [e2e тесты][3].

[1]: https://go.dev/dl/
[2]: https://research.protocol.ai/blog/2019/a-new-lab-for-resilient-networks-research/PL-TechRep-gossipsub-v0.1-Dec30.pdf
[3]: https://software-testing.ru/library/testing/testing-for-beginners/3978-e2e-testing-manifesto