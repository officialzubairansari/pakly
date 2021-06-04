# PAKLY
Pakly is a FREE and custom URL shortener.

# DEMO
pakly.netlify.app
(Site will redirect to https://github.com/officialzubairansari)

pakly.netlify.app/pakly
(Site will redirect to https://github.com/officialzubairansari/pakly)

# Create Your Own
How to Create Your Own Private URL Shortener for Free
Your Own – Your domain, your branding, not using a service like goo.gl or bit.ly

Private – You decide which URLs to be added, what should be the “shortened URL”

Free – Yes, absolutely 100{a8d0fabefeccbf1d125e3e25c91db392f6d8308bcafe6010e3a2ab0b301c1f15} free

What you’ll need
Domain name (even a subdomain is enough)
GitHub account
Netlify account (free plan)
How it Works
Netlify is a free (freemium) static hosting website which is super fast. One of their features, “redirects” helps to decide on a request, where it should be redirected. We’ll tell them if its “/abc”, redirect to “www.something.com”. Netlify just need these URLs in a file called _redrects

What is the role of GitHub here?
Our _redirects file will be held in GitHub, whenever we need to add/remove a URL we’ll edit that file. Netlify has great integrations with GitHub and GitLab. Whenever there is a change in that file, Netlify will pull that file and deploy it.

Let’s do it – The Hard Way
(scroll down for an easy method)

Step 1

Create a new repo in GitHub, and create a new file _redirects in the root directory. Paste the following code. Edit the URLs as you wish

Step 2

Create a new site in Netlify, select your git provider and choose the repo that you’ve created just above. Netlify will pull your repo and deploy it in a few seconds


Step 3

Connect your domain by going to Site Settings -> Domain Management


Let’s do it – The Easy Way
Fork my repo https://github.com/officialzubairansari/pakly and click on “Deploy to Netlify”


Done!
So you’ve built your own URL shortener in just 3 steps. Whenever you need to add a URL, just edit that file directly in GitHub. It will be deployed by Netlify in a few seconds!
