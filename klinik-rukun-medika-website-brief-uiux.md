# Klinik RUKUN Medika Sentul — Website Brief & UI/UX Notes

> Source: **Brief and Copy Webpage KLINIK RUKUN — 16 Sep 2026**
>
> This document converts the supplied PDF into Markdown and adds implementation-oriented UI/UX notes. Content from the PDF is preserved; UI/UX notes are recommendations.

---

## 1. SEO Setup

### SEO Title
**Klinik RUKUN Medika Sentul | Dokter Umum, Gigi & Fisioterapi**

### Meta Description
Klinik RUKUN Medika di Sentul menyediakan dokter umum, dokter gigi, IGD, vaksinasi, infus, fisioterapi dan farmasi. Senin–Sabtu 08.00–20.00.

### Suggested URL
`/klinik-rukun-medika-sentul`

### Primary Keywords
- Klinik Sentul
- Klinik di Sentul
- Klinik Babakan Madang
- Klinik RUKUN Medika

### Supporting Keywords
- dokter umum Sentul
- dokter gigi Sentul
- klinik gigi Sentul
- fisioterapi Sentul
- vaksinasi Sentul
- klinik keluarga Sentul
- klinik Bogor
- klinik dekat Babakan Madang

---

# 2. One-Page Website Structure

## Navbar

**Beranda | Layanan | Dokter | Tentang Kami | FAQ | Lokasi**

### UI/UX Notes
- Use a **sticky navbar** on desktop and mobile.
- Add a clearly visible **primary CTA: “Reservasi Sekarang”**.
- On mobile, use a hamburger menu but keep WhatsApp/reservation easily accessible.
- Highlight the currently active section while scrolling.
- Keep navigation labels short and familiar.
- Consider a floating WhatsApp button on mobile.

---

# 3. Hero Section

## Content

### Klinik RUKUN Medika Sentul

**Layanan Kesehatan untuk Anda dan Keluarga**

Klinik RUKUN Medika menyediakan layanan kesehatan yang nyaman dan mudah diakses bagi masyarakat Sentul, Babakan Madang, dan sekitarnya.

Mulai dari dokter umum, dokter gigi, tindakan medis, IGD, vaksinasi, infus, fisioterapi hingga layanan farmasi, kami hadir untuk membantu kebutuhan kesehatan Anda dan keluarga dalam satu lokasi.

**Jam operasional:** Senin–Sabtu | 08.00–20.00

**CTA:** Reservasi Sekarang

**WhatsApp:** 0813-1088-2505

### UI/UX Notes
- The hero should answer three questions immediately:
  1. **What is this?** → Klinik RUKUN Medika.
  2. **Where is it?** → Sentul/Babakan Madang.
  3. **What can I do here?** → Book/ask via WhatsApp.
- Make **Reservasi Sekarang** the dominant CTA.
- Add a secondary CTA such as **Lihat Layanan** that scrolls to the services section.
- Show operating hours close to the CTA.
- Consider a trust indicator near the hero, e.g. **“Akreditasi Paripurna”**, because this is explicitly stated in the source.
- Recommended visual: authentic clinic/facility photography rather than generic medical stock imagery.
- Avoid overcrowding the hero with every service. Services can be summarized using small icons/cards below.

---

# 4. About / Clinic Introduction

## Klinik Keluarga di Sentul dengan Pelayanan yang Nyaman

Berada di kawasan Darmawan Park, Sentul, Klinik RUKUN Medika melayani masyarakat umum dan keluarga dengan pendekatan pelayanan yang ramah, personal, dan efisien.

Klinik kami didukung oleh dokter berpengalaman serta fasilitas yang dirancang agar pasien dapat menjalani pemeriksaan dan perawatan dengan lebih nyaman.

Klinik RUKUN Medika juga mendukung kebutuhan kesehatan penghuni kawasan RUKUN Senior Living, sehingga fasilitas klinik memiliki akses yang ramah bagi senior dan pengguna kursi roda.

**Klinik RUKUN Medika telah memperoleh Akreditasi Paripurna.**

### UI/UX Notes
- Use a **split layout**:
  - left: clinic/facility image
  - right: concise introduction
- Put **Akreditasi Paripurna** into a visually distinct trust badge.
- Use accessibility-related content as a separate small highlight:
  - Senior-friendly
  - Wheelchair-friendly
- Do not make this section text-heavy; use short paragraphs and visual hierarchy.

---

# 5. Services

## Layanan Klinik RUKUN Medika

Recommended UI pattern: **service cards** with icon + short description + optional CTA.

---

## 5.1 Dokter Umum

Konsultasikan berbagai keluhan kesehatan Anda bersama dokter umum Klinik RUKUN Medika.

