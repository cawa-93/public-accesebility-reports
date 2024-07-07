# https://drukarnia.com.ua/articles/hogwarts-legacy-khaltura-roku-YftXv

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

### ARIA role should be appropriate for the element

Ensures role attribute has an appropriate value for the element

Impact: **minor**

Need to fix one of the following issues:

- ARIA role presentation is not allowed for given element.

Affected elements:

- `img[height="467"]`

	![screenshot](screenshots/2-0.jpg)
- `img[height="393"]`

	![screenshot](screenshots/3-0.jpg)

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

- `#headlessui-menu-button-9`

	![screenshot](screenshots/4-0.jpg)
- `#headlessui-popover-button-406680`

	![screenshot](screenshots/5-0.jpg)
- `#headlessui-menu-button-406682`

	![screenshot](screenshots/6-0.jpg)
- `#headlessui-menu-button-10`

	![screenshot](screenshots/7-0.jpg)

### Elements must only use permitted ARIA attributes

Ensures ARIA attributes are not prohibited for an element&#039;s role

Impact: **serious**

Required to satisfy [WCAG 2.0 Level A](https://www.w3.org/TR/WCAG20/), [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf)

Need to fix all the following issues:

- aria-label attribute cannot be used on a div with no valid role attribute..

Affected elements:

- `.gap-4.flex-col.flex > .profile.bg-brand-light.rounded-2xl > .profile-info-container.border-b.text-center > .actions.flex-wrap.justify-center > .share-button.right-4.top-4 > .rtl\:text-right.text-left[data-headlessui-state=""]`

	![screenshot](screenshots/8-0.jpg)
- `.flex-1.justify-center.flex > .rtl\:text-right.text-left[data-headlessui-state=""]`

	![screenshot](screenshots/9-0.jpg)

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

- `#headlessui-menu-button-9 > .text-base.p-2\.5.hover\:bg-primary-50`

	![screenshot](screenshots/10-0.jpg)
- `.grow > .text-base.p-2\.5.hover\:bg-primary-50`

	![screenshot](screenshots/11-0.jpg)
- `#headlessui-popover-button-406680 > .hover\:bg-white.dark\:hover\:bg-gray-900.text-gray-900`

	![screenshot](screenshots/12-0.jpg)
- `#headlessui-menu-button-406682 > .hover\:bg-primary-50.dark\:hover\:bg-primary-800.hover\:text-primary`

	![screenshot](screenshots/13-0.jpg)
- `#headlessui-menu-button-10 > .text-black.hover\:bg-gray-50[type="button"]`

	![screenshot](screenshots/14-0.jpg)

### Elements must meet minimum color contrast ratio thresholds

Ensures the contrast between foreground and background colors meets WCAG 2 AA minimum contrast ratio thresholds

Impact: **serious**

Required to satisfy [WCAG 2.0 Level AA](https://www.w3.org/TR/WCAG20/), [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf)

Need to fix one of the following issues:

- Element has insufficient color contrast of 4.33 (foreground color: #64748b, background color: #edf6f6, font size: 12.0pt (16px), font weight: normal). Expected contrast ratio of 4.5:1.

Affected elements:

- `.gap-4.flex-col.flex > .profile.bg-brand-light.rounded-2xl > .profile-info-container.border-b.text-center > .profile-info.justify-center.flex-col > div > .text-gray-500.dark\:text-gray-400`

	![screenshot](screenshots/15-0.jpg)

Need to fix one of the following issues:

- Element has insufficient color contrast of 4.33 (foreground color: #64748b, background color: #edf6f6, font size: 10.5pt (14px), font weight: normal). Expected contrast ratio of 4.5:1.

Affected elements:

- `.gap-4.flex-col.flex > .profile.bg-brand-light.rounded-2xl > .profile-info-container.border-b.text-center > .profile-info.justify-center.flex-col > div > .profile-stats.my-6.max-w-xs > .mr-6.flex-col[title="5269"] > .font-semibold.text-gray-500.dark\:text-gray-400`

	![screenshot](screenshots/16-0.jpg)
- `.gap-4.flex-col.flex > .profile.bg-brand-light.rounded-2xl > .profile-info-container.border-b.text-center > .profile-info.justify-center.flex-col > div > .profile-stats.my-6.max-w-xs > .border-x.border-gray-300.px-6 > .font-semibold.text-gray-500.dark\:text-gray-400`

	![screenshot](screenshots/17-0.jpg)
- `.gap-4.flex-col.flex > .profile.bg-brand-light.rounded-2xl > .profile-info-container.border-b.text-center > .profile-info.justify-center.flex-col > div > .profile-stats.my-6.max-w-xs > .ml-6.text-inherit.flex-col > .font-semibold.text-gray-500.dark\:text-gray-400`

	![screenshot](screenshots/18-0.jpg)
- `.gap-4.flex-col.flex > .profile.bg-brand-light.rounded-2xl > .m-3.gap-x-16.gap-y-2 > .gap-1.text-gray-500.dark\:text-gray-400`

	![screenshot](screenshots/19-0.jpg)

Need to fix one of the following issues:

- Element has insufficient color contrast of 3.29 (foreground color: #34988e, background color: #f3faf9, font size: 9.0pt (12px), font weight: normal). Expected contrast ratio of 4.5:1.

Affected elements:

- `section[aria-labelledby="semantic-section-871559"] > .hover\:bg-white.dark\:hover\:bg-gray-900[href$="dostupnist"] > .rounded-md.px-1\.5.py-0\.5`

	![screenshot](screenshots/20-0.jpg)
- `section[aria-labelledby="semantic-section-871560"] > .hover\:bg-white.dark\:hover\:bg-gray-900[href$="ui-ux"] > .rounded-md.px-1\.5.py-0\.5`

	![screenshot](screenshots/21-0.jpg)
- `section[aria-labelledby="semantic-section-871561"] > .hover\:bg-white.dark\:hover\:bg-gray-900[href$="css"] > .rounded-md.px-1\.5.py-0\.5`

	![screenshot](screenshots/22-0.jpg)
- `section[aria-labelledby="semantic-section-871567"] > .hover\:bg-white.dark\:hover\:bg-gray-900[href$="cyberpunk-2077"] > .rounded-md.px-1\.5.py-0\.5`

	![screenshot](screenshots/23-0.jpg)
- `section[aria-labelledby="semantic-section-871568"] > .hover\:bg-white.dark\:hover\:bg-gray-900[href$="igri"] > .rounded-md.px-1\.5.py-0\.5`

	![screenshot](screenshots/24-0.jpg)
- `section[aria-labelledby="semantic-section-871569"] > .hover\:bg-white.dark\:hover\:bg-gray-900[href$="igri"] > .rounded-md.px-1\.5.py-0\.5`

	![screenshot](screenshots/25-0.jpg)

Need to fix one of the following issues:

- Element has insufficient color contrast of 3.48 (foreground color: #ffffff, background color: #34988e, font size: 10.5pt (14px), font weight: bold). Expected contrast ratio of 4.5:1.

Affected elements:

- `.w-fit.hover\:bg-primary-400[href$="write"] > span`

	![screenshot](screenshots/26-0.jpg)
- `section[aria-labelledby="semantic-section-18"] > .border-t.pt-4 > div > .max-h-\[36px\].mt-3.items-end > .gap-2.flex > .items-center.flex > .gap-x-2.px-3.py-2 > span:nth-child(2)`

	![screenshot](screenshots/27-0.jpg)

Need to fix one of the following issues:

- Element has insufficient color contrast of 3.32 (foreground color: #34988e, background color: #f8fafc, font size: 10.5pt (14px), font weight: bold). Expected contrast ratio of 4.5:1.

Affected elements:

- `section[aria-labelledby="semantic-section-18"] > div:nth-child(2) > .hover\:text-primary-600.disabled\:text-primary-500.dark\:hover\:text-primary-500 > span`

	![screenshot](screenshots/28-0.jpg)

Need to fix one of the following issues:

- Element has insufficient color contrast of 3.18 (foreground color: #34988e, background color: #f1f5f9, font size: 9.0pt (12px), font weight: bold). Expected contrast ratio of 4.5:1.

Affected elements:

- `section[aria-labelledby="semantic-section-871566"] > .divide-y.m-0.list-none > .py-3:nth-child(3) > .group[aria-labelledby="64a0be7b280f442102f06403-title"][show-tags="false"] > .justify-between.min-w-0.flex:nth-child(1) > .space-y-2.min-w-0[data-v-cf967814=""] > .min-w-0.flex[data-v-cf967814=""] > .\!flex-shrink.underline-offset-4[href$="konark"] > .bg-gray-100.dark\:bg-gray-800.justify-center > .leading-none.dark\:text-primary-400.text-primary-500`

	![screenshot](screenshots/29-0.jpg)

### Frames must have an accessible name

Ensures &lt;iframe&gt; and &lt;frame&gt; elements have an accessible name

Impact: **serious**

Required to satisfy [WCAG 2.0 Level A](https://www.w3.org/TR/WCAG20/), [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf)

Need to fix one of the following issues:

- Element has no title attribute.
- aria-label attribute does not exist or is empty.
- aria-labelledby attribute does not exist, references elements that do not exist or references elements that are empty.
- Element&#039;s default semantics were not overridden with role=&quot;none&quot; or role=&quot;presentation&quot;.

Affected elements:

- `.frame-wrapper:nth-child(14) > .frame[frameborder="0"][scrolling="no"]`

	![screenshot](screenshots/30-0.jpg)
- `.frame-wrapper:nth-child(72) > .frame[frameborder="0"][scrolling="no"]`

	![screenshot](screenshots/31-0.jpg)
- `.frame-wrapper:nth-child(85) > .frame[frameborder="0"][scrolling="no"]`

	![screenshot](screenshots/32-0.jpg)
- `.frame-wrapper:nth-child(96) > .frame[frameborder="0"][scrolling="no"]`

	![screenshot](screenshots/33-0.jpg)
- `.frame-wrapper:nth-child(101) > .frame[frameborder="0"][scrolling="no"]`

	![screenshot](screenshots/34-0.jpg)
- `.frame-wrapper:nth-child(115) > .frame[frameborder="0"][scrolling="no"]`

	![screenshot](screenshots/35-0.jpg)
- `.frame-wrapper:nth-child(135) > .frame[frameborder="0"][scrolling="no"]`

	![screenshot](screenshots/36-0.jpg)
- `.frame-wrapper:nth-child(153) > .frame[frameborder="0"][scrolling="no"]`

	![screenshot](screenshots/37-0.jpg)
- `.frame-wrapper:nth-child(155) > .frame[frameborder="0"][scrolling="no"]`

	![screenshot](screenshots/38-0.jpg)

### Alternative text of images should not be repeated as text

Ensure image alternative is not repeated as text

Impact: **minor**

Need to fix all the following issues:

- Element contains &lt;img&gt; element with alt text that duplicates existing text.

Affected elements:

- `.h-12.w-12[alt="Олександр Козак"]`

	![screenshot](screenshots/39-0.jpg)

### Ensures landmarks are unique

Landmarks should have a unique role or role/label/title (i.e. accessible name) combination

Impact: **moderate**

Need to fix one of the following issues:

- The landmark must have a unique aria-label, aria-labelledby, or title to make landmarks distinguishable.

Affected elements:

- `section[aria-labelledby="semantic-section-871559"]`

	![screenshot](screenshots/40-0.jpg)

### Interactive controls must not be nested

Ensures interactive controls are not nested as they are not always announced by screen readers or can cause focus problems for assistive technologies

Impact: **serious**

Required to satisfy [WCAG 2.0 Level A](https://www.w3.org/TR/WCAG20/), [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf)

Need to fix one of the following issues:

- Element has focusable descendants.

Affected elements:

- `#headlessui-popover-button-406678`

	![screenshot](screenshots/41-0.jpg)
- `#headlessui-menu-button-9`

	![screenshot](screenshots/42-0.jpg)
- `#headlessui-popover-button-406680`

	![screenshot](screenshots/43-0.jpg)
- `#headlessui-menu-button-406682`

	![screenshot](screenshots/44-0.jpg)
- `#headlessui-popover-button-406683`

	![screenshot](screenshots/45-0.jpg)
- `#headlessui-menu-button-10`

	![screenshot](screenshots/46-0.jpg)
