# vuenotes

Front-end frameworks aim to fix the following issues in front-end web development:

- Long development times
- Difficult bug fixes and updates
- Slow page rendering

The first thing you’ll need to do to begin using any front-end framework is to add the framework to your project. You can import Vue by adding a `<script>` tag inside the `<head>` of your project’s HTML file:

```
<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js" defer></script>
```

Above we load the current version of Vue, hosted by the Vue team, directly into your project. We use the defer attribute on the `<script>` tag to make sure that the page is loaded and ready to hook up to Vue before we actually load Vue.