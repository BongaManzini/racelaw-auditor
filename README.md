# ️ The Law Auditor: Verifying Viral Claims of 145 Race Laws
### An Independent Student Legal Audit Checking Statutes Against the Official Government Gazette

> **Live Website**: [https://bongamanzini.github.io/racelaw-auditor/](https://bongamanzini.github.io/racelaw-auditor/) 
> **Built by**: Bonga Manzini (BSc Informatics student at UNISA)

---

## About This Project

A list claiming that South Africa has '145 race-based laws' was widely shared across news debates, talk radio, and social media. People were arguing that modern laws like B-BBEE and Employment Equity are 'just apartheid in reverse'.

I wanted to find out if that claim was actually true. I went through the official South African Government Gazette, SAFLII legal databases, and Law Reform Commission records to audit every single cited act.

Many cited acts were old apartheid laws from the 1950s that were repealed decades ago. Other cited acts were standard democratic programs protected under Section 9(2) of our Constitution (our Bill of Rights), which allows the government to help people who were historically disadvantaged. I built this searchable tool so anyone can read the actual acts and see what is real and what is repealed.

---

## The 11 Questions: The Facts Behind The Project

### 1. Who is this for?
- Law students, journalists, voters, and curious citizens who want to know what laws are actually active in South Africa.

### 2. Where does this focus on?
- South African national legislation and the official Government Gazette.

### 3. Why did I build it?
- Public debates were getting heated based on an unverified viral PDF. I wanted to build a neutral, factual search engine where anyone can verify statutes in seconds.

### 4. How does the tool work?
- A fast search bar where you can type in any act (or filter by decade from 1910 to 2026).
- Shows badges for Active, Repealed, or Constitutional Redress.
- Links directly to the original Government Gazette notices.

### 5. When were these laws passed?
- Spans historical legislation from 1910 to the present day (1994–2026).

### 6. The Problem I Noticed
- **The Myth**: A viral document claimed 145 discriminatory laws exist, without explaining that many were repealed decades ago or were created to fix historical inequalities under the Constitution.
- **The Reality**: Modern constitutional redress laws are voluntary business development incentives, not criminal penalties like apartheid laws.

### 7. Where I Got The Data
1. **The South African Government Gazette**: Official state notices.
2. **SAFLII (Southern African Legal Information Institute)**: Comprehensive database of statutes and court rulings.
3. **South African Law Reform Commission (SALRC)**: Official repeal lists (Project 25).

### 8. Why I Trusted This Source
- The Government Gazette is the official legal publication of the Republic of South Africa.
- SAFLII is the gold standard for free public access to legal texts.

### 9. How I Built It
- I collected all cited statutes, verified their legal status with SALRC records, and wrote a clean JavaScript search tool with zero slow backend delays.

### 10. What I Hope To Achieve
- Provide an honest, neutral civic tool that helps people fact-check legal claims in under 10 seconds.

### 11. Why This Matters In Real Life
- Legal language can be confusing. Translating statutes into plain English bridges the gap between lawyers and everyday citizens.

---

## ️ Tech Stack
- **HTML5 & Vanilla JavaScript**
- **Tailwind CSS**
- **Search & Filtering Engine** (runs 100% in browser)

---

## Contributing & Pull Requests

Found an unlisted statute or want to update legal references?
1. Fork this repository
2. Create a branch (`git checkout -b feature/statute-update`)
3. Add comments explaining your changes
4. Submit a Pull Request!
