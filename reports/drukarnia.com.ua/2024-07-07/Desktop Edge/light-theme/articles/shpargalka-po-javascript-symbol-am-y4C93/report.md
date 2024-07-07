# https://drukarnia.com.ua/articles/shpargalka-po-javascript-symbol-am-y4C93

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

- `#headlessui-menu-button-9`

	![screenshot](screenshots/2-0.jpg)
- `#headlessui-popover-button-397634`

	![screenshot](screenshots/3-0.jpg)
- `#headlessui-menu-button-397636`

	![screenshot](screenshots/4-0.jpg)
- `#headlessui-menu-button-10`

	![screenshot](screenshots/5-0.jpg)

### Elements must only use permitted ARIA attributes

Ensures ARIA attributes are not prohibited for an element&#039;s role

Impact: **serious**

Required to satisfy [WCAG 2.0 Level A](https://www.w3.org/TR/WCAG20/), [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf)

Need to fix all the following issues:

- aria-label attribute cannot be used on a div with no valid role attribute..

Affected elements:

- `.gap-4.flex-col.flex > .profile.rounded-2xl.bg-brand-light > .profile-info-container.border-b.text-center > .actions.flex-wrap.justify-center > .share-button.right-4.top-4 > .rtl\:text-right.text-left[data-headlessui-state=""]`

	![screenshot](screenshots/6-0.jpg)
- `.flex-1.justify-center.flex > .rtl\:text-right.text-left[data-headlessui-state=""]`

	![screenshot](screenshots/7-0.jpg)

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

	![screenshot](screenshots/8-0.jpg)
- `.grow > .text-base.p-2\.5.hover\:bg-primary-50`

	![screenshot](screenshots/9-0.jpg)
- `#headlessui-popover-button-397634 > .hover\:bg-white.dark\:hover\:bg-gray-900.text-gray-900`

	![screenshot](screenshots/10-0.jpg)
- `#headlessui-menu-button-397636 > .hover\:bg-primary-50.dark\:hover\:bg-primary-800.hover\:text-primary`

	![screenshot](screenshots/11-0.jpg)
- `pre:nth-child(4) > .hover\:text-primary-500.hover\:dark\:text-primary-500.bottom-2`

	![screenshot](screenshots/12-0.jpg)
- `pre:nth-child(6) > .hover\:text-primary-500.hover\:dark\:text-primary-500.bottom-2`

	![screenshot](screenshots/13-0.jpg)
- `pre:nth-child(8) > .hover\:text-primary-500.hover\:dark\:text-primary-500.bottom-2`

	![screenshot](screenshots/14-0.jpg)
- `pre:nth-child(13) > .hover\:text-primary-500.hover\:dark\:text-primary-500.bottom-2`

	![screenshot](screenshots/15-0.jpg)
- `pre:nth-child(17) > .hover\:text-primary-500.hover\:dark\:text-primary-500.bottom-2`

	![screenshot](screenshots/16-0.jpg)
- `pre:nth-child(19) > .hover\:text-primary-500.hover\:dark\:text-primary-500.bottom-2`

	![screenshot](screenshots/17-0.jpg)
- `pre:nth-child(23) > .hover\:text-primary-500.hover\:dark\:text-primary-500.bottom-2`

	![screenshot](screenshots/18-0.jpg)
- `pre:nth-child(25) > .hover\:text-primary-500.hover\:dark\:text-primary-500.bottom-2`

	![screenshot](screenshots/19-0.jpg)
- `pre:nth-child(29) > .hover\:text-primary-500.hover\:dark\:text-primary-500.bottom-2`

	![screenshot](screenshots/20-0.jpg)
- `pre:nth-child(32) > .hover\:text-primary-500.hover\:dark\:text-primary-500.bottom-2`

	![screenshot](screenshots/21-0.jpg)
- `pre:nth-child(37) > .hover\:text-primary-500.hover\:dark\:text-primary-500.bottom-2`

	![screenshot](screenshots/22-0.jpg)
- `pre:nth-child(40) > .hover\:text-primary-500.hover\:dark\:text-primary-500.bottom-2`

	![screenshot](screenshots/23-0.jpg)
- `pre:nth-child(43) > .hover\:text-primary-500.hover\:dark\:text-primary-500.bottom-2`

	![screenshot](screenshots/24-0.jpg)
- `pre:nth-child(46) > .hover\:text-primary-500.hover\:dark\:text-primary-500.bottom-2`

	![screenshot](screenshots/25-0.jpg)
- `pre:nth-child(49) > .hover\:text-primary-500.hover\:dark\:text-primary-500.bottom-2`

	![screenshot](screenshots/26-0.jpg)
- `pre:nth-child(52) > .hover\:text-primary-500.hover\:dark\:text-primary-500.bottom-2`

	![screenshot](screenshots/27-0.jpg)
- `pre:nth-child(55) > .hover\:text-primary-500.hover\:dark\:text-primary-500.bottom-2`

	![screenshot](screenshots/28-0.jpg)
- `#headlessui-menu-button-10 > .hover\:bg-gray-50.text-black[type="button"]`

	![screenshot](screenshots/29-0.jpg)

### Elements must meet minimum color contrast ratio thresholds

Ensures the contrast between foreground and background colors meets WCAG 2 AA minimum contrast ratio thresholds

Impact: **serious**

Required to satisfy [WCAG 2.0 Level AA](https://www.w3.org/TR/WCAG20/), [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf)

Need to fix one of the following issues:

- Element has insufficient color contrast of 4.33 (foreground color: #64748b, background color: #edf6f6, font size: 12.0pt (16px), font weight: normal). Expected contrast ratio of 4.5:1.

Affected elements:

- `.gap-4.flex-col.flex > .profile.rounded-2xl.bg-brand-light > .profile-info-container.border-b.text-center > .profile-info.flex-col.justify-center > div > .text-gray-500.dark\:text-gray-400`

	![screenshot](screenshots/30-0.jpg)

Need to fix one of the following issues:

- Element has insufficient color contrast of 4.33 (foreground color: #64748b, background color: #edf6f6, font size: 10.5pt (14px), font weight: normal). Expected contrast ratio of 4.5:1.

Affected elements:

- `.gap-4.flex-col.flex > .profile.rounded-2xl.bg-brand-light > .profile-info-container.border-b.text-center > .profile-info.flex-col.justify-center > div > .profile-stats.my-6.max-w-xs > .mr-6.flex-col[title="5264"] > .font-semibold.text-gray-500.dark\:text-gray-400`

	![screenshot](screenshots/31-0.jpg)
- `.gap-4.flex-col.flex > .profile.rounded-2xl.bg-brand-light > .profile-info-container.border-b.text-center > .profile-info.flex-col.justify-center > div > .profile-stats.my-6.max-w-xs > .border-x.border-gray-300.px-6 > .font-semibold.text-gray-500.dark\:text-gray-400`

	![screenshot](screenshots/32-0.jpg)
- `.gap-4.flex-col.flex > .profile.rounded-2xl.bg-brand-light > .profile-info-container.border-b.text-center > .profile-info.flex-col.justify-center > div > .profile-stats.my-6.max-w-xs > .ml-6.text-inherit.flex-col > .font-semibold.text-gray-500.dark\:text-gray-400`

	![screenshot](screenshots/33-0.jpg)
- `.gap-4.flex-col.flex > .profile.rounded-2xl.bg-brand-light > .m-3.gap-x-16.gap-y-2 > .gap-1.text-gray-500.dark\:text-gray-400`

	![screenshot](screenshots/34-0.jpg)

Need to fix one of the following issues:

- Element has insufficient color contrast of 3.29 (foreground color: #34988e, background color: #f3faf9, font size: 9.0pt (12px), font weight: normal). Expected contrast ratio of 4.5:1.

Affected elements:

- `section[aria-labelledby="semantic-section-851944"] > .hover\:bg-white.dark\:hover\:bg-gray-900[href$="dostupnist"] > .rounded-md.px-1\.5.py-0\.5`

	![screenshot](screenshots/35-0.jpg)
- `section[aria-labelledby="semantic-section-851945"] > .hover\:bg-white.dark\:hover\:bg-gray-900[href$="ui-ux"] > .rounded-md.px-1\.5.py-0\.5`

	![screenshot](screenshots/36-0.jpg)
- `section[aria-labelledby="semantic-section-851946"] > .hover\:bg-white.dark\:hover\:bg-gray-900[href$="css"] > .rounded-md.px-1\.5.py-0\.5`

	![screenshot](screenshots/37-0.jpg)
- `section[aria-labelledby="semantic-section-851952"] > .hover\:bg-white.dark\:hover\:bg-gray-900[href$="paiton-dlya-novachkiv"] > .rounded-md.px-1\.5.py-0\.5`

	![screenshot](screenshots/38-0.jpg)
- `section[aria-labelledby="semantic-section-851953"] > .hover\:bg-white.dark\:hover\:bg-gray-900[href$="programuvannya"] > .rounded-md.px-1\.5.py-0\.5`

	![screenshot](screenshots/39-0.jpg)
- `section[aria-labelledby="semantic-section-851954"] > .hover\:bg-white.dark\:hover\:bg-gray-900[href$="python"] > .rounded-md.px-1\.5.py-0\.5`

	![screenshot](screenshots/40-0.jpg)

Need to fix one of the following issues:

- Element has insufficient color contrast of 3.92 (foreground color: #6272a4, background color: #121416, font size: 10.5pt (14px), font weight: normal). Expected contrast ratio of 4.5:1.

Affected elements:

- `pre:nth-child(4) > code > .hljs-comment`

	![screenshot](screenshots/41-0.jpg)
- `pre:nth-child(6) > code > .hljs-comment`

	![screenshot](screenshots/42-0.jpg)
- `pre:nth-child(8) > code > .hljs-comment:nth-child(10)`

	![screenshot](screenshots/43-0.jpg)
- `.hljs-comment:nth-child(16)`

	![screenshot](screenshots/44-0.jpg)
- `pre:nth-child(19) > code > .hljs-comment:nth-child(8)`

	![screenshot](screenshots/45-0.jpg)
- `.hljs-comment:nth-child(9)`

	![screenshot](screenshots/46-0.jpg)
- `pre:nth-child(19) > code > .hljs-comment:nth-child(10)`

	![screenshot](screenshots/47-0.jpg)
- `pre:nth-child(23) > code > .hljs-comment:nth-child(19)`

	![screenshot](screenshots/48-0.jpg)
- `.hljs-comment:nth-child(20)`

	![screenshot](screenshots/49-0.jpg)
- `.hljs-comment:nth-child(21)`

	![screenshot](screenshots/50-0.jpg)
- `pre:nth-child(29) > code > .hljs-comment`

	![screenshot](screenshots/51-0.jpg)
- `pre:nth-child(32) > code > .hljs-comment:nth-child(12)`

	![screenshot](screenshots/52-0.jpg)
- `pre:nth-child(32) > code > .hljs-comment:nth-child(19)`

	![screenshot](screenshots/53-0.jpg)
- `pre:nth-child(46) > code > .hljs-comment:nth-child(5)`

	![screenshot](screenshots/54-0.jpg)
- `.hljs-comment:nth-child(23)`

	![screenshot](screenshots/55-0.jpg)
- `.hljs-comment:nth-child(27)`

	![screenshot](screenshots/56-0.jpg)
- `pre:nth-child(52) > code > .hljs-comment:nth-child(4)`

	![screenshot](screenshots/57-0.jpg)
- `pre:nth-child(52) > code > .hljs-comment:nth-child(8)`

	![screenshot](screenshots/58-0.jpg)
- `pre:nth-child(52) > code > .hljs-comment:nth-child(12)`

	![screenshot](screenshots/59-0.jpg)
- `.hljs-comment:nth-child(13)`

	![screenshot](screenshots/60-0.jpg)
- `.hljs-comment:nth-child(30)`

	![screenshot](screenshots/61-0.jpg)
- `.hljs-comment:nth-child(34)`

	![screenshot](screenshots/62-0.jpg)
- `.hljs-comment:nth-child(38)`

	![screenshot](screenshots/63-0.jpg)
- `.hljs-comment:nth-child(14)`

	![screenshot](screenshots/64-0.jpg)
- `.hljs-comment:nth-child(17)`

	![screenshot](screenshots/65-0.jpg)

Need to fix one of the following issues:

- Element has insufficient color contrast of 3.48 (foreground color: #ffffff, background color: #34988e, font size: 10.5pt (14px), font weight: bold). Expected contrast ratio of 4.5:1.

Affected elements:

- `.w-fit > span`

	![screenshot](screenshots/66-0.jpg)
- `section[aria-labelledby="semantic-section-18"] > .border-t.pt-4 > div > .max-h-\[36px\].mt-3.items-end > .gap-2.flex > .items-center.flex > .gap-x-2.px-3.py-2 > span:nth-child(2)`

	![screenshot](screenshots/67-0.jpg)

Need to fix one of the following issues:

- Element has insufficient color contrast of 3.32 (foreground color: #34988e, background color: #f8fafc, font size: 10.5pt (14px), font weight: bold). Expected contrast ratio of 4.5:1.

Affected elements:

- `section[aria-labelledby="semantic-section-18"] > div:nth-child(2) > .hover\:text-primary-600.disabled\:text-primary-500.dark\:hover\:text-primary-500 > span`

	![screenshot](screenshots/68-0.jpg)

### Alternative text of images should not be repeated as text

Ensure image alternative is not repeated as text

Impact: **minor**

Need to fix all the following issues:

- Element contains &lt;img&gt; element with alt text that duplicates existing text.

Affected elements:

- `.h-12.w-12[alt="Олександр Козак"]`

	![screenshot](screenshots/69-0.jpg)

### Ensures landmarks are unique

Landmarks should have a unique role or role/label/title (i.e. accessible name) combination

Impact: **moderate**

Need to fix one of the following issues:

- The landmark must have a unique aria-label, aria-labelledby, or title to make landmarks distinguishable.

Affected elements:

- `section[aria-labelledby="semantic-section-851944"]`

	![screenshot](screenshots/70-0.jpg)

### Interactive controls must not be nested

Ensures interactive controls are not nested as they are not always announced by screen readers or can cause focus problems for assistive technologies

Impact: **serious**

Required to satisfy [WCAG 2.0 Level A](https://www.w3.org/TR/WCAG20/), [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf)

Need to fix one of the following issues:

- Element has focusable descendants.

Affected elements:

- `#headlessui-popover-button-397632`

	![screenshot](screenshots/71-0.jpg)
- `#headlessui-menu-button-9`

	![screenshot](screenshots/72-0.jpg)
- `#headlessui-popover-button-397634`

	![screenshot](screenshots/73-0.jpg)
- `#headlessui-menu-button-397636`

	![screenshot](screenshots/74-0.jpg)
- `#headlessui-popover-button-397637`

	![screenshot](screenshots/75-0.jpg)
- `#headlessui-menu-button-10`

	![screenshot](screenshots/76-0.jpg)
