# https://drukarnia.com.ua/articles/shpargalka-po-javascript-symbol-am-y4C93

Report created at 7/7/2024

## Test environment

- Browser: Mozilla/5.0 (iPad; CPU OS 12_2 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/17.4 Mobile/15E148 Safari/604.1
- Resolution: 834x1194

![Full page screenshot](screenshots/1-0.jpg)

## Compliance with standards

Not satisfy the requirements for:

- [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf)
- [WCAG 2.0 Level A](https://www.w3.org/TR/WCAG20/)
- [WCAG 2.0 Level AA](https://www.w3.org/TR/WCAG20/)

## Violations

### ARIA commands must have an accessible name

Ensures every ARIA button, link and menuitem has an accessible name

Impact: **serious**

Required to satisfy [WCAG 2.0 Level A](https://www.w3.org/TR/WCAG20/), [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf)

Need to fix one of the following issues:

- Element does not have text that is visible to screen readers.
- aria-label attribute does not exist or is empty.
- aria-labelledby attribute does not exist, references elements that do not exist or references elements that are empty.
- Element has no title attribute.

Affected elements:

- `#headlessui-popover-button-395020`

	![screenshot](screenshots/2-0.jpg)
- `#headlessui-menu-button-395025`

	

### Elements must only use permitted ARIA attributes

Ensures ARIA attributes are not prohibited for an element&#039;s role

Impact: **serious**

Required to satisfy [WCAG 2.0 Level A](https://www.w3.org/TR/WCAG20/), [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf)

Need to fix all the following issues:

- aria-label attribute cannot be used on a div with no valid role attribute..

Affected elements:

- `:root`

	![screenshot](screenshots/4-0.jpg)

### Buttons must have discernible text

Ensures buttons have discernible text

Impact: **critical**

Required to satisfy [WCAG 2.0 Level A](https://www.w3.org/TR/WCAG20/), [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf)

Need to fix one of the following issues:

- Element does not have inner text that is visible to screen readers.
- aria-label attribute does not exist or is empty.
- aria-labelledby attribute does not exist, references elements that do not exist or references elements that are empty.
- Element has no title attribute.
- Element&#039;s default semantics were not overridden with role=&quot;none&quot; or role=&quot;presentation&quot;.

Affected elements:

- `.text-base`

	![screenshot](screenshots/5-0.jpg), ![screenshot](screenshots/5-1.jpg)
- `#headlessui-popover-button-395020 > button`

	![screenshot](screenshots/6-0.jpg)
- `.hover\:bg-primary-50.dark\:hover\:bg-primary-800`

	![screenshot](screenshots/7-0.jpg), ![screenshot](screenshots/7-1.jpg), ![screenshot](screenshots/7-2.jpg), ![screenshot](screenshots/7-3.jpg), ![screenshot](screenshots/7-4.jpg), ![screenshot](screenshots/7-5.jpg), ![screenshot](screenshots/7-6.jpg), ![screenshot](screenshots/7-7.jpg), ![screenshot](screenshots/7-8.jpg), ![screenshot](screenshots/7-9.jpg), ![screenshot](screenshots/7-10.jpg), ![screenshot](screenshots/7-11.jpg), ![screenshot](screenshots/7-12.jpg)

### Elements must meet minimum color contrast ratio thresholds

Ensures the contrast between foreground and background colors meets WCAG 2 AA minimum contrast ratio thresholds

Impact: **serious**

Required to satisfy [WCAG 2.0 Level AA](https://www.w3.org/TR/WCAG20/), [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf)

Need to fix one of the following issues:

- Element has insufficient color contrast of 4.33 (foreground color: #64748b, background color: #edf6f6, font size: 12.0pt (16px), font weight: normal). Expected contrast ratio of 4.5:1.

Affected elements:

- `.mt-4 > .profile.rounded-2xl.bg-brand-light > .profile-info-container.border-b.text-center > .profile-info.justify-center.flex-col > div > .text-gray-500.dark\:text-gray-400`

	![screenshot](screenshots/8-0.jpg)

Need to fix one of the following issues:

- Element has insufficient color contrast of 4.33 (foreground color: #64748b, background color: #edf6f6, font size: 10.5pt (14px), font weight: normal). Expected contrast ratio of 4.5:1.

Affected elements:

- `.mt-4 > .profile.rounded-2xl.bg-brand-light > .profile-info-container.border-b.text-center > .profile-info.justify-center.flex-col > div > .profile-stats.my-6.max-w-xs > .mr-6.flex-col[title="5264"] > .font-semibold.text-gray-500.dark\:text-gray-400`

	![screenshot](screenshots/9-0.jpg)
- `.mt-4 > .profile.rounded-2xl.bg-brand-light > .profile-info-container.border-b.text-center > .profile-info.justify-center.flex-col > div > .profile-stats.my-6.max-w-xs > .border-x.border-gray-300.px-6 > .font-semibold.text-gray-500.dark\:text-gray-400`

	![screenshot](screenshots/10-0.jpg)
- `.mt-4 > .profile.rounded-2xl.bg-brand-light > .profile-info-container.border-b.text-center > .profile-info.justify-center.flex-col > div > .profile-stats.my-6.max-w-xs > .ml-6.text-inherit.flex-col > .font-semibold.text-gray-500.dark\:text-gray-400`

	![screenshot](screenshots/11-0.jpg)
- `.mt-4 > .profile.rounded-2xl.bg-brand-light > .m-3.gap-x-16.gap-y-2 > .gap-1.text-gray-500.dark\:text-gray-400`

	![screenshot](screenshots/12-0.jpg)

Need to fix one of the following issues:

- Element has insufficient color contrast of 3.29 (foreground color: #34988e, background color: #f3faf9, font size: 9.0pt (12px), font weight: normal). Expected contrast ratio of 4.5:1.

Affected elements:

- `section[aria-labelledby="semantic-section-846244"] > .hover\:bg-white.dark\:hover\:bg-gray-900[href$="dostupnist"] > .px-1\.5.py-0\.5.bg-primary-50`

	![screenshot](screenshots/13-0.jpg)
- `section[aria-labelledby="semantic-section-846245"] > .hover\:bg-white.dark\:hover\:bg-gray-900[href$="ui-ux"] > .px-1\.5.py-0\.5.bg-primary-50`

	![screenshot](screenshots/14-0.jpg)
- `section[aria-labelledby="semantic-section-846246"] > .hover\:bg-white.dark\:hover\:bg-gray-900[href$="css"] > .px-1\.5.py-0\.5.bg-primary-50`

	![screenshot](screenshots/15-0.jpg)
- `section[aria-labelledby="semantic-section-846248"] > .hover\:bg-white.dark\:hover\:bg-gray-900[href$="paiton-dlya-novachkiv"] > .px-1\.5.py-0\.5.bg-primary-50`

	![screenshot](screenshots/16-0.jpg)
- `section[aria-labelledby="semantic-section-846249"] > .hover\:bg-white.dark\:hover\:bg-gray-900[href$="programuvannya"] > .px-1\.5.py-0\.5.bg-primary-50`

	![screenshot](screenshots/17-0.jpg)
- `section[aria-labelledby="semantic-section-846250"] > .hover\:bg-white.dark\:hover\:bg-gray-900[href$="python"] > .px-1\.5.py-0\.5.bg-primary-50`

	![screenshot](screenshots/18-0.jpg)

### Alternative text of images should not be repeated as text

Ensure image alternative is not repeated as text

Impact: **minor**

Need to fix all the following issues:

- Element contains &lt;img&gt; element with alt text that duplicates existing text.

Affected elements:

- `.h-12.w-12[alt="Олександр Козак"]`

	![screenshot](screenshots/19-0.jpg)

### Ensures landmarks are unique

Landmarks should have a unique role or role/label/title (i.e. accessible name) combination

Impact: **moderate**

Need to fix one of the following issues:

- The landmark must have a unique aria-label, aria-labelledby, or title to make landmarks distinguishable.

Affected elements:

- `section[aria-labelledby="semantic-section-846244"]`

	![screenshot](screenshots/20-0.jpg)

### Interactive controls must not be nested

Ensures interactive controls are not nested as they are not always announced by screen readers or can cause focus problems for assistive technologies

Impact: **serious**

Required to satisfy [WCAG 2.0 Level A](https://www.w3.org/TR/WCAG20/), [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf)

Need to fix one of the following issues:

- Element has focusable descendants.

Affected elements:

- `#headlessui-popover-button-395018`

	![screenshot](screenshots/21-0.jpg)
- `#headlessui-popover-button-395020`

	![screenshot](screenshots/22-0.jpg)
- `#headlessui-popover-button-395023`

	![screenshot](screenshots/23-0.jpg)
- `#headlessui-menu-button-395025`

	

