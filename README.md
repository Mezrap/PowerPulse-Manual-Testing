# PowerPulse – Manual Testing Project

PowerPulse, kullanıcıların günlük aktivitelerini, beslenme ve egzersiz süreçlerini takip etmelerini sağlayan bir web uygulamasıdır.

Bu repository, PowerPulse uygulamasının **manuel yazılım testleri** kapsamında gerçekleştirilen QA çalışmalarını, test dokümantasyonunu, test sonuçlarını, hata raporlarını ve proje yönetimi çalışmalarını içermektedir.

---

## 🎯 Projenin Amacı

Bu projenin amacı, PowerPulse uygulamasının müşteri gereksinimlerine ve beklenen kullanıcı davranışlarına uygunluğunu manuel test yöntemleriyle doğrulamaktır.

Test sürecinde;

- Gereksinimler analiz edilmiş,
- Test kapsamı belirlenmiş,
- Checklist'ler hazırlanmış,
- Test Case'ler oluşturulmuş,
- Test Case'ler yürütülmüş,
- Hatalar tespit edilerek Bug Report'lar hazırlanmış,
- API / backend davranışları Swagger ve Chrome DevTools üzerinden doğrulanmış,
- Test sonuçları RTM üzerinden izlenebilir hale getirilmiş,
- Test ve hata yönetimi Jira ve TestRail üzerinden takip edilmiştir.

---

## 🔍 Test Kapsamı

Proje kapsamında aşağıdaki kullanıcı ve modüller test edilmiştir:

### Yetkisiz Kullanıcı

- Başlangıç Sayfası
- Header
- Sign In
- Sign Up
- Email Validation
- Password Validation
- Name Validation

### Yetkili Kullanıcı

- Header
- Profile Settings
- Diary
- Products
- Exercises

Testler kapsamında UI, fonksiyonel davranışlar, veri görüntüleme, validasyon, state management, business logic, responsive davranışlar ve backend entegrasyonları kontrol edilmiştir.

---

## 🧪 Test Yaklaşımı

Proje manuel test odaklı yürütülmüştür.

Test çalışmalarında gereksinim bazlı test yaklaşımı esas alınarak:

- Functional Testing
- UI Testing
- Validation Testing
- Navigation Testing
- Data Display Testing
- State Management Testing
- Business Logic Testing
- Responsive UI Testing
- Backend Integration Testing
- API Testing
- Integration Testing
- System Testing
- Acceptance Testing
- Regression / Re-test kontrolleri

uygulanmıştır.

Test Case'ler müşteri gereksinimleri ve ilgili checklist maddeleri üzerinden oluşturularak yürütülmüştür.

---

## 📋 Test Dokümantasyonu

Proje kapsamında aşağıdaki QA dokümanları hazırlanmıştır:

| Doküman | Amaç |
|---|---|
| **RTM – Requirements Traceability Matrix** | Gereksinimlerin checklist, test case ve bug raporlarıyla izlenebilirliğini sağlamak |
| **Checklist** | Gereksinimlerin varlık, görünürlük ve temel davranış kontrollerini gerçekleştirmek |
| **Test Case** | Fonksiyonların adım adım test edilmesini ve beklenen sonuçların doğrulanmasını sağlamak |
| **Bug Report** | Tespit edilen hataları standart formatta belgelemek |
| **İçindekiler** | Modül dokümanlarının hiyerarşik olarak düzenlenmesini sağlamak |
| **Sprint Planı** | Sprint bazında yapılacak QA çalışmalarını planlamak |
| **Günlük Scrum Kaydı** | Gerçekleşen günlük çalışmaların takip edilmesini sağlamak |
| **QA Dokümantasyon Standardı** | Proje genelindeki ID, kod, numaralandırma ve test type standartlarını belirlemek |
| **QA Belge Dizini** | Proje dokümanlarının merkezi olarak takip edilmesini sağlamak |

---

## 🗂️ Proje Yapısı

```text
PowerPulse-Manual-Testing/
│
├── 00_Proje_Yönetimi/
│   ├── 00 - QA_Dokümantasyon_Standardı.docx
│   ├── 01 - QA_Belge_Dizini.xlsx
│   ├── 03 - Sprint_Planı.docx
│   ├── 04 - Günlük_Scrum_Kaydı.xlsx
│   └── ...
│
├── 01_Yetkisiz_Kullanıcı_Başlangıç_Header/
│
├── 02_Yetkisiz_Kullanıcı_Kayıt_Giriş/
│
├── 03_Yetkili_Kullanıcı_Header/
│
├── 04_Yetkili_Kullanıcı_Profile_Settings/
│
├── 05_Yetkili_Kullanıcı_Diary/
│
├── 06_Yetkili_Kullanıcı_Products/
│
├── 07_Yetkili_Kullanıcı_Exercises/
│
└── README.md# 

---

### 📁 Tüm Proje Dokümantasyonu

**[PowerPulse – QA Project Documentation](https://drive.google.com/drive/folders/1TnHAVVsTXDlDeeHpc6fVwZJIBEFSwNx9?usp=drive_link)**

Projenin tüm QA dokümantasyonuna, test çalışmalarına ve destekleyici proje dosyalarına Google Drive üzerinden erişilebilir.


## 👤 QA Tester

**Beril Z. Ovayurt**

**Role:** Manual QA / Software Test Engineer**