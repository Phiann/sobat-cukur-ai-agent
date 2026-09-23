# 💈 Sobat Cukur

### AI-Powered WhatsApp Barbershop Assistant

> AI Agent yang membantu pelanggan melakukan reservasi,
> mengecek jadwal barber, dan mendapatkan informasi layanan
> barbershop melalui WhatsApp.

---

## 📌 About

**Sobat Cukur** adalah AI Agent berbasis WhatsApp yang dirancang
untuk membantu operasional barbershop secara otomatis.

Sistem ini memungkinkan pelanggan berinteraksi dengan barbershop
melalui WhatsApp tanpa harus dilayani secara manual untuk setiap
permintaan.

---

## ✨ Features

- 💬 Customer service melalui WhatsApp
- 💈 Melihat daftar barber
- 📅 Mengecek jadwal barber
- 🕐 Mengecek slot tersedia
- 📋 Membuat booking
- 🔄 Mengelola booking
- 👤 Mengelola profil customer
- 🔔 Notifikasi booking
- 🤖 AI-powered conversation

---

## 🏗️ System Architecture

```text
Customer
    │
    ▼
 WhatsApp
    │
    ▼
  Fonnte
    │
    ▼
 n8n Webhook
    │
    ▼
 AI Agent
    │
    ├── Search Barber
    ├── Search Booking
    ├── Create Booking
    ├── Update Booking
    └── Customer Profile
    │
    ▼
  NocoDB
    │
    ▼
 PostgreSQL
