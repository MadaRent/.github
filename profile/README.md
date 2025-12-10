# 🏠 MadaRent — The Modern Real-Estate Platform for Madagascar  
*(Starting with long-term rentals)*

**MadaRent** is becoming a complete real-estate ecosystem designed for **Madagascar**.  
The first version focuses entirely on **monthly rentals**, but the long-term vision covers the full property market: renting, buying, selling, and property management.

---

## 🌍 What MadaRent Aims to Solve

- Fragmented real-estate market  
- Scattered and unreliable Facebook listings  
- Lack of transparency in availability and pricing  
- Difficult communication between renters, owners, and agencies  
- No modern tools for agencies and property managers  

**MadaRent centralizes, cleans, and modernizes the entire experience.**

---

## 🚀 Platform Scope

### **Phase 1 — Long-Term Rentals (Current Focus)**  
- Listings aggregated from Facebook + manual submissions  
- Verified and reviewed posts  
- Meilisearch-powered filters  
- Unlock contact for **5,000 Ar**  
- Visit confirmation fee for owners/agencies (**10,000 Ar**)  
- Owner & agency dashboards  
- Subdomain architecture (app, agency, admin)

### **Phase 2 — Buying & Selling Properties (Coming Soon)**  
- Dedicated “Buy / Sell” section  
- Property categories: land, houses, apartments, commercial  
- Premium visibility options for agencies  
- Lead generation tools  
- Enhanced property pages (plans, maps, more photos)

### **Phase 3 — Professional Tools for Agencies & Owners**  
- Full real-estate CRM  
- Multi-agent teams  
- Automated Facebook reposting  
- Property performance analytics  
- Owner/tenant communication  
- Basic property management tools (payments, history, receipts)

### **Phase 4 — Advanced Real-Estate Services**  
- Secure deposit payments  
- Rent collection via mobile money  
- Property value estimation (ML-powered in the future)  
- Mortgage calculator + partnerships with banks  
- Home services marketplace (moving, cleaning, repairs)  
- Advertising & promotions for agencies and developers

---

## 🧱 Technical Architecture

| Technology | Purpose |
|-----------|---------|
| **SvelteKit** | Main UI for users, owners, and agencies |
| **PocketBase** | Authentication, DB, file storage, API |
| **Bun + Hono** | High-performance microservice for Facebook sync |
| **Meilisearch** | Ultra-fast search engine with sync service |
| **Dokploy** | Container management and deployments |
| **Netcup G1000 v11** (4 vCores / 8GB RAM) | Production hosting |
| **CapacitorJS** | Lightweight Android mobile build |

---

## 🌐 App Structure (Subdomains)

- **madarent.mg** → Public website, SEO, listings, Tenant & owner dashboard
- **agence.madarent.mg** → Professional agency platform (CRM, listings, sync)  
- **backoffice.madarent.mg** → Internal backoffice

All subdomains authenticate through the same PocketBase backend.

---

## 🎯 Product Workflow (Rentals)

### 1️⃣ Explore Listings  
Listings updated continuously from Facebook and owners.

### 2️⃣ Fast Search  
Powered by Meilisearch with filters: price, city, type, availability, amenities.

### 3️⃣ Unlock Contact  
Tenants pay **5,000 Ar** to view owner/agency contact details.

### 4️⃣ Manage Properties  
Owners and agencies can post, edit, deactivate, and sync listings.

### 5️⃣ Confirmed Visits  
Professionals pay **10,000 Ar** per confirmed visit through the platform.

---

## 🔮 The Big Vision

> **MadaRent will evolve into the all-in-one real-estate platform of Madagascar.**  
Starting with long-term rentals, then expanding into buying, selling, management, and professional tools — all built with a modern, scalable architecture.

---
