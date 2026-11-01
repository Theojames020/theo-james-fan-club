THEO JAMES FAN CLUB — CMS-READY WEBSITE STARTER

Included:
- index.html: public black-and-gold fan website
- admin/index.html: Decap CMS owner dashboard entry point
- admin/config.yml: editable Fan Updates collection
- content/news.json: news content shown on the public homepage
- uploads/: create this folder for uploaded images (CMS can create it when publishing)

IMPORTANT STATUS
This is a prepared website package, NOT a live published website yet.
No domain has been purchased, no hosting account has been connected, and no owner login has been created.
Do not share passwords, recovery codes, or payment details in chat.

PUBLISHING PLAN (Netlify + GitHub + Decap CMS)
1. With help from a parent/guardian where required, create/sign in to your GitHub and Netlify accounts.
2. Create a GitHub repository named: theo-james-fan-club
3. Upload all files and folders in this package to the repository root.
4. In admin/config.yml, the GitHub repository is preconfigured for the username theojames020.
5. In Netlify, choose Add new project > Import an existing project, connect GitHub, select theo-james-fan-club, then publish.
6. Configure Decap CMS authentication. The config currently uses the GitHub backend. This requires an OAuth authentication provider/server configured for Decap CMS and a GitHub account with write access to the repository. Follow current Decap CMS GitHub-backend documentation:
   https://decapcms.org/docs/github-backend/
   Decap Turbo is another hosted backend option described by Decap.
7. Once the site is deployed and authentication is configured, visit:
   https://YOUR-NETLIFY-SITE.netlify.app/admin/
   Sign in using the configured owner account. Keep registration restricted to invited editors only.
8. In the owner dashboard, open Fan Updates to add, edit, and publish announcements. Published updates appear on the public homepage after the Netlify build completes.
9. To add a custom domain, use Netlify Project overview > Domain management > Add a domain. Register the domain first; domain registration is usually a paid yearly service. Check availability and renewal cost before buying.

DOMAIN IDEA
theojamesfanclub.com is only a suggested name. Availability and trademark/brand permissions have not been checked. Use a clearly independent fan-site identity.

COMMUNITY BOARD
The sample fan message board on the homepage is a browser-local demo only; it is not a shared online forum. A real shared community needs a separate hosted database and moderation controls. Do not publish a public board without spam protection and moderation.

SECURITY
- Never put passwords, access tokens, or API keys in website files.
- Use invite-only access for the owner dashboard.
- Do not impersonate Theo James or suggest this is his official site.
- Use only photos and media you have permission to publish.
