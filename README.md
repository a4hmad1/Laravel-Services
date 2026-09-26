<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="340" alt="Laravel Logo">
  </a>
</p>

<h1 align="center">Laravel Services Hub</h1>

<p align="center">
  <strong>The Ultimate Cloud Services, AI Gateway & DevOps Operations Control Plane for Modern Laravel Applications.</strong>
</p>

<p align="center">
  <a href="https://packagist.org/packages/laravel-services/hub"><img src="https://img.shields.io/badge/Packagist-v1.0.0-FF2D20?style=for-the-badge&logo=packagist&logoColor=white" alt="Packagist Version"></a>
  <a href="https://php.net"><img src="https://img.shields.io/badge/PHP-%3E%3D%208.2-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP Version"></a>
  <a href="https://laravel.com"><img src="https://img.shields.io/badge/Laravel-10%20%7C%2011%20%7C%2012-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel Framework"></a>
  <a href="https://github.com/a4hmad1/Laravel-Services/actions"><img src="https://img.shields.io/badge/CI%2FCD-Passing-22c55e?style=for-the-badge&logo=githubactions&logoColor=white" alt="CI Status"></a>
  <a href="https://github.com/a4hmad1/Laravel-Services/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-0ea5e9?style=for-the-badge" alt="License"></a>
  <a href="https://github.com/a4hmad1/Laravel-Services/stargazers"><img src="https://img.shields.io/github/stars/a4hmad1/Laravel-Services?style=for-the-badge&color=eab308&logo=github&logoColor=white" alt="Stars"></a>
</p>

---

## ⚡ Executive Overview

**Laravel Services Hub** bridges the gap between your Laravel codebase and the modern cloud ecosystem. Rather than juggling dozens of disparate cloud consoles, scattered API keys, divergent `.env` configurations, and detached webhook listeners, **Services Hub** delivers a unified, zero-configuration in-app control plane.

