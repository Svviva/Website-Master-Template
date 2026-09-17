# Website Master Template

Reusable bilingual English/Arabic school website foundation built with Astro. It preserves responsive layouts, RTL support, admissions/contact patterns, gallery/news structures, mobile navigation and subtle accessible animations.

## Start a new school website
Create a fresh repository from this master. Keep each school's content, photographs, deployment and domain settings separate.

Before publishing, replace and verify the school name in both languages, logo and branding, location/address/map, phone/email/WhatsApp, social links, principal details and photograph, grade range, curriculum and academic claims, admissions requirements/fees, activities/facilities, news, gallery photographs, portal link, privacy/legal wording, domain and hosting.

## Content rule
Never carry factual claims from one school to another. English and Arabic pages should communicate the same verified facts naturally rather than mechanically word-for-word.

## Photography rule
Use genuine photographs supplied or approved for the new school. Do not generate substitute student, classroom or activity photographs.

## Local development
```bash
npm install
npm run dev
```
For phone testing on the same local network:
```bash
npm run dev -- --host
```

## Build
```bash
npm run build
```
The production output is written to `dist`.

See `WEBSITE-MASTER-TEMPLATE.md` for the full customization checklist.
