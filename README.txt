SHADOWGRID WEBSITE: HOW TO PUBLISH AND EDIT
============================================

FILES
-----
index.html      Home page
about.html      About page
articles.html   List of articles
book.html       Appointment page (opens your email app)
articles/       One file per article
css/style.css   Colours, fonts and layout
js/site.js      Copy buttons and the appointment form
images/         Your photos
sitemap.xml     List of pages for Google
robots.txt      Tells Google it may read the site

1) PUBLISH FOR FREE
-------------------
Pick ONE free host. Each gives a free address (subdomain) with HTTPS:
  - Cloudflare Pages  -> yourname.pages.dev
  - Netlify           -> yourname.netlify.app
  - GitHub Pages      -> username.github.io
Create a free account, create a new site, and upload this whole folder
(or the zip). Choose the site name you want, for example "shadowgrid".

2) CHANGE THE WEB ADDRESS IN THE FILES
--------------------------------------
The files currently assume the address:
  https://shaikhishammi-boop.github.io
If your final address is different, use "Find and replace" in a text editor
(for example VS Code or Notepad++) to replace it everywhere, in all files,
including sitemap.xml and robots.txt. Then upload the files again.

3) SHOW UP ON GOOGLE
--------------------
  a. Open Google Search Console (search.google.com/search-console) and sign in.
  b. Add your site address as a property and verify it with the method shown.
  c. In "Sitemaps", enter:  sitemap.xml  and submit.
  d. Use "URL inspection" on your home page and click "Request indexing".
Google can take days or weeks to list a new site. Add articles regularly.

4) EDIT THE SITE LATER
----------------------
All text is plain HTML. Open a file in any text editor and change the words
between the tags, for example between <p> and </p>.
  - Email address: search for shaikhishammi@gmail.com (in js/site.js, book.html and the footer of every page).
  - Appointment time options: in book.html, find the "time" select.
  - New article: copy one file in articles/, change the title, description
    and text, then add it to articles.html and to sitemap.xml.
  - Photo: replace the files in images/ with the same file names.
Or send your changes to Claude and ask for updated files.

5) OWN DOMAIN LATER (OPTIONAL)
------------------------------
A .com domain costs about 10 USD per year from a domain registrar. Your host
(Cloudflare, Netlify or GitHub) has a "Custom domain" setting that connects it.
Then repeat step 2 with the new address.
