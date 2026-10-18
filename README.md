# Dr. Vibhor Pateriya Brain and Spine Clinic

A responsive React/Vite clinic website and connected frontend operations demo. It includes public pages, online booking, role workspaces, patient registration, doctor queue, consultation and prescription flow, pharmacy dispensing, inventory, billing/report placeholders, and clinic settings.

## Run locally

```bash
npm install
npm run dev
```

Production build:

```bash
npm run build
```

## Demo behavior

Choose **Staff Sign In** from the public site to open Doctor, Reception, Pharmacy, or Administrator workspaces. Data is synthetic and stored only in the current browser for connected demo workflows. Use the reception walk-in flow, start the visit from the doctor queue, finalize a prescription, then dispense it from Pharmacy to see state propagate.

## Production requirements

This repository is a frontend demonstration, not a production medical-record system. A production release requires a secured backend with authenticated sessions, server-side role authorization, encrypted databases and object storage, immutable audit logs, consent and retention controls, amendment history, CSRF/rate-limit protections, server-side validation, atomic stock and payment operations, backups, verified payment webhooks, and professional review against applicable Indian data-protection and healthcare obligations.

Do not store real patient records in browser storage. Replace the demo repository with approved APIs before clinical use.

## Verification-sensitive content

Medical qualifications, registration details, consultation fees, telephone/WhatsApp numbers, full address, timings, doctor photograph, signature, services, and Google Maps embed remain configurable and unpublished until verified by the clinic administrator.
