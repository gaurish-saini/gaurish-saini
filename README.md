<p align="center">
  <a href="https://gaurishsaini.hashnode.dev/" title="Read Systems Behind the Interface">
    <img src="./assets/profile-header.png" alt="Systems Behind the Interface, my engineering case studies" width="100%" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/gaurish-prakhar-saini/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect with Gaurish on LinkedIn" /></a>
  <a href="https://gaurishsaini.hashnode.dev/"><img src="https://img.shields.io/badge/Hashnode-Read-2962FF?style=for-the-badge&logo=hashnode&logoColor=white" alt="Read Gaurish's technical case studies on Hashnode" /></a>
  <a href="https://x.com/SainiGaurish"><img src="https://img.shields.io/badge/X-Follow-111827?style=for-the-badge&logo=x&logoColor=white" alt="Follow Gaurish on X" /></a>
  <a href="mailto:gaurishprakhar@gmail.com"><img src="https://img.shields.io/badge/Email-Say_Hello-0F766E?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Gaurish" /></a>
</p>

## Frontend & product engineering

I’m Gaurish. I build web applications with **React, TypeScript, and Node.js**. My work has ranged from analytics dashboards in React and D3 to a Next.js marketplace for vehicle discovery, bookings, and payments. I like owning a feature across the UI and API, especially when a request can fail halfway through or a user’s permissions can change between visits.

At Anatta, I build customer account and B2B workflows and the tools we use to ship them. I worked with UI architects to move a **74-route storefront to Remix 2 and Vite**. We released it in stages, checked account and checkout behavior, and rehearsed rollback. I also expanded our pull-request previews so QA could test the intended revision against the right storefront and data.

## Engineering notes from production

- **[Customer identity migration](https://gaurishsaini.hashnode.dev/shopify-customer-accounts-migration-headless-storefront)** — how we kept accounts and carts in sync when OAuth refreshed a session during a redirect.
- **[Pull-request previews on Fly.io](https://gaurishsaini.hashnode.dev/pr-previews-flyio-domains-data-profiles)** — how a reviewer’s preview URL resolves to the code, domain, and data profile they intend to test.
- **[Checkout-safe cart flows](https://gaurishsaini.hashnode.dev/checkout-safe-cart-flows-headless-shopify)** — which edits can be replayed after a cart expires and why checkout waits until the correct buyer identity is in place.

## Independent work

In my **[conversational AI CLI](https://github.com/gaurish-saini/agents-v2)**, I implemented approval controls for file tools, cancellation, and timeouts. The [multi-turn evaluations](https://github.com/gaurish-saini/agents-v2/tree/master/evals) run the same agent loop as the CLI with deterministic test tools. They check tool selection and call order, including cases where a tool should stay unused.

I’m also developing an environmental monitoring product with **React, TypeScript, Go, and PostgreSQL**.
