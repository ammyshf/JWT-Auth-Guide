# JWT-Auth-Guide
# JWT Authentication with Spring Security — Complete Visual Guide

A comprehensive, interactive visual guide covering the complete JWT Authentication flow with Spring Security.

## Live Demo

**[View the Guide](https://ammyshf.github.io/JWT-Auth-Guide/JWT_Authentication_Guide.html)**

## What's Covered

- **Architecture Overview** — Filters, Providers, Services & how they connect
- **JWT Structure** — Header, Payload, Signature with decoded view
- **Tamper Detection** — How signature verification prevents tampering
- **Session vs JWT** — Side-by-side comparison
- **Provider Routing** — Strategy Pattern with DaoAuth & JWTAuth providers
- **Step 1: Registration** — BCrypt password hashing flow
- **Step 2: Login** — Authentication + Token generation (Access + Refresh)
- **Step 3: Validation** — JWT verification on every API call
- **Step 4: Refresh** — Token refresh using HttpOnly cookies

## Tech Stack

- Spring Security Filter Chain (3 custom filters)
- DaoAuthenticationProvider & custom JWTAuthenticationProvider
- BCrypt password encoding
- JJWT library for token operations
- HttpOnly secure cookies for refresh tokens

## Author

**Amaan Sharif Nirban**

---

Built with dark theme, color-coded components, and visual flow diagrams for easy understanding.

