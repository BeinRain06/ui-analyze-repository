## Analyzing heurio.com website

![./assets/%20Dieter%20Rams'%2010%20Principles%20of%20Good%20Design%20Heurio%20-%20landing-page.png](./assets/%20Dieter%20Rams'%2010%20Principles%20of%20Good%20Design%20Heurio%20-%20landing-page.png)

    heurio.com--analyze-layout-white_space-class_css

[https://www.heurio.co/dieter-rams-10-principles-of-good-design](https://www.heurio.co/dieter-rams-10-principles-of-good-design)

### Colors Pattern

#### 1. background-navbar + color navbar

    Hex code: #fff //bg-nav

    Hex code: #303d4e // color-text

#### Type: pure **white** (--white) & dark black (--black-800)

#### 2. background-body

    Hex code: #f7f8fa ; font-weight: 400; line-height: 30; font-size: 18px

#### Type: soft **blue-gray** (--blueish-grey--25)

#### 3. bg-color-main-button

    Hex code: #2ea2f6

#### Type: light **Blue** (--blue--500)

#### 4. color-text-auxiliary-button

    Hex code: #303d4e // color-text (background: transparent)

#### Type: **dark black** (--black-800)

#### 5. background-section1-body

    Hex code: #1c232d

#### Type: strong **Dark-Blue** (--blue--900)

#### 6. background-section2-body

    Hex code: #fff

#### Type: pure **White**

#### 7. color-text-subheading

    Hex code: #1c232d ; font-weight: 700; line-height: 28; font-size: 18px

#### Type: **dark black** (--black-900)

#### 8. color-text-body

    Hex code: #303d4e; font-weight: 400; line-height: 24; font-size: 16px

#### Type: **dark black** (--black-800)

#### 9. color-text-main-button & footer

    Hex code: #fff

#### Type: pure **White**

#### 10. color-text-higlight

    Hex code: #9dacc1; font-weight: 700; line-height: 24; font-size: 12px

#### Type: **blue-gray** (--blueish-grey--300-301)

#### 11. color-text-title2

    Hex code: #4c617f; font-weight: 700; line-height: 24; font-size: 12px

#### Type: **blue-gray** (--blueish-grey--600)

#### 12. color-text-link-body

    Hex code: #2ea2f6; font-weight: 600; line-height: 24; font-size: 14px

#### Type: light **Blue** (--blue--500)

#### 13. color-text-link-footer

    Hex code: #9dacc1; font-weight: 500; line-height: 20px; font-size: 14px

    Hex code: #4c617f; font-weight: 500; line-height: 20px; font-size: 14px

#### Type: light **Blue** (--blueish-grey--300-301) & (--blueish-grey--600)

#### 14. background-color-footer

    Hex code: #092031; font-weight: 400; line-height: 30; font-size: 18px; max-width: 1280px

#### Type: dark **Blue** (--blue--900)

---

### Colors scheme Recaps

| color          | hex code | area                     | mood                      | annotation              |
| -------------- | -------- | ------------------------ | ------------------------- | ----------------------- |
| soft blue-gray | #f7f8fa; | background-body          | peaceful, comfortable     | --blueish-grey--25      |
|                |          |                          |                           |                         |
|                |          | background-navbar        |                           |                         |
|                |          | text-main-button         |                           |                         |
| white          | #fff     | text-hero-title          | optimist, clear, engaging | --white                 |
|                |          |                          |                           |                         |
|                | #092031  | background-section1-body | reliability, easiness     |                         |
| dark blue      |          | background-footer        | reliability, easiness     | --blue-900              |
|                |          |                          |                           |                         |
| light blue     | #2ea2e6  | background-main-button   | appeasing , cool, soft    | --blue--500             |
|                |          |                          |                           |                         |
|                | #9dacc1  | text-highlight           |                           | --blueish-grey--300-301 |
|                |          | text-link-footer-1       |                           |                         |
|                |          |                          |                           |                         |
| blue-gray      |          | text-title2              |                           |                         |
|                | #4c617f  | text-link-footer-2       |                           | --blueish-grey--600     |
|                |          |                          |                           |                         |
| dark-black-1   | #1c232d  | text-subheading          |                           | --black-900             |
|                |          |                          |                           |                         |
| dark-black-2   | #303d4c  | text-paragraph           |                           |                         |
|                |          | text-aux.-button         |                           | --black-800             |
|                |          | text-nabar-link          |                           |                         |

### Tips class css style

### create default design

#### A/ TITLE

**h1** , **h2**, ... (style : margin-top, margin-bottom, font-family, font-size, font-weight, line-height)

**remarks** : In case you nedd to modify one style attribute in a specific component , just add a **classname** to the html tag (h1, h2, ...) and under the css file of this component modify properties you want (e.g: font-size, line-height)

#### A/ Link

**a**, ... (style : font-family, font-size, font-weight, line-height, cursor-pointer, text-decoration)

**a** specific button in a component `<a class="nav-btn w-button"></a>` or `<a class="nav-link w-nav-link"></a>`

(**nav-btn/nav-link** style : color, background-color, margin, padding, display, font-size, line-height, border, border-radius, transition)

(**w-button/w-nav-link** style : color, background-color, margin, padding, font-size, line-height, border )

**remarks**:

- **a** & **h1, h2, ...**, **div** : `same font-family` (1) // e.g: font-family: Gordita,sans-serif;
- **p** , **span**, **div** : `same font-famiy` (2) // e.g: font-family: Manrope,sans-serif;

(1) different of (2) .

<br/>

### Text CSS main-properties (project)

`font-size, font-family, font-weight, line-height, font-size`

#### font-size

font-size :

- 42px ~ (hero-section-title),
- 18px ~ (link-footer-title, paragraph, subtitle),
- 16px ~ (text-button, pargagraph)
- 14px ~ (link-footer-item, ),
- 12px(external-link),

#### line-height

line-height:

- 54px(hero-title) 30px(gen-body),
- 28px(title),
- 24px(subtitle, link, paragraph),
- 20px(footer-item)

#### title

title : h1, h2, h3
