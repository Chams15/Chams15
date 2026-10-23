<!--
  ============================================================================
  PROFILE README - TEMPLATE
  ============================================================================
  This repo generates a dynamic GitHub profile README using a Cloudflare Worker.
  Replace every YOUR_... placeholder below, then deploy your Worker.

  YOUR_WORKER_URL        -> your deployed Worker URL
                          (e.g. https://your-profile-readme.YOUR_SUBDOMAIN.workers.dev)
  YOUR_GITHUB_USERNAME   -> your GitHub username
  YOUR_RESUME_FILENAME   -> your resume file inside /files (e.g. YourName-Resume.pdf)
  YOUR_WEBSITE_URL       -> your personal website
  YOUR_LINKEDIN_URL      -> your LinkedIn profile
  YOUR_FACEBOOK_URL      -> your Facebook profile
  YOUR_INSTAGRAM_URL     -> your Instagram profile
  YOUR_TWITTER_URL       -> your X/Twitter profile
  YOUR_NAME              -> your name (used in alt text)
  YOUR_TAGLINE           -> a short tagline about you
  ============================================================================
-->


<picture>
  <source media="(prefers-color-scheme: dark)" srcset="YOUR_WORKER_URL/?section=top&theme=dark">
  <img src="YOUR_WORKER_URL/?section=top&theme=light" width="100%" height="20" align="left">
</picture>
<img src="data:null;," width="100%" height="0" align="left" alt="">
<a target="_blank" href="https://github.com/YOUR_GITHUB_USERNAME/YOUR_GITHUB_USERNAME/blob/main/files/YOUR_RESUME_FILENAME?raw=true">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="YOUR_WORKER_URL/?section=link-resume&theme=dark" label="Visit">
    <img src="YOUR_WORKER_URL/?section=link-resume&theme=light&i=0" alt="YOUR_NAME's Resume" width="100" height="18px" align="left">
  </picture>
</a>
<img src="data:null;," width="100%" height="0" align="left" alt="">
<a target="_blank" href="YOUR_WEBSITE_URL">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="YOUR_WORKER_URL/?section=link-website&theme=dark" label="Visit">
    <img src="YOUR_WORKER_URL/?section=link-website&theme=light&i=0" alt="visit my website" width="100" height="18px" align="left">
  </picture>
</a>
<img src="data:null;," width="100%" height="0" align="left" alt="">
<a target="_blank" href="YOUR_LINKEDIN_URL">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="YOUR_WORKER_URL/?section=link-linkedin&theme=dark" label="Visit">
    <img src="YOUR_WORKER_URL/?section=link-linkedin&theme=light&i=0" alt="visit my linkedin" width="100" height="18px" align="left">
  </picture>
</a>
<img src="data:null;," width="100%" height="0" align="left" alt="">
<a target="_blank" href="YOUR_FACEBOOK_URL">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="YOUR_WORKER_URL/?section=link-facebook&theme=dark">
    <img src="YOUR_WORKER_URL/?section=link-facebook&theme=light&i=1" alt="visit my Facebook" width="100" height="18" align="left">
  </picture>
</a>
<img src="data:null;," width="100%" height="0" align="left" alt="">
<a target="_blank" href="YOUR_INSTAGRAM_URL">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="YOUR_WORKER_URL/?section=link-instagram&theme=dark">
    <img src="YOUR_WORKER_URL/?section=link-instagram&theme=light&i=2" alt="visit my Instagram" width="100" height="18" align="left">
  </picture>
</a>
<img src="data:null;," width="100%" height="0" align="left" alt="">
<a target="_blank" href="YOUR_TWITTER_URL">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="YOUR_WORKER_URL/?section=link-twitter&theme=dark">
    <img src="YOUR_WORKER_URL/?section=link-twitter&theme=light&i=1" alt="visit my Twitter/X profile" width="100" height="18" align="left">
  </picture>
</a>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="YOUR_WORKER_URL/?section=fallback&theme=dark">
  <img src="YOUR_WORKER_URL/?section=fallback&theme=light" alt="" width="420" align="left">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="YOUR_WORKER_URL/?section=main&theme=dark">
  <img src="YOUR_WORKER_URL/?section=main&theme=light" alt="Hello, World. I am YOUR_NAME. YOUR_TAGLINE." width="100%" height="310" align="left">
</picture>