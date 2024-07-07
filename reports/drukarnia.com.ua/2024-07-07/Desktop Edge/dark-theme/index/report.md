# https://drukarnia.com.ua/

Report created at 7/7/2024

## Test environment

- Browser: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/127.0.6533.17 Safari/537.36 Edg/127.0.6533.17
- Resolution: 1280x720

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

- `#headlessui-popover-button-389136`

	![screenshot](screenshots/2-0.jpg)

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

- `.justify-end.grow.flex > .p-2\.5.hover\:bg-primary-50.dark\:hover\:bg-primary-800`

	![screenshot](screenshots/3-0.jpg)
- `#headlessui-popover-button-389136 > .hover\:bg-white.dark\:hover\:bg-gray-900`

	![screenshot](screenshots/4-0.jpg)

### Elements must meet minimum color contrast ratio thresholds

Ensures the contrast between foreground and background colors meets WCAG 2 AA minimum contrast ratio thresholds

Impact: **serious**

Required to satisfy [WCAG 2.0 Level AA](https://www.w3.org/TR/WCAG20/), [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf)

Need to fix one of the following issues:

- Element has insufficient color contrast of 3.48 (foreground color: #ffffff, background color: #34988e, font size: 13.5pt (18px), font weight: bold). Expected contrast ratio of 4.5:1.

Affected elements:

- `.sm\:text-lg > span`

	![screenshot](screenshots/5-0.jpg)

Need to fix one of the following issues:

- Element has insufficient color contrast of 3.03 (foreground color: #48a391, background color: #ffffff, font size: 12.0pt (16px), font weight: bold). Expected contrast ratio of 4.5:1.

Affected elements:

- `.px-6`

	![screenshot](screenshots/6-0.jpg)

Need to fix one of the following issues:

- Element has insufficient color contrast of 3.48 (foreground color: #ffffff, background color: #34988e, font size: 10.5pt (14px), font weight: bold). Expected contrast ratio of 4.5:1.

Affected elements:

- `a[href$="/#login"] > span`

	![screenshot](screenshots/7-0.jpg)

### Images must have alternate text

Ensures &lt;img&gt; elements have alternate text or a role of none or presentation

Impact: **critical**

Required to satisfy [WCAG 2.0 Level A](https://www.w3.org/TR/WCAG20/), [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf)

Need to fix one of the following issues:

- Element does not have an alt attribute.
- aria-label attribute does not exist or is empty.
- aria-labelledby attribute does not exist, references elements that do not exist or references elements that are empty.
- Element has no title attribute.
- Element&#039;s default semantics were not overridden with role=&quot;none&quot; or role=&quot;presentation&quot;.

Affected elements:

- `img[src$="glad-rev.jpg"]`

	![screenshot](screenshots/8-0.jpg)
- `img[src$="syromanka-rev.jpg"]`

	![screenshot](screenshots/9-0.jpg)
- `img[src$="slava-rev.jpg"]`

	![screenshot](screenshots/10-0.jpg)
- `img[src$="vlad-rev.jpg"]`

	![screenshot](screenshots/11-0.jpg)
- `img[src$="dmtr-rev.jpg"]`

	![screenshot](screenshots/12-0.jpg)
- `.max-w-\[330px\].py-6.px-4:nth-child(6) > .justify-between.flex > .flex > .h-12.w-12.text-lg > .h-12.w-12.text-lg`

	![screenshot](screenshots/13-0.jpg)

### Interactive controls must not be nested

Ensures interactive controls are not nested as they are not always announced by screen readers or can cause focus problems for assistive technologies

Impact: **serious**

Required to satisfy [WCAG 2.0 Level A](https://www.w3.org/TR/WCAG20/), [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf)

Need to fix one of the following issues:

- Element has focusable descendants.

Affected elements:

- `#headlessui-popover-button-389134`

	![screenshot](screenshots/14-0.jpg)
- `#headlessui-popover-button-389136`

	![screenshot](screenshots/15-0.jpg)