### Layanan
- Konsultasi dan pemeriksaan kesehatan
- Pemeriksaan tekanan darah
- Pemeriksaan gula darah
- Pemeriksaan kondisi kesehatan umum
- Penanganan keluhan demam, batuk, flu dan gangguan kesehatan umum
- Perawatan luka
- Suntik
- Nebulizer
- Infus
- Medical check-up
- Surat keterangan sehat
- Pemantauan kesehatan senior

**CTA:** Buat Janji Dokter Umum

### UI/UX Notes
- Do not display all bullets by default if the card becomes too long.
- Show 3–5 key services first, then use **“Lihat semua layanan”**.
- Use a doctor/medical consultation icon.
- CTA should go directly to WhatsApp with a pre-filled message if technically possible.

---

## 5.2 Poli Gigi

### Perawatan Gigi untuk Seluruh Keluarga

Jaga kesehatan gigi dan mulut melalui pemeriksaan dan perawatan bersama dokter gigi Klinik RUKUN Medika di Sentul.

### Layanan
- Pemeriksaan gigi rutin
- Pembersihan karang gigi
- Penambalan gigi
- Pencabutan gigi
- Pembuatan gigi tiruan
- Konsultasi kesehatan gigi dan mulut

Pemeriksaan berkala membantu menemukan masalah gigi sejak dini sebelum berkembang menjadi kondisi yang lebih kompleks.

**CTA:** Reservasi Dokter Gigi

### UI/UX Notes
- Use a dedicated dental visual rather than the same image used for general practice.
- Make **Reservasi Dokter Gigi** a clear CTA.
- Consider displaying popular services as small chips:
  - Scaling
  - Tambal gigi
  - Cabut gigi
  - Gigi tiruan

---

## 5.3 IGD & Tindakan Medis

Klinik RUKUN Medika menyediakan layanan IGD dan tindakan medis selama jam operasional klinik untuk membantu menangani kondisi yang membutuhkan pemeriksaan dan penanganan segera.

### Layanan dapat mencakup
- Penanganan awal kondisi medis
- Perawatan luka
- Infus
- Suntik
- Nebulizer
- Pemeriksaan tanda-tanda vital
- Observasi kondisi pasien
- Tindakan medis sesuai indikasi dokter

> Untuk kondisi kegawatdaruratan berat yang membutuhkan fasilitas rumah sakit, pasien dapat diarahkan ke fasilitas kesehatan yang sesuai.

### UI/UX Notes
- This section should be visually distinct because users may visit it under time pressure.
- Clearly display **operating hours** nearby.
- Avoid using design patterns that imply 24/7 emergency service, because the source states the service is available during clinic operating hours.
- Add a prominent **WhatsApp / Call** action.
- Consider an informational warning box explaining that severe emergencies may require referral to a hospital.
- Do not use overly alarming animations.

---

## 5.4 Vaksinasi

### Perlindungan Kesehatan untuk Anda dan Keluarga

Klinik RUKUN Medika menyediakan layanan vaksinasi bagi masyarakat sesuai kebutuhan dan ketersediaan vaksin.

Konsultasikan terlebih dahulu dengan tim kami untuk mengetahui jenis vaksin, jadwal, dan ketersediaannya.

**CTA:** Tanyakan Ketersediaan Vaksin

### UI/UX Notes
- Do not create a static vaccine catalog unless current availability is maintained.
- Emphasize **“cek ketersediaan”** rather than implying every vaccine is always available.
- Use WhatsApp as the primary conversion path.

---

## 5.5 Fisioterapi

### Membantu Memulihkan Gerak dan Aktivitas

Layanan fisioterapi Klinik RUKUN Medika membantu pasien menjaga dan meningkatkan fungsi gerak, mobilitas, serta kemampuan menjalankan aktivitas sehari-hari.

### Fisioterapi dapat mendukung kondisi seperti
- Pemulihan setelah cedera
- Nyeri otot dan sendi
- Gangguan mobilitas
- Pemulihan pasca operasi
- Pemulihan pasca stroke
- Penurunan kekuatan dan keseimbangan
- Kebutuhan latihan gerak pada senior

Program fisioterapi disesuaikan dengan kondisi dan kebutuhan setiap pasien.

**CTA:** Konsultasi Fisioterapi

### UI/UX Notes
- Use imagery showing movement/rehabilitation rather than generic hospital imagery.
- Highlight **individualized treatment** as the main supporting message.
- A simple “Kondisi yang dapat dibantu” icon grid can improve scanability.

---

## 5.6 Farmasi

### Obat dan Kebutuhan Kesehatan Lebih Mudah Diakses

Layanan farmasi Klinik RUKUN Medika tersedia tidak hanya bagi pasien klinik, tetapi juga untuk masyarakat umum.

Kami menyediakan pilihan obat dan kebutuhan kesehatan dasar. Karena ragam obat yang tersedia masih terbatas, silakan menghubungi kami terlebih dahulu apabila Anda mencari obat tertentu.

**CTA:** Cek Ketersediaan Obat

