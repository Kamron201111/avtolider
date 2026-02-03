# TEXNIK TOPSHIRIQ (TZ)
## Avtolider - Avtomaktab O'quv Tizimi

---

## 📋 LOYIHA HAQIDA

**Loyiha nomi:** Avtolider - Professional Avtomaktab Veb Platformasi  
**Texnologiyalar:** React, TypeScript, Tailwind CSS v4  
**Versiya:** 1.0  
**Sana:** 2024-yil  

---

## 🎯 LOYIHANING MAQSADI

Avtolider avtomaktabi uchun zamonaviy, to'liq funksional veb-platforma yaratish:
- Online ro'yxatdan o'tish tizimi
- Interaktiv o'quv platformasi
- Test va imtihon tizimi
- Obuna va to'lov tizimi
- Dark/Light mode qo'llab-quvvatlash

---

## 🎨 DIZAYN TIZIMI

### Rang Palitra
- **Asosiy qora:** `#0a0a0a` (background)
- **Asosiy qizil/burgundy:** `#8b2e2e` (primary)
- **Oq:** `#ffffff` (text)
- **Kulrang tonlar:** Muted foreground va secondary ranglari

### Dizayn Uslubi
- ✅ Zamonaviy dark theme (default)
- ✅ Light mode qo'llab-quvvatlash
- ✅ Responsive dizayn (mobile, tablet, desktop)
- ✅ Smooth animatsiyalar va transitions
- ✅ Professional va minimalistik

---

## 📁 ARXITEKTURA

### Fayl Tuzilishi
```
/src
  /app
    /components
      - Header.tsx              # Sticky header, navigation
      - Footer.tsx              # Footer linklar va aloqa
      - Hero.tsx                # Landing bosh section
      - About.tsx               # Kompaniya haqida
      - Courses.tsx             # Kurslar ro'yxati
      - Contact.tsx             # Aloqa forma
      - AuthModal.tsx           # Login/Register modal
      - UserDashboard.tsx       # User shaxsiy kabineti
      - PrivacyPolicy.tsx       # Maxfiylik siyosati sahifa
      - TermsOfService.tsx      # Foydalanish shartlari
      - ThemeToggle.tsx         # Dark/Light mode toggle
      - SubscriptionPlans.tsx   # Obuna rejalari
      - TestSystem.tsx          # Imtihon test tizimi
    - App.tsx                   # Asosiy routing va state
  /styles
    - fonts.css                 # Font importlar
    - theme.css                 # CSS tokenlar
```

---

## 🔧 ASOSIY FUNKSIYALAR

### 1. LANDING SAHIFA (Home)

#### 1.1 Header
- ✅ Logo (Avtolider) - 12px balandlik
- ✅ Desktop navigation: Kurslar, Nega biz?, O'qish jarayoni
- ✅ Theme toggle (dark/light mode)
- ✅ "Ro'yxatdan o'tish" tugmasi
- ✅ Mobile hamburger menu
- ✅ Sticky positioning
- ✅ Backdrop blur effect

