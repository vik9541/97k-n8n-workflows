# 97k-n8n-workflows - Automation Module of super-brain-digital-twin

> **MAIN PROJECT:** [super-brain-digital-twin v5.0 (97v.ru)](https://github.com/vik9541/super-brain-digital-twin)  
> **MASTER DOC:** [MASTER_README.md](https://github.com/vik9541/super-brain-digital-twin/blob/main/MASTER_README.md)  
> **ARCHITECTURE:** [STRUCTURE.md](https://github.com/vik9541/super-brain-digital-twin/blob/main/STRUCTURE.md)

---

## This Module: n8n Automation Workflows

- Status: 4 CORE WORKFLOWS ACTIVE
- Platform: n8n (Open-source workflow automation)
- Integration: Webhooks to 97k-backend API

## Workflows

1. **Order Processing** - New order -> Validate -> Sync to 1C -> Confirm
2. **Payment Gateway** - Payment request -> Verify -> Process -> Receipt
3. **EDO Integration** - Invoice -> Send to portal -> Track status
4. **Inventory Sync** - Daily 08:00 -> Fetch from 1C -> Update DB

## Deployment

docker run -d -p 5678:5678 --name n8n n8nio/n8n

## Related Modules

- [super-brain-digital-twin](https://github.com/vik9541/super-brain-digital-twin) - Main Project
- [97k-backend](https://github.com/vik9541/97k-backend) - NestJS API
- [97k-frontend](https://github.com/vik9541/97k-frontend) - React app
- [97k-database](https://github.com/vik9541/97k-database) - PostgreSQL schema
- [97k-infrastructure](https://github.com/vik9541/97k-infrastructure) - DevOps
- [97k-97v-specs](https://github.com/vik9541/97k-97v-specs) - Specs

---

**Status**: ACTIVE | **Workflows**: 4 | **Module of**: super-brain-digital-twin v5.0
