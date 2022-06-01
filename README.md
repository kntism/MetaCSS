# MetaCSS
 MetaCSS is only a basic stylesheet file. I like the idea of TailwindCSS，but don't like the complexity of it. So I create this for using in my project.

 Use it is very easy.

 You can download the `meta.css` file and put it into your project. Then you can import it to your stylesheet to use.

 For example:

```
<div class="boxes">
    <div class="box"></div>
    <div class="box"></div>
    <div class="box"></div>
    <div class="box"></div>
</div>
```

When you want to style the `boxes` to flex, you can:

```
<div class="boxes flex">
    <div class="box"></div>
    <div class="box"></div>
    <div class="box"></div>
    <div class="box"></div>
</div>
```

What you only do in your stylesheet is:

```
@import 'meta.css';
```