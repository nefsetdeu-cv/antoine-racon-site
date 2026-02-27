# Antoine Racon — E-Commerce CV Store

A creative online CV built as an e-commerce product page.

## Quick Deploy to Netlify (easiest)

1. Install Node.js (https://nodejs.org — LTS version)
2. Open your terminal in this folder
3. Run: `npm install`
4. Run: `npm run build`
5. Go to https://app.netlify.com/drop
6. Drag the entire `build` folder onto the page
7. Done! You'll get a live URL instantly

## Connect Your Custom Domain

1. Buy a domain (e.g. antoineracon.com) on Namecheap, Google Domains, or Porkbun
2. In Netlify → Site Settings → Domain Management → Add custom domain
3. Follow the DNS instructions (usually just change nameservers)
4. SSL is automatic — your site will be live on https://yourdomain.com

## Local Development

```bash
npm install
npm start
```

Opens at http://localhost:3000

## Deploy to Vercel (alternative)

1. Push this folder to a GitHub repo
2. Go to https://vercel.com → Import Project → Select your repo
3. It auto-detects React and deploys
4. Connect your custom domain in Vercel dashboard
