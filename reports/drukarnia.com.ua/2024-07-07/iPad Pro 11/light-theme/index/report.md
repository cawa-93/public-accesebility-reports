# https://drukarnia.com.ua/

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

- Element has insufficient color contrast of 2.58 (foreground color: #ff6768, background color: #edf6f6, font size: 27.0pt (36px), font weight: bold). Expected contrast ratio of 3:1.

Affected elements:

- `.text-4xl`

	![screenshot](screenshots/6-0.jpg)

Need to fix one of the following issues:

- Element has insufficient color contrast of 3.48 (foreground color: #ffffff, background color: #34988e, font size: 10.5pt (14px), font weight: bold). Expected contrast ratio of 4.5:1.

Affected elements:

- `a[href$="/#login"] > span`

	![screenshot](screenshots/7-0.jpg)

Need to fix one of the following issues:

- Element has insufficient color contrast of 1.04 (foreground color: #ffffff, background color: #f8fafc, font size: 10.5pt (14px), font weight: bold). Expected contrast ratio of 4.5:1.

Affected elements:

- `a[href="/?mode=login#login"] > span`

	![screenshot](screenshots/8-0.jpg)

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

	![screenshot](screenshots/9-0.jpg)
- `img[src$="syromanka-rev.jpg"]`

	![screenshot](screenshots/10-0.jpg)
- `img[src$="slava-rev.jpg"]`

	![screenshot](screenshots/11-0.jpg)
- `img[src$="vlad-rev.jpg"]`

	![screenshot](screenshots/12-0.jpg)
- `img[src$="dmtr-rev.jpg"]`

	![screenshot](screenshots/13-0.jpg)
- `.max-w-\[330px\].py-6.px-4:nth-child(6) > .justify-between.flex > .flex > .h-12.w-12.text-lg > .h-12.w-12.text-lg`

	![screenshot](screenshots/14-0.jpg)

### Interactive controls must not be nested

Ensures interactive controls are not nested as they are not always announced by screen readers or can cause focus problems for assistive technologies

Impact: **serious**

Required to satisfy [WCAG 2.0 Level A](https://www.w3.org/TR/WCAG20/), [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf)

Need to fix one of the following issues:

- Element has focusable descendants.

Affected elements:

- `#headlessui-popover-button-389134`

	![screenshot](screenshots/15-0.jpg)
- `#headlessui-popover-button-389136`

	![screenshot](screenshots/16-0.jpg)