### UI/UX Notes
- Make the limitation explicit rather than presenting the pharmacy as a complete pharmacy catalog.
- CTA should open WhatsApp with a pre-filled request such as:
  **“Halo Klinik RUKUN Medika, saya ingin menanyakan ketersediaan obat …”**
- Avoid showing outdated stock information.
- Consider a simple “Pasien klinik / Masyarakat umum” explanation.

---

# 6. Doctor Schedule

## Jadwal Dokter Klinik RUKUN Medika

| Doctor | Specialty | Schedule |
|---|---|---|
| dr. Susy Theresia, MMRs. | Dokter Umum | Senin–Sabtu, 08.00–14.00 |
| dr. Sumina Saleh | Dokter Umum | Senin–Sabtu, 14.00–20.00 |
| drg. Sinka Puji Yuninda, M.T.Kes | Dokter Gigi | Senin–Rabu, 08.00–14.00 |
| drg. Anggita Prawesti W | Dokter Gigi | Kamis–Jumat, 14.00–20.00 |

> Jadwal dokter dapat berubah. Disarankan melakukan konfirmasi sebelum berkunjung.

**CTA:** Konfirmasi Jadwal & Reservasi

### UI/UX Notes
- Use **doctor cards** on desktop and a horizontally scrollable/card stack layout on mobile.
- Include doctor photos if available.
- Make specialty and schedule visually scannable.
- Do not rely on color alone to distinguish doctors.
- Put the schedule-change disclaimer directly below the schedule.
- CTA should be repeated here because this is a high-intent section.
- If the schedule will be updated frequently, consider managing it through CMS rather than hard-coding it.

---

# 7. Family & Senior Care

## Mendukung Kesehatan Keluarga dan Senior

Klinik RUKUN Medika melayani masyarakat umum dari berbagai kelompok usia, mulai dari anak dewasa, keluarga hingga senior.

Lokasinya yang berada di kawasan Darmawan Park juga memungkinkan klinik mendukung kebutuhan kesehatan komunitas RUKUN Senior Living.

Pengalaman tersebut membantu kami memahami bahwa setiap pasien memiliki kebutuhan yang berbeda, termasuk pasien senior yang mungkin membutuhkan waktu pemeriksaan lebih nyaman, akses kursi roda, serta pendampingan keluarga.

### UI/UX Notes
This can work well as a **human-centered storytelling section**.

Recommended visual structure:

```text
[Large authentic photo]
        |
        +-- Anak & Keluarga
        +-- Dewasa
        +-- Senior
        +-- Akses Kursi Roda
```

Keep the copy concise and let photography communicate warmth.

---

# 8. Why Choose Klinik RUKUN Medika

## Pelayanan Kesehatan yang Lebih Nyaman di Sentul

### 1. Dokter Berpengalaman
Pemeriksaan dan perawatan dilakukan oleh tenaga medis profesional sesuai kebutuhan pasien.

### 2. Antrean Lebih Singkat
Kami berupaya memberikan proses pelayanan yang efisien agar waktu tunggu pasien lebih nyaman.

### 3. Pelayanan Ramah
Tim kami mengutamakan komunikasi yang baik dan pelayanan personal kepada pasien dan keluarga.

### 4. Fasilitas Nyaman
Lingkungan klinik dirancang agar kunjungan kesehatan terasa lebih nyaman.

### 5. Akses Ramah Kursi Roda
Mendukung pasien dengan keterbatasan mobilitas serta pasien senior.

### 6. Area Parkir Tersedia
Memberikan kemudahan bagi pasien dan keluarga yang datang menggunakan kendaraan.

### 7. Beragam Layanan dalam Satu Lokasi
Dokter umum, dokter gigi, tindakan medis, IGD, fisioterapi, vaksinasi dan farmasi tersedia dalam satu fasilitas.

### UI/UX Notes
- Use a **7-item icon grid**.
- Keep each item to one short sentence.
- Prioritize concrete benefits over generic marketing statements.
- Avoid making every benefit look like a CTA.
- On mobile: 1 column or 2-column compact grid.

---

# 9. Location

## Lokasi Klinik RUKUN Medika

### Klinik di Sentul, Babakan Madang

**Klinik RUKUN Medika**  
Kawasan Darmawan Park  
Jl. Babakan Madang No. 99  
Sentul Selatan, Bogor 16810

### Jam Operasional
**Senin–Sabtu**  
**08.00–20.00**

### WhatsApp & Reservasi
**0813-1088-2505**

### Instagram
**@klinik_rukunmedika**

**CTA:** Buka Google Maps

### UI/UX Notes
Recommended layout:

```text
+---------------------------------------------+
|                  Google Map                 |
|                                             |
+----------------------+----------------------+
| Address              | Operating Hours      |
| WhatsApp             | Instagram            |
| [Maps]               | [WhatsApp]           |
+----------------------+----------------------+
```

