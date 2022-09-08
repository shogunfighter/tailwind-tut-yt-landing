This is a practice I found in youtube. 
Kodus to the original author. [link](https://www.youtube.com/watch?v=00gyCtIQp8E)

```
#### tailwind dependency
$ npm install -D tailwindcss

#### integrate with IDE - class intellisense
$ npm i autoprefixer postcss -D
```

#### create the tailwind.config.js (we modified the config, see the changes in the file)
```
$ npx tailwindcss init
```

#### add to package.json script to watch and compile tailwind
```
$ npx tailwindcss -i ./src/tailwind.css -o ./dist/tailwind-public.css --watch
```

#### create index.html and add in the required repos
```
<!-- font-awesome version 5.15.3 -->
<link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"
    integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w=="
    crossorigin="anonymous"
    referrerpolicy="no-referrer"
/>

<!-- our tailwind compiled file -->
<link href="tailwind-public.css" rel="stylesheet">
```

#### start practicing with the tutorial: [link](https://www.youtube.com/watch?v=00gyCtIQp8E)