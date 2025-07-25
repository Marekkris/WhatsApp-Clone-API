# WhatsApp-Clone-API

🚀 **Backend**: Java Spring Boot  
🎨 **Frontend**: Angular (TypeScript)  
🔒 **Auth**: Keycloak  
🗄️ **Database**: PostgreSQL  
🌐 **Real-time**: WebSockets  

## 📖 Описание проекта
Проект представляет собой веб-приложение с разделением на бэкенд и фронтенд части.

## 🛠 Технологический стек

### **Backend** ⚙️
| Компонент | Назначение |
|-----------|------------|
| <img src="https://cdn.worldvectorlogo.com/logos/intellij-idea-1.svg" width=20> **IntelliJ IDEA** | IDE для разработки |
| <img src="https://cdn.worldvectorlogo.com/logos/spring-3.svg" width=20> **Spring Boot 3.4.2** | Бэкенд-фреймворк |
| <img src="https://www.keycloak.org/resources/images/logo.svg" width=100> **Keycloak** | Аутентификация |
| <img src="https://cdn.worldvectorlogo.com/logos/postgresql.svg" width=20> **PostgreSQL 15** | База данных |
| <img src="https://cdn.worldvectorlogo.com/logos/websocket.svg" width=20> **WebSockets** | Реальный времени |

### **Frontend** 🎨
| Компонент | Назначение |
|-----------|------------|
| <img src="https://cdn.worldvectorlogo.com/logos/angular-icon-1.svg" width=20> **Angular 19+** | Фронтенд-фреймворк |
| <img src="https://cdn.worldvectorlogo.com/logos/typescript.svg" width=20> **TypeScript** | Основной язык |

## 🚀 Запуск проекта
### Backend
1. Развернуть Keycloak и PostgreSQL в Docker Desktop и запустить их:
   ```bash
   docker-compose up -d
2. Запустите Spring Boot приложение:
   ```bash
   ./mvnw spring-boot:run
или
(В IntelliJ IDEA нажмите кнопку запуска)

### Frontend
1. Установите зависимости:
   ```bash
   npm install
2. Запустите Angular приложение:
   ```bash
   ng serve

📦 Зависимости Frontend по отдельности:
   ```bash
npm i @fortawesome/fontawesome-free
npm i bootstrap
npm i keycloak-js
npm i ng-openapi-gen
npm i quill
npm i sockjs-client
npm i stompjs
