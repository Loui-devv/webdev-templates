# Web Dev Templates

Base template at mga variant para sa freelance web dev — landing pages para sa small businesses sa Pilipinas.

## Structure

- `base/template.html` — ang source of truth. Huwag babaguhin ito kada client.
- `variants/` — mga skin ng base template para sa specific na industriya (portfolio pieces).
- `assets/` — shared placeholder images/logos.

## Paano gumawa ng bagong bersyon para sa client

1. Kopyahin ang `base/template.html` papunta sa bagong folder (huwag sa `variants/` — gumawa ng `clients/[pangalan-ng-client]/`).
2. Baguhin lang ang mga `[...]` placeholder text.
3. I-adjust ang `:root { }` CSS variables sa taas para sa kulay ng brand.
4. Tanggalin ang mga section na hindi kailangan (hal. testimonials).
5. Palitan ang placeholder images ng totoong larawan.

## Stack

Plain HTML/CSS/JS lang — walang framework, walang build step. Puwedeng i-host sa GitHub Pages, Netlify, o kahit shared hosting.
