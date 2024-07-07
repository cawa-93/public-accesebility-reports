# https://drukarnia.com.ua/articles/chomu-avtomatichni-importi-bud-de-ce-zhakhliva-ideya-tnH24

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

- `img[width="400"]`

	![screenshot](screenshots/2-0.jpg)
- `img[height="420"]`

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

- `#headlessui-popover-button-396719`

	![screenshot](screenshots/4-0.jpg)
- `#headlessui-menu-button-396724`

	

### Elements must only use permitted ARIA attributes

Ensures ARIA attributes are not prohibited for an element&#039;s role

Impact: **serious**

Required to satisfy [WCAG 2.0 Level A](https://www.w3.org/TR/WCAG20/), [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf)

Need to fix all the following issues:

- aria-label attribute cannot be used on a div with no valid role attribute..

Affected elements:

- `:root`

	![screenshot](screenshots/6-0.jpg)

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

	![screenshot](screenshots/7-0.jpg), ![screenshot](screenshots/7-1.jpg)
- `#headlessui-popover-button-396719 > button`

	![screenshot](screenshots/8-0.jpg)
- `.hover\:bg-primary-50.dark\:hover\:bg-primary-800`

	![screenshot](screenshots/9-0.jpg), ![screenshot](screenshots/9-1.jpg), ![screenshot](screenshots/9-2.jpg), ![screenshot](screenshots/9-3.jpg), ![screenshot](screenshots/9-4.jpg), ![screenshot](screenshots/9-5.jpg), ![screenshot](screenshots/9-6.jpg), ![screenshot](screenshots/9-7.jpg), ![screenshot](screenshots/9-8.jpg), ![screenshot](screenshots/9-9.jpg), ![screenshot](screenshots/9-10.jpg), ![screenshot](screenshots/9-11.jpg), ![screenshot](screenshots/9-12.jpg)

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

- `iframe`

	![screenshot](screenshots/10-0.jpg), ![screenshot](screenshots/10-1.jpg)

### Alternative text of images should not be repeated as text

Ensure image alternative is not repeated as text

Impact: **minor**

Need to fix all the following issues:

- Element contains &lt;img&gt; element with alt text that duplicates existing text.

Affected elements:

- `.h-12.w-12[alt="Олександр Козак"]`

	![screenshot](screenshots/11-0.jpg)

### Ensures landmarks are unique

Landmarks should have a unique role or role/label/title (i.e. accessible name) combination

Impact: **moderate**

Need to fix one of the following issues:

- The landmark must have a unique aria-label, aria-labelledby, or title to make landmarks distinguishable.

Affected elements:

- `section[aria-labelledby="semantic-section-850012"]`

	![screenshot](screenshots/12-0.jpg)

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

	![screenshot](screenshots/13-0.jpg)

### Interactive controls must not be nested

Ensures interactive controls are not nested as they are not always announced by screen readers or can cause focus problems for assistive technologies

Impact: **serious**

Required to satisfy [WCAG 2.0 Level A](https://www.w3.org/TR/WCAG20/), [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf)

Need to fix one of the following issues:

- Element has focusable descendants.

Affected elements:

- `#headlessui-popover-button-396717`

	![screenshot](screenshots/14-0.jpg)
- `#headlessui-popover-button-396719`

	![screenshot](screenshots/15-0.jpg)
- `#headlessui-popover-button-396722`

	![screenshot](screenshots/16-0.jpg)
- `#headlessui-menu-button-396724`

	

