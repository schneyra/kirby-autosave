# Kirby Autosave
Saves your page automatically.

## Usage
Add the field to the blueprint of your pages. You can override the label and interval.

Example:

```yml
fields:
    ...
    autosave:
        label: Save me!
        interval: 3000
    ...
```

## Development
```bash
// develop
npx -y kirbyup serve src/index.js

// build
npx -y kirbyup src/index.js
```