- Use an embedded Google Maps map.
- Add **“Buka Google Maps”** for navigation.
- Make address copyable.
- Make WhatsApp number clickable.
- On mobile, prioritize:
  1. WhatsApp
  2. Directions
  3. Address
  4. Operating hours
- If parking availability is useful to visitors, surface “Area Parkir Tersedia” here as well.

---

# 10. FAQ

## FAQ Klinik RUKUN Medika

### Apakah Klinik RUKUN Medika menerima pasien umum?
Ya. Klinik RUKUN Medika terbuka untuk masyarakat umum dan keluarga di Sentul, Babakan Madang, Bogor dan sekitarnya.

### Apakah Klinik RUKUN Medika menerima BPJS?
Saat ini Klinik RUKUN Medika belum melayani pasien BPJS Kesehatan.

### Apakah tersedia dokter umum setiap hari?
Dokter umum tersedia Senin sampai Sabtu pukul 08.00–20.00, terbagi dalam dua jadwal dokter.

### Apakah tersedia dokter gigi di Klinik RUKUN Medika?
Ya. Poli gigi menyediakan pemeriksaan gigi, pembersihan karang gigi, penambalan, pencabutan, pembuatan gigi tiruan dan layanan kesehatan gigi lainnya.

### Apakah bisa melakukan fisioterapi di Klinik RUKUN Medika?
Ya. Klinik RUKUN Medika menyediakan layanan fisioterapi untuk membantu pemulihan fungsi gerak, mobilitas dan berbagai kondisi yang membutuhkan rehabilitasi fisik.

### Apakah tersedia vaksinasi?
Ya. Layanan vaksinasi tersedia sesuai kebutuhan dan stok vaksin. Hubungi klinik untuk menanyakan jenis vaksin yang tersedia.

### Apakah farmasi Klinik RUKUN Medika bisa digunakan masyarakat umum?
Ya. Farmasi terbuka untuk masyarakat umum. Namun, karena pilihan obat masih terbatas, sebaiknya konfirmasi ketersediaan obat terlebih dahulu melalui WhatsApp.

### Apakah klinik ramah untuk lansia dan pengguna kursi roda?
Ya. Klinik memiliki akses kursi roda dan juga mendukung kebutuhan kesehatan penghuni kawasan RUKUN Senior Living.

### UI/UX Notes
- Use an accordion.
- Keep only one answer expanded by default, or all collapsed.
- Put the most practical questions first:
  - pasien umum
  - BPJS
  - jam dokter
  - layanan
  - vaksin
  - farmasi
  - akses lansia/kursi roda
- Add FAQ structured data if appropriate for SEO implementation.
- Make WhatsApp CTA available after the FAQ.

---

# 11. Recommended Final Page Flow

The PDF gives the content structure, but for UX the page can be reorganized into this conversion-oriented flow:

```text
1. Sticky Navbar
   ├── Beranda
   ├── Layanan
   ├── Dokter
   ├── Tentang Kami
   ├── FAQ
   └── Lokasi
       └── [Reservasi Sekarang]

2. Hero
   ├── Main value proposition
   ├── Location
   ├── Operating hours
   ├── Reservasi CTA
   └── WhatsApp CTA

3. Trust / Quick Facts
   ├── Akreditasi Paripurna
   ├── Senin–Sabtu
   ├── 08.00–20.00
   ├── Senior-friendly
   └── Wheelchair access

4. Services
   ├── Dokter Umum
   ├── Poli Gigi
   ├── IGD & Tindakan
   ├── Vaksinasi
   ├── Fisioterapi
   └── Farmasi

5. About / Family & Senior Care

6. Why Choose Us

7. Doctor Schedule

8. FAQ

9. Location + Google Maps

10. Final CTA
    ├── Reservasi via WhatsApp
    └── Buka Google Maps

11. Footer
```

---

# 12. Conversion / CTA Strategy

The main conversion appears to be **contacting the clinic / making an appointment through WhatsApp**.

Recommended CTA hierarchy:

### Primary CTA
**Reservasi Sekarang**

### Contextual CTAs
- Buat Janji Dokter Umum
- Reservasi Dokter Gigi
- Konsultasi Fisioterapi
- Tanyakan Ketersediaan Vaksin
- Cek Ketersediaan Obat
- Konfirmasi Jadwal & Reservasi

### Navigation CTA
**Buka Google Maps**

### UI/UX recommendation
Use the same visual treatment for the primary conversion action throughout the website. Contextual CTAs can remain secondary.

---

# 13. Mobile UX

Because patients may access the site from mobile, prioritize mobile-first behavior.

### Recommended mobile actions

```text
┌──────────────────────────────┐
│ Logo             ☰           │
├──────────────────────────────┤
│                              │
│ Klinik RUKUN Medika          │
│ Sentul                       │
│                              │
│ Layanan Kesehatan...         │
│                              │
│ [Reservasi Sekarang]         │
│ [Lihat Layanan]              │
│                              │
├──────────────────────────────┤
│ 🕐 Senin–Sabtu 08–20         │
│ 📍 Sentul, Bogor             │
│ ✓ Akreditasi Paripurna       │
├──────────────────────────────┤
│ Layanan                      │
│ [Card] [Card]                │
│ [Card] [Card]                │
└──────────────────────────────┘
                         [WA]
```

