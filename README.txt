THUSHAANTH BALA — PORTFOLIO WEBSITE
===================================

Files
  index.html              the whole site (styles + 3D animation built in)
  assets/thushaanth.png   profile photo
  .htaccess               settings for Apache/cPanel hosts (ignored elsewhere)
  robots.txt              lets search engines index the site
  netlify.toml            only used if you host on Netlify

No build step. Upload everything as-is.

A) cPanel hosting (GoDaddy, Namecheap, Hostinger, Bluehost …)
  1. Log in to cPanel → File Manager → open the folder  public_html
  2. Click Upload and upload this zip, then select it → Extract.
  3. Make sure index.html sits directly inside public_html
     (not inside a sub-folder). Move the files up if needed.
  4. Turn on hidden files (Settings → Show Hidden Files) to confirm .htaccess is there.
  5. Turn on the free SSL certificate (cPanel → SSL/TLS Status or "Let's Encrypt"),
     then open .htaccess and remove the # on the three "Force HTTPS" lines.

B) Netlify (free) with your own domain
  1. app.netlify.com → your site → Deploys → drag this folder in.
  2. Domain management → Add a domain → type your domain.
  3. At your domain registrar, set the DNS records Netlify shows you.
     HTTPS is switched on automatically.

To replace the photo, overwrite assets/thushaanth.png with a square image (same name).
