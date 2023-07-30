---
title: Matt Anderson
summary: Slide Deck for Matt Anderson
authors: []
tags: ['Highlights']
categories: []
date: '2019-02-05'
slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: night
  size: 16:9

  # Choose a code highlighting style (see Hugo docs on Chroma)
  #   Light style: github-light. Dark style: dracula (default).
  highlight_style: dracula
  paginate: false

# https://gist.github.com/yhatt/a7d33a306a87ff634df7bb96aab058b5
---

# Matt Anderson

[Website](https://andersonrayner.github.io/) | [Google Scholar](https://scholar.google.com/citations?user=yG6xm2gAAAAJ) | [CV](https://github.com/AndersonRayner/cv/releases/download/main/ANDERSON_Matt.pdf) | [Download Slides](https://github.com/AndersonRayner/AndersonRayner.github.io/releases/download/main/ANDERSON_Matt_Slides.pdf)

![bg opacity ](images/river/colorado_river1.jpg)

---

# LINC
- Learing intropsection and control
- slkdjfklj
- sdfs

<!-- ![width:100px height:100px](./image.jpg) ![width:100px height:100px](./image.jpg)
![width:100px height:100px](./image.jpg) ![width:100px height:100px](./image.jpg) -->

<!-- ![bg](./image.jpg) ![bg](./image.jpg) -->
<!-- ![bg](./image.jpg) -->
![bg right:60% vertical ](images/image.jpg)
![Volcano](images/volcano/volcano0.jpg)
<!-- ![](./image.jpg) -->

---

## <!--fit--> Auto-fitting header (only for Marp Core) sjkldfjslkfdjkl sjfkl sjkf
![bg left](./image.jpg)

![width:100px height:100px](./image.jpg)


---

![bg right](./image.jpg)

## Features

- Efficiently write slides in Markdown
- 3-in-1: Create, Present, and Publish your slides
- Supports speaker notes
- Mobile friendly slides

* Efficiently write slides in Markdown
  * 3-in-1: Create, Present, and Publish your slides
* Supports speaker notes
  * Mobile friendly slides


---

## Controls

- Next: `Right Arrow` or `Space`
- Previous: `Left Arrow`
- Start: `Home`
- Finish: `End`
- Overview: `Esc`
- Speaker notes: `S`
- Fullscreen: `F`
- Zoom: `Alt + Click`
- [PDF Export](https://revealjs.com/pdf-export/)

---

## Code Highlighting
![bg opacity](https://yhatt-marp-cli-example.netlify.com/assets/gradient.jpg)

Inline code: `variable`

Code block:

```python
porridge = "blueberry"
if porridge == "blueberry":
    print("Eating...")
```

---

# Math

In-line math: $x + y = z$

Block math:

$$
f\left( x \right) = \;\frac{{2\left( {x + 4} \right)\left( {x - 4} \right)}}{{\left( {x + 4} \right)\left( {x + 1} \right)}}
$$


### Math down a slide
In-line math: $x + y = z$

Block math:

$$
f\left( x \right) = \;\frac{{2\left( {x + 4} \right)\left( {x - 4} \right)}}{{\left( {x + 4} \right)\left( {x + 1} \right)}}
$$


---

## Fragments

Make content appear incrementally

```
{{</* fragment */>}} $\mathbf{y} =  $ {{</* /fragment */>}}
{{</* fragment */>}} $X\boldsymbol\beta$ {{</* /fragment */>}}
{{</* fragment */>}} $+ \boldsymbol\varepsilon$ {{</* /fragment */>}}
```

Press `Space` to play!

{{< fragment >}} $\mathbf{y} =  $ {{< /fragment >}}
{{< fragment >}} $X\boldsymbol\beta$ {{< /fragment >}}
{{< fragment >}} $+ \boldsymbol\varepsilon$ {{< /fragment >}}

---

A fragment can accept two optional parameters:

- `class`: use a custom style (requires definition in custom CSS)
- `weight`: sets the order in which a fragment appears

---

## Speaker Notes

Add speaker notes to your presentation

```markdown
{{%/* speaker_note */%}}

- Only the speaker can read these notes
- Press `S` key to view

{{%/* /speaker_note */%}}
```

Press the `S` key to view the speaker notes!

{{< speaker_note >}}

- Only the speaker can read these notes
- Press `S` key to view

{{< /speaker_note >}}

---

## Themes

- black: Black background, white text, blue links (default)
- white: White background, black text, blue links
- league: Gray background, white text, blue links
- beige: Beige background, dark text, brown links
- sky: Blue background, thin dark text, blue links

---

- night: Black background, thick white text, orange links
- serif: Cappuccino background, gray text, brown links
- simple: White background, black text, blue links
- solarized: Cream-colored background, dark green text, blue links

---

{{< slide background-image="boards.webp" >}}

## Custom Slide

Customize the slide style and background

```markdown
{{</* slide background-image="boards.webp" */>}}
{{</* slide background-color="#0000FF" */>}}
{{</* slide class="my-style" */>}}
```

---

## Custom CSS Example

Let's make headers navy colored.

Create `assets/css/reveal_custom.css` with:

```css
.reveal section h1,
.reveal section h2,
.reveal section h3 {
  color: navy;
}
```

---

# Questions?

[Ask](https://discord.gg/z8wNYzb)

[Documentation](https://wowchemy.com/docs/content/slides/)
