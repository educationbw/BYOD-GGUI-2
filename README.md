# SchoolsOfEasternNevada.github.io

Thank you for using G.GUI!

This repository hosts the website for SchoolsOfEasternNevada. The site can be hosted using GitHub Pages or deployed instantly using services like Vercel or Netlify.

---

## Table of Contents

- [Website](#Website)
- [Deployment (Vercel / Netlify)](#Deployment)
- [Running Locally](#RunLocally)
- [Custom Domains With GitHub Pages](#GithubPages)
---

## Website

Visit the website for this repository at:

https://schoolsofeasternnevada.github.io

This website contains tools and proxies that can access websites through the interface.

Use these tools appropriately and follow your network or school rules.

---


## Deployment

This section explains how to deploy your BYOD site using hosting services

If you choose to deploy to a hosting service, fork this repository, and use it in the listed steps below.

### Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)

Steps:

1. Click the button
2. Sign into Vercel
3. Import this repository
4. Click Deploy

Vercel will automatically build and host the website.

---

### Deploy to Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start)

Steps:

1. Click the button
2. Sign into Netlify
3. Select the repository
4. Click Deploy

Netlify will automatically host the website.

---

### Other hosting services

We can't list all of the hosting services here, so here is a general guide on how to deploy using a hosting serice:

1. Find out if you can import the repository directly for from Github
   - If your answer is yes, continue with the "A" steps below
    -  If your answer is no, continue with the "B" steps below

2A. Choose the forked repository you want to host
-
2B. Download the source code for G.GUI through Github
-
3A. Deploy the website - YOUR DONE
-
3B. Fix any folder structure issues, and add any required files that hosting service requires
-
4B. Deploy the website - YOUR DONE

# RunLocally

To run the website on your computer:

Clone the repository:

git clone https://github.com/SchoolsOfEasternNevada/SchoolsOfEasternNevada.github.io

Open the project folder:

cd SchoolsOfEasternNevada.github.io

Open index.html in your browser.

You can also start a local server.

Example using Python:

python -m http.server 8000

Then visit:

http://localhost:8000

---

# GithubPages 

You can host G.GUI on github pages by:

->Forking this repository
Settings > Pages > Select Main and Root and click Save

You can connect your own domain (for example example.com) to your GitHub Pages site.

### Step 1 — Buy a Domain, Or get a free one

Purchase a domain from a registrar such as:

- Namecheap
- GoDaddy
- Google Domains
- Cloudflare

Or claim free subdomains from [FreeDNS](https://freedns.afraid.org/) or other services

Example domain:

example.com

---

### Step 2 — Add the Domain to GitHub

1. Open the repository on GitHub
2. Click Settings
3. Click Pages
4. Find the Custom Domain section
5. Enter your domain

Example:

www.example.com

GitHub will create a file named:

CNAME

inside the repository.

---

### Step 3 — Configure DNS

Now go to your domain provider and configure DNS.

If you are using a root domain:

Add these A records:

185.199.108.153  
185.199.109.153  
185.199.110.153  
185.199.111.153  

If you are using a subdomain (recommended):

Create a CNAME record:

www → yourusername.github.io

Example:

www → schoolsofeasternnevada.github.io

---

### Step 4 — Wait for DNS

DNS changes usually take between:

5 minutes to 24 hours

After propagation finishes your website will load from your custom domain.

Example:

https://www.example.com

---


© 2026 G.GUI Project - BYOD Guide