Designed to live alongside flagship tools like **Laravel Forge**, **Laravel Cloud**, **Laravel Pulse**, and **Laravel Horizon**, Services Hub provides full-stack visibility, operational diagnostics, and interactive credential management for **108+ cloud drivers and services** across 13 essential operational domains.

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                            LARAVEL SERVICES HUB                             │
├─────────────────┬───────────────────┬───────────────────┬───────────────────┤
│  AI & LLM HUB   │ 108+ INTEGRATIONS │ DEVOPS & CI/CD    │ SECRETS & .ENV    │
│  OpenAI, Claude │ AWS, Stripe,      │ Git push to Forge │ AES-256-GCM Vault │
│  Gemini, Groq   │ Resend, Supabase  │ Cloud, Hetzner    │ Zero-drift sync   │
└─────────────────┴───────────────────┴───────────────────┴───────────────────┘
```

---

## 📸 Flagship Product Tour

### 🖥️ 1. Real-Time Operations Command Center
> High-density KPI telemetry, service health matrix, live latency gauges, instant driver status, and recent audit activity streams.

<p align="center">
  <img src="art/dashboard.png" alt="Laravel Services Dashboard Overview" width="100%" style="border-radius: 10px; border: 1px solid rgba(255, 45, 32, 0.2); box-shadow: 0 15px 35px rgba(0,0,0,0.3);">
</p>

---

### 🔌 2. The 108+ Services & Drivers Marketplace
> Schema-driven marketplace featuring 13 operational domains: AI, Cloud Infrastructure, Payments, Storage, Databases, Email, Messaging, DevOps, Security, and Monitoring.

<p align="center">
  <img src="art/integrations.png" alt="Laravel Services Marketplace Catalog" width="100%" style="border-radius: 10px; border: 1px solid rgba(255, 45, 32, 0.2); box-shadow: 0 15px 35px rgba(0,0,0,0.3);">
</p>

---

### 🚀 3. Multi-Cloud DevOps & Deployment Fleet Orchestrator
> Automated Git-to-production deployment pipeline, environment promotion workflows, server health telemetry (Hetzner Cloud, AWS EC2, DigitalOcean), and seamless integration with **Laravel Forge** and **Laravel Cloud**.

<p align="center">
  <img src="art/deployments.png" alt="DevOps, Deployments and Server Fleet" width="100%" style="border-radius: 10px; border: 1px solid rgba(255, 45, 32, 0.2); box-shadow: 0 15px 35px rgba(0,0,0,0.3);">
</p>

---

### 🤖 4. Unified AI & LLM Engine
> Multimodal AI operations studio with hot-swappable providers (OpenAI GPT-4o, Anthropic Claude 3.5, Google Gemini 2.0, Groq), live prompt sandbox, token consumption tracking, and vector database embeddings.

<p align="center">
  <img src="art/ai.png" alt="Unified AI and LLM Suite" width="100%" style="border-radius: 10px; border: 1px solid rgba(255, 45, 32, 0.2); box-shadow: 0 15px 35px rgba(0,0,0,0.3);">
</p>

---

## 🏛️ Key Architectural Pillars

| Architectural Pillar | Technical Specification | Operational Benefit |
| :--- | :--- | :--- |
| **Unified Driver Registry** | Centralized schema contract across 108+ service adapters | Standardized test-pings, validation, and credentials management |
| **Zero-Drift .env Sync** | Bi-directional synchronization with automated diff checking | Prevents runtime breakage caused by out-of-sync team environment keys |
| **Cryptographic Secrets Vault** | Hardware-grade AES-256-GCM encryption rooted in `APP_KEY` | Sensitive credentials never exposed in plaintext in logs or frontend state |
| **Multi-Cloud Fleet Telemetry** | Server resource agent (CPU, RAM, Disk, IOPS) via SSH / API | Monitor Hetzner, AWS, and DigitalOcean instances next to Forge & Cloud |
| **Smart AI Gateway Router** | Fallback-capable LLM abstraction with prompt cache optimization | Zero vendor lock-in; switch from OpenAI to Claude or Gemini with 1 click |
| **Webhook Replay Lab** | HMAC-SHA256 signature verification & payload simulation | Inspect, debug, and replay inbound Stripe, GitHub, and Resend webhooks |
| **Laravel Window Bridge** | Zero-build frontend delivery through runtime state hydration | Host application requires zero Node.js/Vite tooling to run dashboard |

---

## 📦 Supported Ecosystem (108+ Services)

<details open>
<summary><b>Click to inspect the complete 13-category service directory</b></summary>

<br>

| Domain | Supported Providers & Drivers |
| :--- | :--- |
| 🧠 **AI & Machine Learning** | OpenAI (GPT-4o), Anthropic (Claude 3.5), Google Gemini 2.0, Groq, Mistral AI, Hugging Face, Pinecone Vector DB |
| ☁️ **Cloud Infrastructure** | Amazon Web Services (AWS), Google Cloud Platform (GCP), Microsoft Azure, Cloudflare, Firebase |
| 💳 **Payments & Billing** | Stripe, Laravel Cashier, PayPal, Lemon Squeezy, Paddle, Adyen, Mollie, Razorpay |
| 📬 **Email & Transactional** | Resend, Postmark, Amazon SES, Mailgun, SendGrid, Custom SMTP / Brevo |
| 🗄️ **Databases & Caching** | Redis, Supabase, Neon Postgres, PlanetScale, MongoDB, PostgreSQL, MySQL |
| 📦 **Storage & CDN** | AWS S3, Cloudflare R2, Backblaze B2, Google Cloud Storage, Local / NFS |
| 🔐 **Authentication & OAuth** | Laravel Socialite (GitHub, Google, Apple, Discord), Firebase Auth, Auth0, Keycloak |
| 📨 **Messaging & Push** | Twilio, Telegram Bot API, Slack Notifications, WhatsApp Business, Discord, Pusher, Vonage |
| 🛠️ **DevOps & CI/CD** | GitHub Actions, Docker, Kubernetes, Terraform, Ansible, GitLab CI |
| 🖥️ **Server Platforms** | Laravel Forge, Laravel Cloud, Laravel Vapor, Laravel Envoyer, Hetzner Cloud, DigitalOcean, Railway, Fly.io, Vercel |
| 📈 **Monitoring & APM** | Sentry, Better Stack, Datadog, Bugsnag, New Relic, Grafana, CloudWatch |
| 🛡️ **Security & Protection** | Cloudflare Turnstile, Google reCAPTCHA v3, HashiCorp Vault, AWS KMS, AWS Secrets Manager |
| ⚡ **Laravel Native** | Laravel Horizon, Laravel Pulse, Laravel Telescope, Laravel Sanctum |

</details>

---

## 🚀 Quickstart & Installation

Install the package via Composer into your Laravel application:

```bash
composer require laravel-services/hub
```

Publish the configuration, assets, and service provider:

```bash
php artisan services:install
```

Run database migrations for audit logs and the encrypted secrets vault:

```bash
php artisan migrate
```

### Authorization Gate

Protect your Services Hub route (`/services`) using standard Laravel authorization gates inside `app/Providers/AppServiceProvider.php`:

```php
use Illuminate\Support\Facades\Gate;

