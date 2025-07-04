# ✅ Development Roadmap - Ecommerce Java Spring Boot API

This file tracks development progress for building a real-world eCommerce backend project with Java and Spring Boot.

---

## Phase 1: Initial Setup
- [x] Create GitHub repo with `.gitignore`, MIT license, and `README.md`
- [ ] Scaffold Spring Boot project (Web, Security, JPA, H2)
- [ ] First commit and push project to GitHub

---

## Phase 2: Domain & Database
- [ ] Create `Product` model (id, name, price, etc.)
- [ ] Create `User` model with roles (`ADMIN`, `CUSTOMER`)
- [ ] Create `CartItem` and `Order` models
- [ ] Set up repositories using Spring Data JPA
- [ ] Configure H2 database with `application.properties`

---

## Phase 3: API Endpoints
- [ ] Build `ProductController` with CRUD endpoints
- [ ] Build `CartController` (add/remove/view items)
- [ ] Build `OrderController` with checkout flow
- [ ] Add basic admin dashboard functionality (optional)

---

## Phase 4: Authentication & Security
- [ ] Implement Spring Security
- [ ] Add login/signup endpoints
- [ ] Apply role-based access (admin vs customer)
- [ ] Store passwords securely (BCrypt)

---

## Phase 5: Testing & Documentation
- [ ] Add test data (`data.sql`)
- [ ] Test endpoints with Postman
- [ ] Update `README.md` with usage instructions and endpoints
- [ ] Optional: Add Docker support or deploy online

---

## Final Goal
🟢 A complete, job-ready eCommerce backend API showing:
- Java proficiency
- Spring Boot architecture
- Real-world RESTful API design
- Security, roles, and business logic
