## Simple Guide to Updating Menu Code Blocks

### 1. Changing Menu Links

```html

Link Text
```

**To update a link:**
- Find the `href="/something"` part
- Replace what's between the quotes with your new URL
- Example: Change `/election-security` to `/new-program-page`

### 2. Changing Link Text

```html
Change This Text
```

**To update the text:**
- Look for the text between `>` and `</a>`
- Replace that text with your new wording
- Example: Change "Course Overview" to "Program Details"

### 3. Changing the Main Title

```html
CHANGE THIS TITLE
```

**To update the title:**
- Find the text between `>` and `</h2>`
- Replace with your new title
- Example: Change "ELECTION SECURITY" to "CYBER DEFENSE"

### 4. Changing Button Text

```html
CHANGE BUTTON TEXT
```

**To update button text:**
- Find the text between `>` and `</a>` in the button section
- Replace with your new button text
- Example: Change "LEARN MORE" to "REGISTER NOW"

### 5. Changing Colors

#### Background Color
```html

```

**To change the background color:**
- Find `background-color: #173852;`
- Replace the hex code (#173852) with your new color
- Example: Change to `background-color: #0a2240;`

#### Button Color
```html

```

**To change button color:**
- Find `background-color: #D4AF37;`
- Replace the hex code with your new color
- Example: Change to `background-color: #ffc72c;`

### 6. Changing Menu Width

```html

```

**To adjust the width:**
- Find `width: 300px;`
- Change the pixel value to make it wider or narrower
- Example: Change to `width: 350px;`

### 7. Adding a New Link

```html
New Link Text
```

**To add a new link:**
- Copy an existing `<li>...</li>` line
- Paste it where you want the new link to appear
- Update the href and link text with your new information

### Tips:
- Make a backup copy before editing
- Test your changes on a development site first
- Use a color picker tool to find hex codes for colors
- When in doubt, only change the parts mentioned above
- Keep the styling attributes to maintain consistent appearance