### Important
- Use large tap targets.
- Keep WhatsApp reachable without requiring the user to return to the top.
- Avoid huge paragraphs.
- Use accordions for detailed service lists.
- Compress images for performance.
- Ensure phone numbers are clickable with `tel:` and WhatsApp links use the appropriate `wa.me` format.

---

# 14. Accessibility

The content specifically mentions senior patients and wheelchair users, so accessibility should be treated as part of the product experience.

### Recommendations
- WCAG-conscious contrast.
- Visible keyboard focus.
- Semantic HTML.
- Proper heading hierarchy (`h1 → h2 → h3`).
- Alt text for meaningful images.
- Do not communicate information by color alone.
- Buttons should have descriptive labels.
- Minimum comfortable touch target on mobile.
- Respect reduced-motion preferences.
- Make text resizable without breaking layout.
- Ensure the map has a text-based address alternative.

---

# 15. Visual Design Direction

## Suggested design personality

**Warm + trustworthy + clean + family-oriented**

Avoid making the website feel like:
- a hospital emergency portal,
- a pharmaceutical catalog,
- an overly corporate healthcare landing page.

The content supports a positioning closer to:

> **A comfortable neighborhood/family clinic in Sentul with general medical, dental, rehabilitation, pharmacy and supporting services.**

### Visual hierarchy
1. Clinic identity
2. Primary CTA
3. Services
4. Doctor availability
5. Trust signals
6. Location
7. FAQ

### Photography
Prefer:
- Actual clinic exterior/interior
- Real doctor/team photos
- Real consultation scenes
- Physiotherapy activity
- Accessible facility features
- Pharmacy/facility photos

Avoid excessive generic stock photography.

---

# 16. Content / UX Issues to Validate Before Development

These points are present in the source and should be verified with the clinic before publishing:

- Doctor schedules can change.
- Vaccine availability depends on stock.
- Pharmacy selection is limited.
- Confirm exact scope and operating behavior of the “IGD” service.
- Confirm whether all listed medical procedures are currently available.
- Confirm the exact Google Maps location/link.
- Confirm Instagram handle.
- Confirm whether WhatsApp is used for reservation, consultation, or both.
- Confirm current BPJS status before publication.
- Confirm the “Akreditasi Paripurna” claim and whether a certificate/badge can be displayed.
- Confirm accessibility claims, especially wheelchair access.

---

# 17. Suggested Component Architecture

If implementing this as a modern React/Inertia/Tailwind website:

```text
KlinikRukunPage
│
├── Navbar
├── HeroSection
├── TrustHighlights
├── ServicesSection
│   ├── ServiceCard
│   ├── ServiceCard
│   └── ...
├── AboutSection
├── FamilySeniorSection
├── BenefitsSection
├── DoctorScheduleSection
│   └── DoctorCard
├── FAQSection
│   └── FAQAccordion
├── LocationSection
│   ├── Map
│   └── ContactInfo
├── FinalCTA
└── Footer
```

### Suggested reusable data structure

```js
const services = [
  {
    slug: 'dokter-umum',
    title: 'Dokter Umum',
    description: '...',
    items: [],
    ctaLabel: 'Buat Janji Dokter Umum',
  },
  // ...
];

const doctors = [
  {
    name: 'dr. Susy Theresia, MMRs.',
    specialty: 'Dokter Umum',
    schedule: 'Senin–Sabtu',
    time: '08.00–14.00',
    image: null,
  },
  // ...
];
```

This keeps content separate from presentation and makes a future CMS migration easier.

---

# 18. Technical SEO Checklist

- `<title>` uses the supplied SEO title.
- Meta description uses the supplied description.
- Canonical URL: `/klinik-rukun-medika-sentul`
- Use one clear `<h1>`.
- Use semantic `<h2>` for major sections.
- Add LocalBusiness/MedicalClinic structured data after validating the appropriate schema properties.
- Add Organization/clinic logo information where available.
- Add opening hours based on the verified schedule.
- Add address consistently across page metadata and visible content.
- Add `alt` text to images.
- Generate sitemap.
- Add robots.txt.
- Connect and verify Google Search Console.
- Optimize Core Web Vitals.
- Optimize image formats and dimensions.
- Add Open Graph metadata for social sharing.

---

# 19. Information Architecture Summary

| Section | Main user question | Primary action |
|---|---|---|
| Hero | “What is this clinic and where is it?” | Reservasi |
| Services | “Can they treat my need?” | Service-specific CTA |
| Doctors | “Who is available?” | Confirm schedule |
| About | “Can I trust/feel comfortable here?” | Explore |
| Benefits | “Why visit this clinic?” | Explore |
| FAQ | “What practical details do I need?” | WhatsApp |
| Location | “Where is it and how do I get there?” | Google Maps |
| Final CTA | “How do I contact them?” | WhatsApp |

