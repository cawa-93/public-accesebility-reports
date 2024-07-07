# https://drukarnia.com.ua/search?text=%D1%82%D0%B5%D1%81%D1%82

Report created at 7/7/2024

## Test environment

- Browser: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/127.0.6533.17 Safari/537.36 Edg/127.0.6533.17
- Resolution: 1280x720

![Full page screenshot](screenshots/1-0.jpg)

## Compliance with standards

Not satisfy the requirements for:

- [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf)
- [WCAG 2.0 Level A](https://www.w3.org/TR/WCAG20/)

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

- `#headlessui-menu-button-11`

	![screenshot](screenshots/2-0.jpg)
- `#headlessui-popover-button-406413`

	![screenshot](screenshots/3-0.jpg)

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

- `#headlessui-menu-button-11 > .text-base.p-2\.5.hover\:bg-primary-50`

	![screenshot](screenshots/4-0.jpg)
- `.grow > .text-base.p-2\.5.hover\:bg-primary-50`

	![screenshot](screenshots/5-0.jpg)
- `#headlessui-popover-button-406413 > .hover\:bg-white.dark\:hover\:bg-gray-900.text-gray-900`

	![screenshot](screenshots/6-0.jpg)

### Document should have one main landmark

Ensures the document has a main landmark

Impact: **moderate**

Need to fix all the following issues:

- Document does not have a main landmark.

Affected elements:

- html

### Interactive controls must not be nested

Ensures interactive controls are not nested as they are not always announced by screen readers or can cause focus problems for assistive technologies

Impact: **serious**

Required to satisfy [WCAG 2.0 Level A](https://www.w3.org/TR/WCAG20/), [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf)

Need to fix one of the following issues:

- Element has focusable descendants.

Affected elements:

- `#headlessui-popover-button-406411`

	![screenshot](screenshots/7-0.jpg)
- `#headlessui-menu-button-11`

	![screenshot](screenshots/8-0.jpg)
- `#headlessui-popover-button-406413`

	![screenshot](screenshots/9-0.jpg)

### Page should contain a level-one heading

Ensure that the page, or at least one of its frames contains a level-one heading

Impact: **moderate**

Need to fix all the following issues:

- Page must have a level-one heading.

Affected elements:

- html

### All page content should be contained by landmarks

Ensures all page content is contained by landmarks

Impact: **moderate**

Need to fix one of the following issues:

- Some page content is not contained by landmarks.

Affected elements:

- `#headlessui-combobox-input-12`

	![screenshot](screenshots/10-0.jpg)
- `section`

	![screenshot](screenshots/11-0.jpg), ![screenshot](screenshots/11-1.jpg), ![screenshot](screenshots/11-2.jpg), ![screenshot](screenshots/11-3.jpg), ![screenshot](screenshots/11-4.jpg), ![screenshot](screenshots/11-5.jpg), ![screenshot](screenshots/11-6.jpg), ![screenshot](screenshots/11-7.jpg), ![screenshot](screenshots/11-8.jpg), ![screenshot](screenshots/11-9.jpg), ![screenshot](screenshots/11-10.jpg), ![screenshot](screenshots/11-11.jpg), ![screenshot](screenshots/11-12.jpg), ![screenshot](screenshots/11-13.jpg), ![screenshot](screenshots/11-14.jpg), ![screenshot](screenshots/11-15.jpg), ![screenshot](screenshots/11-16.jpg), ![screenshot](screenshots/11-17.jpg), ![screenshot](screenshots/11-18.jpg), ![screenshot](screenshots/11-19.jpg), ![screenshot](screenshots/11-20.jpg)

