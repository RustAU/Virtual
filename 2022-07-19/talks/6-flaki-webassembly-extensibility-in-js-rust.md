---
type: slide
slideOptions:
  theme: white
  transition: slide
---

<style>
    .reveal section img {
        border-color: rgba(0,128,255,.4);
        border-radius: 10px;
    }
    .reveal h1 {
        color: #654ff0;
        text-shadow: 0 5px white;
        font-family: Dela Gothic One;
        font-size: 1em;
        padding-bottom: 50vh;
    }
    .reveal h6 {
        padding: 1em;
    }
    .reveal blockquote {
        width: auto;
    }
</style>

<!-- .slide: data-background="https://markdown.flak.is/uploads/upload_e7ab490e6489473a8b511ffb738a9cec.png" data-background-color="#fff" data-background-size="60vh" -->

# WebAssembly Extensibility<br />with JavaScript — and Rust!

---

![It me!](https://flak.is/s/flaki.png =128x128)

Hi, I'm Flaki!
<small>(the short for "Istvan Szmozsanszky")</small>

[@flakoot@toot.cafe](https://toot.cafe/@flakoot/) | [@slsoftworks](https://twitter.com/slsoftworks)


<a href="https://suborbital.dev/"><img src="https://ucarecdn.com/f429371c-399f-43dc-90fa-0a047a8da2f3/" style="height: 10vh"></a>
<a href="https://rustfest.world/"><img src="https://rustfest.world/assets/posts/project/rustfest-project-header.png" style="height: 10vh"></a>


---

<iframe width="560" height="315" sandbox="allow-same-origin allow-scripts allow-popups" title="A WebAssembly Field Guide easily worth like 70 bottle caps — Flaki @ JSConf Korea 2019" src="https://pityu.flaki.hu/videos/embed/962bdc3c-7525-4a84-87af-084a9420a893" frameborder="0" allowfullscreen></iframe>

###### [A WebAssembly Field Guide easily worth like 70 bottle caps — Flaki @ JSConf Korea 2019](https://pityu.flaki.hu/videos/watch/962bdc3c-7525-4a84-87af-084a9420a893)

---

<img src="https://bytecodealliance.org/articles/img/2021-06-02-js-on-wasm/02-01-but-why.png" style="height: 50vh; border: none; box-shadow: none">


###### "<a href="https://bytecodealliance.org/articles/making-javascript-run-fast-on-webassembly">Making JavaScript run fast on WebAssembly</a>",<br/> image & blogpost by Lin Clark

---

> - Good for the browser, great for the cloud 
> - Security and sandboxing
> - Cross-platform and cross-architecture
> 
> — ["Why WebAssembly Belongs Outside the Browser"](https://www.wasm.builders/thomastaylor312/why-webassembly-belongs-outside-the-browser-331a)
> 
<!--
WebAssembly in the *Web browser* was hailed by many as our lord & savior from JavaScript's terror. Many, except the people who were actually building the technology. WebAssembly *is* intended to break the haegemony of JS on the Web -- but in cooperation with JS and not via *[defenestration](https://en.wikipedia.org/wiki/Defenestration)*.

I stress *the Web browser*, because it's an important distinction to make. When it comes to outside-of-the-browser usecases...
-->

---

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/rPf7llaTWvg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Using [Javy](https://github.com/Shopify/javy/tree/main/crates) in the WebAssembly Edge with [Suborbital](https://github.com/suborbital/javy)



---

[`wit-bindgen`](https://github.com/bytecodealliance/wit-bindgen)

[WebAssembly Interface Types](https://github.com/WebAssembly/interface-types)

###### Check out Radu's blogpost on [WebAssembly Components](https://radu-matei.com/blog/intro-wasm-components/)!

---

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/dlPVdzcgECQ?start=2233" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

###### [Using JavaScript & TypeScript in Suborbital Reactr](https://youtu.be/dlPVdzcgECQ?t=2233) <br> — by Oscar Spencer

---

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/C6pcWRpHWG0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

###### "[Wasm Snapshots for Fast Startup](https://www.youtube.com/watch?v=C6pcWRpHWG0)" using [Wizer](https://github.com/bytecodealliance/wizer) <br> — by Nick Fitzgerald

---

**Thank you!**

Slides:

![QR code version of the link below](img/qr-rustau.png)

[talk.flak.is/wasm/ext/rustau](https://talk.flak.is/wasm/ext/rustau)
