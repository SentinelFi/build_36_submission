### Reviewer Comment:
> This project has strong potential to bring sophisticated DeFi tools to Stellar while leveraging the ecosystem's advantages. The team's experience and existing traction make it a reasonable investment, but the regulatory and security aspects need more attention.

**Response:**

Thank you for the thoughtful feedback. At its core, our project is not a direct-to-consumer insurance product, but a **framework**—a modular infrastructure for building parametric insurance markets on-chain. This allows developers, DAOs, and risk underwriters to create insurance products tailored to their region or vertical. Those building on top of the framework will ultimately be responsible for adhering to local regulatory requirements. That said, for the verticals we ourselves choose to launch (such as flight delay and wildfire insurance), we are fully conscious of compliance considerations and are designing accordingly.

Encouragingly, regulatory support is emerging. In California, [AB 1236](https://leginfo.legislature.ca.gov/faces/billTextClient.xhtml?bill_id=202320240AB1236) proposes a grant program to fund the development of innovative insurance models, including parametric and community-based coverage. Administered by the Department of Insurance, the program explicitly recognizes parametric insurance as a way to reduce climate risk and improve accessibility—especially for underserved and low-income communities.

At the same time, the broader insurance industry is beginning to embrace blockchain. Lemonade, a major digital insurer, has launched the [Lemonade Crypto Climate Coalition](https://www.lemonade.com/blog/crypto-climate-coalition/), an initiative that uses blockchain technology to provide climate-related parametric insurance for subsistence farmers in emerging markets. This signals that even mainstream insurers are exploring smart contract-based models to reduce overhead, ensure transparency, and bring insurance to underserved populations.

Our project directly aligns with these trends. We use smart contracts not just for automation, but for built-in compliance. Specifically, we are implementing on-chain checks that prevent overextension of coverage by ensuring that liabilities can never exceed the vault’s collateral. We also plan to encode jurisdiction-specific regulatory rules as conditions within the contract—for example, limits on per-user coverage or region-specific triggers. These safeguards ensure responsible underwriting, transparency, and protection against systemic risk.

We are also committed to robust data and contract security. Flight delay triggers are powered by Acurast’s TEE-based oracle system, ensuring reliable and tamper-proof off-chain data delivery. Before mainnet launch, all contracts will undergo independent audits, and all payout logic will be fully transparent. While we’re still early, we believe that as the regulatory environment evolves, our architecture will position us to scale securely and compliantly—while helping define how real-world DeFi infrastructure can address tangible, global problems.

---

### Reviewer Comment:
> This seems like an interesting project, and the team appears experienced in the space. Their GTM plan will be especially important, not just for finding PMF but also for educating users/devs about the value of what they’re building. It's unclear how the team plans to onboard users and build early traction.

**Response:**

As a framework, our focus is enabling other developers to build vertical-specific parametric insurance products on top of us. We’re investing in clear documentation, starter kits, and community grants, and would love to collaborate with SCF on composability-focused hackathons to accelerate adoption.

On the DeFi side, we’ll offer a seamless way for users to earn real, sustainable yield on USDC by backing real-world risks. We plan to run incentivized test campaigns to bootstrap liquidity and demonstrate the viability of RWA-backed yield.

For distribution, we aim to build simple UX layers—like a Chrome extension for travelers—to make parametric coverage accessible. Our initial target users will be crypto-native individuals attending conferences like Devconnect and Devcon, where delay protection can be directly valuable and easily understood.

---

### Reviewer Comment:
> The integration of the vault standard, risk/hedge/controller logic, and Acurast TEE is logical and well-conceived.

**Response:**

Thank you — our goal is to ensure all insurance payouts and liquidations are driven by clear, reliable oracle data and a transparent, on-chain mechanism.

---

### Reviewer Comment:
> The need for flight delay insurance on Stellar is unclear and seems more like a proof of concept for Acurast rather than a viable platform proposition. This aspect may be challenging to justify to voters.

**Response:**

Thank you for the feedback. To clarify, this is not just a flight delay insurance product—it’s an open-source **framework** for building parametric insurance on Soroban. Flight delay is simply our first implementation to demonstrate the potential. Developers can use our system to launch their own insurance products across verticals like earthquake protection, cyberattack coverage, or rainfall-triggered crop insurance. As long as there's reliable oracle data, our framework can support it.

We chose Acurast because TEE-based infrastructure was the only trust-minimized method we found to bring Web2 data to Soroban. Existing oracles largely focus on price feeds or on-chain activity, which aren’t sufficient for event-driven insurance. Acurast offered a practical integration path, but the framework is not vendor-locked—we plan to explore and test other TEE and AVS-based solutions like Phala, Lit Protocol, and Eigenlayer as we grow and secure more runway.

Everything we learn through this process will be openly documented through articles and technical publications, so the community can build on top of our findings and avoid duplicating work. Our goal is to make reliable real-world data access a shared resource for the entire Soroban ecosystem.

All our oracle integrations and vault logic will be fully open-sourced, and we’re committed to documenting our learnings through articles and technical publications. We’re also actively working on vault standards and developer tooling to make building on top of our framework easy and composable. We welcome collaboration with SCF and look forward to supporting hackathons, grants, and developer onboarding to grow this ecosystem together.

---

### Reviewer Comment:
> The project's deliverables span six months, meaning the full project won't be visible for another year. It may be beneficial to split the idea into parts, focusing on the open-source reference or finding a platform proposition that resonates with crypto users and builders.

**Response:**

Thank you for the suggestion. We agree that splitting the project into parts is logical, and we’ve approached it that way—first building the open-source framework, then launching flight delay insurance as the first vertical. We chose flight delay because it’s a clear, data-rich use case that lets us showcase how parametric insurance can work end-to-end on Soroban with real oracle inputs.

However, if we stop after building just the framework, we won’t have a working product on mainnet to demonstrate traction or real-world usage. That limits the impact we can show during the Build phase. While the framework alone is valuable as a public good, we believe pairing it with a live vertical is critical to proving its potential, attracting builders, and giving the Soroban ecosystem something tangible and functional to rally around.

---

### Reviewer Comment:
> The team is strong, and the use-case is interesting, but the solution may be too niche to attract a broad audience.

**Response:**

Thank you for the feedback. While flight delay insurance is our initial use case, our project is fundamentally an open-source **framework** for building parametric insurance products on Soroban. This framework enables developers to create insurance solutions across various verticals, including earthquake protection, cyberattack coverage, and rainfall-triggered crop insurance, provided there is reliable oracle data.

Parametric insurance is experiencing significant growth, driven by the increasing frequency and severity of climate-related disasters. The global parametric insurance market was valued at **USD 16.2 billion in 2024** and is projected to reach **USD 51.3 billion by 2034**, growing at a **CAGR of 12.6%**. This growth underscores the expanding demand for innovative insurance solutions that offer rapid, transparent payouts based on predefined triggers.

Flight delay insurance, while serving as our initial demonstration, addresses a substantial market. The global airline industry serves billions of passengers annually, and flight disruptions are a common occurrence. By providing immediate compensation for delays, our solution offers tangible benefits to travelers, showcasing the practical applications of parametric insurance.

By launching with a real-world use case and providing a versatile framework, we aim to demonstrate the viability of parametric insurance on Soroban and encourage developers to build diverse insurance products that address various risks and industries.
