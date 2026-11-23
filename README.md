# Bori 3D Print & Design website

The landing page for Bori 3D Print & Design: custom 3D printed parts, organizers, mounts and figures, designed in Fusion 360 and printed in-house.

It is a single static page (`index.html`) with its photos in `images/`. There is no build step.

## Going live on GitHub Pages

1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment**, pick **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
3. After a minute or two the site is at `https://787boridesign-hub.github.io/b3dpd-website/`.

A custom domain can be added later on the same settings page.

## Still to do

- **Quote form:** it sends to bori@b3dpd.com through [FormSubmit](https://formsubmit.co) (free, no account). The very first submission triggers a one-time "Activate Form" email to that inbox; click the button in it, and every request after that arrives as a normal email. The address is set in `QUOTE_ENDPOINT` near the bottom of `index.html`.
- **Logo:** the header logo art currently reads "BORI Print & 3D Design". Swap in the reworded copy at `images/bori-logo-lockup-3dpd.png` when it is ready.
