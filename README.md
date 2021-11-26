# SpreadSimple-Code
> A little place to hold all the custom code snippets used inside of spread simple SaaS to improve UI/UX
> in order to make things a little easier to find rather than digging through hundreds of posts the snips will be catagorically organized provided by the community at large (Spreadsimple). This repository contains basice HTML, CSS, and Javascript code used in the edit sections of a spreadsimple project. This code is assumed to be tested by the person who has submitted and in as many cases as possible the submitter will also provide a link to their project or a screenshot showing how the code affects the front end inteface of their project.

* you can check out the [Spreadsimple](https://spreadsimple.com) website and take a look at the amazing SaaS product they offer!

<details closed>
<summary>Search Bar Customization</summary>
<br>
  
```
.sv-viewer-form__search-inner {border: 1px solid #e9ecef; border-radius:10px}
.sv-viewer-form__input-icon {
padding-right: 10px;
padding-left: 10px;
background-color: #fafafa;
margin-right: 5px;
}
```
  
Thank You: Fernando Vasco
</details>

<details closed>
<summary>Remove darsj shade on main image</summary>
<br>
  
```
<style>
.sv-viewer-intro.sv-has-cover:before {opacity:0}
}
</style>
```
  
Thank You: Felipe Chaves
</details>

<details closed>
<summary>Resize main image</summary>
<br>
  
```
<style>
.sv-viewer-intro__logo.sv-img-reset {
max-width: 300px;
max-height: 150px;
}
</style>
```
  
Thank You: Felipe Chaves
</details>

<details closed>
<summary>Radius square and HEX colors for badge</summary>
<br>
  
```
<style>
.sv-badge { border-radius: 0px; }
.sv-badge__1 { background-color: #77c9d6; color: #0f0f0f }
.sv-badge__2 { background-color: #77c9d6; color: #0f0f0f }
.sv-badge__3 { background-color: #77c9d6; color: #0f0f0f }
.sv-badge__4 { background-color: #77c9d6; color: #0f0f0f }
.sv-badge__5 { background-color: #276bb0; }
.sv-badge__6 { background-color: #276bb0; }
.sv-badge__7 { background-color: #e0e27c; color: #0f0f0f }
.sv-badge__8 { background-color: #fde1eb; color: #696969 }
.sv-badge__9 { background-color: #98f5FF; color: #696969 }
</style>
```
  
Thank You: François P
</details>


<details closed>
<summary>New back button in details page</summary>
<br>
  
```
<style>
.sv-product__back-btn {
width: 100px;
height: 40px;
font-size: 12px;
border: 2px solid;
border-radius: 0%;
}
.sv-icon-arrow:before {
content: "\E905"" RETOUR";
}
</style>
```
  
Thank You: François P
</details>

<details closed>
<summary>No text when empty result after search</summary>
<br>
  
```
<style>
.sv-viewer__empty-state-title {
font-size: 0px;
}
.sv-viewer__empty-state-subtitle {
font-size: 0px;
}
</style>
```
  
Thank You: François P
</details>

<details closed>
<summary>Modify alignement of specifications in detail pages</summary>
<br>
  
```
<style>.sv-product__spec { align-items: baseline; } </style>
```
  
Thank You: François P
</details>