---

# 20. MVP Recommendation

For the first version, focus on the patient journey rather than adding too many interactive features.

### MVP
- One-page responsive website
- Sticky navbar
- Hero + CTA
- Service cards
- Doctor schedule
- About/trust section
- FAQ accordion
- Google Maps
- WhatsApp CTA
- SEO metadata
- Basic accessibility
- Fast loading

### Later
- Online booking form
- CMS-managed doctor schedule
- CMS-managed services
- Vaccine availability
- Pharmacy stock inquiry
- Patient testimonials
- Blog/health articles
- Analytics/event tracking
- Search Console integration
- Appointment status / CRM integration

---

## Source Boundary

All clinic-specific facts, service descriptions, schedules, address, contact details, FAQ answers, and SEO copy above are based on the supplied PDF. UI/UX and implementation notes are recommendations added during this Markdown conversion.

---

# 21. Website Implementation Checklist

Use this checklist to track which requirements have been reviewed and completed. Mark an item with `[x]` after checking it in the website preview and, where applicable, in the final implementation.

## A. Project and Source Review

- [ ] Confirm the brief is the source of truth for clinic-specific content.
- [ ] Confirm all clinic facts are verified before publication.
- [ ] Confirm the final selected design version.
- [ ] Confirm the final selected content version.
- [ ] Record any content that still requires approval from the clinic.

## B. SEO and Metadata

- [ ] Page title uses: `Klinik RUKUN Medika Sentul | Dokter Umum, Gigi & Fisioterapi`.
- [ ] Meta description includes Sentul, dokter umum, dokter gigi, IGD, vaksinasi, infus, fisioterapi, farmasi, and operating hours.
- [ ] Primary keywords are used naturally in the page content.
- [ ] The page has one clear `<h1>`.
- [ ] Heading order is logical: `<h1>` → `<h2>` → `<h3>`.
- [ ] Canonical URL is configured.
- [ ] Open Graph metadata is configured.
- [ ] MedicalClinic or LocalBusiness structured data is added after validation.
- [ ] Address and opening hours are consistent in visible content and metadata.
- [ ] Sitemap and robots.txt are prepared.

## C. Navbar and Global Navigation

- [ ] Navbar contains exactly: Beranda, Layanan, Dokter, Tentang Kami, FAQ, Lokasi.
- [ ] Every navbar link points to an existing section ID.
- [ ] Navbar remains usable on desktop.
- [ ] Navbar remains usable on mobile.
- [ ] Mobile hamburger menu opens and closes correctly.
- [ ] Mobile menu closes after selecting a navigation link.
- [ ] Primary CTA is visible in the navbar.
- [ ] Primary CTA label is `Reservasi Sekarang` or an approved equivalent.
- [ ] WhatsApp/reservation remains easy to access on mobile.
- [ ] Active-section highlighting is implemented or intentionally deferred.
- [ ] Sticky/fixed navbar does not cover section headings after anchor navigation.

## D. Hero Section

- [ ] Clinic name is shown as `Klinik RUKUN Medika Sentul`.
- [ ] Main message is `Layanan Kesehatan untuk Anda dan Keluarga`.
- [ ] Sentul, Babakan Madang, and surrounding areas are mentioned.
- [ ] The copy explains that the service is comfortable and easy to access.
- [ ] The copy mentions dokter umum, dokter gigi, tindakan medis, IGD, vaksinasi, infus, fisioterapi, and farmasi.
- [ ] Operating hours show Senin–Sabtu, 08.00–20.00.
- [ ] `Reservasi Sekarang` is the dominant CTA.
- [ ] WhatsApp number is `0813-1088-2505`.
- [ ] WhatsApp CTA opens the correct `wa.me` link.
- [ ] `Lihat Layanan` scrolls to the services section.
- [ ] Akreditasi Paripurna is shown as a trust indicator.
- [ ] Hero image is relevant, authentic-looking, and has useful alt text.
- [ ] Hero does not become overcrowded on mobile.

## E. About / Clinic Introduction

- [ ] Section is labeled `Tentang Kami` in the navigation.
- [ ] Section has the ID `tentang-kami`.
- [ ] Heading is `Klinik Keluarga di Sentul dengan Pelayanan yang Nyaman`.
- [ ] Darmawan Park and Sentul are mentioned.
- [ ] Public and family services are explained.
- [ ] Friendly, personal, and efficient service is mentioned.
- [ ] Experienced doctors are mentioned.
- [ ] Comfortable examination and treatment facilities are mentioned.
- [ ] RUKUN Senior Living support is mentioned.
- [ ] Senior-friendly and wheelchair-friendly access is mentioned.
- [ ] Akreditasi Paripurna is displayed as a distinct trust element.
- [ ] The section uses short paragraphs and clear visual hierarchy.
- [ ] About content is not excessively text-heavy on mobile.

