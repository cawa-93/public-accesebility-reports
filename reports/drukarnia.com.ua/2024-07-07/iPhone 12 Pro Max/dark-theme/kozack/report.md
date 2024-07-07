# https://drukarnia.com.ua/kozack

Report created at 7/7/2024

## Test environment

- Browser: Mozilla/5.0 (iPhone; CPU iPhone OS 14_4 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/17.4 Mobile/15E148 Safari/604.1
- Resolution: 428x746

![Full page screenshot](screenshots/1-0.jpg)

## Compliance with standards

Not satisfy the requirements for:

- [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf)
- [WCAG 2.0 Level A](https://www.w3.org/TR/WCAG20/)

## Violations

### ARIA role should be appropriate for the element

Ensures role attribute has an appropriate value for the element

Impact: **minor**

Need to fix one of the following issues:

- ARIA role presentation is not allowed for given element.

Affected elements:

- `article[aria-labelledby="6649bf1ae6363e315a60a765-title"] > .gap-x-5.gap-y-2.md\:flex-row > .shrink-0.md\:w-1\/3 > .aspect-image-preview.h-auto.object-cover`

	![screenshot](screenshots/2-0.jpg)
- `article[aria-labelledby="64b40b08280f44210202a9ff-title"] > .gap-x-5.gap-y-2.md\:flex-row > .shrink-0.md\:w-1\/3 > .aspect-image-preview.h-auto.object-cover`

	![screenshot](screenshots/3-0.jpg)
- `article[aria-labelledby="649d69e3280f442102ecbaf7-title"] > .gap-x-5.gap-y-2.md\:flex-row > .shrink-0.md\:w-1\/3 > .aspect-image-preview.h-auto.object-cover`

	![screenshot](screenshots/4-0.jpg)
- `article[aria-labelledby="6494b136280f442102e4ee6b-title"] > .gap-x-5.gap-y-2.md\:flex-row > .shrink-0.md\:w-1\/3 > .aspect-image-preview.h-auto.object-cover`

	![screenshot](screenshots/5-0.jpg)
- `article[aria-labelledby="6491631f280f442102e0cdb3-title"] > .gap-x-5.gap-y-2.md\:flex-row > .shrink-0.md\:w-1\/3 > .aspect-image-preview.h-auto.object-cover`

	![screenshot](screenshots/6-0.jpg)
- `article[aria-labelledby="648c8be7280f442102da8e21-title"] > .gap-x-5.gap-y-2.md\:flex-row > .shrink-0.md\:w-1\/3 > .aspect-image-preview.h-auto.object-cover`

	![screenshot](screenshots/7-0.jpg)
- `article[aria-labelledby="648c5888280f442102da3d40-title"] > .gap-x-5.gap-y-2.md\:flex-row > .shrink-0.md\:w-1\/3 > .aspect-image-preview.h-auto.object-cover`

	![screenshot](screenshots/8-0.jpg)
- `article[aria-labelledby="6470e3a3c149c83ef753c0b7-title"] > .gap-x-5.gap-y-2.md\:flex-row > .shrink-0.md\:w-1\/3 > .aspect-image-preview.h-auto.object-cover`

	![screenshot](screenshots/9-0.jpg)
- `article[aria-labelledby="645903d1c149c83ef73715d8-title"] > .gap-x-5.gap-y-2.md\:flex-row > .shrink-0.md\:w-1\/3 > .aspect-image-preview.h-auto.object-cover`

	![screenshot](screenshots/10-0.jpg)
- `article[aria-labelledby="644e85be7305cb90edb048e8-title"] > .gap-x-5.gap-y-2.md\:flex-row > .shrink-0.md\:w-1\/3 > .aspect-image-preview.h-auto.object-cover`

	![screenshot](screenshots/11-0.jpg)

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

- `#headlessui-popover-button-405290`

	![screenshot](screenshots/12-0.jpg)

### Certain ARIA roles must contain particular children

Ensures elements with an ARIA role that require child roles contain them

Impact: **critical**

Required to satisfy [WCAG 2.0 Level A](https://www.w3.org/TR/WCAG20/), [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf)

Need to fix one of the following issues:

- Element has children which are not allowed: ul[tabindex].

Affected elements:

- `div[role="feed"]`

	![screenshot](screenshots/13-0.jpg)

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

	![screenshot](screenshots/14-0.jpg)
- `#headlessui-popover-button-405290 > .text-gray-900.hover\:bg-white.dark\:hover\:bg-gray-900`

	![screenshot](screenshots/15-0.jpg)

### Ensures landmarks are unique

Landmarks should have a unique role or role/label/title (i.e. accessible name) combination

Impact: **moderate**

Need to fix one of the following issues:

- The landmark must have a unique aria-label, aria-labelledby, or title to make landmarks distinguishable.

Affected elements:

- `section[aria-labelledby="semantic-section-868656"]`

	![screenshot](screenshots/16-0.jpg)

### Links must have discernible text

Ensures links have discernible text

Impact: **serious**

Required to satisfy [WCAG 2.0 Level A](https://www.w3.org/TR/WCAG20/), [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf)

Need to fix one of the following issues:

- Element does not have text that is visible to screen readers.
- aria-label attribute does not exist or is empty.
- aria-labelledby attribute does not exist, references elements that do not exist or references elements that are empty.
- Element has no title attribute.

Affected elements:

- `.flex-center[href$="home"]`

	![screenshot](screenshots/17-0.jpg)

Need to fix all the following issues:

- Element is in tab order and does not have accessible text.Need to fix one of the following issues:

- Element does not have text that is visible to screen readers.
- aria-label attribute does not exist or is empty.
- aria-labelledby attribute does not exist, references elements that do not exist or references elements that are empty.
- Element has no title attribute.

Affected elements:

- `article[aria-labelledby="6649bf1ae6363e315a60a765-title"] > .gap-x-5.gap-y-2.md\:flex-row > .shrink-0.md\:w-1\/3`

	![screenshot](screenshots/18-0.jpg)
- `article[aria-labelledby="64b40b08280f44210202a9ff-title"] > .gap-x-5.gap-y-2.md\:flex-row > .shrink-0.md\:w-1\/3`

	![screenshot](screenshots/19-0.jpg)
- `article[aria-labelledby="649d69e3280f442102ecbaf7-title"] > .gap-x-5.gap-y-2.md\:flex-row > .shrink-0.md\:w-1\/3`

	![screenshot](screenshots/20-0.jpg)
- `article[aria-labelledby="6494b136280f442102e4ee6b-title"] > .gap-x-5.gap-y-2.md\:flex-row > .shrink-0.md\:w-1\/3`

	![screenshot](screenshots/21-0.jpg)
- `article[aria-labelledby="6491631f280f442102e0cdb3-title"] > .gap-x-5.gap-y-2.md\:flex-row > .shrink-0.md\:w-1\/3`

	![screenshot](screenshots/22-0.jpg)
- `article[aria-labelledby="648c8be7280f442102da8e21-title"] > .gap-x-5.gap-y-2.md\:flex-row > .shrink-0.md\:w-1\/3`

	![screenshot](screenshots/23-0.jpg)
- `article[aria-labelledby="648c5888280f442102da3d40-title"] > .gap-x-5.gap-y-2.md\:flex-row > .shrink-0.md\:w-1\/3`

	![screenshot](screenshots/24-0.jpg)
- `article[aria-labelledby="6470e3a3c149c83ef753c0b7-title"] > .gap-x-5.gap-y-2.md\:flex-row > .shrink-0.md\:w-1\/3`

	![screenshot](screenshots/25-0.jpg)
- `article[aria-labelledby="645903d1c149c83ef73715d8-title"] > .gap-x-5.gap-y-2.md\:flex-row > .shrink-0.md\:w-1\/3`

	![screenshot](screenshots/26-0.jpg)
- `article[aria-labelledby="644e85be7305cb90edb048e8-title"] > .gap-x-5.gap-y-2.md\:flex-row > .shrink-0.md\:w-1\/3`

	![screenshot](screenshots/27-0.jpg)

### Interactive controls must not be nested

Ensures interactive controls are not nested as they are not always announced by screen readers or can cause focus problems for assistive technologies

Impact: **serious**

Required to satisfy [WCAG 2.0 Level A](https://www.w3.org/TR/WCAG20/), [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf)

Need to fix one of the following issues:

- Element has focusable descendants.

Affected elements:

- `#headlessui-popover-button-405288`

	![screenshot](screenshots/28-0.jpg)
- `#headlessui-popover-button-405290`

	![screenshot](screenshots/29-0.jpg)

### Page should contain a level-one heading

Ensure that the page, or at least one of its frames contains a level-one heading

Impact: **moderate**

Need to fix all the following issues:

- Page must have a level-one heading.

Affected elements:

- html

