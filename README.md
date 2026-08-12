# Kalamitra AI Photoshoot

**Status:** frontend prototype · local demo

A React/Vite product-workflow concept for Indian artisans: upload a product photo, generate a styled scene with Gemini, draft listing copy, and preview a simple storefront flow.

## Product flow

1. Upload an original product image and confirm consent.
2. Choose a photoshoot mode and generate an edited scene.
3. Produce listing content from the product context.
4. Review buyer-copilot and storefront previews.

## Quick start

```bash
npm install
printf 'GEMINI_API_KEY=your_key_here\n' > .env.local
npm run dev
```

`npm run build` performs the available production build check.

## Boundaries

Login, analytics, pricing, social sharing, and storefront behaviour are prototype UI flows rather than verified production integrations. Generated images and copy require human review; the repository does not establish customer usage or commercial performance.

## Limitations

There is no automated test suite, production authentication, durable backend, or verified hosted deployment.