#### 1.2 Hero Section
- ✅ Gradient background
- ✅ Asosiy heading: "Haydovchilik san'atini professional o'rganing"
- ✅ Qizil va oq ranglar uchun gradient text
- ✅ 2ta CTA tugma:
  - "KURSGA YOZILISH" (gradient red)
  - "Telegram orqali savol berish" (border, light modeda ko'rinadi)
- ✅ Statistika kartochkalari: 1500+, 95%, 12+
- ✅ Counter animatsiyalari
- ✅ Hover scale effects

#### 1.3 About (Nega biz?)
- ✅ 6ta ustunlik kartochkalari:
  - Professional instruktorlar
  - Zamonaviy mashina parki
  - Moslashuvchan jadval
  - 95% muvaffaqiyat
  - Qulay narxlar
  - Imtihonga tayyorgarlik
- ✅ Icon + title + description
- ✅ Hover animatsiyalar

#### 1.4 Courses (Kurslar)
- ✅ Kurs kartochkalari:
  - B toifa - yengil avtomobillar
  - Intensiv kurs
  - VIP individual kurs
  - Qayta tayyorlov kursi
- ✅ Narx, muddat, darslar soni
- ✅ "Batafsil" tugmalari
- ✅ Badge (Mashhur, Yangi)

#### 1.5 Contact (Aloqa)
- ✅ Contact forma:
  - Ism (required)
  - Telefon (required)
  - Kurs turi (select)
  - Xabar (textarea, optional)
  - "Yuborish" tugmasi (animatsiya bilan)
- ✅ Send icon animation (1000px translateX/Y)
- ✅ Success message (3 soniya)
- ✅ Aloqa ma'lumotlari:
  - Telefon: +998 90 123 45 67, +998 91 234 56 78
  - Email: info@avtolider.uz
  - Manzil: Toshkent sh., Yunusobod t.
  - Ish vaqti: Du-Sh: 8:00-20:00, Yak: 9:00-16:00
- ✅ Yandex Map (3ta filial belgilari)

#### 1.6 Footer
- ✅ Logo va tavsif
- ✅ Social media icons (Facebook, Instagram, Telegram, YouTube)
  - Light modeda qizil, dark modeda oq
  - Hover effects
- ✅ 4ta ustun:
  - Tezkor havolalar
  - Kurslar
  - Aloqa
- ✅ Bottom bar:
  - Copyright © 2024
  - "Maxfiylik siyosati" tugmasi
  - "Foydalanish shartlari" tugmasi

---

### 2. AUTENTIFIKATSIYA TIZIMI

#### 2.1 AuthModal
- ✅ Login/Register tabs
- ✅ Formalar:
  - **Login:** Email/Telefon, Parol
  - **Register:** Ism, Telefon, Email, Parol, Parolni tasdiqlash
- ✅ Validation
- ✅ Modal backdrop blur
- ✅ Close button
- ✅ Smooth animations

---

### 3. USER DASHBOARD (Shaxsiy Kabinet)

#### 3.1 Sidebar Navigation
- ✅ 6ta bo'lim:
  - 📚 Mavzular
  - ✍️ Imtihonlar
  - 🎥 Video Darsliklar (default active)
  - 📊 Natijalar
  - 💳 Obuna
  - 👤 Profil
- ✅ Active state indication
- ✅ Icon + label
- ✅ "Chiqish" tugmasi

#### 3.2 Mavzular (Topics)
- ✅ Topic kartochkalari:
  - Nomi, tavsif
  - Progress bar
  - Status badge (Boshlandi, Tugallanmagan, Tugallandi)
- ✅ "Davom etish" tugmalari

#### 3.3 Imtihonlar (Exams)
- ✅ Test tizimi:
  - 20ta random test savollari
  - Multiple choice (A, B, C, D)
  - A va D javoblar qizil, B va C javoblar ko'k
  - Test rasmlari (traffic signs, road situations)
  - Progress indicator (1/20, 2/20...)
  - Timer (30 daqiqa)
  - "Keyingi savol" tugmasi
- ✅ Natijalar ekrani:
  - To'g'ri javoblar soni / 20
  - O'tish/O'tmaslik (15+ to'g'ri = O'tdi)
  - "Qayta topshirish" tugmasi
  - "Natijalarni ko'rish" tugmasi

#### 3.4 Video Darsliklar
- ✅ Video kartochkalari:
  - Thumbnail
  - Sarlavha, tavsif
  - Davomiylik vaqti (ko'k rangda)
  - Play button
  - Muddat
  - Progress (badges)
- ✅ Video tavsiyalar (Recommended):
  - 3ta qo'shimcha video
  - Thumbnail preview
  - Qisqacha tavsif

#### 3.5 Natijalar (Results)
- ✅ Statistika kartochkalari:
  - Jami testlar: 12
  - O'rtacha ball: 78%
  - Eng yaxshi natija: 95%
  - Bu hafta: 4 ta test
- ✅ **Rivojlanish grafigi** (Line Chart):
  - 12ta test natijalari
  - Recharts kutubxonasi
  - Qizil (#8b2e2e) rangda chiziq
  - Interactive tooltip
  - Responsive dizayn
- ✅ **So'nggi testlar** ro'yxati:
  - 5ta oxirgi test natijalari
  - Test nomi, sana, ball
  - Topic badge
  - Status ranglar (yashil 85%+, sariq 70-84%, qizil <70%)
  - Hover effects
- ✅ **Mavzular bo'yicha natijalar**:
  - 5ta asosiy mavzu
  - Progress bar har bir mavzu uchun
  - O'rtacha ball ko'rsatkichi
  - Bar Chart visualization
  - Ranglar: yashil, ko'k, sariq, binafsha, to'q sariq
  - Test soni va ball foizi

#### 3.6 Obuna (Subscription)
- ✅ 3ta obuna rejasi:
  - **1 Haftalik:** 25,000 so'm
  - **2 Haftalik:** 40,000 so'm (Mashhur badge)
  - **3 Haftalik:** 60,000 so'm (Premium badge)
- ✅ Har bir reja uchun xususiyatlar ro'yxati
- ✅ To'lov usullari:
  - Karta orqali to'lov (Uzcard, Humo)
  - Payme orqali to'lov
- ✅ To'lov usulini tanlash tizimi
- ✅ Active subscription indication
- ✅ Gradient backgrounds

#### 3.7 Profil (Profile)
- ✅ Foydalanuvchi ma'lumotlari:
  - Avatar (circle)
  - Ism, telefon, email
- ✅ Edit tugmasi
- ✅ Qo'shimcha ma'lumotlar:
  - Ro'yxatdan o'tgan sana
  - Aktiv obuna turi
  - Tugallanish muddati

---

### 4. MAXFIYLIK VA SHARTLAR

#### 4.1 Maxfiylik Siyosati (PrivacyPolicy)
- ✅ 10ta bo'lim:
  1. Umumiy ma'lumot
  2. To'planadigan ma'lumotlar
  3. Ma'lumotlardan foydalanish
  4. Ma'lumotlarni himoya qilish
  5. Ma'lumotlarni uchinchi shaxslarga berish
  6. Sizning huquqlaringiz
  7. Cookies va tracking
  8. Bolalar maxfiyligi
  9. Siyosatdagi o'zgarishlar
  10. Biz bilan bog'lanish
- ✅ "Orqaga" tugmasi
- ✅ Card layout
- ✅ Bullet points
- ✅ Contact info box

#### 4.2 Foydalanish Shartlari (TermsOfService)
- ✅ 12ta bo'lim:
  1. Umumiy qoidalar
  2. Xizmatlar tavsifi
  3. Ro'yxatdan o'tish va hisob
  4. To'lovlar va qaytarish
  5. O'quvchi majburiyatlari
  6. Avtomaktab huquqlari
  7. Mas'uliyat cheklovi
  8. Intellektual mulk
  9. Darslar jadvali va bekor qilish
  10. Nizolarni hal qilish
  11. Shartlardagi o'zgarishlar
  12. Bog'lanish ma'lumotlari
- ✅ "Orqaga" tugmasi
- ✅ Subsections (4.1, 4.2...)
- ✅ Warning box (Eslatma)
- ✅ Professional formatting

---

## 🎭 ANIMATSIYALAR VA EFFEKTLAR

### Animatsiya Ro'yxati
1. ✅ **Counter animations** - Statistikada raqamlar oshishi
2. ✅ **Hover scale** - Kartochkalar kattalashtirish (1.05x)
3. ✅ **Send button animation** - 1000px translateX va translateY
4. ✅ **Smooth scroll** - Section navigationda
5. ✅ **Fade in up** - Hero sectionda kartochkalar
6. ✅ **Border hover** - Kartochka borderlari rangi o'zgarishi
7. ✅ **Icon hover translate** - Arrow iconlar siljishi
8. ✅ **Progress bar animation** - Fill animatsiyasi
9. ✅ **Modal slide** - Modal ochilish/yopilish
10. ✅ **Theme transition** - Dark/light mode smooth o'tish

### Transition Tezliklari
- Default: `transition-all` (0.3s)
- Slow animations: `duration-1000` (1s)
- Button hover: `transition-colors`

---

## 🌐 RESPONSIVE DIZAYN

### Breakpoints
- **Mobile:** < 768px
- **Tablet:** 768px - 1024px
- **Desktop:** > 1024px

### Mobile Optimizatsiyalar
- ✅ Hamburger menu (Header)
- ✅ Stacked layouts (grid → stack)
- ✅ Smaller font sizes
- ✅ Touch-friendly buttons (min 44px)
- ✅ Simplified navigation
- ✅ Collapsible sidebar (Dashboard)
- ✅ **Subscription Modal** - 3 kolonli grid mobile uchun 1 kolonga
- ✅ **Dashboard Tabs** - Horizontal scroll, icon-only mobileda
- ✅ **Statistics Cards** - 4 kolondan 2x2 grid
- ✅ **Charts** - Kichik font, qisqa labels
- ✅ **Forms** - Vertical stack, kichikroq inputs
- ✅ **Tables** - Responsive layout, wrap content
- ✅ **Spacing** - Padding/margin mobile uchun kamaytirilgan
- ✅ **Typography** - Responsive font sizes (sm:text-base)
- ✅ **Scrollbar** - Hide on horizontal scrolling elements

### Grid Systems
- Landing: `grid md:grid-cols-2 lg:grid-cols-3`
- Footer: `grid md:grid-cols-2 lg:grid-cols-4`
- Cards: `grid-cols-1 md:grid-cols-2 lg:grid-cols-3`

---

## 🎨 THEME SYSTEM

### CSS Tokens (theme.css)
```css
/* Dark Mode (default) */
--background: #0a0a0a
--foreground: #ffffff
--primary: #8b2e2e
--card: #1a1a1a
--border: rgba(255,255,255,0.1)
--muted-foreground: rgba(255,255,255,0.7)

/* Light Mode */
--background: #ffffff
--foreground: #0a0a0a
--primary: #8b2e2e
--card: #f5f5f5
--border: rgba(0,0,0,0.1)
--muted-foreground: rgba(0,0,0,0.6)
```

### Theme Toggle
- ✅ Sun/Moon icon
- ✅ localStorage persistence
- ✅ System preference detection
- ✅ Smooth transition

---

## 🔐 MA'LUMOTLAR VA XAVFSIZLIK

### Shaxsiy Ma'lumotlar
- Ism, familiya
- Telefon raqam
- Email manzil
- Parol (hashed)
- Tug'ilgan sana
- Pasport ma'lumotlari

### Xavfsizlik Choralari
- Input validation
- XSS protection
- CSRF protection
- Secure password hashing
- HTTPS only
- Privacy policy compliance

---

## 📊 TEST TIZIMI DETALLARI

### Test Savollari
- ✅ 20ta random savol har safar
- ✅ Multiple choice (A, B, C, D)
- ✅ Tasvirlar (yo'l belgilari, vaziyatlar)
- ✅ O'zbek tilida

### Test Logikasi
- Timer: 30 daqiqa
- Minimal o'tish ball: 15/20 (75%)
- Progress tracking
- Answer selection
- Result calculation

### Test Rasmlari
1. Yo'l belgilari (to'xtash, ta'qiqlash)
2. Yo'l vaziyatlari (kesishmalar)
3. Xavfsizlik qoidalari
4. Parking holatlari
5. Svetofor signallari

---

## 💳 OBUNA REJALARI

### 1 Haftalik (25,000 so'm)
- Barcha mavzularga kirish
- Cheksiz testlar
- Video darsliklar
- Imtihon tayyorgarligi

### 2 Haftalik (40,000 so'm) - MASHHUR
- Barcha 1 Haftalik xususiyatlar
- Natijalar tahlili
- Email qo'llab-quvvatlash
- 10,000 so'm tejash

### 3 Haftalik (60,000 so'm) - PREMIUM
- Barcha 2 Haftalik xususiyatlar
- Shaxsiy mentor
- 24/7 yordam
- 15,000 so'm tejash

---

## 💰 TO'LOV TIZIMI

### To'lov Usullari
1. **Karta orqali to'lov**
   - Uzcard qo'llab-quvvatlash
   - Humo qo'llab-quvvatlash
   - Karta raqami (16 raqam)
   - Amal qilish muddati (MM/YY)
   - CVV kod (3 raqam)
   - Karta egasining ismi

2. **Payme orqali to'lov**
   - Telefon raqam orqali
   - Payme ilovasida ro'yxatdan o'tgan raqam
   - SMS kod tasdiqlanishi
   - Mobil to'lov

### To'lov Jarayoni
1. Obuna rejasini tanlash (1, 2 yoki 3 haftalik)
2. To'lov usulini tanlash (Karta yoki Payme)
3. Ma'lumotlarni kiritish
4. To'lov summasi ko'rsatiladi
5. To'lovni tasdiqlash
6. Premium obuna aktivatsiyasi

### Xavfsizlik
- SSL sertifikati
- PCI DSS compliance
- Karta ma'lumotlari himoyalangan
- Secure payment gateway

---

## 🔄 ROUTING VA NAVIGATION

### Page States
1. **home** - Landing page
2. **privacy** - Maxfiylik siyosati
3. **terms** - Foydalanish shartlari
4. **dashboard** - User logged in state

### Navigation Flow
```
Landing → AuthModal → Dashboard
Landing → Footer Links → Privacy/Terms
Dashboard → Logout → Landing
```

---

## 📱 ALOQA MA'LUMOTLARI

- **Telefon:** +998 90 123 45 67, +998 91 234 56 78
- **Email:** info@avtolider.uz, support@avtolider.uz
- **Manzil:** Toshkent shahar, Yunusobod tumani, Amir Temur ko'chasi 123
- **Ish vaqti:** Dushanba-Shanba: 8:00-20:00, Yakshanba: 9:00-16:00

---

## 🚀 KEYINGI BOSQICHLAR (Future Updates)

### V1.1 - Rejadagi Funksiyalar
- [ ] Real Supabase backend integratsiya
- [ ] Real video player integration
- [ ] Real-time chat qo'llab-quvvatlash
- [ ] SMS notification tizimi
- [ ] Online to'lov integratsiyasi (Click, Payme)
- [ ] Calendar booking system
- [ ] Instructor profile sahifalari
- [ ] Student review/rating tizimi
- [ ] Blog/News section
- [ ] FAQ page
- [ ] Certificate generator
- [ ] Email notification system

### V2.0 - Kengaytmalar
- [ ] Mobile app (React Native)
- [ ] Admin panel
- [ ] Instructor dashboard
- [ ] Live streaming darslar
- [ ] Gamification (badges, achievements)
- [ ] Referral program
- [ ] Multi-language support (Rus, Eng)
- [ ] Advanced analytics
- [ ] AI chatbot
- [ ] Voice navigation

---

## ✅ JORIY HOLAT (Current Status)

### Tugallangan
- ✅ Landing page (Hero, About, Courses, Contact)
- ✅ Header va Footer
- ✅ Authentication Modal
- ✅ User Dashboard (barcha 6 bo'lim)
- ✅ Test System (20 savol, timer, results)
- ✅ Subscription Plans (yangilangan narxlar)
- ✅ **Rivojlanish grafigi** (Recharts - Line Chart)
- ✅ **So'nggi testlar ro'yxati** (5ta oxirgi test)
- ✅ **Mavzular bo'yicha natijalar** (Progress bars + Bar Chart)
- ✅ **To'lov tizimi** (Karta va Payme)
- ✅ Dark/Light mode toggle
- ✅ Privacy Policy page
- ✅ Terms of Service page
- ✅ Responsive dizayn
- ✅ Barcha animatsiyalar
- ✅ Smooth scroll navigation

### Oxirgi Qo'shilgan Funksiyalar (2026-yil, Yanvar 6)
1. ✅ Obuna narxlari yangilandi:
   - 1 haftalik: 25,000 so'm
   - 2 haftalik: 40,000 so'm
   - 3 haftalik: 60,000 so'm
2. ✅ Rivojlanish grafigi (Line Chart) qo'shildi
3. ✅ So'nggi 5ta test natijalari ro'yxati
4. ✅ Mavzular bo'yicha natijalar (Progress + Bar Chart)
5. ✅ To'lov tizimi:
   - Karta orqali to'lov
   - Payme orqali to'lov
   - To'lov usulini tanlash
6. ✅ **Multi-language Support (3 til)**:
   - O'zbek tili (Lotin) - Default
   - Русский язык
   - Ўзбекча (Кирилл)
   - Language Selector komponenti
   - Context API orqali tarjimalar
   - LocalStorage da til saqlash
7. ✅ **Mobile Optimizatsiya**:
   - Responsive dizayn barcha komponentlarda
   - Touch-friendly UI elementlar
   - Horizontal scroll navigation
   - Optimallashtirilgan chart sizlar

### Yangi Funksiyalar (2026-yil, Yanvar 8)
8. ✅ **Contact Forma - Label Tuzatildi**:
   - Textarea label dark/light modeda ko'rinadi
   - text-foreground class qo'shildi

9. ✅ **Kurs Batafsil Sahifasi**:
   - CourseDetailPage komponenti yaratildi
   - To'liq kurs ma'lumotlari
   - Instruktorlar haqida ma'lumot
   - Narxlar va obuna tizimi
   - "KURSGA YOZILISH" tugmasidan ochiladi

10. ✅ **SMS Kod Verification**:
    - 3 bosqichli ro'yxatdan o'tish tizimi
    - Telefon raqam → SMS kod → Ma'lumotlar to'ldirish
    - LocalStorage da foydalanuvchilar saqlanadi
    - Mavjud foydalanuvchilarni avtomatik tanish
    - Telegram bot simulatsiyasi (console/alert)

11. ✅ **Dashboard Headerda Profil Rasmi**:
    - Profil rasmi yoki avatar ko'rsatiladi
    - Dinamik yangilanadi

12. ✅ **Profil Tahrirlash va Rasm Upload**:
    - ProfileSection to'liq qayta yozildi
    - Edit mode - ism va email o'zgartirish
    - Profil rasm upload (Camera tugmasi)
    - LocalStorage da saqlanish
    - Obuna ma'lumotlari ko'rsatish
    - Hisob o'chirish funksiyasi

13. ✅ **YouTube Video Darsliklar**:
    - YouTube video ID qo'llab-quvvatlash
    - Thumbnail avtomatik yuklanish
    - Video player interfeysi
    - Kategoriyalar bo'yicha filter
    - Tavsiya etilgan videolar tizimi
    - Ko'rilgan videolarni belgilash
    - Progress statistikasi

14. ✅ **Kompyuter Varianti Test Tizimi**:
    - Desktop layout optimizatsiya
    - Chap: Savol rasmi
    - O'ng: Savol matni va javoblar
    - Tepada: Savol raqami (chap), Timer (o'ng)
    - Pastda: Navigatsiya tugmalari (orqaga/keyingi)
    - Savol navigator (barcha savollar tugmalari)
    - Real-time timer
    - Natijalar sahifasi
    - Qayta topshirish imkoniyati

### Hozirgi Texnik Stack
- React 18
- TypeScript
- Tailwind CSS v4
- Recharts 2.15.2 (Chart library)
- Lucide React Icons
- Vite build tool

---

## 📝 QOIDALAR VA STANDARTLAR

### Code Style
- TypeScript strict mode
- Functional components
- React Hooks
- Props typing
- Interface definitions
- Component composition

### Naming Conventions
- Components: PascalCase (UserDashboard.tsx)
- Functions: camelCase (handleSubmit)
- CSS classes: kebab-case (bg-primary)
- Files: PascalCase.tsx

### File Organization
- One component per file
- Grouped by feature
- Shared components in /components
- Styles in /styles

---

## 🎯 SUCCESS METRICS

### Performance
- Tez yuklash vaqti (< 3s)
- Smooth 60fps animatsiyalar
- Mobile responsive
- SEO optimized

### User Experience
- Intuitiv navigation
- Clear CTAs
- Professional dizayn
- Accessible (ARIA labels)

### Business Goals
- Ko'p ro'yxatdan o'tishlar
- Yuqori conversion rate
- User engagement
- Customer satisfaction

---

## 📞 SUPPORT

Texnik savol va takliflar uchun:
- **Developer Email:** dev@avtolider.uz
- **Support:** support@avtolider.uz

---

**Hujjat versiyasi:** 1.0  
**Oxirgi yangilanish:** 2024-yil  
**Muallif:** Avtolider Development Team  
**Status:** ✅ Production Ready

---

## 🏁 XULOSA

Ushbu texnik topshiriq Avtolider avtomaktabi uchun yaratilgan to'liq funksional veb-platformaning barcha asosiy xususiyatlarini, texnik detaillarini va dizayn elementlarini o'z ichiga oladi. Loyiha zamonaviy texnologiyalar va best practice'lar asosida qurilgan bo'lib, kelajakda kengaytirish va yangilash uchun qulay arxitekturaga ega.