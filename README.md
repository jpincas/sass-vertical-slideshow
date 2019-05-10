# Pure SASS Vertical Slideshow/Gallery/Scroller

Uses CSS keyframe animation to create a multistep slideshow that transitions with a vertical stepped 'scroll'.

Demo: [https://codepen.io/jpincas/pen/xNVEOr](https://codepen.io/jpincas/pen/xNVEOr)

Use SASS variables to control the slides:

```scss
$noItems: 5;
$words: 31;
$fontSize: 18px;
$animationSpeed: 1s;
```

Put your content in a `ul` inside a container with `ss-container` class:

```html
<section class="ss-container">
    <ul>
        <li>T1 Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ratione, voluptate, error ea voluptates
            soluta voluptas nam excepturi eius molestias officia dolor nobis adipisci temporibus eos laudantium
            obcaecati cum aspernatur veniam.</li>

        <li>T2 Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ratione, voluptate, error ea voluptates
            soluta voluptas nam excepturi eius molestias officia dolor nobis adipisci temporibus eos laudantium
            obcaecati cum aspernatur veniam.</li>

        <li>T3 Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ratione, voluptate, error ea voluptates
            soluta voluptas nam excepturi eius molestias officia dolor nobis adipisci temporibus eos laudantium
            obcaecati cum aspernatur veniam.</li>

        <li>T4 Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ratione, voluptate, error ea voluptates
            soluta voluptas nam excepturi eius molestias officia dolor nobis adipisci temporibus eos laudantium
            obcaecati cum aspernatur veniam.</li>

        <li>T5 Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ratione, voluptate, error ea voluptates
            soluta voluptas nam excepturi eius molestias officia dolor nobis adipisci temporibus eos laudantium
            obcaecati cum aspernatur veniam.</li>
    </ul>
</section>
```

