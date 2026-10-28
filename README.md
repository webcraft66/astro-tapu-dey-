# AstroTapudey Website

A static website (no build step). Everything is in `index.html`.

## Open it locally
Double-click `index.html`. (Needs internet for the 3D hero, which loads Three.js from cdnjs.)

## What to edit (open index.html in any text editor)
- **Phone / WhatsApp**: search for `917002692683` and `70026 92683`, replace with the confirmed number.
- **Services, prices**: find `const CFG=` near the bottom (services, plans).
- **Testimonials**: find `const TESTIMONIALS=[` and add `{name:"First name",text:"Their own words"}`. Add only genuine feedback with the person's permission.
- **YouTube video**: find `const YT_ID=` and change the video ID. Channel link: search `youtube.com/@astrotapudey`.
- **Syllabus / batch info**: search `Course Outline` in the Academy section.
- **Photos**: images are embedded in the file. Replace by editing the `data:image/jpeg;base64` values, or move to an `images/` folder and use normal `src="images/photo.jpg"` paths.

## Deploy free on Vercel
1. Create a GitHub account, then a new repository (e.g. `astrotapudey`).
2. Upload `index.html` and `README.md` to the repository (Add file -> Upload files -> Commit).
3. Go to vercel.com, sign in with GitHub, click **Add New -> Project**, import the repository.
4. Framework Preset: **Other**. Leave Build Command and Output Directory empty. Click **Deploy**.
5. Every future change committed to GitHub redeploys automatically.

## Connect the client's own domain
1. Buy a domain from any registrar.
2. In Vercel: Project -> Settings -> Domains -> add the domain.
3. At the registrar's DNS settings add what Vercel shows (usually an **A record** `76.76.21.21` for the root domain and a **CNAME** `cname.vercel-dns.com` for `www`).
4. Wait for DNS to update (minutes to a few hours). Vercel adds HTTPS automatically.

## Important limits
- The enquiry form and all booking buttons open WhatsApp with a pre-filled message. Nothing is stored or emailed by the site.
- Real form delivery (email/database), online payments and appointment scheduling need separate integrations (for example a form service, a payment gateway, a booking tool).
- Do not mark a consultation as booked until the astrologer confirms it.

## To confirm with the astrologer
Main WhatsApp number (channel description shows a different one), Sar Vigyan details, final syllabus, batch dates and timings, genuine testimonials with permission, original high-resolution photos, final approved logo.
