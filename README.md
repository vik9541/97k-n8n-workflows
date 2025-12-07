# ⚙️ 97k n8n Workflows

**n8n Workflow Automation для заказов, платежей, ЭДО и интеграций**

## Установка

```bash
# Клонируем
git clone https://github.com/vik9541/97k-n8n-workflows.git
cd 97k-n8n-workflows

# Запуск n8n
docker-compose up -d

# http://localhost:5678
```

## Основные Workflows

### 1. Order Processing
- Trigger: Новый заказ в BD
- Акции: Выгружка в 1С, генерация PDF, email

### 2. Payment Processing
- Trigger: Webhook от YooKassa
- Акции: Обновление статуса, МуОП, email

### 3. EDO Integration
- Trigger: Webhook от Diadoc
- Акции: Обновление статуса, архивирование

### 4. Inventory Sync
- Trigger: Каждый час
- Акции: Синхронизация товаров и остатков

## Конфигурация

Очистите креденциалы для ваших интеграций:

- YooKassa API key
- Diadoc Auth token
- 1С credentials
- SendGrid API key
- Twilio credentials
