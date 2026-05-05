# Tasks

## In Progress
- [ ] Home page slideshow — auto-cycling, clickable to advance
- [ ] Scroll detail page visual review — compare spacing/layout side-by-side with slowduststudio.com
- [ ] Move images into repo — Squarespace CDN URLs will eventually break

## Pre-launch Checklist (Slow Dust Studio v1)

### Content & copy
- [ ] All project titles spelled correctly
- [ ] Client names accurate (NDA / approval check)
- [ ] Homepage subhead correct ("Interior Design · Los Angeles")
- [ ] About bio reads well (if About is enabled)
- [ ] Contact intro reads well
- [ ] Email correct (katrina@slowduststudio.com)
- [ ] Instagram handle / URL correct
- [ ] 404 page copy ("Off the floor plan.")
- [ ] No placeholder text or test data anywhere

### Functional
- [ ] Each nav link goes to the right page
- [ ] Each project tile opens the correct project page
- [ ] All project images load (no broken WebPs)
- [ ] Prev / next chevrons cycle through projects
- [ ] Back-to-work button returns to category
- [ ] Hamburger drawer opens, closes; all drawer links work
- [ ] Active page highlighted in drawer
- [ ] Email link (mailto) opens correctly
- [ ] Instagram link opens in new tab
- [ ] Home slideshow auto-advances AND click-to-advance works
- [ ] Theme/accent color is correct (#7d6b5d)

### Cross-device
- [ ] iPhone Pro / notched, portrait
- [ ] iPhone Pro / notched, landscape (immersive treatment)
- [ ] Older iPhone (no notch), landscape
- [ ] iPad portrait
- [ ] iPad landscape (note: hover-only interactions don't trigger)
- [ ] Desktop Chrome
- [ ] Desktop Safari
- [ ] Desktop Firefox (verify :has() selector behavior)
- [ ] Android phone (Chrome)

### Performance
- [ ] Lighthouse on /, /#work, project page (90+ Perf, 95+ A11y)
- [ ] WebP images loading (Network tab content-type: image/webp)
- [ ] No .jpg requests in network tab
- [ ] Throttled "Fast 3G" first paint reasonable
- [ ] No layout shift on home during slideshow

### Visual / UX edge cases
- [ ] No horizontal scroll anywhere
- [ ] No images overflow their containers
- [ ] No text overlaps or clips on any breakpoint
- [ ] Slideshow images all preload, crossfade cleanly
- [ ] Typography readable at 90% / 100% / 125% / 150% zoom
- [ ] No console errors / warnings

### SEO & metadata
- [ ] Page title correct
- [ ] Meta description set
- [ ] OG image set (optional, nice for social previews)
- [ ] Favicon loads in browser tab
- [ ] allowIndexing: true in site.json
- [ ] robots.txt not blocking (GitHub Pages default is fine)

### Production environment
- [ ] Custom domain (slowduststudio.com) resolves
- [ ] HTTPS works (no mixed-content warnings)
- [ ] CNAME file references slowduststudio.com
- [ ] DNS records point to GitHub Pages

### Final pass
- [ ] Walk through every page on phone like a fresh visitor
- [ ] Test mailto actually delivers
- [ ] Compare against client expectations
- [ ] Tag this version: `git tag client-v1 && git push --tags`

## Backlog
- [ ] Image logo support — replace text brand name with uploaded image
- [ ] Fold Identity fields into Appearance tab (remove General tab) — studio.html cleanup
- [ ] Move splash + 404 config into Pages tab — studio.html cleanup

## Done
- [x] overlay-cover style — white wash clears on hover to reveal image; auto-applied to scroll categories; wired into studio
- [x] overlay-label style — title only, bottom-left, no play button
- [x] Contact intro text — configurable sentence above email; wired into studio
- [x] Instagram footer link — @slowdust_la fixed to bottom-right; pulled from site.json
- [x] Instagram icon on contact page — shown when about.social.instagram is set
- [x] Slow Dust Studio content — site.json + projects.json configured and deployed
- [x] Scroll view (type: 'scroll') — project detail page with 2-col image grid, prev/next nav
- [x] Gallery Images field in project editor — textarea for scroll-type projects
- [x] Home page feature — full-bleed bg image + video, headline, subhead, CTAs
- [x] Serif + sans font pickers with size scale sliders
- [x] Home bg image drop zone / uploader
- [x] Accent hex input — accept no-# prefix and 3-digit shorthand
- [x] Preview ↗ buttons on section titles
- [x] Home nav link when home page enabled
- [x] Tag v1.0.0