/**
 * Register any application services.
 */
public function boot(): void
{
    Gate::define('viewServicesHub', function ($user) {
        return in_array($user->email, [
            'admin@your-company.com',
            'lead-dev@your-company.com',
        ]) || $user->hasRole('admin');
    });
}
```

---

## 💻 Artisan Command Suite

Services Hub includes a command-line interface for DevOps automation and CI/CD pipelines:

```bash
# Check health of all configured cloud drivers
php artisan services:health

# Ping and validate specific service connection
php artisan services:ping stripe
php artisan services:ping aws-s3

# Validate .env file integrity against schema
php artisan services:env:verify

# Export encrypted secrets vault for team sync
php artisan services:vault:export --env=production

# Dispatch deployment webhook via Laravel Forge / Cloud
php artisan services:deploy --target=production
```

---

## 🔒 Enterprise Security & Architecture

- **Defense in Depth**: Zero sensitive secrets are ever transmitted in plain text or rendered unmasked in frontend state.
- **Cryptographic Storage**: Secrets stored in database columns utilize Laravel's native authenticated encryption (`AES-256-GCM`).
- **Signature Verification**: Webhooks enforce strict HMAC-SHA256 signature verification matching provider specifications.
- **Zero Frontend Dependencies**: The SPA compiles to high-performance standalone bundles; host Laravel applications require no Node.js runtime or Vite installation.

---

## 🤝 Synergy with Laravel Ecosystem Products

Services Hub was architected to be the missing operational glue that enhances Laravel's first-party ecosystem:

- **Laravel Cloud & Forge**: Orchestrate builds, webhooks, and multi-server environments with single-click promotion.
- **Laravel Pulse**: Surfaces Pulse metrics alongside third-party APM diagnostics (Sentry, Datadog) for 360-degree observability.
- **Laravel Horizon**: Real-time worker supervision and queue health displayed right inside the operational command center.
- **Laravel Cashier & Socialite**: Instant UI configuration wizards for Stripe webhooks and OAuth providers without touching raw config files.

---

## 📜 Roadmap & Milestones

- [x] **v1.0-alpha**: Architectural design & full 30-page interactive React/TypeScript control plane
- [x] **v1.0-beta**: Centralized Service Registry with 108+ validated service adapters
- [x] **v1.0-rc**: Zero-drift environment validation & encrypted team secrets vault
- [ ] **v1.0-stable**: Packagist release (`composer require laravel-services/hub`)
- [ ] **v1.1**: Native mobile companion app & Telegram DevOps incident bot

---

## 🌟 Acknowledgments & Credits

We extend our deep gratitude to the creators and visionaries who made PHP and Laravel the premier web platform in the world:

- **Taylor Otwell** & the **Laravel Core Team** for creating Laravel, Forge, Vapor, and Laravel Cloud.
- **Spatie** (Freek Van der Herten & team) for setting the standard in open-source PHP excellence.
- **Caleb Porzio** (Livewire, Alpine.js) & **Jonathan Reinink** (Inertia.js) for full-stack innovation.
- **Dan Harrin** & the **Filament Team** for championing the modern administrative ecosystem.

---

## 📄 License & Trademarks

- **License:** Open-source software licensed under the [MIT License](LICENSE).
- **Trademark Notice:** *Laravel* is a registered trademark of Taylor Otwell. *Laravel Services Hub* is an independent open-source contribution designed for the Laravel developer community.

<p align="center">
  <sub>Engineered with precision by <strong>Ahmad</strong> (<a href="https://github.com/a4hmad1">@a4hmad1</a>) • Built for Web Artisans Worldwide</sub>
</p>
