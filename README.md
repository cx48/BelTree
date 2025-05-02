### BelTree

***A clean and elegant Linktree alternative that offers customizable links and a user-friendly design***

Powered by [Zola](https://getzola.org/). Styled with Tailwind CSS & Font Awesome.

> “Bel” in French means beautiful — this is your Beautiful Linktree!

## Preview

[BelTree](https://cx48.github.io/BelTree/) can be deployed for free using GitHub Pages or Vercel

### Mobile View

#### Deep Ocean | Mint Fresh | Sunset

<img src="https://raw.githubusercontent.com/cx48/BelTree/refs/heads/main/static/screenshots/mobile-deep-ocean.png" alt="BelTree Mobile View | Deep Ocean" style="max-width: 400px; height: 800px;"> &nbsp; <img src="https://raw.githubusercontent.com/cx48/BelTree/refs/heads/main/static/screenshots/mobile-mint-fresh.png" alt="BelTree Mobile View | Mint Fresh" style="max-width: 400px; height: 800px;"> &nbsp; <img src="https://raw.githubusercontent.com/cx48/BelTree/refs/heads/main/static/screenshots/mobile-sunset.png" alt="BelTree Mobile View | Sunset" style="max-width: 400px; height: 800px;">

### Desktop View

#### Deep Ocean

![BelTree Desktop View | Deep Ocean](https://raw.githubusercontent.com/cx48/BelTree/refs/heads/main/static/screenshots/desktop-deep-ocean.png)

#### Mint Fresh

![BelTree Desktop View | Mint Fresh](https://raw.githubusercontent.com/cx48/BelTree/refs/heads/main/static/screenshots/desktop-mint-fresh.png)

#### Sunset

![BelTree Desktop View | Sunset](https://raw.githubusercontent.com/cx48/BelTree/refs/heads/main/static/screenshots/desktop-sunset.png)

## Quick Start

1. **Install Zola**: [https://getzola.org/documentation/getting-started/installation/](https://getzola.org/documentation/getting-started/installation/) 

2. **Clone repository**:
   ```bash
   git clone https://github.com/cx48/BelTree
   cd BelTree
   ```

3. **Serve locally**:
   ```bash
   zola serve
   ```

   After making necessary changes to HTML files present under `partials/` visit [http://127.0.0.1:1111](http://127.0.0.1:1111)

4. **Build static site**:
   ```bash
   zola build
   ```
   All files output to `/public`

## Deployment Guide

> Deploy to GitHub Pages

1. Run Zola build:
   ```bash
   zola build
   ```

2. Commit and push the contents of the `public/` folder to your `gh-pages` branch

3. In GitHub repo settings, enable Pages from the `/public` folder or `gh-pages` branch

4. Your site will be live at `https://yourusername.github.io/BelTree/`

> Deploy to Vercel

1. Login to [Vercel](https://vercel.com) and import your GitHub repo

2. Set **Build Command** to:
   ```bash
   zola build
   ```

3. Set **Output Directory** to:
   ```bash
   public
   ```
   
4. Set **Framework Preset** to `Other`

5. Click **Deploy**

Zola will build and serve from the `public/` folder automatically on every push

## Customization Guide will be added soon!


## Get in Touch

Have feedback, questions, or just want to say hello?  
Feel free to [open an issue](https://github.com/cx48/BelTree/issues) or reach out directly:

> Check my GitHub profile for contact links
