```typescript
// wvrld/README.ts

interface Identity {
    readonly handle:     string;
    readonly alias:      string;
    readonly role:       Role[];
    readonly company:    string;
    readonly website:    string;
    readonly mission:    string;
}

type Role = "Pentester" | "Developer" | "Privacy & Security Promoter";

const wvrld: Identity = {
    handle:    "62104e53b9fc85ef",
    alias:     "wvrld",
    role:      ["Pentester", "Developer", "Privacy & Security Promoter"],
    company:   "Bitbone",
    website:   "https://wvrld.cloud",
    mission:   "Software was meant to be light and feel effortless to use.",
};
```

---

```typescript
type TechStack = {
    languages:  readonly string[];
    os:         readonly string[];
    interests:  readonly string[];
};

const stack: TechStack = {
    languages:  ["Python", "JavaScript", "TypeScript", "Solidity", "Go"],
    os:         ["macOS Tahoe", "TailsOS", "ParrotOS"],
    interests:  ["Offensive Security", "Privacy Engineering", "Web3", "OSINT", "GEOINT", "IMINT", "SOCMINT", "TECHINT", "Reverse Engineering"],
};
```

---

```typescript
// Bitbone — Cybersecurity & AI Solutions | Brno, CZ
// https://bitbone.io

type Service = {
    name:         string;
    description:  string;
};

const bitbone: Service[] = [
    {
        name:         "Application Security",
        description:  "Code review and security analysis across Python, TypeScript, and Go",
    },
    {
        name:         "Penetration Testing",
        description:  "Manual testing and advanced threat simulations for web apps, APIs, and networks",
    },
    {
        name:         "Infrastructure Security",
        description:  "Cloud and hybrid environment assessments — AWS, Azure, GCP",
    },
    {
        name:         "AI Solutions",
        description:  "Production-ready RAG systems, custom LLM integrations, and intelligent automation",
    },
    {
        name:         "Secure Development",
        description:  "Architecture review, auth mechanisms, and data handling from day one",
    },
];
```

---

```typescript
const links: Record<string, string> = {
    portfolio:    "https://wvrld.cloud",
    tryhackme:    "https://tryhackme.com/p/xwvrld",
    company:      "https://bitbone.io",
};
```

<img src="https://tryhackme-badges.s3.amazonaws.com/xwvrld.png" alt="TryHackMe">

---

```typescript
type Contact = {
    email:        () => string;
    pgp: {
        fingerprint:  string;
        keyserver:    string;
        download:     string;
    };
};

const contact: Contact = {
    email:        () => atob("bHVrYXNAYml0Ym9uZS5pbw=="),
    pgp: {
        fingerprint:  "04BC DACE 96C2 F6AE 58E1 5F25 E7C8 355A 9F42 AC35",
        keyserver: "https://keys.openpgp.org/search?q=04BCDACE96C2F6AE58E15F25E7C8355A9F42AC35",
        download: "https://keys.openpgp.org/vks/v1/by-fingerprint/04BCDACE96C2F6AE58E15F25E7C8355A9F42AC35",
    },
};

// Please encrypt and sign your emails if you are a PGP user. All communication is expected to be encrypted where possible.
```

---

```typescript
const principles: readonly string[] = [
    "Privacy is a fundamental right, not a feature.",
    "Security through obscurity is no security at all.",
    "If it's not open source, it's not trustworthy.",
    "Minimal footprint. Maximum impact.",
];
```

---

<br>

> *"Arguing that you don't care about the right to privacy because you have nothing to hide is no different than saying you don't care about free speech because you have nothing to say."*
>
> *"A free press benefits more than just those who read the paper."*
>
> E. J. Snowden, [2015](https://www.reddit.com/r/IAmA/comments/36ru89/just_days_left_to_kill_mass_surveillance_under/crglgh2/)

---

<p align="center"><sub>// EOF</sub></p>
