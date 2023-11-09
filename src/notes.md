# Notes

- npm create astro@latest = create new astro project
- npm run dev = run the dev server
- Anything between the 3 dashes seems like the dynamic javascript part
- Dynamic values are being recevied as Astro.props
- The general structure seems to be - 
    - Pages
    - Layout
    - Components
- All CSS is scoped by default by means of a unique id being generated for each element
- To use CSS just use style tag
- To use global on complete CSS we can use `<style is:global>`
- To use global on a particular selector we can use :global like so - `:global(h1) {}`
- `class:list` attribute can be used to assign an array of classes on an element.
- `class:list` is also used when we need dynamic CSS based on runtime value coming from JS
- `<h1 class:list={['box', {red: isRed}]}>` Here isRed is defined in the dashed area of the code
- To use variables in CSS we can use `define:vars` on style tag - `<style define:vars={{foreground, background}}>`. The variables `foreground` and `background` are defined in the dynamic section of the code
- 


