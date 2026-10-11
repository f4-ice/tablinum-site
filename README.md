# Tablinum website

The public pages for the Tablinum app: a short introduction, the privacy
policy and the support page. Plain HTML and CSS, no build step.

    index.html            home
    privacy/index.html    privacy policy   (the App Store's "Privacy Policy URL")
    support/index.html    support          (the App Store's "Support URL")
    assets/               the stylesheet, logo and icon

Published with GitHub Pages from the main branch, root folder. To look at the
pages before publishing, run this in the folder and open http://localhost:8000:

    python3 -m http.server
