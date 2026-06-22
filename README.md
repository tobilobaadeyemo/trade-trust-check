# Trade Trust Check

**[Open the live tool →](https://tobilobaadeyemo.github.io/trade-trust-check/)**

A free, open-source verification aid for cross-border trade. It applies the zero-trust principle, assume nothing and verify what you can, to a trade counterparty before you send money.

Cross-border trade rarely fails on capital. It fails on trust. Who is the supplier? Are they real? Who is accountable when something goes wrong? Those are identity questions, and most of the time they go unanswered until it is too late. This tool makes the verification structured instead of a gut call.

## What it does

1. **Live domain signal.** Enter a counterparty's domain and it runs a public RDAP registration lookup in your browser: registration date, registrar, expiry. A domain registered last month is a different risk than one trading since 2009, and a brand-new domain is the single most common red flag in supplier fraud.
2. **A zero-trust checklist.** Four pillars, drawn from the questions any zero-trust system asks:
   - **Identity** — who is the actor?
   - **Provability** — what can they prove?
   - **Authorization** — what are they authorized to do?
   - **Resilience** — what happens if we assume breach?
3. **A verifiability score.** A transparent, weighted 0 to 100 score with a clear verdict and a prioritized list of the highest-value gaps to close before you commit funds.

## Honest scope

This is a structured verification aid, not legal, financial, or compliance advice, and not a guarantee. It does not score the counterparty for you; it scores how much **you** have independently verified. Registration data is a signal, not proof.

## Privacy

Everything runs in your browser. No backend, no accounts, no data stored or sent anywhere except the public RDAP lookup for the domain you type.

## Tech

Plain HTML, CSS and JavaScript. No build step, no dependencies. The only network call is to public RDAP (`rdap.org`). Deployed on GitHub Pages.

## Run locally

Open `index.html` in a browser. That's it.

## Why this exists

I build identity-first security systems, and I have spent years moving goods across African borders. The same verification logic governs both: the systems that move data and the systems that move goods both fail when trust is assumed instead of engineered. This tool is that idea, small enough to use.

Read the longer argument: [Why Identity-First Security Matters for Cross-Border Trade](https://tobilobaadeyemo.com/writing/identity-first-security-cross-border-trade/).

## Author

Built by **Tobiloba Adeyemo**, Cloud Security Engineer and founder of Raptview Labs.
[tobilobaadeyemo.com](https://tobilobaadeyemo.com) · [LinkedIn](https://www.linkedin.com/in/tobilobaadeyemo)

## License

MIT. See [LICENSE](LICENSE).
