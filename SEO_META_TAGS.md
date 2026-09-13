# SEO Meta Tags Reference — personal-portfolio-001

## Essential Meta Tags (add to index.html <head>)

```html
<!-- Primary Meta Tags -->
<title>Personal Portfolio 001 - Your Money, Moving Smarter</title>
<meta name="title" content="Personal Portfolio 001 - Your Money, Moving Smarter" />
<meta
  name="description"
  content="Modern financial technology with transparent fees, fast applications, and bank-grade security — built to earn trust."
/>
<meta
  name="keywords"
  content="fintech, financial services, digital banking, secure payments, transparent fees"
/>
<meta name="robots" content="index, follow" />
<meta name="language" content="English" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<link rel="canonical" href="https://www.personal-portfolio-001.com" />

<!-- Open Graph / Facebook -->
<meta property="og:type" content="website" />
<meta property="og:url" content="https://www.personal-portfolio-001.com" />
<meta property="og:title" content="Personal Portfolio 001 - Your Money, Moving Smarter" />
<meta
  property="og:description"
  content="Transparent, secure, and effortless — the fintech experience customers want."
/>
<meta property="og:image" content="https://www.personal-portfolio-001.com/og-image.jpg" />

<!-- Twitter Card -->
<meta property="twitter:card" content="summary_large_image" />
<meta property="twitter:url" content="https://www.personal-portfolio-001.com" />
<meta property="twitter:title" content="Personal Portfolio 001 - Your Money, Moving Smarter" />
<meta
  property="twitter:description"
  content="Transparent, secure, and effortless — the fintech experience customers want."
/>
<meta property="twitter:image" content="https://www.personal-portfolio-001.com/twitter-image.jpg" />

<!-- JSON-LD Structured Data -->
<script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Organization",
    "name": "Personal Portfolio 001",
    "url": "https://www.personal-portfolio-001.com",
    "description": "Transparent, secure, and effortless — the fintech experience customers want.",
    "foundingDate": "2026",
    "contactPoint": {
      "@type": "ContactPoint",
      "contactType": "customer service",
      "availableLanguage": ["English", "Urdu"]
    },
    "sameAs": [
      "https://www.facebook.com/personal-portfolio-001",
      "https://www.instagram.com/personal-portfolio-001",
      "https://twitter.com/personal-portfolio-001"
    ]
  }
</script>
```

## Multilingual (hreflang) — Add if i18n enabled

```html
<link rel="alternate" hreflang="en" href="https://www.personal-portfolio-001.com/" />
<link rel="alternate" hreflang="ur" href="https://www.personal-portfolio-001.com/ur/" />
<link rel="alternate" hreflang="ar" href="https://www.personal-portfolio-001.com/ar/" />
<link rel="alternate" hreflang="x-default" href="https://www.personal-portfolio-001.com/" />
```

## PWA Meta Tags — Add if PWA enabled

```html
<link rel="manifest" href="/manifest.json" />
<meta name="theme-color" content="#0d9488" />
<meta name="apple-mobile-web-app-capable" content="yes" />
<meta name="apple-mobile-web-app-status-bar-style" content="default" />
<meta name="apple-mobile-web-app-title" content="Personal Portfolio 001" />
```
