<p align="center">
<img src="https://www.kanha.ai/og-banner.png">
</p>

<h1 align="center">Kanha</h1>

<p align="center">
  <strong>Train AI chatbots on your website. Run them entirely on-device.</strong>
</p>

<p align="center">
  <a href="https://kanha.ai">Website</a> &middot;
  <a href="https://kanha.ai/docs">Docs</a> &middot;
  <a href="https://kanha.ai/showcase">Showcase</a> &middot;
  <a href="https://kanha.ai/pricing">Pricing</a> &middot;
  <a href="https://www.npmjs.com/package/kanha-ai">npm</a>
</p>

---

Kanha crawls your website, generates training data, fine-tunes a custom language model, and serves it directly in your visitors' browsers via WebGPU. No API calls per query. No per-token costs. No data leaves the device.

### How it works

1. **Crawl** — Point Kanha at your site. We index your pages, handling JavaScript-rendered content automatically.
2. **Train** — We generate question-answer pairs from your content and fine-tune a compact model tailored to your site.
3. **Deploy** — Drop in a script tag, Web Component, or React component. The model loads and runs on-device via WebGPU.

### Integrate in one line

```html
<script type="module" src="https://cdn.jsdelivr.net/npm/kanha/dist/widget.js"></script>
<kanha-bot embed-key="your-bot-key"></kanha-bot>
```

Or with React:

```tsx
import { KanhaBot } from 'kanha';

<KanhaBot embedKey="your-bot-key" />
```

### Links

- [Documentation](https://kanha.ai/docs) — Sites, datasets, training, SDK integration
- [Showcase](https://kanha.ai/showcase) — Live demo bots
- [Careers](https://kanha.ai/careers) — We're hiring

---

<p align="center">
  <sub>Built by <a href="https://kanha.ai/careers">a small team</a> that believes AI should run where the user is.</sub>
</p>
