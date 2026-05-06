# Hola, soy Luis Angel Aranda Avila 👋

## Ingeniero Backend | Arquitecto en la Nube | Especialista en Python

<div align="center">

[![GitHub followers](https://img.shields.io/github/followers/tuUsuario?style=social)](https://github.com/tuUsuario)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://linkedin.com/in/luis-aranda-backend)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=flat&logo=gmail)](mailto:aranda.117318@gmail.com)
[![Twitter](https://img.shields.io/badge/Twitter-Follow-1DA1F2?style=flat&logo=twitter)](https://twitter.com/tuHandle)

**Mérida, Yucatán, México 🌎 | Remote Developer 💻**

</div>

---

## 🚀 Acerca de Mí

Soy un ingeniero backend con **más de 5 años de experiencia** diseñando y construyendo **APIs escalables, microservicios y arquitecturas en la nube**. 

He liderado el desarrollo de **18+ proyectos en producción** en diversas industrias (fintech, deportes, bienes raíces, SaaS), generando impacto real en millones de transacciones y usuarios activos.

**Mi enfoque:** Construir sistemas confiables, bien documentados y orientados al negocio que escalen eficientemente.

---

## 🛠️ Tech Stack

### Lenguajes
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

### Backend Frameworks
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat&logo=laravel&logoColor=white)

### Bases de Datos
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-13AA52?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

### Cloud & DevOps
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![CloudFormation](https://img.shields.io/badge/CloudFormation-FF9900?style=flat&logo=amazon-aws&logoColor=white)

### Herramientas & Servicios
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-626262?style=flat&logo=stripe&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37B24D?style=flat&logo=celery&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-2496ED?style=flat&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)

---

## 💼 Experiencia Profesional

### Ingeniero Backend | **Dacodes** 
**Enero 2020 – Presente (6 años)**  
*Mérida, Yucatán, México*

Lideré desarrollo backend en 18+ proyectos de producción. Arquitecturé sistemas escalables en AWS, gestioné bases de datos complejas e implementé integraciones de pagos y APIs críticas.

#### Logros Clave:
- 🏆 **Poball Platform:** Plataforma de apuestas deportivas con 50K+ usuarios diarios, implementando procesamiento asincrónico con Celery, Redis optimization y arquitectura de microservicios AWS (ECS/Fargate) con 99.9% uptime
  
- 🏆 **Bili System:** Sistema integral de procesamiento de tickets con WhatsApp, Google Cloud Vision OCR, S3 file handling, y generación automática de facturas CFDI. 10K+ transacciones mensuales.

- 🏆 **Payment Integration:** Implementación completa de Stripe (suscripciones, webhooks, precios dinámicos) + Apple IAP para monetización híbrida web/móvil

- 🏆 **AWS Infrastructure:** Diseñé infraestructura con Auto Scaling Groups, ALBs, CloudFront CDN, Lambda automation, CloudFormation IaC y secure VPC networking

- 🏆 **Team Leadership:** Mentoresé 5+ desarrolladores junior, establecí estándares de testing (pytest), documentación y best practices

#### Métricas de Impacto:
- ✅ 18+ proyectos en producción
- ✅ 99.9% uptime en sistemas críticos
- ✅ 40+ AWS Lambda automations deployadas
- ✅ 100+ API endpoints documentados
- ✅ 5+ team members capacitados

---

## 🎯 Proyectos Destacados

### 1. **Poball** — Plataforma de Apuestas Deportivas
**Django + Celery + AWS ECS/Fargate + Stripe**

Una plataforma compleja de apuestas deportivas que requería procesamiento asincrónico en tiempo real, sincronización de datos y escalabilidad horizontal.

**Desafíos Técnicos:**
- Procesamiento de millones de transacciones diarias
- Lógica de torneos y reglas complejas
- High-concurrency environment (50K+ usuarios simultáneos)

**Solución:**
- Workers Celery distribuidos con Redis broker
- AWS ECS/Fargate para escalabilidad horizontal
- PostgreSQL optimizado con índices estratégicos
- CloudFront CDN para assets estáticos
- Stripe webhooks para eventos de billing

**Resultado:**
- 99.9% uptime en producción
- <200ms latencia promedio en APIs
- Procesamiento de 1M+ requests/día

```bash
# Stack Técnico:
Django 4.2 | Django REST Framework | Celery | Redis
PostgreSQL | AWS ECS | Fargate | ALB | CloudFront
Stripe API | AWS Lambda | CloudFormation
```

---

### 2. **Bili** — Sistema de Procesamiento de Tickets
**FastAPI + Google Cloud Vision + S3 + CFDI**

Sistema integral de gestión de gastos que procesa tickets fiscales vía WhatsApp, extrae datos con OCR y genera facturas automáticamente.

**Desafíos Técnicos:**
- Extracción de datos desde imágenes (OCR)
- Integración WhatsApp para entrada de datos
- Multi-tenant architecture con data isolation
- Generación de documentos fiscales (CFDI)

**Solución:**
- FastAPI para API moderna y rápida
- Google Cloud Vision para OCR de imágenes
- Twilio Sandbox para WhatsApp integration
- AWS S3 para almacenamiento seguro
- JWT authentication con role-based access control

**Resultado:**
- 10K+ transacciones procesadas
- 95%+ accuracy en OCR
- Multi-tenant system escalable

```bash
# Stack Técnico:
FastAPI | Google Cloud Vision | AWS S3 | Twilio
PostgreSQL | JWT Authentication | Role-Based Access Control
```

---

### 3. **Dingus** — Sistema de Versionado de Productos
**Flask + MongoDB + Docker**

Sistema flexible de versionado de productos con plantillas dinámicas para agilizar flujos de negocio.

**Features:**
- Múltiples versiones de plantillas
- Módulos reutilizables y dinámicos
- Autenticación JWT + session management
- AWS Secrets Manager para credenciales
- Docker containerization

**Testing & Quality:**
- Pytest con >80% coverage
- Automated CI/CD pipeline
- Comprehensive test scenarios

```bash
# Stack Técnico:
Flask | MongoDB | Docker | JWT | AWS Secrets Manager | Pytest
```

---

### 4. **Dvlopers** — Plataforma Inmobiliaria
**Strapi Headless CMS + PostgreSQL + CDN**

Marketplace inmobiliario con catálogo de 500+ propiedades y filtrado avanzado.

**Features:**
- Content modeling avanzado
- Custom API endpoints
- Multimedia handling (imágenes, videos)
- CDN integration
- Advanced filtering & search

**Optimización:**
- API response tuning
- Efficient pagination
- Media optimization

```bash
# Stack Técnico:
Strapi | PostgreSQL | Node.js | CloudFront CDN
```

---

## 📊 Estadísticas & Datos

<div align="center">

| Métrica | Valor |
|---------|-------|
| **Años de Experiencia** | 5+ |
| **Proyectos en Producción** | 18+ |
| **Lenguaje Principal** | Python 🐍 |
| **Framework Preferido** | FastAPI / Django |
| **Cloud Platform** | AWS ☁️ |
| **Uptime Promedio** | 99.9% |
| **API Endpoints Documentados** | 100+ |
| **Team Members Mentoreados** | 5+ |

</div>

---

## 🎓 Educación & Certificaciones

### 📚 Educación
- **Licenciatura en Ingeniería Informática**  
  Instituto Tecnológico de Tizimín (2015 – 2021)

### 🏆 Certificaciones
- **AWS Certified Cloud Practitioner** (2023 – 2024)
- **Ultimate AWS Certified Cloud Practitioner** — Udemy

---

## 🌟 Habilidades Clave

### Backend Development
- ✅ API Design (REST, GraphQL)
- ✅ Database Architecture & Optimization
- ✅ Microservices Design
- ✅ Async Processing & Queues
- ✅ Authentication & Security

### Cloud Architecture
- ✅ AWS Infrastructure
- ✅ Infrastructure as Code (CloudFormation, Terraform)
- ✅ Container Orchestration
- ✅ CI/CD Pipelines
- ✅ Monitoring & Observability

### Software Engineering
- ✅ Test-Driven Development (TDD)
- ✅ Code Review & Quality Standards
- ✅ System Design
- ✅ Technical Documentation
- ✅ Agile/Scrum Methodology

### Leadership & Communication
- ✅ Team Mentoring
- ✅ Technical Presentations
- ✅ Cross-functional Collaboration
- ✅ Problem Solving
- ✅ Knowledge Sharing

---

## 📚 Blog & Articulos

Comparto conocimiento y experiencias en:

- **"5 Django Performance Optimization Tricks"** — Optimization patterns que uso en producción
- **"AWS Lambda Cold Starts Solutions"** — Cómo optimizar Lambda para mejor performance
- **"Stripe Integration Best Practices"** — Lecciones de 5+ integraciones exitosas
- **"Building Scalable Payment Systems"** — Arquitectura para sistemas de pago

---

## 🤝 Cómo Trabajar Conmigo

### Estoy Abierto a:
- 💼 **Roles Técnicos:** Senior Backend Developer, Tech Lead, Staff Engineer
- 🏗️ **Proyectos:** Arquitectura, consultoría, code review
- 📚 **Mentoring:** Juntar developers, technical guidance
- 🎓 **Speaking:** Conferencias, webinars, meetups

### Mi Enfoque:
- 🎯 **Calidad:** Clean code, testing, documentation
- 🚀 **Escalabilidad:** Sistemas que crecen con el negocio
- 📊 **Impacto:** Soluciones orientadas a resultados
- 🤝 **Colaboración:** Trabajo en equipo, knowledge sharing

---

## 🔗 Conecta Conmigo

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/luis-aranda-backend)
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tuUsuario)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aranda.117318@gmail.com)
[![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white)](https://twitter.com/tuHandle)
[![Portfolio](https://img.shields.io/badge/Portfolio-%23000000.svg?style=for-the-badge&logo=firefox&logoColor=white)](https://tuportfolio.com)

**Siempre estoy abierto a conversaciones sobre:**
- 💡 Proyectos interesantes
- 🤝 Colaboraciones
- 💬 Intercambio de ideas
- 🎓 Mentoring

**¡No dudes en contactarme!** 📧

</div>

---

## 💬 Testimonios

> "Luis es un desarrollador excepcional con habilidades técnicas profundas y excelente capacidad de comunicación. Su trabajo en la arquitectura de Poball fue crucial para nuestro éxito."
> 
> — *Manager, Dacodes*

> "Trabajar con Luis en la integración de Stripe fue muy smooth. Documentó todo perfectamente y siempre estuvo disponible para preguntas."
> 
> — *Frontend Developer, Dacodes*

---

## 📝 Últimas Actualizaciones

### Mayo 2026
- ✅ Completé optimización de perfil GitHub
- ✅ Publiqué artículo sobre "AWS Lambda Best Practices"
- ✅ Mentoreé 2 nuevos developers junior
- ✅ Contribuí a 3 open source projects

### Abril 2026
- ✅ Implementé nuevo módulo en Poball
- ✅ Optimicé queries en PostgreSQL (-40% time)
- ✅ Escribí documentación de API
- ✅ Capacité al equipo en best practices

---

## 💡 Open Source Contributions

Si tienes proyectos interesantes o necesitas ayuda con:

- **Backend Development** — Django, FastAPI, Flask
- **AWS Architecture** — Diseño de infraestructura escalable
- **Database Optimization** — Performance tuning
- **Payment Integration** — Stripe, Apple IAP, etc.
- **Docker & DevOps** — Containerización y orquestación

**¡Me encantaría contribuir!** Abre un issue o contacta directamente.

---

<div align="center">

### ⭐ Si te gusta mi trabajo, dale una estrella a mis repos!

**"El código es poesía. La arquitectura es arte."**

---

![Profile Views](https://komarev.com/ghpvc/?username=tuUsuario&color=blue&style=flat-square)

Última actualización: 6 de mayo, 2026

</div>
