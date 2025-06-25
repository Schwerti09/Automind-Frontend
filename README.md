# Automi# 🚀 AUTOMIND – AI Agency-in-a-Box

**AUTOMIND** ist eine vollautomatisierte KI-Agentenplattform mit moderner Fullstack-Architektur. Entwickelt für Creator, Entwickler und Unternehmen, die skalierbare KI-Agenten sofort deployen und steuern wollen – ohne komplizierten Setup.

---

## 🔧 Tech Stack

- **Backend:** Deno + Oak (leicht, performant, sofort deploybar)
- **Frontend:** (optional) SvelteKit / Next.js / HTML+JS – nach Bedarf anschließbar
- **Datenhaltung:** `.env`-based, flexibel erweiterbar (MongoDB, SurrealDB etc.)
- **Deployment:** Railway, Vercel, Docker, alles möglich

---

## 📂 Projektstruktur

```bash
/
├── main.ts                 # Server-Entry
├── routes/
│   └── index.ts            # Basisroute
├── services/
│   └── verify.ts           # Interne Verifizierung für API-Calls
├── .env                    # Secrets und API-Keys (nicht commiten!)
├── Dockerfile              # Deployment-ready Docker Setup
├── import_map.json         # Deno Module Import Config
└── README.md               # Diese Datei
nd-Frontend
