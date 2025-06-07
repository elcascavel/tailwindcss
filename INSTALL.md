### [Tailwind](https://tailwindcss.com)

A Tailwind theme that enables the use of the Dracula colour palette.

Hopefully this will give you some great dark colors in your next project, and save you 5 min of setting up custom colors.

#### Installation

```
npm i tailwind-dracula --save-dev
```

#### Usage

Import theme in same file as your `tailwindcss` import.

```scss
@import "tailwindcss";
@import "tailwind-dracula/dracula.css";
```

You now have access to the Dracula theme anywhere you would use normally tailwind colours.

```html
<div class="bg-drac-buffy">
  <p class="text-drac-nosferatu">I vant to suck your blood...</p>
</div>
```

Color naming has two options (based on Dracula's names with some changes where needed):

- The color name option. <i>ie. darker, pink, purple</i>
- The vampire name option. <i>ie. dracula, vonCount, buffy</i>
