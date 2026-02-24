# AyCafe - Bulut Tabanlı Mobil Ödeme ve Cafe Yönetim Sistemi

AyCafe, modern web mimarileri ve bulut bilişim teknolojileri kullanılarak geliştirilmiş kapsamlı bir dijital cüzdan ve cafe sadakat sistemidir. Bu proje, bir mobil arayüzün güçlü bir backend mimarisi (Firebase & Iyzico API) ile nasıl entegre edildiğini göstermek amacıyla bir Web Programlama projesi olarak geliştirilmiştir.

## 🚀 Proje Genel Özellikleri
* **Kullanıcı Yönetimi:** Firebase Auth ile güvenli kayıt ve giriş sistemi.
* **Dijital Cüzdan:** Kullanıcıların hesaplarına bakiye yükleyebilmesi ve takip edebilmesi.
* **Iyzico Entegrasyonu:** 3D Secure destekli, güvenli ve gerçek zamanlı ödeme alma mekanizması.
* **Bulut Veritabanı:** Firestore NoSQL ile senkronize veri yönetimi.
* **Serverless Backend:** Node.js tabanlı Firebase Cloud Functions ile sunucu taraflı işlem yönetimi.

## 🏗️ Kullanılan Teknolojiler
* **Frontend:** Kotlin (Android SDK)
* **Backend:** Node.js (Firebase Cloud Functions)
* **Veritabanı:** Firebase Firestore
* **Ödeme Gateway:** Iyzico Checkout Form API
* **Mimariler:** RESTful API prensipleri, Server-Side Logic

## 📅 Proje Planlama ve Yapım Aşamaları
1. **Analiz ve Tasarım:** Veri modellerinin (User, Balance, Transaction) Firestore üzerinde kurgulanması.
2. **Backend Kurulumu:** Firebase projesinin oluşturulması ve Node.js ortamının (Functions) hazırlanması.
3. **Ödeme Entegrasyonu:** Iyzico Sandbox anahtarlarının backend'e tanımlanması ve ödeme formunu oluşturan web servisinin yazılması.
4. **Android Geliştirme:** WebView ve Firebase SDK kullanılarak mobil arayüzün backend servislerine bağlanması.
5. **Test ve Optimizasyon:** Sandbox kartları ile ödeme akışının ve veritabanı güncellemelerinin test edilmesi.

## 🛠️ Kurulum Notları
Projenin backend kısmını çalıştırmak için `iyzi` klasörü altında `npm install` komutu çalıştırılmalı ve `firebase deploy` ile buluta yüklenmelidir.