## F. Services

### Dokter Umum

- [ ] Consultation and general examination are listed.
- [ ] Blood pressure and blood sugar checks are listed.
- [ ] General health complaints are covered.
- [ ] Wound care is listed.
- [ ] Injection, nebulizer, and infusion services are listed.
- [ ] Medical check-up is listed.
- [ ] Health certificate is listed.
- [ ] Senior health monitoring is mentioned.
- [ ] CTA says `Buat Janji Dokter Umum`.
- [ ] CTA opens WhatsApp with an appropriate pre-filled message.

### Poli Gigi

- [ ] Section uses the title `Poli Gigi` or approved equivalent.
- [ ] Routine dental examination is listed.
- [ ] Scaling is listed.
- [ ] Filling, extraction, and dentures are listed.
- [ ] Oral health consultation is listed.
- [ ] CTA says `Reservasi Dokter Gigi`.
- [ ] Dental service visual is distinct or appropriate.
- [ ] CTA opens WhatsApp with an appropriate pre-filled message.

### IGD and Medical Procedures

- [ ] Initial medical handling is listed.
- [ ] Wound care, infusion, injection, and nebulizer are listed.
- [ ] Vital-sign examination and observation are listed.
- [ ] Service is clearly limited to clinic operating hours.
- [ ] Design does not imply 24/7 emergency service.
- [ ] Hospital referral warning is displayed.
- [ ] Call and/or WhatsApp action is prominent.

### Vaccination

- [ ] Vaccination service is included.
- [ ] Copy explains that availability depends on need and stock.
- [ ] Copy does not imply that every vaccine is always available.
- [ ] CTA says `Tanyakan Ketersediaan Vaksin` or an approved equivalent.
- [ ] CTA opens WhatsApp.

### Physiotherapy

- [ ] Recovery after injury is covered.
- [ ] Muscle and joint pain are covered.
- [ ] Mobility problems are covered.
- [ ] Post-operation and post-stroke recovery are covered.
- [ ] Strength and balance needs for seniors are covered.
- [ ] Individualized treatment is mentioned.
- [ ] CTA says `Konsultasi Fisioterapi`.
- [ ] CTA opens WhatsApp.

### Pharmacy

- [ ] Pharmacy is stated to be open to the general public.
- [ ] Basic medicines and health needs are mentioned.
- [ ] Limited medicine selection is clearly disclosed.
- [ ] Visitors are instructed to confirm availability first.
- [ ] CTA says `Cek Ketersediaan Obat` or an approved equivalent.
- [ ] CTA opens WhatsApp with a medicine-availability message.

## G. Doctor Schedule

- [ ] Dr. Susy Theresia, MMRs. is listed correctly.
- [ ] Dr. Sumina Saleh is listed correctly.
- [ ] Drg. Sinka Puji Yuninda, M.T.Kes is listed correctly.
- [ ] Drg. Anggita Prawesti W is listed correctly.
- [ ] All specialties are correct.
- [ ] All days and times match the brief.
- [ ] Schedule-change disclaimer is displayed directly below the schedule.
- [ ] `Konfirmasi Jadwal & Reservasi` CTA is available.
- [ ] Doctor cards are readable on mobile.
- [ ] Schedule does not rely on color alone.

## H. Family and Senior Care

- [ ] Section explains that the clinic serves children/adults, families, and seniors as applicable.
- [ ] RUKUN Senior Living connection is explained.
- [ ] Different patient needs are acknowledged.
- [ ] Comfortable examination time is mentioned.
- [ ] Wheelchair access is mentioned.
- [ ] Family accompaniment is mentioned.
- [ ] Visual communicates warmth and accessibility.

## I. Why Choose Klinik RUKUN Medika

- [ ] Experienced doctors benefit is included.
- [ ] Shorter queue or efficient service benefit is included.
- [ ] Friendly and personal service benefit is included.
- [ ] Comfortable facilities benefit is included.
- [ ] Wheelchair-friendly access benefit is included.
- [ ] Parking availability benefit is included.
- [ ] Multiple services in one location benefit is included.
- [ ] Benefits use concise, concrete descriptions.
- [ ] Benefits are displayed in a scannable icon/grid layout.

## J. FAQ

- [ ] FAQ navigation link points to `#faq`.
- [ ] General-patient availability question is answered.
- [ ] BPJS status is answered.
- [ ] General-doctor availability is answered.
- [ ] Dentist availability is answered.
- [ ] Physiotherapy availability is answered.
- [ ] Vaccination availability and stock limitation are answered.
- [ ] Pharmacy public access and limited stock are answered.
- [ ] Senior and wheelchair accessibility is answered.
- [ ] Accordion opens and closes correctly.
- [ ] Accordion is keyboard accessible.
- [ ] WhatsApp CTA is available after or near the FAQ.

