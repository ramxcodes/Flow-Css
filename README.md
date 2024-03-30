
# Flow CSS
 

`Flow CSS` is a lightweight CSS utility library created by Ramkrishna aka @ramxcodes. It provides simple utility classes to quickly style your HTML elements. With Flow CSS, create modern, aesthetically pleasing websites has never been easier. Design faster, smarter, better!
<p style="font-size: 1.6rem;">Go with the <b>Flow</b>, CSS that Makes Your Website <b>Glow</b>!</p>

![GitHub repo size](https://img.shields.io/github/repo-size/ramxcodes/Flow-Css)
![GitHub stars](https://img.shields.io/github/stars/ramxcodes/Flow-Css?style=social)
![GitHub forks](https://img.shields.io/github/forks/ramxcodes/Flow-Css?style=social)
[![Twitter Follow](https://img.shields.io/twitter/follow/ramxcodes?style=social)](https://twitter.com/intent/follow?screen_name=ramxcodes)



## Table of Contents
- [Getting Started](#getting-started)
- [Utility Classes](#utility-classes)
- [Spacing Padding and Margin](#Spacing-Padding-and-Margin)
- [Text and Element Alignment](#Text-and-Element-Alignment)
- [Text and Background Colors](#text-and-background-colors)
- [Screen Height and Width](#screen-height-and-width)
- [Display](#display)
- [Credits](#Credits)
- [License](#license)



## Getting Started

To get started with `Flow CSS`, simply include the CSS file in your HTML document.
<br>
<br>
<img style="height: 10em; width: 10em; border: 1px solid #000; border-radius: 1em;" src="Assests/logo.jpg" alt="">
<br>
<br>
<b>Local</b> 
```html
<link rel="stylesheet" href="flow.css">
```
<b>Cdn</b>
```html
<link rel="stylesheet" href="https://raw.githubusercontent.com/ramxcodes/ramxcodes/main/Flow-Css">
```

## Last Updated
Last updated : `31 March 2024`

<details>
<summary>changelog</summary>
<br>

| Version | Description |
|---|---|
| <p style="font-size: 2rem;"><b>V 1.0</b></p> | <ul><li>Removed all default styles for elements and pseudo elements</li><li>Added Custom Variables pseudo root class</li><li>Added Padding & Margin classes</li><li>Added Center Text and Element classes</li><li>Added Text color classes</li><li>Added Background color classes</li><li>Added screen height and width classes</li></ul> |
</details>

## Utility Classes

### Spacing Padding and Margin

`Flow CSS` provides utility classes for padding and margin. The classes follow a naming convention like `p-{value}` for padding and `m-{value}` for margin, where `{value}` ranges from 0 to 10.

Example:
```html
<div class="p-4">This div has padding of 1rem.</div>
<div class="m-2">This div has margin of 0.5rem.</div>
```

### Padding Classes

<details>
<summary>Padding</summary>
<br>

| Padding Classes | Description |
|---|---|
| p-0  | Padding of 0 |
| p-1  | Padding of 0.25rem |
| p-2  | Padding of 0.5rem |
| p-3  | Padding of 0.75rem |
| p-4  | Padding of 1rem |
| p-5  | Padding of 1.5rem |
| p-6  | Padding of 2rem |
| p-7  | Padding of 2.5rem |
| p-8  | Padding of 3rem |
| p-9  | Padding of 4rem |
| p-10 | Padding of 5rem |
</details>

<details>
<summary>Padding Top</summary>
<br>

| Padding Top Classes | Description |
|---|---|
| pt-0 | Padding top of 0 |
| pt-1 | Padding top of 0.25rem |
| pt-2 | Padding top of 0.5rem |
| pt-3 | Padding top of 0.75rem |
| pt-4 | Padding top of 1rem |
| pt-5 | Padding top of 1.5rem |
| pt-6 | Padding top of 2rem |
| pt-7 | Padding top of 2.5rem |
| pt-8 | Padding top of 3rem |
| pt-9 | Padding top of 4rem |
| pt-10| Padding top of 5rem |
</details>

<details>
<summary>Padding Bottom</summary>
<br>

| Padding Bottom Classes | Description |
|---|---|
| pb-0 | Padding bottom of 0 |
| pb-1 | Padding bottom of 0.25rem |
| pb-2 | Padding bottom of 0.5rem |
| pb-3 | Padding bottom of 0.75rem |
| pb-4 | Padding bottom of 1rem |
| pb-5 | Padding bottom of 1.5rem |
| pb-6 | Padding bottom of 2rem |
| pb-7 | Padding bottom of 2.5rem |
| pb-8 | Padding bottom of 3rem |
| pb-9 | Padding bottom of 4rem |
| pb-10| Padding bottom of 5rem |
</details>


<details>
<summary>Padding Left</summary>
<br>

| Padding left Classes | Description |
|---|---|
| pl-0 | Padding left of 0 |
| pl-1 | Padding left of 0.25rem |
| pl-2 | Padding left of 0.5rem |
| pl-3 | Padding left of 0.75rem |
| pl-4 | Padding left of 1rem |
| pl-5 | Padding left of 1.5rem |
| pl-6 | Padding left of 2rem |
| pl-7 | Padding left of 2.5rem |
| pl-8 | Padding left of 3rem |
| pl-9 | Padding left of 4rem |
| pl-10| Padding left of 5rem |
</details>

<details>
<summary>Padding Right</summary>
<br>

| Padding Right Classes | Description |
|---|---|
| pr-0 | Padding right of 0 |
| pr-1 | Padding right of 0.25rem |
| pr-2 | Padding right of 0.5rem |
| pr-3 | Padding right of 0.75rem |
| pr-4 | Padding right of 1rem |
| pr-5 | Padding right of 1.5rem |
| pr-6 | Padding right of 2rem |
| pr-7 | Padding right of 2.5rem |
| pr-8 | Padding right of 3rem |
| pr-9 | Padding right of 4rem |
| pr-10| Padding right of 5rem |
</details>

<details>
<summary>Padding Left & Right</summary>
<br>

| Padding Left & Right Classes | Description |
|---|---|
| px-0 | Padding Left & Right of 0 |
| px-1 | Padding Left & Right of 0.25rem |
| px-2 | Padding Left & Right of 0.5rem |
| px-3 | Padding Left & Right of 0.75rem |
| px-4 | Padding Left & Right of 1rem |
| px-5 | Padding Left & Right of 1.5rem |
| px-6 | Padding Left & Right of 2rem |
| px-7 | Padding Left & Right of 2.5rem |
| px-8 | Padding Left & Right of 3rem |
| px-9 | Padding Left & Right of 4rem |
| px-10| Padding Left & Right of 5rem |
</details>

<details>
<summary>Padding Top & Bottom</summary>
<br>

| Padding Top & Bottom Classes | Description |
|---|---|
| py-0 | Padding Top & Bottom of 0 |
| py-1 | Padding Top & Bottom of 0.25rem |
| py-2 | Padding Top & Bottom of 0.5rem |
| py-3 | Padding Top & Bottom of 0.75rem |
| py-4 | Padding Top & Bottom of 1rem |
| py-5 | Padding Top & Bottom of 1.5rem |
| py-6 | Padding Top & Bottom of 2rem |
| py-7 | Padding Top & Bottom of 2.5rem |
| py-8 | Padding Top & Bottom of 3rem |
| py-9 | Padding Top & Bottom of 4rem |
| py-10| Padding Top & Bottom of 5rem |
</details>


### Margin Classes

<details>
<summary>Margin</summary>
<br>

| Margin Classes | Description |
|---|---|
| m-0  | Margin of 0 |
| m-1  | Margin of 0.25rem |
| m-2  | Margin of 0.5rem |
| m-3  | Margin of 0.75rem |
| m-4  | Margin of 1rem |
| m-5  | Margin of 1.5rem |
| m-6  | Margin of 2rem |
| m-7  | Margin of 2.5rem |
| m-8  | Margin of 3rem |
| m-9  | Margin of 4rem |
| m-10 | Margin of 5rem |
</details>

<details>
<summary>Margin Top</summary>
<br>

| Margin Top Classes | Description |
|---|---|
| mt-0 | Margin top of 0 |
| mt-1 | Margin top of 0.25rem |
| mt-2 | Margin top of 0.5rem |
| mt-3 | Margin top of 0.75rem |
| mt-4 | Margin top of 1rem |
| mt-5 | Margin top of 1.5rem |
| mt-6 | Margin top of 2rem |
| mt-7 | Margin top of 2.5rem |
| mt-8 | Margin top of 3rem |
| mt-9 | Margin top of 4rem |
| mt-10| Margin top of 5rem |
</details>

<details>
<summary>Margin Bottom</summary>
<br>

| Margin Bottom Classes | Description |
|---|---|
| mb-0 | Margin bottom of 0 |
| mb-1 | Margin bottom of 0.25rem |
| mb-2 | Margin bottom of 0.5rem |
| mb-3 | Margin bottom of 0.75rem |
| mb-4 | Margin bottom of 1rem |
| mb-5 | Margin bottom of 1.5rem |
| mb-6 | Margin bottom of 2rem |
| mb-7 | Margin bottom of 2.5rem |
| mb-8 | Margin bottom of 3rem |
| mb-9 | Margin bottom of 4rem |
| mb-10| Margin bottom of 5rem |
</details>


<details>
<summary>Margin Left</summary>
<br>

| Margin left Classes | Description |
|---|---|
| ml-0 | Margin left of 0 |
| ml-1 | Margin left of 0.25rem |
| ml-2 | Margin left of 0.5rem |
| ml-3 | Margin left of 0.75rem |
| ml-4 | Margin left of 1rem |
| ml-5 | Margin left of 1.5rem |
| ml-6 | Margin left of 2rem |
| ml-7 | Margin left of 2.5rem |
| ml-8 | Margin left of 3rem |
| ml-9 | Margin left of 4rem |
| ml-10| Margin left of 5rem |
</details>

<details>
<summary>Margin Right</summary>
<br>

| Margin Right Classes | Description |
|---|---|
| mr-0 | Margin right of 0 |
| mr-1 | Margin right of 0.25rem |
| mr-2 | Margin right of 0.5rem |
| mr-3 | Margin right of 0.75rem |
| mr-4 | Margin right of 1rem |
| mr-5 | Margin right of 1.5rem |
| mr-6 | Margin right of 2rem |
| mr-7 | Margin right of 2.5rem |
| mr-8 | Margin right of 3rem |
| mr-9 | Margin right of 4rem |
| mr-10| Margin right of 5rem |
</details>

<details>
<summary>Margin Left & Right</summary>
<br>

| Margin Left & Right Classes | Description |
|---|---|
| mx-0 | Margin Left & Right of 0 |
| mx-1 | Margin Left & Right of 0.25rem |
| mx-2 | Margin Left & Right of 0.5rem |
| mx-3 | Margin Left & Right of 0.75rem |
| mx-4 | Margin Left & Right of 1rem |
| mx-5 | Margin Left & Right of 1.5rem |
| mx-6 | Margin Left & Right of 2rem |
| mx-7 | Margin Left & Right of 2.5rem |
| mx-8 | Margin Left & Right of 3rem |
| mx-9 | Margin Left & Right of 4rem |
| mx-10| Margin Left & Right of 5rem |
</details>

<details>
<summary>Margin Top & Bottom</summary>
<br>

| Margin Top & Bottom Classes | Description |
|---|---|
| my-0 | Margin Top & Bottom of 0 |
| my-1 | Margin Top & Bottom of 0.25rem |
| my-2 | Margin Top & Bottom of 0.5rem |
| my-3 | Margin Top & Bottom of 0.75rem |
| my-4 | Margin Top & Bottom of 1rem |
| my-5 | Margin Top & Bottom of 1.5rem |
| my-6 | Margin Top & Bottom of 2rem |
| my-7 | Margin Top & Bottom of 2.5rem |
| my-8 | Margin Top & Bottom of 3rem |
| my-9 | Margin Top & Bottom of 4rem |
| my-10| Margin Top & Bottom of 5rem |
</details>


### Text and Element Alignment

Classes `text-center`, `center-x`, `center-y`, and `center-xy` are provided for text and element alignment.

Example:
```html
<div class="text-center">This text is centered.</div>
<div class="center-x">This element is horizontally centered.</div>
<div class="center-y">This element is vertically centered.</div>
<div class="center-xy">This element is horizontally and vertically centered.</div>
```

### Text and Background Colors

Utility classes are available for text and background colors using semantic color names.

Example:
```html
<div class="text-primary">This text is in primary color.</div>
<div class="bg-secondary">This div has secondary background color.</div>
```
<details>
<summary>Text Colors</summary>
<br>

<p style='color: #007bff;'>text-primary</p>
<p style='color: #6c757d;'>text-secondary</p>
<p style='color: #28a745;'>text-success</p>
<p style='color: #dc3545;'>text-danger</p>
<p style='color: #ffc107;'>text-warning</p>
<p style='color: #17a2b8;'>text-info</p>
<p style='color: #f8f9fa;'>text-light</p>
<p style='color: #343a40;'>text-dark</p>
</details>

<details>
<summary>Background Colors</summary>
<br>

<p style='background-color: #007bff; color: #343a40;'>bg-primary</p>
<p style='background-color: #6c757d; color: #343a40;'>bg-secondary</p>
<p style='background-color: #28a745; color: #343a40;'>bg-success</p>
<p style='background-color: #dc3545; color: #343a40;'>bg-danger</p>
<p style='background-color: #ffc107; color: #343a40;'>bg-warning</p>
<p style='background-color: #17a2b8; color: #343a40;'>bg-info</p>
<p style='background-color: #f8f9fa; color: #343a40;'>bg-light</p>
<p style='background-color: #343a40; color: #ffffff;'>bg-dark</p>
</details>


### Screen Height and Width

Classes `screen-height` and `screen-width` are provided to set elements to full viewport height and width.

Example:
```html
<div class="screen-height">This div takes full viewport height.</div>
<div class="screen-width">This div takes full viewport width.</div>
```

### Display

Classes like `inline`, `block`, and `inline-block` are available to set the display property of elements.

Example:
```html
<span class="inline">This text is displayed inline.</span>
<div class="block">This div is displayed as a block element.</div>
<div class="inline-block">This div is displayed as a inline block element.</div>
```

## Credits

`Flow CSS` is created by `Ramkrishna` don't forgot to star the git repo follow me on github [ramxcodes](https://github.com/ramxcodes).

## Contributing

Feel free to contribute to `Flow CSS` by submitting `pull requests` or `opening issues` on GitHub.

## License

`Flow CSS` is released under the MIT License. See [LICENSE](./LICENSE) for details.