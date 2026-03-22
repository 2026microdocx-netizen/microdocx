# Microdocx Brand Colors

## Primary Colors
- **Primary Green:** #3EDD03
- **Primary Gray:** #808488

## Secondary Colors
- **Dark Gray:** #778B76
- **Light Green:** #E4FAD1
- **Light Gray:** #C1F3AD

## Usage
- **Web background:** #FFFFFF (white)
- **Dark mode background:** #1a1a1a (very dark gray)
- **Primary accent:** #3EDD03 (bright green - buttons, highlights)
- **Secondary accent:** #808488 (gray - text, borders)

## CSS Variables

:root {
  --primary-green: #3EDD03;
  --primary-gray: #808488;
  --dark-gray: #778B76;
  --light-green: #E4FAD1;
  --light-gray: #C1F3AD;
  --white: #FFFFFF;
  --dark-bg: #1a1a1a;
}

[data-theme="dark"] {
  --bg: #1a1a1a;
  --text: #FFFFFF;
  --accent: #3EDD03;
}