## K. Location and Contact

- [ ] Clinic name is displayed correctly.
- [ ] Address matches the brief exactly.
- [ ] Google Maps embed points to the correct location.
- [ ] `Buka Google Maps` opens the correct map link.
- [ ] Operating hours are shown.
- [ ] Phone/WhatsApp number is clickable.
- [ ] Instagram handle is shown correctly.
- [ ] Address can be copied or selected easily.
- [ ] Mobile layout prioritizes WhatsApp, directions, address, and operating hours.

## L. Final CTA and Footer

- [ ] Final CTA uses the approved reservation wording.
- [ ] Final CTA opens the correct WhatsApp conversation.
- [ ] Footer contains clinic name and location.
- [ ] Footer contains operating hours.
- [ ] Footer contains phone/WhatsApp number.
- [ ] Footer contains Instagram handle.
- [ ] Copyright year is current or generated dynamically.
- [ ] Footer links and external links work correctly.

## M. Mobile UX

- [ ] Layout works at small mobile widths.
- [ ] Tap targets are large enough and comfortable.
- [ ] WhatsApp remains reachable without returning to the top.
- [ ] Phone number uses a `tel:` link.
- [ ] WhatsApp links use the correct `wa.me` format.
- [ ] Long paragraphs do not dominate the screen.
- [ ] Detailed service lists use accordions or progressive disclosure where needed.
- [ ] Images are responsive and do not overflow.
- [ ] Bottom action bar does not cover page content.

## N. Accessibility

- [ ] Color contrast is sufficient.
- [ ] Keyboard focus is visible.
- [ ] Semantic HTML elements are used.
- [ ] Heading hierarchy is correct.
- [ ] Meaningful images have descriptive alt text.
- [ ] Decorative icons do not create confusing screen-reader output.
- [ ] Buttons have descriptive labels.
- [ ] Information is not communicated by color alone.
- [ ] Text can be resized without breaking the layout.
- [ ] Reduced-motion preferences are respected.
- [ ] Map has a text-based address alternative.
- [ ] Mobile menu exposes correct expanded/collapsed state.

## O. Performance and Technical Validation

- [ ] All three HTML pages load without console errors.
- [ ] Tailwind CDN/configuration loads correctly where used.
- [ ] External images load or have a suitable fallback.
- [ ] Lazy loading is used for below-the-fold images where appropriate.
- [ ] Images are compressed and appropriately sized.
- [ ] Google Maps embed loads correctly.
- [ ] WhatsApp links work on desktop and mobile.
- [ ] All internal anchor links work.
- [ ] No placeholder copy remains.
- [ ] No accidental citation markers or AI-generation artifacts remain.
- [ ] HTML structure passes a validator or manual DOM review.
- [ ] Core Web Vitals are checked before production.

## P. Three-Version Comparison

The checks marked below are based on a static review of the current HTML content and structure in all three preview files. Console-error checks remain unchecked until each page is opened and tested in a browser.

### `chatgpt.html`

- [x] Navbar checked against the brief.
- [x] Hero checked against the brief.
- [x] About section checked against the brief.
- [x] Services checked against the brief.
- [x] Doctor schedule checked against the brief.
- [x] Family and senior care checked against the brief.
- [x] Benefits checked against the brief.
- [x] FAQ checked against the brief.
- [x] Location and contact checked against the brief.
- [x] Mobile layout checked.
- [x] Accessibility checked.
- [ ] Console checked for errors.

### `claude.html`

- [x] Navbar checked against the brief.
- [x] Hero checked against the brief.
- [x] About section checked against the brief.
- [x] Services checked against the brief.
- [x] Doctor schedule checked against the brief.
- [x] Family and senior care checked against the brief.
- [x] Benefits checked against the brief.
- [x] FAQ checked against the brief.
- [x] Location and contact checked against the brief.
- [x] Mobile layout checked.
- [x] Accessibility checked.
- [ ] Console checked for errors.

### `gemini.html`

- [x] Navbar checked against the brief.
- [x] Hero checked against the brief.
- [x] About section checked against the brief.
- [x] Services checked against the brief.
- [x] Doctor schedule checked against the brief.
- [x] Family and senior care checked against the brief.
- [x] Benefits checked against the brief.
- [x] FAQ checked against the brief.
- [x] Location and contact checked against the brief.
- [x] Mobile layout checked.
- [x] Accessibility checked.
- [ ] Console checked for errors.

## Q. Final Approval

- [ ] All clinic-specific facts were confirmed with the clinic.
- [ ] Final design version was selected.
- [ ] Final copy was approved.
- [ ] All high-priority issues are resolved.
- [ ] All three previews were compared side by side.
- [ ] Production page was tested on desktop.
- [ ] Production page was tested on mobile.
- [ ] Final stakeholder approval was received.