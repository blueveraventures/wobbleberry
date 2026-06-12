WOBBLEBERRY WEBSITE FOLDER
==========================

WHAT IS IN HERE
- index.html ............ the complete website (single file, everything included)
- favicon.png ........... browser tab icon
- favicon.ico ........... legacy browser tab icon
- apple-touch-icon.png .. icon when saved to an iPhone home screen

DEPLOY TO VERCEL
1. Go to vercel.com and sign in
2. Add New > Project > deploy this whole Website folder (drag and drop)
3. Check the preview URL it gives you
4. Settings > Domains > add wobbleberry.com
5. Copy the two DNS records Vercel shows into your domain registrar
6. Add wobbleberrykids.com as a redirect to wobbleberry.com
7. Done. SSL is automatic.

UPDATING THE SITE LATER
Edit index.html in this folder, then drag the folder into Vercel again
(or connect the folder to GitHub for automatic deploys).

THREE PLACEHOLDERS STILL INSIDE index.html
1. VIDEO_ID ......... replace with the YouTube video ID (the text after
                      watch?v= in the video URL) so the song plays on the site
2. YOUR_FORM_ID ..... make a free form at formspree.io and paste its ID
                      to turn on the free coloring page email capture
3. STRIPE_LINKS ..... at the bottom of the file. When a product is ready,
                      create it in Stripe, make a Payment Link, paste the
                      link between the quotes. The Buy button turns on
                      automatically.

BRAND RULES FOR ANY FUTURE EDITS
Colors, characters, and voice live in:
02_Bible/WOBBLEBERRY-PROJECT-BRIEF.md
No dashes in site copy. Contact email is blueveraventures@gmail.com.
