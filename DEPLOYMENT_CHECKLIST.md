# Portfolio Deployment & Verification Checklist

## 1. Repository

- [x] Repository: `Kimiti4/Portfolio`
- [x] Default branch: `main`
- [x] GitHub Pages is enabled
- [x] Canonical Pages path: `https://kimiti4.github.io/Portfolio/`
- [ ] Confirm the latest `main` commit is the intended release

## 2. Content Integrity

- [x] Homepage presents Amos Kimiti as a Software & AI Systems Engineer
- [x] Tiannara is identified as the flagship private system
- [x] ASC and EFDI are presented as research tracks, not standalone repositories
- [x] Measurement Integrity is represented as an engineering/verification practice
- [x] Public repositories have explicit links
- [x] Private work is not represented with fabricated GitHub links
- [x] Historical IYF work remains available as supporting evidence
- [ ] Review every factual project claim against the underlying repository before major applications

## 3. Link Integrity

- [ ] Home navigation works on every page
- [ ] About navigation works on every page
- [ ] Systems navigation works on every page
- [ ] Contact navigation works on every page
- [ ] Public GitHub links resolve
- [ ] Live project links resolve
- [ ] Local Markdown documentation links resolve on GitHub and Pages as intended
- [ ] No `href="#"` placeholders remain
- [ ] No obsolete `iyf-s10-week-02-Kimiti4` portfolio URL remains

## 4. Responsive Verification

Test at minimum:

- [ ] 320px mobile
- [ ] 375px mobile
- [ ] 768px tablet
- [ ] 1024px desktop
- [ ] 1440px desktop
- [ ] 1920px desktop

Verify:

- [ ] Navigation opens/closes correctly
- [ ] No horizontal overflow
- [ ] Hero remains readable
- [ ] Cards stack cleanly
- [ ] Buttons remain usable
- [ ] Footer does not overflow
- [ ] Images preserve aspect ratio

## 5. Accessibility

- [ ] One meaningful `h1` per page
- [ ] Heading hierarchy is logical
- [ ] Navigation has an accessible label
- [ ] Current page uses `aria-current`
- [ ] Images have meaningful alt text
- [ ] Interactive elements are keyboard reachable
- [ ] Focus states are visible
- [ ] Text/background contrast is acceptable
- [ ] Reduced-motion preference is respected
- [ ] No information depends exclusively on color

## 6. Performance

- [ ] Run Lighthouse on Home, About, Systems and Contact
- [ ] Check for layout shift
- [ ] Check image dimensions and file sizes
- [ ] Confirm CSS loads without 404s
- [ ] Confirm external requests are intentional
- [ ] Re-run after any major visual change

## 7. Browser Verification

- [ ] Chromium / Chrome
- [ ] Edge
- [ ] Firefox
- [ ] Safari where available
- [ ] Android mobile browser

## 8. Deployment Verification

After pushing to `main`:

1. Wait for GitHub Pages deployment.
2. Open the canonical Pages URL.
3. Hard refresh.
4. Visit all four pages.
5. Test navigation and outbound links.
6. Inspect the browser console for errors.
7. Run Lighthouse again against the deployed URL.

## 9. Git Discipline

Use a focused commit for each coherent change. Before committing:

```bash
git status
git diff --check
git diff
```

Do not commit secrets, credentials, local machine paths or generated build artifacts unless intentionally required.

## 10. Maintenance

- Review project descriptions whenever the underlying system changes materially.
- Keep private/public boundaries explicit.
- Replace temporary links immediately when canonical URLs change.
- Preserve historical coursework as evidence, but keep it subordinate to current engineering work.
- Re-run accessibility, link and performance checks after significant redesigns.

## Release standard

The portfolio is ready for external use when:

- every visible claim is defensible;
- every important link resolves;
- the mobile and desktop layouts are stable;
- there are no placeholder destinations;
- accessibility and performance checks have been run on the deployed site; and
- private research is clearly distinguished from public code.
