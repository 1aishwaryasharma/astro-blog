# Notes

## General

- npm create astro@latest = create new astro project
- npm run dev = run the dev server
- Anything between the 3 dashes seems like the dynamic javascript part
- Dynamic values are being recevied as Astro.props
- The general structure seems to be - 
    - Pages
    - Layout
    - Components

## Styling

- All CSS is scoped by default by means of a unique id being generated for each element
- To use CSS just use style tag
- To use global on complete CSS we can use `<style is:global>`
- To use global on a particular selector we can use :global like so - `:global(h1) {}`
- `class:list` attribute can be used to assign an array of classes on an element.
- `class:list` is also used when we need dynamic CSS based on runtime value coming from JS
- `<h1 class:list={['box', {red: isRed}]}>` Here isRed is defined in the dashed area of the code
- To use variables in CSS we can use `define:vars` on style tag - `<style define:vars={{foreground, background}}>`. The variables `foreground` and `background` are defined in the dynamic section of the code
- We can also use inline styles in the css-as-js format - `<h1 style={{fontWeight: 300}}>`
- We can also use *.css files by importing them into our files
- We can also use external CSS libraries like tailwind.
- npx astro add tailwind

## Routing

- Astro has support for both static and dynamic routing
- Each file creates a new route
- folders create new fragments of the URL
- index maps to /



