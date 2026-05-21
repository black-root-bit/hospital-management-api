# 🏥 hospital-management-api

> Complete hospital management backend — patients, doctors, appointments, prescriptions, billing.

[![Java](https://img.shields.io/badge/Java-17-ED8B00?style=flat-square&logo=openjdk)](https://openjdk.org/)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.2-6DB33F?style=flat-square&logo=springboot)](https://spring.io/projects/spring-boot)
[![MySQL](https://img.shields.io/badge/MySQL-8-4479A1?style=flat-square&logo=mysql)](https://mysql.com)

**Features:** Patient records management · Doctor scheduling & availability · Appointment booking system · Prescription management · Lab test results · Billing & invoicing · Department management · Role-based access (ADMIN / DOCTOR / NURSE / PATIENT)

**Key Endpoints:**
```
POST  /api/v1/patients                         # Register patient
GET   /api/v1/doctors/{id}/availability        # Doctor schedule
POST  /api/v1/appointments                     # Book appointment
PUT   /api/v1/appointments/{id}/confirm        # Confirm [DOCTOR]
POST  /api/v1/prescriptions                    # Create prescription [DOCTOR]
GET   /api/v1/patients/{id}/records            # Medical history
POST  /api/v1/billing/generate                 # Generate invoice [ADMIN]
```

**GitHub Topics:** `java` `spring-boot` `healthcare` `hospital-management` `rest-api` `mysql` `docker` `swagger`
