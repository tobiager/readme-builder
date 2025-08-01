<div align="center">

<p align="center">
  <a href="https://github.com/tobiager" target="_blank">
    <img src="banner2.png" alt="Banner Constructor" width="800" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/tobiager/readme-builder?style=for-the-badge" />
  <img src="https://img.shields.io/github/forks/tobiager/readme-builder?style=for-the-badge" />
  <img src="https://img.shields.io/github/issues/tobiager/readme-builder?style=for-the-badge" />
</p>

<p align="center">
  <a href="https://github.com/tobiager">
    <img src="https://img.shields.io/github/followers/tobiager?label=Follow%20@tobiager&style=social" alt="Follow @tobiager" />
  </a>
</p>

# Readme Builder


✦ [How to Use](#how-to-use) ✦ [Top Contributors](#top-Contributors) ✦ 

##  What is this?

**README Builder** is a complete toolkit to create and customize professional GitHub READMEs without writing from scratch.  
It includes templates, badges, GitHub stats, custom banners, and everything you need to build a standout profile or project README.  
Perfect for developers who want to showcase their work, highlight contributions, and personalize their GitHub presence in minutes.

</div>

---

## Index

- [Advanced Formatting](#advanced-formatting)
- [GitHub Stats](#github-stats)
- [Badges & Shields](#badges--shields)
- [Creating GIFs](#creating-gifs)
- [How to Use](#how-to-use)
- [Examples](#examples)
- [Why This Exists](#why-this-exists)
- [License](#license)

---
<summary><h2>Advanced Formatting</h2></summary>


## Alerts

Alerts are a Markdown extension based on the blockquote syntax that you can use to emphasize critical information. They are displayed with distinct colors and icons to indicate the importance of the content.

> [!NOTE]  
> Useful information that users should know, even when skimming content.

> [!TIP]  
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]  
> Key information users need to know to achieve their goal.

> [!WARNING]  
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]  
> Advises about risks or negative outcomes of certain actions.

## Collapsible Section

You can temporarily hide sections of your Markdown by creating an expandable section that the reader can choose to open. For example, when you want to include technical details in an issue comment that might not be relevant or interesting to all readers, you can place those details in a collapsible section.

Any Markdown inside the `<details>` block will remain collapsed until the reader clicks to expand it.

Inside the `<details>` block, use the `<summary>` tag to give readers a preview of what's inside. The label appears next to the arrow.

<details>

<summary>Tips for collapsed sections</summary>

### You can add a header

You can add text within a collapsed section.

You can also include an image or a code block.

```ruby
   puts "Hello World"
```

</details>

## Mermaid Diagrams

**Mermaid** is a Markdown-inspired tool that transforms text into diagrams. For example, Mermaid can render flowcharts, sequence diagrams, pie charts, and much more.

To create a Mermaid diagram, add the Mermaid syntax inside a fenced code block with the language identifier `mermaid`.

Here is a simple flow chart:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

## Maps

You can use GeoJSON or TopoJSON syntax to create interactive maps. To create a map, place GeoJSON or TopoJSON inside a fenced code block using the `geojson` or `topojson` syntax identifier.

```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "properties": {
        "name": "Obelisco de Buenos Aires"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [-58.381570, -34.603738]
      }
    }
  ]
}


```

---

<details id="github-stats" close>
<summary><h2>GitHub Stats</h2></summary>

#  How to Use GitHub Stats Cards

## How to Use the Cards?

It's simple: just copy and paste into your README — and you're done!

Replace `tobiager` with your GitHub username if you're sharing this with others.

```md
[![card](https://github-readme-stats.vercel.app/api?username=tobiager&theme=default)](https://github.com/tobiager/github-readme-stats)
```

[![tobiager](https://github-readme-stats.vercel.app/api?username=tobiager&theme=default)](https://github.com/tobiager/github-readme-stats)

### Adding Icons

```md
[![card](https://github-readme-stats.vercel.app/api?username=tobiager&theme=default&show_icons=true)](https://github.com/anuraghazra/github-readme-stats)
```

[![tobiager](https://github-readme-stats.vercel.app/api?username=tobiager&theme=default&show_icons=true)](https://github.com/tobiager/github-readme-stats)

## Showing Languages

```md
[![tobiager](https://github-readme-stats.vercel.app/api/top-langs/?username=tobiager&hide=html&layout=compact&theme=default)](https://github.com/anuraghazra/github-readme-stats)
```

[![tobiager](https://github-readme-stats.vercel.app/api/top-langs/?username=tobiager&hide=html&layout=compact&theme=default)](https://github.com/tobiager/github-readme-stats)

## Or

```md
[![tobiager](https://github-readme-stats.vercel.app/api/top-langs/?username=tobiager&layout=compact)](https://github.com/anuraghazra/github-readme-stats)
```

[![tobiager](https://github-readme-stats.vercel.app/api/top-langs/?username=tobiager&layout=compact)](https://github.com/tobiager/github-readme-stats)

---
## 📊 GitHub Stats

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=tobiager&theme=transparent" width="90%" />
</p>

```md
<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=tobiager&theme=transparent" width="90%" />
```

📌 What it does:  
Summarizes your contributions: commits, PRs, issues, code reviews, and more — in a compact summary card.

## 📈 GitHub Graphic

<!-- GitHub Activity Graph -->
<a href="https://github.com/ashutosh00710/github-readme-activity-graph">
  <img alt="tobiager's Activity Graph" src="https://github-readme-activity-graph.vercel.app/graph/?username=tobiager&theme=github-compact&bg_color=00000000&color=2986cc&line=2986cc&point=3d85c6&area=true&hide_border=true" />
</a>

```md
<img alt="tobiager's Activity Graph" src="https://github-readme-activity-graph.vercel.app/graph/?username=tobiager&theme=github-compact&bg_color=00000000&color=2986cc&line=2986cc&point=3d85c6&area=true&hide_border=true" />
```

📌 What it does:  
Displays a heatmap-style graph showing your daily commit activity over time.

## 🔥 GitHub Streak

<p align="center">
  <img src="https://nirzak-streak-stats.vercel.app/?user=tobiager&theme=transparent&hide_border=true" />
</p>

```md
<img src="https://nirzak-streak-stats.vercel.app/?user=tobiager&theme=transparent&hide_border=true" />
```

📌 What it does:  
Tracks your current streak of consecutive days with contributions.

---

## 🔝 Top Contributed Repo

<p align="center">
  <img src="https://github-contributor-stats.vercel.app/api?username=tobiager&limit=5&theme=shadow_blue&combine_all_yearly_contributions=true" />
</p>

```md
<img src="https://github-contributor-stats.vercel.app/api?username=tobiager&limit=5&theme=shadow_blue&combine_all_yearly_contributions=true" />
```

📌 What it does:  
Lists the top repositories (including others') you've contributed to the most.

---

## 📍 Repositories Pin
<a href="https://github.com/tobiager/readme-builder">
  <img width="400" src="https://github-readme-stats.vercel.app/api/pin/?username=tobiager&repo=readme-builder&theme=transparent&hide_border=true" alt="readme-builder repo card"/>
</a>

<a href="https://github.com/tobiager/POO-UNNE-2024">
  <img width="400" src="https://github-readme-stats.vercel.app/api/pin/?username=tobiager&repo=POO-UNNE-2024&theme=transparent&hide_border=true" alt="POO-UNNE-2024 repo card"/>
</a>


```md
<a href="https://github.com/tobiager/readme-builder">
  <img width="400" src="https://github-readme-stats.vercel.app/api/pin/?username=tobiager&repo=readme-builder&theme=transparent&hide_border=true" alt="readme-builder repo card"/>
</a>

<a href="https://github.com/tobiager/POO-UNNE-2024">
  <img width="400" src="https://github-readme-stats.vercel.app/api/pin/?username=tobiager&repo=POO-UNNE-2024&theme=transparent&hide_border=true" alt="POO-UNNE-2024 repo card"/>
</a>
```

📌 What it does:  
Highlights specific repositories with details like name, description, stars, and tech stack — ideal for featured projects.

## Quick Tip (Align The Cards)

By default, GitHub does not lay out the cards side by side. To do that, you can use this approach:

```html
<a href="https://github.com/tobiager/github-readme-stats">
  <img height=200 align="center" src="https://github-readme-stats.vercel.app/api?username=tobiager" />
</a>
<a href="https://github.com/tobiager/github-readme-stats">
  <img height=200 align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=tobiager&layout=compact&langs_count=8&card_width=320" />
</a>
```

```html
<a href="https://github.com/tobiager/readme-builder">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=tobiager&repo=readme-builder" />
</a>
<a href="https://github.com/tobiager/readme-builder">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=tobiager&repo=POO-UNNE-2024" />
</a>
```

<details>
<summary>:eyes: Show example</summary>

<a href="https://github.com/tobiager/github-readme-stats">
  <img height=200 align="center" src="https://github-readme-stats.vercel.app/api?username=tobiager" />
</a>
<a href="https://github.com/tobiager/github-readme-stats">
  <img height=200 align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=tobiager&layout=compact&langs_count=8&card_width=320" />
</a>

***

<a href="https://github.com/tobiager/readme-builder">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=tobiager&repo=readme-builder" />
</a>
<a href="https://github.com/tobiager/readme-builder">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=tobiager&repo=POO-UNNE-2024" />
</a>

</details>

## Themes

Change `default` to the theme name you want to use.

Available themes: dark, radical, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, highcontrast, and dracula.

### Default

[![tobiager](https://github-readme-stats.vercel.app/api?username=tobiager&theme=default)](https://github.com/anuraghazra/github-readme-stats)

[![tobiager](https://github-readme-stats.vercel.app/api/top-langs/?username=tobiager&hide=html&layout=compact&theme=default)](https://github.com/anuraghazra/github-readme-stats)

### Dark

[![tobiager](https://github-readme-stats.vercel.app/api?username=tobiager&theme=dark)](https://github.com/anuraghazra/github-readme-stats)

[![tobiager](https://github-readme-stats.vercel.app/api/top-langs/?username=tobiager&hide=html&layout=compact&theme=dark)](https://github.com/anuraghazra/github-readme-stats)

### Radical

[![tobiager](https://github-readme-stats.vercel.app/api?username=tobiager&theme=radical)](https://github.com/anuraghazra/github-readme-stats)

[![tobiager](https://github-readme-stats.vercel.app/api/top-langs/?username=tobiager&hide=html&layout=compact&theme=radical)](https://github.com/anuraghazra/github-readme-stats)

### Merko

[![tobiager](https://github-readme-stats.vercel.app/api?username=tobiager&theme=merko)](https://github.com/anuraghazra/github-readme-stats)

[![tobiager](https://github-readme-stats.vercel.app/api/top-langs/?username=tobiager&hide=html&layout=compact&theme=merko)](https://github.com/anuraghazra/github-readme-stats)

### Gruvbox

[![tobiager](https://github-readme-stats.vercel.app/api?username=tobiager&theme=gruvbox)](https://github.com/anuraghazra/github-readme-stats)

[![tobiager](https://github-readme-stats.vercel.app/api/top-langs/?username=tobiager&hide=html&layout=compact&theme=gruvbox)](https://github.com/anuraghazra/github-readme-stats)

### Tokyonight

[![tobiager](https://github-readme-stats.vercel.app/api?username=tobiager&theme=tokyonight)](https://github.com/anuraghazra/github-readme-stats)

[![tobiager](https://github-readme-stats.vercel.app/api/top-langs/?username=tobiager&hide=html&layout=compact&theme=tokyonight)](https://github.com/anuraghazra/github-readme-stats)

### Onedark

[![tobiager](https://github-readme-stats.vercel.app/api?username=tobiager&theme=onedark)](https://github.com/anuraghazra/github-readme-stats)

[![tobiager](https://github-readme-stats.vercel.app/api/top-langs/?username=tobiager&hide=html&layout=compact&theme=onedark)](https://github.com/anuraghazra/github-readme-stats)

### Cobalt

[![tobiager](https://github-readme-stats.vercel.app/api?username=tobiager&theme=cobalt)](https://github.com/anuraghazra/github-readme-stats)

[![tobiager](https://github-readme-stats.vercel.app/api/top-langs/?username=tobiager&hide=html&layout=compact&theme=cobalt)](https://github.com/anuraghazra/github-readme-stats)

### Synthwave

[![tobiager](https://github-readme-stats.vercel.app/api?username=tobiager&theme=synthwave)](https://github.com/anuraghazra/github-readme-stats)

[![tobiager](https://github-readme-stats.vercel.app/api/top-langs/?username=tobiager&hide=html&layout=compact&theme=synthwave)](https://github.com/anuraghazra/github-readme-stats)

### Highcontrast

[![tobiager](https://github-readme-stats.vercel.app/api?username=tobiager&theme=highcontrast)](https://github.com/anuraghazra/github-readme-stats)

[![tobiager](https://github-readme-stats.vercel.app/api/top-langs/?username=tobiager&hide=html&layout=compact&theme=highcontrast)](https://github.com/anuraghazra/github-readme-stats)

### Dracula

[![tobiager](https://github-readme-stats.vercel.app/api?username=tobiager&theme=dracula)](https://github.com/anuraghazra/github-readme-stats)

[![tobiager](https://github-readme-stats.vercel.app/api/top-langs/?username=tobiager&hide=html&layout=compact&theme=dracula)](https://github.com/anuraghazra/github-readme-stats)

---

- [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats)

</details>
<details id="badges--shields" close>
<summary><h2>Badges & Shields</h2></summary>

![Markdown-badge-kohasummons-stripped-image](https://user-images.githubusercontent.com/66284362/159115513-3ae48dd6-3d9c-416f-83d4-db48de23fac8.png)

# Markdown Badges
Add badges to your Profile and Projects.

# Usage
To use a badge:
- Via GitHub
    1. Press `Ctrl` + `f` on your keyboard, to bring out the search modal.
    2. Enter the name of the badge you need.
    3. Copy the appropriate `![Name](link)` element and paste it in your Markdown file (e.g. README.md)

# Tips

<details> 
<summary>👇 How to use a different badge style</summary>
<hr>

> <strong>Note:</strong> `for-the-badge` is the style that we chose for appearance purposes. Other styles are available at [https://shields.io/#styles](https://shields.io/#styles) and can be used with the badges here. Thanks, @kingthorin for mentioning this!


Shields.io offers 5 styles, which are:
| S/N | Types         | Styles                                                                                                    |
| :-: | :------------ | :-------------------------------------------------------------------------------------------------------- |
| 1   | Plastic       | ![Plastic](https://shields.io/badge/style-plastic-03650f?logo=appveyor&style=plastic)                     |
| 2   | Flat-square   | ![Flat-square](https://shields.io/badge/style-flat--square-03650f?logo=appveyor&style=flat-square)        |
| 3   | Flat          | ![Flat](https://shields.io/badge/style-flat-03650f?logo=appveyor&style=flat)                              |
| 4   | Social        | ![Social](https://shields.io/badge/style-social-03650f?logo=appveyor&style=social)                        |
| 5   | For-the-badge | ![For-the-badge](https://shields.io/badge/style-for--the--badge-03650f?logo=appveyor&style=for-the-badge) |



💡 To use a different style: Replace `for-the-badge` in the markdown link with any of the styles above.
```
Example.

🧷  For plastic
https://shields.io/badge/style-plastic-green?logo=appveyor&style=plastic

🤏🏽  For Flat
https://shields.io/badge/style-flat-green?logo=appveyor&style=flat
```

</details>

<details> 
<summary>👇 Use Ctrl + F or CMD + F to search</summary>
 <hr>

 > <strong>Tip:</strong> Since there are a lot of badges, to search for the particular badge you are looking for, use Ctrl + F and type the name you want. Thanks, @JakyeRU for mentioning this!
</details>

## Contact

You can reach me on [Twitter @tobiager](https://twitter.com/tobiager)

# Badges

### 🤖 Artificial Intelligence and Bots

| Name             | Badge                                                                                                                                   | Markdown                                                                                                                                  |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| Amazon Alexa     | ![Amazon Alexa](https://img.shields.io/badge/amazon%20alexa-52b5f7?style=for-the-badge&logo=amazon%20alexa&logoColor=white)             | `![Amazon Alexa](https://img.shields.io/badge/amazon%20alexa-52b5f7?style=for-the-badge&logo=amazon%20alexa&logoColor=white)`             |
| ChatGPT       | ![ChatGPT](https://img.shields.io/badge/chatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white)                       | `![ChatGPT](https://img.shields.io/badge/chatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white)`                       |
| Dependabot       | ![Dependabot](https://img.shields.io/badge/dependabot-025E8C?style=for-the-badge&logo=dependabot&logoColor=white)                       | `![Dependabot](https://img.shields.io/badge/dependabot-025E8C?style=for-the-badge&logo=dependabot&logoColor=white)`                       |
| GitHub Copilot   | ![GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-8957E5?style=for-the-badge&logo=github-copilot&logoColor=white) | `![GitHub Copilot](https://img.shields.io/badge/github_copilot-8957E5?style=for-the-badge&logo=github-copilot&logoColor=white)` |
| Google Assistant | ![Google Assistant](https://img.shields.io/badge/google%20assistant-4285F4?style=for-the-badge&logo=google%20assistant&logoColor=white) | `![Google Assistant](https://img.shields.io/badge/google%20assistant-4285F4?style=for-the-badge&logo=google%20assistant&logoColor=white)` |
| Google Gemini    | ![Google Gemini](https://img.shields.io/badge/google%20gemini-8E75B2?style=for-the-badge&logo=google%20gemini&logoColor=white)          | `![Google Gemini](https://img.shields.io/badge/google%20gemini-8E75B2?style=for-the-badge&logo=google%20gemini&logoColor=white)`          |
| Perplexity     | ![Perplexity](https://img.shields.io/badge/perplexity-000000?style=for-the-badge&logo=perplexity&logoColor=088F8F)          | `![Perplexity](https://img.shields.io/badge/perplexity-000000?style=for-the-badge&logo=perplexity&logoColor=088F8F)`          |

[(Back to top)](#table-of-contents)

### 🔗 Blockchain

| Name        | Badge                                                                                                                | Markdown                                                                                                               |
| ----------- | -------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| Bitcoin     | ![Bitcoin](https://img.shields.io/badge/bitcoin-F7931A?style=for-the-badge&logo=bitcoin&logoColor=white)             |`![Bitcoin](https://img.shields.io/badge/bitcoin-2F3134?style=for-the-badge&logo=bitcoin&logoColor=white)`              |
| Hyperledger | ![Hyperledger](https://img.shields.io/badge/hyperledger-F7931A?style=for-the-badge&logo=hyperledger&logoColor=white) | `![Hyperledger](https://img.shields.io/badge/hyperledger-2F3134?style=for-the-badge&logo=hyperledger&logoColor=white)` |

[(Back to top)](#table-of-contents)

### 📝 Blog

| Name       | Badge                                                                                                             | Markdown                                                                                                            |
| ---------- | ----------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| Blogger    | ![Blogger](https://img.shields.io/badge/Blogger-FF5722?style=for-the-badge&logo=blogger&logoColor=white)          | `![Blogger](https://img.shields.io/badge/Blogger-FF5722?style=for-the-badge&logo=blogger&logoColor=white)`          |
| daily.dev  | ![daily.dev](https://img.shields.io/badge/daily.dev-CE3DF3?style=for-the-badge&logo=daily.dev&logoColor=white)    | `![daily.dev](https://img.shields.io/badge/daily.dev-CE3DF3?style=for-the-badge&logo=daily.dev&logoColor=white)`    |
| Dev        | ![Dev.to blog](https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white)        | `![Dev.to blog](https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white)`        |
| Ghost      | ![Ghost](https://img.shields.io/badge/ghost-000?style=for-the-badge&logo=ghost&logoColor=%23F7DF1E)               | `![Ghost](https://img.shields.io/badge/ghost-000?style=for-the-badge&logo=ghost&logoColor=%23F7DF1E)`               |
| Hashnode   | ![Hashnode](https://img.shields.io/badge/Hashnode-2962FF?style=for-the-badge&logo=hashnode&logoColor=white)       | `![Hashnode](https://img.shields.io/badge/Hashnode-2962FF?style=for-the-badge&logo=hashnode&logoColor=white)`       |
| Medium     | ![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)             | `![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)`             |
| Micro.blog | ![Micro.blog](https://img.shields.io/badge/Micro.blog-FF8800?style=for-the-badge&logo=micro.blog&logoColor=white) | `![Micro.blog](https://img.shields.io/badge/Micro.blog-FF8800?style=for-the-badge&logo=micro.blog&logoColor=white)` |
| Rss        | ![Rss](https://img.shields.io/badge/rss-F88900?style=for-the-badge&logo=rss&logoColor=white)                      | `![Rss](https://img.shields.io/badge/rss-F88900?style=for-the-badge&logo=rss&logoColor=white)`                      |
| Substack   | ![Substack](https://img.shields.io/badge/Substack-%23006f5c.svg?style=for-the-badge&logo=substack&logoColor=FF6719)| `![Substack](https://img.shields.io/badge/Substack-%23006f5c.svg?style=for-the-badge&logo=substack&logoColor=FF6719)`    |
| Wix        | ![Wix](https://img.shields.io/badge/wix-000?style=for-the-badge&logo=wix&logoColor=white)                         | `![Wix](https://img.shields.io/badge/wix-000?style=for-the-badge&logo=wix&logoColor=white)`                         |

[(Back to top)](#table-of-contents)

### 🌐 Browsers

| Name          | Badge                                                                                                                       | Markdown                                                                                                                      |
| ------------- | --------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| Brave         | ![Brave](https://img.shields.io/badge/Brave-FB542B?style=for-the-badge&logo=Brave&logoColor=white)                          | `![Brave](https://img.shields.io/badge/Brave-FB542B?style=for-the-badge&logo=Brave&logoColor=white)`                          |
| DuckDuckGo          | ![DuckDuckGo](https://img.shields.io/badge/duckduckgo-de5833?style=for-the-badge&logo=duckduckgo&logoColor=white)      | `![DuckDuckGo](https://img.shields.io/badge/duckduckgo-de5833?style=for-the-badge&logo=duckduckgo&logoColor=white)`                   |
| Edge          | ![Edge](https://img.shields.io/badge/Edge-0078D7?style=for-the-badge&logo=Microsoft-edge&logoColor=white)                   | `![Edge](https://img.shields.io/badge/Edge-0078D7?style=for-the-badge&logo=Microsoft-edge&logoColor=white)`                   |
| Firefox       | ![Firefox](https://img.shields.io/badge/Firefox-FF7139?style=for-the-badge&logo=Firefox&logoColor=white)                    | `![Firefox](https://img.shields.io/badge/Firefox-FF7139?style=for-the-badge&logo=Firefox-Browser&logoColor=white)`            |
| Google Chrome | ![Google Chrome](https://img.shields.io/badge/Google%20Chrome-4285F4?style=for-the-badge&logo=GoogleChrome&logoColor=white) | `![Google Chrome](https://img.shields.io/badge/Google%20Chrome-4285F4?style=for-the-badge&logo=GoogleChrome&logoColor=white)` |
| IceCat        | ![IceCat](https://img.shields.io/badge/icecat-263A85?style=for-the-badge&logo=gnuicecat&logoColor=white)                 | `![IceCat](https://img.shields.io/badge/gnuicecat-263A85?style=for-the-badge&logo=gnuicecat&logoColor=white)`
| IE            | ![IE](https://img.shields.io/badge/Internet%20Explorer-0076D6?style=for-the-badge&logo=Internet%20Explorer&logoColor=white) | `![IE](https://img.shields.io/badge/Internet%20Explorer-0076D6?style=for-the-badge&logo=Internet%20Explorer&logoColor=white)` |
| Opera         | ![Opera](https://img.shields.io/badge/Opera-FF1B2D?style=for-the-badge&logo=Opera&logoColor=white)                          | `![Opera](https://img.shields.io/badge/Opera-FF1B2D?style=for-the-badge&logo=Opera&logoColor=white)`                          |
| Safari        | ![Safari](https://img.shields.io/badge/Safari-000000?style=for-the-badge&logo=Safari&logoColor=white)                       | `![Safari](https://img.shields.io/badge/Safari-000000?style=for-the-badge&logo=Safari&logoColor=white)`                       |
| Tor           | ![Tor](https://img.shields.io/badge/Tor-7D4698?style=for-the-badge&logo=Tor-Browser&logoColor=white)                        | `![Tor](https://img.shields.io/badge/Tor-7D4698?style=for-the-badge&logo=Tor-Browser&logoColor=white)`                        |
| Vivaldi       | ![Vivaldi](https://img.shields.io/badge/Vivaldi-EF3939?style=for-the-badge&logo=Vivaldi&logoColor=white)                    | `![Vivaldi](https://img.shields.io/badge/Vivaldi-EF3939?style=for-the-badge&logo=Vivaldi&logoColor=white)`                    |
| Arc          | ![Arc](https://img.shields.io/badge/Arc-000000?style=for-the-badge&logo=arc&logoColor=white)                          | `![Arc](https://img.shields.io/badge/Arc-000000?style=for-the-badge&logo=arc&logoColor=white)`                          |


[(Back to top)](#table-of-contents)

### 🔬 CI

| Name           | Badge                                                                                                                                 | Markdown                                                                                                                                |
| -------------- |---------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| CircleCI       | ![CircleCI](https://img.shields.io/badge/circleci-%23161616.svg?style=for-the-badge&logo=circleci&logoColor=white)                    | `![CircleCI](https://img.shields.io/badge/circle%20ci-%23161616.svg?style=for-the-badge&logo=circleci&logoColor=white)`                 |
| ChipperCI      | ![ChipperCI](https://img.shields.io/badge/chipperci-1e394e.svg?style=for-the-badge&logo=chipperci&logoColor=white)                    | `![ChipperCI](https://img.shields.io/badge/chipperci-1e394e.svg?style=for-the-badge&logo=chipperci&logoColor=white)`                    |
| CloudBees      | ![CloudBees](https://img.shields.io/badge/CloudBees-1997B5&?logo=cloudbees&logoColor=white&style=for-the-badge)                       | `![CloudBees](https://img.shields.io/badge/CloudBees-1997B5&?logo=cloudbees&logoColor=white&style=for-the-badge)`                       |
| Fastlane       | ![Fastlane](https://img.shields.io/badge/fastlane-%2382bd4e.svg?style=for-the-badge&logo=fastlane&logoColor=black)                    | `![Fastlane](https://img.shields.io/badge/fastlane-%2382bd4e.svg?style=for-the-badge&logo=fastlane&logoColor=black)`                    |
| GitLab CI      | ![GitLab CI](https://img.shields.io/badge/gitlab%20CI-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white)                  | `![GitLab CI](https://img.shields.io/badge/gitlab%20ci-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white)`                  |
| GitHub Actions | ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white) | `![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)` |
| TeamCity       | ![TeamCity](https://img.shields.io/badge/teamcity-000000.svg?style=for-the-badge&logo=teamcity&logoColor=white)                       | `![TeamCity](https://img.shields.io/badge/teamcity-000000.svg?style=for-the-badge&logo=teamcity&logoColor=white)`                       |
| Travis CI      | ![TravisCI](https://img.shields.io/badge/travis%20ci-%232B2F33.svg?style=for-the-badge&logo=travis&logoColor=white)                   | `![TravisCI](https://img.shields.io/badge/travis%20ci-%232B2F33.svg?style=for-the-badge&logo=travis&logoColor=white)`                   |

[(Back to top)](#table-of-contents)

### 📲 CD

| Name           | Badge                                                                                                                          | Markdown                                                                                                                         |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------- |
| Octopus Deploy | ![Octopus Deploy](https://img.shields.io/badge/octopus%20deploy-0D80D8?style=for-the-badge&logo=octopusdeploy&logoColor=white) | `![Octopus Deploy](https://img.shields.io/badge/octopus%20deploy-0D80D8?style=for-the-badge&logo=octopusdeploy&logoColor=white)` |

[(Back to top)](#table-of-contents)

### 📂 Cloud Storage

| Name         | Badge                                                                                                                    | Markdown                                                                                                                   |
| ------------ | ------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------- |
| Amazon S3    | ![Amazon S3](https://img.shields.io/badge/Amazon%20S3-FF9900?style=for-the-badge&logo=amazons3&logoColor=white)          | `![Amazon S3](https://img.shields.io/badge/Amazon%20S3-FF9900?style=for-the-badge&logo=amazons3&logoColor=white)` |
| Dropbox      | ![Dropbox](https://img.shields.io/badge/Dropbox-%233B4D98.svg?style=for-the-badge&logo=Dropbox&logoColor=white)          | `![Dropbox](https://img.shields.io/badge/Dropbox-%233B4D98.svg?style=for-the-badge&logo=Dropbox&logoColor=white)`          |
| Google Drive | ![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white) | `![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)` |
| Mega.nz      | ![Mega.nz](https://img.shields.io/badge/Mega-%23D90007.svg?style=for-the-badge&logo=Mega&logoColor=white)                | `![Mega.nz](https://img.shields.io/badge/Mega-%23D90007.svg?style=for-the-badge&logo=Mega&logoColor=white)`                |
| Microsoft OneDrive   | ![OneDrive](https://img.shields.io/badge/OneDrive-white?style=for-the-badge&logo=Microsoft%20OneDrive&logoColor=0078D4)       | `![OneDrive](https://img.shields.io/badge/OneDrive-white?style=for-the-badge&logo=Microsoft%20OneDrive&logoColor=0078D4)`       |
| Next Cloud   | ![Next Cloud](https://img.shields.io/badge/Next%20Cloud-0B94DE?style=for-the-badge&logo=nextcloud&logoColor=white)       | `![Next Cloud](https://img.shields.io/badge/Next%20Cloud-0B94DE?style=for-the-badge&logo=nextcloud&logoColor=white)`       |
| OneDrive   | ![OneDrive](https://img.shields.io/badge/OneDrive-0078D4.svg?style=for-the-badge&logo=microsoftonedrive&logoColor=white)       | `![OneDrive](https://img.shields.io/badge/OneDrive-0078D4.svg?style=for-the-badge&logo=microsoftonedrive&logoColor=white)`       |
| Proton Drive | ![Proton Drive](https://img.shields.io/badge/Proton%20Drive-6d4aff?style=for-the-badge&logo=proton%20drive&logoColor=white)  |  `![Proton Drive](https://img.shields.io/badge/Proton%20Drive-6d4aff?style=for-the-badge&logo=proton%20drive&logoColor=white)` |

[(Back to top)](#table-of-contents)

### 💲 Cryptocurrency

| Name         | Badge                                                                                                                       | Markdown                                                                                                                      |
| ------------ | --------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| Amp          | ![Amp](https://img.shields.io/badge/Amp-005AF0?style=for-the-badge&logo=amp&logoColor=white)                                | `![Amp](https://img.shields.io/badge/Amp-005AF0?style=for-the-badge&logo=amp&logoColor=white)`                                |
| Bitcoin      | ![Bitcoin](https://img.shields.io/badge/Bitcoin-000?style=for-the-badge&logo=bitcoin&logoColor=white)                       | `![Bitcoin](https://img.shields.io/badge/Bitcoin-000?style=for-the-badge&logo=bitcoin&logoColor=white)`                       |
| Bitcoin Cash | ![Bitcoin Cash](https://img.shields.io/badge/Bitcoin%20Cash-0AC18E?style=for-the-badge&logo=Bitcoin%20Cash&logoColor=white) | `![Bitcoin Cash](https://img.shields.io/badge/Bitcoin%20Cash-0AC18E?style=for-the-badge&logo=Bitcoin%20Cash&logoColor=white)` |
| Bitcoin SV   | ![Bitcoin SV](https://img.shields.io/badge/Bitcoin%20SV-EAB300?style=for-the-badge&logo=Bitcoin%20SV&logoColor=white)       | `![Bitcoin SV](https://img.shields.io/badge/Bitcoin%20SV-EAB300?style=for-the-badge&logo=Bitcoin%20SV&logoColor=white)`       |
| Binance      | ![Binance](https://img.shields.io/badge/Binance-FCD535?style=for-the-badge&logo=binance&logoColor=white)                    | `![Binance](https://img.shields.io/badge/Binance-FCD535?style=for-the-badge&logo=binance&logoColor=white)`                    |
| Chainlink    | ![Chainlink](https://img.shields.io/badge/Chainlink-375BD2?style=for-the-badge&logo=Chainlink&logoColor=white)              | `![Chainlink](https://img.shields.io/badge/Chainlink-375BD2?style=for-the-badge&logo=Chainlink&logoColor=white)`              |
| Dogecoin     | ![Dogecoin](https://img.shields.io/badge/dogecoin-B59A30?style=for-the-badge&logo=dogecoin&logoColor=white)                 | `![Dogecoin](https://img.shields.io/badge/dogecoin-B59A30?style=for-the-badge&logo=dogecoin&logoColor=white)`                 |
| Dash         | ![Dash](https://img.shields.io/badge/dash-008DE4?style=for-the-badge&logo=dash&logoColor=white)                             | `![Dash](https://img.shields.io/badge/dash-008DE4?style=for-the-badge&logo=dash&logoColor=white)`                             |
| Ethereum     | ![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=Ethereum&logoColor=white)                 | `![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=Ethereum&logoColor=white)`                 |
| Iota         | ![Iota](https://img.shields.io/badge/iota-29334C?style=for-the-badge&logo=iota&logoColor=white)                             | `![Iota](https://img.shields.io/badge/iota-29334C?style=for-the-badge&logo=iota&logoColor=white)`                             |
| Litecoin     | ![Litecoin](https://img.shields.io/badge/Litecoin-A6A9AA?style=for-the-badge&logo=Litecoin&logoColor=white)                 | `![Litecoin](https://img.shields.io/badge/Litecoin-A6A9AA?style=for-the-badge&logo=Litecoin&logoColor=white)`                 |
| Monero       | ![Monero](https://img.shields.io/badge/monero-FF6600?style=for-the-badge&logo=monero&logoColor=white)                       | `![Monero](https://img.shields.io/badge/monero-FF6600?style=for-the-badge&logo=monero&logoColor=white)`                       |
| Polkadot     | ![Polkadot](https://img.shields.io/badge/polkadot-E6007A?style=for-the-badge&logo=polkadot&logoColor=white)                 | `![Polkadot](https://img.shields.io/badge/polkadot-E6007A?style=for-the-badge&logo=polkadot&logoColor=white)`                 |
| Stellar      | ![Stellar](https://img.shields.io/badge/Stellar-7D00FF?style=for-the-badge&logo=Stellar&logoColor=white)                    | `![Stellar](https://img.shields.io/badge/Stellar-7D00FF?style=for-the-badge&logo=Stellar&logoColor=white)`                    |
| Tether       | ![Tether](https://img.shields.io/badge/tether-168363?style=for-the-badge&logo=tether&logoColor=white)                       | `![Tether](https://img.shields.io/badge/tether-168363?style=for-the-badge&logo=tether&logoColor=white)`                       |
| Xrp          | ![Xrp](https://img.shields.io/badge/Xrp-black?style=for-the-badge&logo=xrp&logoColor=white)                                 | `![Xrp](https://img.shields.io/badge/Xrp-black?style=for-the-badge&logo=xrp&logoColor=white)`                                 |
| Z Cash       | ![Z Cash](https://img.shields.io/badge/Zcash-F4B728?style=for-the-badge&logo=zcash&logoColor=white)                         | `![Z Cash](https://img.shields.io/badge/Zcash-F4B728?style=for-the-badge&logo=zcash&logoColor=white)`                         |

[(Back to top)](#table-of-contents)

### 💾 Databases

| Name                 | Badge                                                                                                                                                | Markdown                                                                                                                                               |
| -------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Amazon DynamoDB      | ![AmazonDynamoDB](https://img.shields.io/badge/Amazon%20DynamoDB-4053D6?style=for-the-badge&logo=Amazon%20DynamoDB&logoColor=white)                  | `![AmazonDynamoDB](https://img.shields.io/badge/Amazon%20DynamoDB-4053D6?style=for-the-badge&logo=Amazon%20DynamoDB&logoColor=white)`                  |
| Appwrite             | ![Appwrite](https://img.shields.io/badge/Appwrite-%23FD366E.svg?style=for-the-badge&logo=appwrite&logoColor=white)                                   | `![Appwrite](https://img.shields.io/badge/Appwrite-%23FD366E.svg?style=for-the-badge&logo=appwrite&logoColor=white)`                                   |
| ArangoDB             | ![Arango DB](https://img.shields.io/badge/ArangoDB-DDE072?style=for-the-badge&logo=arangodb&logoColor=white)      |  `![Arango DB](https://img.shields.io/badge/ArangoDB-DDE072?style=for-the-badge&logo=arangodb&logoColor=white)`  |
| Cassandra            | ![ApacheCassandra](https://img.shields.io/badge/cassandra-%231287B1.svg?style=for-the-badge&logo=apache-cassandra&logoColor=white)                   | `![ApacheCassandra](https://img.shields.io/badge/cassandra-%231287B1.svg?style=for-the-badge&logo=apache-cassandra&logoColor=white)`                   |
| ClickHouse           | ![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=white)                                    | `![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=white)`                                    |
| Cockroach Labs       | ![CockroachLabs](https://img.shields.io/badge/Cockroach%20Labs-6933FF?style=for-the-badge&logo=Cockroach%20Labs&logoColor=white)                     | `![CockroachLabs](https://img.shields.io/badge/Cockroach%20Labs-6933FF?style=for-the-badge&logo=Cockroach%20Labs&logoColor=white)`                     |
| Couchbase            | ![Couchbase](https://img.shields.io/badge/Couchbase-EA2328?style=for-the-badge&logo=couchbase&logoColor=white)                                       | `![Couchbase](https://img.shields.io/badge/Couchbase-EA2328?style=for-the-badge&logo=couchbase&logoColor=white)`                                       |
| CrateDB              | ![CrateDB](https://img.shields.io/badge/CrateDB-009DC7?style=for-the-badge&logo=CrateDB&logoColor=white)                                             | `![CrateDB](https://img.shields.io/badge/CrateDB-009DC7?style=for-the-badge&logo=CrateDB&logoColor=white)`                                             |
| Firebase             | ![Firebase](https://img.shields.io/badge/firebase-a08021?style=for-the-badge&logo=firebase&logoColor=ffcd34)                                          | `![Firebase](https://img.shields.io/badge/firebase-a08021?style=for-the-badge&logo=firebase&logoColor=ffcd34)`                                          |
| InfluxDB             | ![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?style=for-the-badge&logo=InfluxDB&logoColor=white)                                          | `![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?style=for-the-badge&logo=InfluxDB&logoColor=white)`                                          |
| MariaDB              | ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)                                             | `![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)`                                             |
| MusicBrainz          | ![MusicBrainz](https://img.shields.io/badge/Musicbrainz-EB743B?style=for-the-badge&logo=musicbrainz&logoColor=BA478F)                                | `![MusicBrainz](https://img.shields.io/badge/Musicbrainz-EB743B?style=for-the-badge&logo=musicbrainz&logoColor=BA478F)`                                |
| Microsoft SQL Server | ![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white) | `![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white)` |
| MongoDB              | ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)                                      | `![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)`                                      |
| MySQL                | ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)                                            | `![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)`                                               |
| Neo4J                | ![Neo4J](https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white)                                                   | `![Neo4J](https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white)`                                                   |
| PlanetScale                | ![PlanetScale](https://img.shields.io/badge/planetscale-%23000000.svg?style=for-the-badge&logo=planetscale&logoColor=white)                                                   | `![PlanetScale](https://img.shields.io/badge/planetscale-%23000000.svg?style=for-the-badge&logo=planetscale&logoColor=white)`                                                   |
| PocketBase             | ![PocketBase](https://img.shields.io/badge/pocketbase-%23b8dbe4.svg?style=for-the-badge&logo=Pocketbase&logoColor=black)                                 | `![PocketBase](https://img.shields.io/badge/pocketbase-%23b8dbe4.svg?style=for-the-badge&logo=Pocketbase&logoColor=black)`                                 |
| Postgres             | ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)                                 | `![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)`                                 |
| Realm                | ![Realm](https://img.shields.io/badge/Realm-39477F?style=for-the-badge&logo=realm&logoColor=white)                                                   | `![Realm](https://img.shields.io/badge/Realm-39477F?style=for-the-badge&logo=realm&logoColor=white)`                                                   |
| Redis                | ![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)                                            | `![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)`                                            |
| Single Store         | ![Single Store](https://img.shields.io/badge/Single%20Store-AA00FF?style=for-the-badge&logo=singlestore&logoColor=white)                             | `![Single Store](https://img.shields.io/badge/Single%20Store-AA00FF?style=for-the-badge&logo=singlestore&logoColor=white)`                             |
| SQLite               | ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)                                         | `![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)`                                         |
| Supabase             | ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)                                          | `![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)`                                          |
| SurrealDB             | ![SurrealDB](https://img.shields.io/badge/SurrealDB-FF00A0?style=for-the-badge&logo=surrealdb&logoColor=white)                                          | `![SurrealDB](https://img.shields.io/badge/SurrealDB-FF00A0?style=for-the-badge&logo=surrealdb&logoColor=white)`                                          |
| Teradata             | ![Teradata](https://img.shields.io/badge/Teradata-F37440?style=for-the-badge&logo=teradata&logoColor=white)                                          | `![Teradata](https://img.shields.io/badge/Teradata-F37440?style=for-the-badge&logo=teradata&logoColor=white)`                                          |

[(Back to top)](#table-of-contents)

### 🎨 Design

| Name                    | Badge                                                                                                                                                                | Markdown                                                                                                                                                               |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Adobe                   | ![Adobe](https://img.shields.io/badge/adobe-%23FF0000.svg?style=for-the-badge&logo=adobe&logoColor=white)                                                            | `![Adobe](https://img.shields.io/badge/adobe-%23FF0000.svg?style=for-the-badge&logo=adobe&logoColor=white)`                                                            |
| Adobe Acrobat Reader    | ![Adobe Acrobat Reader](https://img.shields.io/badge/Adobe%20Acrobat%20Reader-EC1C24.svg?style=for-the-badge&logo=Adobe%20Acrobat%20Reader&logoColor=white)          | `![Adobe Acrobat Reader](https://img.shields.io/badge/Adobe%20Acrobat%20Reader-EC1C24.svg?style=for-the-badge&logo=Adobe%20Acrobat%20Reader&logoColor=white)`          |
| Adobe After Effects     | ![Adobe After Effects](https://img.shields.io/badge/Adobe%20After%20Effects-9999FF.svg?style=for-the-badge&logo=Adobe%20After%20Effects&logoColor=white)             | `![Adobe After Effects](https://img.shields.io/badge/Adobe%20After%20Effects-9999FF.svg?style=for-the-badge&logo=Adobe%20After%20Effects&logoColor=white)`             |
| Adobe Audition          | ![Adobe Audition](https://img.shields.io/badge/Adobe%20Audition-9999FF.svg?style=for-the-badge&logo=Adobe%20Audition&logoColor=white)                                | `![Adobe Audition](https://img.shields.io/badge/Adobe%20Audition-9999FF.svg?style=for-the-badge&logo=Adobe%20Audition&logoColor=white)`                                |
| Adobe Creative Cloud    | ![Adobe Creative Cloud](https://img.shields.io/badge/Adobe%20Creative%20Cloud-DA1F26.svg?style=for-the-badge&logo=Adobe%20Creative%20Cloud&logoColor=white)          | `![Adobe Creative Cloud](https://img.shields.io/badge/Adobe%20Creative%20Cloud-DA1F26.svg?style=for-the-badge&logo=Adobe%20Creative%20Cloud&logoColor=white)`          |
| Adobe Dreamweaver       | ![Adobe Dreamweaver](https://img.shields.io/badge/Adobe%20Dreamweaver-FF61F6.svg?style=for-the-badge&logo=Adobe%20Dreamweaver&logoColor=white)                       | `![Adobe Dreamweaver](https://img.shields.io/badge/Adobe%20Dreamweaver-FF61F6.svg?style=for-the-badge&logo=Adobe%20Dreamweaver&logoColor=white)`                       |
| Adobe Fonts             | ![Adobe Fonts](https://img.shields.io/badge/Adobe%20Fonts-000B1D.svg?style=for-the-badge&logo=Adobe%20Fonts&logoColor=white)                                         | `![Adobe Fonts](https://img.shields.io/badge/Adobe%20Fonts-000B1D.svg?style=for-the-badge&logo=Adobe%20Fonts&logoColor=white)`                                         |
| Adobe Illustrator       | ![Adobe Illustrator](https://img.shields.io/badge/adobe%20illustrator-%23FF9A00.svg?style=for-the-badge&logo=adobe%20illustrator&logoColor=white)                    | `![Adobe Illustrator](https://img.shields.io/badge/adobe%20illustrator-%23FF9A00.svg?style=for-the-badge&logo=adobe%20illustrator&logoColor=white)`                    |
| Adobe InDesign          | ![Adobe InDesign](https://img.shields.io/badge/Adobe%20InDesign-49021F?style=for-the-badge&logo=adobeindesign&logoColor=FF3366)                                      | `![Adobe InDesign](https://img.shields.io/badge/Adobe%20InDesign-49021F?style=for-the-badge&logo=adobeindesign&logoColor=white)`                                       |
| Adobe Lightroom         | ![Adobe Lightroom](https://img.shields.io/badge/Adobe%20Lightroom-31A8FF.svg?style=for-the-badge&logo=Adobe%20Lightroom&logoColor=white)                             | `![Adobe Lightroom](https://img.shields.io/badge/Adobe%20Lightroom-31A8FF.svg?style=for-the-badge&logo=Adobe%20Lightroom&logoColor=white)`                             |
| Adobe Lightroom Classic | ![Adobe Lightroom Classic](https://img.shields.io/badge/Adobe%20Lightroom%20Classic-31A8FF.svg?style=for-the-badge&logo=Adobe%20Lightroom%20Classic&logoColor=white) | `![Adobe Lightroom Classic](https://img.shields.io/badge/Adobe%20Lightroom%20Classic-31A8FF.svg?style=for-the-badge&logo=Adobe%20Lightroom%20Classic&logoColor=white)` |
| Adobe Photoshop         | ![Adobe Photoshop](https://img.shields.io/badge/adobe%20photoshop-%2331A8FF.svg?style=for-the-badge&logo=adobe%20photoshop&logoColor=white)                          | `![Adobe Photoshop](https://img.shields.io/badge/adobe%20photoshop-%2331A8FF.svg?style=for-the-badge&logo=adobe%20photoshop&logoColor=white)`                          |
| Adobe Premiere Pro      | ![Adobe Premiere Pro](https://img.shields.io/badge/Adobe%20Premiere%20Pro-9999FF.svg?style=for-the-badge&logo=Adobe%20Premiere%20Pro&logoColor=white)                | `![Adobe Premiere Pro](https://img.shields.io/badge/Adobe%20Premiere%20Pro-9999FF.svg?style=for-the-badge&logo=Adobe%20Premiere%20Pro&logoColor=white)`                |
| Adobe XD                | ![Adobe XD](https://img.shields.io/badge/Adobe%20XD-470137?style=for-the-badge&logo=Adobe%20XD&logoColor=#FF61F6)                                                    | `![Adobe XD](https://img.shields.io/badge/Adobe%20XD-470137?style=for-the-badge&logo=Adobe%20XD&logoColor=#FF61F6)`                                                    |
| Aseprite                | ![Aseprite](https://img.shields.io/badge/Aseprite-FFFFFF?style=for-the-badge&logo=Aseprite&logoColor=#7D929E)                                                        | `![Aseprite](https://img.shields.io/badge/Aseprite-FFFFFF?style=for-the-badge&logo=Aseprite&logoColor=#7D929E)`                                                        |
| Affinity Designer       | ![Affinity Designer](https://img.shields.io/badge/affinity%20desginer-%231B72BE.svg?style=for-the-badge&logo=affinity-designer&logoColor=white)                      | `![Affinity Designer](https://img.shields.io/badge/affinity%20desginer-%231B72BE.svg?style=for-the-badge&logo=affinity-designer&logoColor=white)`                      |
| Affinity Photo          | ![Affinity Photo](https://img.shields.io/badge/affinityphoto-%237E4DD2.svg?style=for-the-badge&logo=affinity-photo&logoColor=white)                                  | `![Affinity Photo](https://img.shields.io/badge/affinityphoto-%237E4DD2.svg?style=for-the-badge&logo=affinity-photo&logoColor=white)`                                  |
| Blender                 | ![Blender](https://img.shields.io/badge/blender-%23F5792A.svg?style=for-the-badge&logo=blender&logoColor=white)                                                      | `![Blender](https://img.shields.io/badge/blender-%23F5792A.svg?style=for-the-badge&logo=blender&logoColor=white)`                                                      |
| Canva                   | ![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white)                                                            | `![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white)`                                                            |
| Clip Studio Paint       | ![Clip Studio Paint](https://img.shields.io/badge/ClipStudioPaint-%23CFD3D3.svg?style=for-the-badge&logo=ClipStudioPaint&logoColor=white)                            | `![Clip Studio Paint](https://img.shields.io/badge/ClipStudioPaint-%23CFD3D3.svg?style=for-the-badge&logo=ClipStudioPaint&logoColor=white)`                                                            |
| Dribbble                | ![Dribbble](https://img.shields.io/badge/Dribbble-EA4C89?style=for-the-badge&logo=dribbble&logoColor=white)                                                          | `![Dribbble](https://img.shields.io/badge/Dribbble-EA4C89?style=for-the-badge&logo=dribbble&logoColor=white)`                                                          |
| Figma                   | ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)                                                            | `![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)`                                                            |
| Framer                  | ![Framer](https://img.shields.io/badge/Framer-black?style=for-the-badge&logo=framer&logoColor=blue)                                                                  | `![Framer](https://img.shields.io/badge/Framer-black?style=for-the-badge&logo=framer&logoColor=blue)`                                                                  |
| Gimp                    | ![Gimp](https://img.shields.io/badge/Gimp-657D8B?style=for-the-badge&logo=gimp&logoColor=FFFFFF)                                                                     | `![Gimp Gnu Image Manipulation Program](https://img.shields.io/badge/Gimp-657D8B?style=for-the-badge&logo=gimp&logoColor=FFFFFF)`                                      |
| Inkscape                | ![Inkscape](https://img.shields.io/badge/Inkscape-e0e0e0?style=for-the-badge&logo=inkscape&logoColor=080A13)                                                         | `![Inkscape](https://img.shields.io/badge/Inkscape-e0e0e0?style=for-the-badge&logo=inkscape&logoColor=080A13)`                                                         |
| Invision                | ![Invision](https://img.shields.io/badge/invision-FF3366?style=for-the-badge&logo=invision&logoColor=white)                                                          | `![Invision](https://img.shields.io/badge/invision-FF3366?style=for-the-badge&logo=invision&logoColor=white)`                                                          |
| Krita                   | ![Krita](https://img.shields.io/badge/Krita-203759?style=for-the-badge&logo=krita&logoColor=EEF37B)                                                                  | `![Krita](https://img.shields.io/badge/Krita-203759?style=for-the-badge&logo=krita&logoColor=EEF37B)`                                                                  |
| Penpot                  | ![Penpot](https://img.shields.io/badge/penpot-%23FFFFFF.svg?style=for-the-badge&logo=penpot&logoColor=black)                                                         | `![Penpot](https://img.shields.io/badge/penpot-%23FFFFFF.svg?style=for-the-badge&logo=penpot&logoColor=black)`                                                         |
| Proto.io                | ![Proto.io](https://img.shields.io/badge/Proto.io-161637?style=for-the-badge&logo=proto.io&logoColor=00e5ff)                                                         | `![Proto.io](https://img.shields.io/badge/Proto.io-161637?style=for-the-badge&logo=proto.io&logoColor=00e5ff)`                                                         |
| Rhinoceros              | ![Rhinoceros](https://img.shields.io/badge/Rhinoceros-801010?style=for-the-badge&logo=rhinoceros&logoColor=white)                                                    | `![Rhinoceros](https://img.shields.io/badge/Rhinoceros-801010?style=for-the-badge&logo=rhinoceros&logoColor=white)`                                                    |
| Sketch                  | ![Sketch](https://img.shields.io/badge/Sketch-FFB387?style=for-the-badge&logo=sketch&logoColor=black)                                                                | `![Sketch](https://img.shields.io/badge/Sketch-FFB387?style=for-the-badge&logo=sketch&logoColor=black)`                                                                |
| Sketch Up               | ![Sketch Up](https://img.shields.io/badge/SketchUp-005F9E?style=for-the-badge&logo=sketchup&logoColor=white)                                                         | `![Sketch Up](https://img.shields.io/badge/SketchUp-005F9E?style=for-the-badge&logo=sketchup&logoColor=white)`                                                         |
| Storybook               | ![Storybook](https://img.shields.io/badge/-Storybook-FF4785?style=for-the-badge&logo=storybook&logoColor=white)                                                      | `![Storybook](https://img.shields.io/badge/-Storybook-FF4785?style=for-the-badge&logo=storybook&logoColor=white)`                                                      |

[(Back to top)](#table-of-contents)

### 🧑‍💻 Developer/Forums

| Name           | Badge                                                                                                                                 | Markdown                                                                                                                                |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| CodeChef       | ![CodeChef](https://img.shields.io/badge/CodeChef-%23964B00.svg?style=for-the-badge&logo=CodeChef&logoColor=white)                    | `![CodeChef](https://img.shields.io/badge/CodeChef-%23964B00.svg?style=for-the-badge&logo=CodeChef&logoColor=white)`                    |
| Codeforces     | ![Codeforces](https://img.shields.io/badge/Codeforces-445f9d?style=for-the-badge&logo=Codeforces&logoColor=white)                     | `![Codeforces](https://img.shields.io/badge/Codeforces-445f9d?style=for-the-badge&logo=Codeforces&logoColor=white)`                     |
| CodePen        | ![CodePen](https://img.shields.io/badge/Codepen-000000?style=for-the-badge&logo=codepen&logoColor=white)                              | `![CodePen](https://img.shields.io/badge/Codepen-000000?style=for-the-badge&logo=codepen&logoColor=white)`                              |
| Hackerearth    | ![Hackerearth](https://img.shields.io/badge/HackerEarth-%232C3454.svg?&style=for-the-badge&logo=HackerEarth&logoColor=Blue)           | `![Hackerearth](https://img.shields.io/badge/HackerEarth-%232C3454.svg?&style=for-the-badge&logo=HackerEarth&logoColor=Blue)`              |               
| Hackerrank    | ![Hackerrank](https://img.shields.io/badge/-Hackerrank-2EC866?style=for-the-badge&logo=HackerRank&logoColor=white)                     | `![Hackerrank](https://img.shields.io/badge/-Hackerrank-2EC866?style=for-the-badge&logo=HackerRank&logoColor=white)`              |    
| Kaggle         | ![Kaggle](https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white)                                 | `![Kaggle](https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white)`                                 |
| LeetCode       | ![LeetCode](https://img.shields.io/badge/Leetcode-000000?style=for-the-badge&logo=LeetCode&logoColor=#d16c06)                         | `![LeetCode](https://img.shields.io/badge/LeetCode-000000?style=for-the-badge&logo=LeetCode&logoColor=#d16c06)`                         |
| OnePlus Forums | ![OnePlus Forums](https://img.shields.io/badge/OnePlusForums-%23EB0028.svg?style=for-the-badge&logo=OnePlus&logoColor=white)          | `![OnePlus Forums](https://img.shields.io/badge/OnePlusForums-%23EB0028.svg?style=for-the-badge&logo=OnePlus&logoColor=white)`          |
| Quora          | ![Quora](https://img.shields.io/badge/Quora-%23B92B27.svg?style=for-the-badge&logo=Quora&logoColor=white)                             | `![Quora](https://img.shields.io/badge/Quora-%23B92B27.svg?style=for-the-badge&logo=Quora&logoColor=white)`                             |
| Reddit         | ![Reddit](https://img.shields.io/badge/Reddit-%23FF4500.svg?style=for-the-badge&logo=Reddit&logoColor=white)                          | `![Reddit](https://img.shields.io/badge/Reddit-%23FF4500.svg?style=for-the-badge&logo=Reddit&logoColor=white)`                          |
| ResearchGate   | ![ResearchGate](https://img.shields.io/badge/ResearchGate-00CCBB?style=for-the-badge&logo=ResearchGate&logoColor=white)               | `![ResearchGate](https://img.shields.io/badge/ResearchGate-00CCBB?style=for-the-badge&logo=ResearchGate&logoColor=white)`               |
| Stack Exchange | ![Stack Exchange](https://img.shields.io/badge/StackExchange-%23ffffff.svg?style=for-the-badge&logo=StackExchange)    | `![Stack Exchange](https://img.shields.io/badge/StackExchange-%23ffffff.svg?style=for-the-badge&logo=StackExchange)`    |
| Stack Overflow | ![Stack Overflow](https://img.shields.io/badge/-Stackoverflow-FE7A16?style=for-the-badge&logo=stack-overflow&logoColor=white)         | `![Stack Overflow](https://img.shields.io/badge/-Stackoverflow-FE7A16?style=for-the-badge&logo=stack-overflow&logoColor=white)`         |
| XDA-Developers | ![XDA-Developers](https://img.shields.io/badge/XDA--Developers-%23AC6E2F.svg?style=for-the-badge&logo=XDA-Developers&logoColor=white) | `![XDA-Developers](https://img.shields.io/badge/XDA--Developers-%23AC6E2F.svg?style=for-the-badge&logo=XDA-Developers&logoColor=white)` |

[(Back to top)](#table-of-contents)

### 📑 Documentation Platforms

| Name      | Badge                                                                                                                 | Markdown                                                                                                                |
| --------- | --------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| Bookstack | ![Bookstack](https://img.shields.io/badge/Bookstack-%230288D1.svg?style=for-the-badge&logo=bookstack&logoColor=white) | `![Bookstack](https://img.shields.io/badge/Bookstack-%230288D1.svg?style=for-the-badge&logo=bookstack&logoColor=white)` |
| GitBook | ![GitBook](https://img.shields.io/badge/GitBook-%23000000.svg?style=for-the-badge&logo=gitbook&logoColor=white) | `![GitBook](https://img.shields.io/badge/GitBook-%23000000.svg?style=for-the-badge&logo=gitbook&logoColor=white)` |
| ReadTheDocs | ![ReadTheDocs](https://img.shields.io/badge/Readthedocs-%23000000.svg?style=for-the-badge&logo=readthedocs&logoColor=white) | `![ReadTheDocs](https://img.shields.io/badge/Readthedocs-%23000000.svg?style=for-the-badge&logo=readthedocs&logoColor=white)` |
| Wikipedia | ![Wikipedia](https://img.shields.io/badge/Wikipedia-%23000000.svg?style=for-the-badge&logo=wikipedia&logoColor=white) | `![Wikipedia](https://img.shields.io/badge/Wikipedia-%23000000.svg?style=for-the-badge&logo=wikipedia&logoColor=white)` |
| Wiki.js   | ![Wiki.js](https://img.shields.io/badge/wiki.js-%231976D2.svg?style=for-the-badge&logo=wikidotjs&logoColor=white)     | `![Wiki.js](https://img.shields.io/badge/wiki.js-%231976D2.svg?style=for-the-badge&logo=wikidotjs&logoColor=white)`     |

[(Back to top)](#table-of-contents)

### 🎓 Education

| Name            | Badge                                                                                                                        | Markdown                                                                                                                       |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| 42    | ![42](https://img.shields.io/badge/-42-black?style=for-the-badge&logo=42&logoColor=white)           | `![42](https://img.shields.io/badge/-42-black?style=for-the-badge&logo=42&logoColor=white)`           |
| Codecademy      | ![Codecademy](https://img.shields.io/badge/Codecademy-FFF0E5?style=for-the-badge&logo=codecademy&logoColor=1F243A)           | `![Codecademy](https://img.shields.io/badge/Codecademy-FFF0E5?style=for-the-badge&logo=codecademy&logoColor=1F243A)`           |
| Codingninjas      | ![codingninjas](https://img.shields.io/badge/coding%20ninjas-DD6620?style=for-the-badge&logo=codingninjas&logoColor=white) | `![codingninjas](https://img.shields.io/badge/coding%20ninjas-DD6620?style=for-the-badge&logo=codingninjas&logoColor=white)`      |
| Codewars        | ![Codewars](https://img.shields.io/badge/Codewars-B1361E?style=for-the-badge&logo=codewars&logoColor=black)                  | `![Codewars](https://img.shields.io/badge/Codewars-B1361E?style=for-the-badge&logo=codewars&logoColor=grey)`                   |
| Coursera        | ![Coursera](https://img.shields.io/badge/Coursera-%230056D2.svg?style=for-the-badge&logo=Coursera&logoColor=white)           | `![Coursera](https://img.shields.io/badge/Coursera-%230056D2.svg?style=for-the-badge&logo=Coursera&logoColor=white)`           |
| Datacamp        | ![Datacamp](https://img.shields.io/badge/Datacamp-05192D?style=for-the-badge&logo=datacamp&logoColor=03E860)                 | `![Datacamp](https://img.shields.io/badge/Datacamp-05192D?style=for-the-badge&logo=datacamp&logoColor=03E860)`                 |
| Duolingo        | ![Duolingo](https://img.shields.io/badge/Duolingo-%234DC730.svg?style=for-the-badge&logo=Duolingo&logoColor=white)           | `![Duolingo](https://img.shields.io/badge/Duolingo-%234DC730.svg?style=for-the-badge&logo=Duolingo&logoColor=white)`           |
| edX             | ![edX](https://img.shields.io/badge/edX-%2302262B.svg?style=for-the-badge&logo=edX&logoColor=white)                          | `![edX](https://img.shields.io/badge/edX-%2302262B.svg?style=for-the-badge&logo=edX&logoColor=white)`                          |
| Exercism        | ![Exercism](https://img.shields.io/badge/Exercism-009CAB?style=for-the-badge&logo=exercism&logoColor=white)                  | `![Exercism](https://img.shields.io/badge/Exercism-009CAB?style=for-the-badge&logo=exercism&logoColor=white)`                  |
| FreeCodeCamp    | ![FreeCodeCamp](https://img.shields.io/badge/Freecodecamp-%23123.svg?style=for-the-badge&logo=freecodecamp&logoColor=green)  | `![FreeCodeCamp](https://img.shields.io/badge/Freecodecamp-%23123.svg?&style=for-the-badge&logo=freecodecamp&logoColor=green)` |
| Future Learn    | ![Future Learn](https://img.shields.io/badge/future%20learn-DE00A5?style=for-the-badge&logo=futurelearn&logoColor=white)     | `![Future Learn](https://img.shields.io/badge/future%20learn-DE00A5?style=for-the-badge&logo=futurelearn&logoColor=white)`     |
| GeeksforGeeks   | ![GeeksforGeeks](https://img.shields.io/badge/GeeksforGeeks-gray?style=for-the-badge&logo=geeksforgeeks&logoColor=35914c)    | `![GeeksForGeeks](https://img.shields.io/badge/GeeksforGeeks-gray?style=for-the-badge&logo=geeksforgeeks&logoColor=35914c)`    |
| Google Scholar  | ![Google Scholar](https://img.shields.io/badge/Google%20Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white) | `![Google Scholar](https://img.shields.io/badge/Google%20Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white)`    |
| Khan Academy    | ![Khan Academy](https://img.shields.io/badge/KhanAcademy-%2314BF96.svg?style=for-the-badge&logo=KhanAcademy&logoColor=white) | `![Khan Academy](https://img.shields.io/badge/KhanAcademy-%2314BF96.svg?style=for-the-badge&logo=KhanAcademy&logoColor=white)` |
| MDN Web Docs    | ![MDN Web Docs](https://img.shields.io/badge/MDN_Web_Docs-black?style=for-the-badge&logo=mdnwebdocs&logoColor=white)         | `![MDN Web Docs](https://img.shields.io/badge/MDN_Web_Docs-black?style=for-the-badge&logo=mdnwebdocs&logoColor=white)`         |
| Microsoft Learn | ![Microsoft Learn](https://img.shields.io/badge/Microsoft_Learn-258ffa?style=for-the-badge&logo=microsoft&logoColor=white)   | `![Microsoft Learn](https://img.shields.io/badge/Microsoft_Learn-258ffa?style=for-the-badge&logo=microsoft&logoColor=white)`   |
| Pluralsight     | ![Pluralsight](https://img.shields.io/badge/Pluralsight-EE3057?style=for-the-badge&logo=pluralsight&logoColor=white)         | `![Pluralsight](https://img.shields.io/badge/Pluralsight-EE3057?style=for-the-badge&logo=pluralsight&logoColor=white)`         |
| Scrimba         | ![Scrimba](https://img.shields.io/badge/scrimba-2B283A?style=for-the-badge&logo=scrimba&logoColor=white)                     | `![Scrimba](https://img.shields.io/badge/scrimba-2B283A?style=for-the-badge&logo=scrimba&logoColor=white)`                     |
| Skill Share     | ![Skill Share](https://img.shields.io/badge/Skill%20share-002333?style=for-the-badge&logo=skillshare&logoColor=00FF84)       | `![Skill Share](https://img.shields.io/badge/Skill%20share-002333?style=for-the-badge&logo=skillshare&logoColor=00FF84)`       |
| Udacity         | ![Udacity](https://img.shields.io/badge/Udacity-grey?style=for-the-badge&logo=udacity&logoColor=15B8E6)                      | `![Udacity](https://img.shields.io/badge/Udacity-grey?style=for-the-badge&logo=udacity&logoColor=15B8E6)`                      |
| Udemy           | ![Udemy](https://img.shields.io/badge/Udemy-A435F0?style=for-the-badge&logo=Udemy&logoColor=white)                           | `![Udemy](https://img.shields.io/badge/Udemy-A435F0?style=for-the-badge&logo=Udemy&logoColor=white)`                           |

[(Back to top)](#table-of-contents)

### 💰 Funding

| Name                | Badge                                                                                                                               | Markdown                                                                                                                              |
| ------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |---------------------------------------------------------------------------------------------------------------------------------------|
| Amazon Pay          | ![Amazon Pay](https://img.shields.io/badge/AmazonPay-ff9900.svg?style=for-the-badge&logo=Amazon-Pay&logoColor=white)                | `![Amazon Pay](https://img.shields.io/badge/AmazonPay-ff9900.svg?style=for-the-badge&logo=Amazon-Pay&logoColor=white)`                |
| Apple Pay           | ![Apple Pay](https://img.shields.io/badge/ApplePay-000000.svg?style=for-the-badge&logo=Apple-Pay&logoColor=white)                   | `![Apple Pay](https://img.shields.io/badge/ApplePay-000000.svg?style=for-the-badge&logo=Apple-Pay&logoColor=white)`                   |
| Buy Me a Coffee     | ![BuyMeACoffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black) | `![BuyMeACoffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)` |
| Github Sponsors     | ![Github-sponsors](https://img.shields.io/badge/sponsor-30363D?style=for-the-badge&logo=GitHub-Sponsors&logoColor=#EA4AAA)          | `![Github-sponsors](https://img.shields.io/badge/sponsor-30363D?style=for-the-badge&logo=GitHub-Sponsors&logoColor=#EA4AAA)`          |
| Google Pay          | ![Google Pay](https://img.shields.io/badge/GooglePay-%233780F1.svg?style=for-the-badge&logo=Google-Pay&logoColor=white)             | `![Google Pay](https://img.shields.io/badge/GooglePay-%233780F1.svg?style=for-the-badge&logo=Google-Pay&logoColor=white)`             |
| Ko-Fi               | ![Ko-Fi](https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)                                 | `![Ko-Fi](https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)`                                 |
| LiberaPay           | ![LiberaPay](https://img.shields.io/badge/Liberapay-F6C915?style=for-the-badge&logo=liberapay&logoColor=black)                      | `![LiberaPay](https://img.shields.io/badge/Liberapay-F6C915?style=for-the-badge&logo=liberapay&logoColor=black)`                      |
| Patreon             | ![Patreon](https://img.shields.io/badge/Patreon-F96854?style=for-the-badge&logo=patreon&logoColor=white)                            | `![Patreon](https://img.shields.io/badge/Patreon-F96854?style=for-the-badge&logo=patreon&logoColor=white)`                            |
| PayPal              | ![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)                               | `![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)`                               |
| Paytm               | ![Paytm](https://img.shields.io/badge/Paytm-1C2C94?style=for-the-badge&logo=paytm&logoColor=05BAF3)                                 | `![Paytm](https://img.shields.io/badge/Paytm-1C2C94?style=for-the-badge&logo=paytm&logoColor=05BAF3)`                                 |
| Phonepe             | ![Phonepe](https://img.shields.io/badge/Phonepe-54039A?style=for-the-badge&logo=phonepe&logoColor=white)                            | `![Phonepe](https://img.shields.io/badge/Phonepe-54039A?style=for-the-badge&logo=phonepe&logoColor=white)`                            |
| Samsung Pay         | ![Samsung Pay](https://img.shields.io/badge/SamsungPay-1428A0.svg?style=for-the-badge&logo=Samsung-Pay&logoColor=white)             | `![Samsung Pay](https://img.shields.io/badge/SamsungPay-1428A0.svg?style=for-the-badge&logo=Samsung-Pay&logoColor=white)`             |
| Stripe              | ![Stripe](https://img.shields.io/badge/Stripe-5469d4?style=for-the-badge&logo=stripe&logoColor=ffffff)                              | `![Stripe](https://img.shields.io/badge/Stripe-5469d4?style=for-the-badge&logo=stripe&logoColor=ffffff)`                              |
| Wise | ![Wise](https://img.shields.io/badge/wise-394e79?style=for-the-badge&logo=wise&logoColor=00B9FF)                            | `![Wise](https://img.shields.io/badge/Wise-394e79?style=for-the-badge&logo=wise&logoColor=00B9FF)`                            |

[(Back to top)](#table-of-contents)

### 📚 Frameworks, Platforms and Libraries

| Name               | Badge                                                                                                                                           | Markdown                                                                                                                                          |
| ------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| .NET               | ![.Net](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white)                                                 | `![.Net](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white)`                                                 |
| AdonisJS           | ![AdonisJS](https://img.shields.io/badge/adonisjs-%23220052.svg?style=for-the-badge&logo=adonisjs&logoColor=white)                              | `![AdonisJS](https://img.shields.io/badge/adonisjs-%23220052.svg?style=for-the-badge&logo=adonisjs&logoColor=white)`                              |
| Aiohttp            | ![Aiohttp](https://img.shields.io/badge/aiohttp-%232C5bb4.svg?style=for-the-badge&logo=aiohttp&logoColor=white)                                 |`[Aiohttp](https://img.shields.io/badge/aiohttp-%232C5bb4.svg?style=for-the-badge&logo=aiohttp&logoColor=white)`                               |
| Alpine.js           | ![Alpine.js](https://img.shields.io/badge/alpinejs-white.svg?style=for-the-badge&logo=alpinedotjs&logoColor=%238BC0D0)                              | `![Alpine.js](https://img.shields.io/badge/alpinejs-white.svg?style=for-the-badge&logo=alpinedotjs&logoColor=%238BC0D0)`                              |
| AMD HIP            | ![AMD_HIP](https://img.shields.io/badge/HIP-%23000000.svg?style=for-the-badge&logo=amd&logoColor=white&logoSize=auto)                                  | `![AMD_HIP](https://img.shields.io/badge/HIP-%23000000.svg?style=for-the-badge&logo=amd&logoColor=white&logoSize=auto)`
| Anaconda           | ![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)                              | `![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)`                              |
| Angular            | ![Angular](https://img.shields.io/badge/angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white)                                 | `![Angular](https://img.shields.io/badge/angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white)`                                 |
| Angular.js         | ![Angular.js](https://img.shields.io/badge/angular.js-%23E23237.svg?style=for-the-badge&logo=angularjs&logoColor=white)                         | `![Angular.js](https://img.shields.io/badge/angular.js-%23E23237.svg?style=for-the-badge&logo=angularjs&logoColor=white)`                         |
| Ant Design         | ![Ant-Design](https://img.shields.io/badge/-AntDesign-%230170FE?style=for-the-badge&logo=ant-design&logoColor=white)                            | `![Ant-Design](https://img.shields.io/badge/-AntDesign-%230170FE?style=for-the-badge&logo=ant-design&logoColor=white)`                            |
| Apache Spark       | ![Apache Spark](https://img.shields.io/badge/Apache%20Spark-FDEE21?style=for-the-badge&logo=apachespark&logoColor=black)                          | `![Apache Spark](https://img.shields.io/badge/Apache%20Spark-FDEE21?style=flat-square&logo=apachespark&logoColor=black)`                        |
| Apache Kafka       | ![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-000?style=for-the-badge&logo=apachekafka)                                           | `![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-000?style=for-the-badge&logo=apachekafka)`                                           |
| Apache Hadoop      | ![Apache Hadoop](https://img.shields.io/badge/Apache%20Hadoop-66CCFF?style=for-the-badge&logo=apachehadoop&logoColor=black)                     | `![Apache Hadoop](https://img.shields.io/badge/Apache%20Hadoop-66CCFF?style=for-the-badge&logo=apachehadoop&logoColor=black)`                     |
| Apache Hive        | ![Apache Hive](https://img.shields.io/badge/Apache%20Hive-FDEE21?style=for-the-badge&logo=apachehive&logoColor=black)                           | `![Apache Hive](https://img.shields.io/badge/Apache%20Hive-FDEE21?style=for-the-badge&logo=apachehive&logoColor=black)`
| Apollo GraphQL     | ![Apollo-GraphQL](https://img.shields.io/badge/-ApolloGraphQL-311C87?style=for-the-badge&logo=apollo-graphql)                                   | `![Apollo-GraphQL](https://img.shields.io/badge/-ApolloGraphQL-311C87?style=for-the-badge&logo=apollo-graphql)`                                   |
| Astro              | ![Astro](https://img.shields.io/badge/astro-%232C2052.svg?style=for-the-badge&logo=astro&logoColor=white)                                   | `![Astro](https://img.shields.io/badge/astro-%232C2052.svg?style=for-the-badge&logo=astro&logoColor=white)`                                   |
| Aurelia            | ![Aurelia](https://img.shields.io/badge/aurelia-%23ED2B88.svg?style=for-the-badge&logo=aurelia&logoColor=fff)                                   | `![Aurelia](https://img.shields.io/badge/aurelia-%23ED2B88.svg?style=for-the-badge&logo=aurelia&logoColor=fff)`                                   |
| Blazor             | ![Blazor](https://img.shields.io/badge/blazor-%235C2D91.svg?style=for-the-badge&logo=blazor&logoColor=white)                                    | `![Blazor](https://img.shields.io/badge/blazor-%235C2D91.svg?style=for-the-badge&logo=blazor&logoColor=white)`                                    |
| Bootstrap          | ![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)                           | `![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)`                           |
| Buefy              | ![Buefy](https://img.shields.io/badge/Buefy-7957D5?style=for-the-badge&logo=buefy&logoColor=48289E)                                             | `![Buefy](https://img.shields.io/badge/Buefy-7957D5?style=for-the-badge&logo=buefy&logoColor=48289E)`                                             |
| Bulma              | ![Bulma](https://img.shields.io/badge/bulma-00D0B1?style=for-the-badge&logo=bulma&logoColor=white)                                             | `![Bulma](https://img.shields.io/badge/bulma-00D0B1?style=for-the-badge&logo=bulma&logoColor=white)`                                             |
| Bun                | ![Bun](https://img.shields.io/badge/Bun-%23000000.svg?style=for-the-badge&logo=bun&logoColor=white)                                             | `![Bun](https://img.shields.io/badge/Bun-%23000000.svg?style=for-the-badge&logo=bun&logoColor=white)`                                             |
| Celery             | ![Celery](https://img.shields.io/badge/celery-%23a9cc54.svg?style=for-the-badge&logo=celery&logoColor=ddf4a4)              |`![Celery](https://img.shields.io/badge/celery-%23a9cc54.svg?style=for-the-badge&logo=celery&logoColor=ddf4a4)`                                                          |
| Chakra UI          | ![Chakra](https://img.shields.io/badge/chakra-%234ED1C5.svg?style=for-the-badge&logo=chakraui&logoColor=white)                                  | `![Chakra](https://img.shields.io/badge/chakra-%234ED1C5.svg?style=for-the-badge&logo=chakraui&logoColor=white)`                                  |
| Chart.js           | ![Chart.js](https://img.shields.io/badge/chart.js-F5788D.svg?style=for-the-badge&logo=chart.js&logoColor=white)                                 | `![Chart.js](https://img.shields.io/badge/chart.js-F5788D.svg?style=for-the-badge&logo=chart.js&logoColor=white)`                                 |
| Code Igniter       | ![Code-Igniter](https://img.shields.io/badge/CodeIgniter-%23EF4223.svg?style=for-the-badge&logo=codeIgniter&logoColor=white)                    | `![Code-Igniter](https://img.shields.io/badge/CodeIgniter-%23EF4223.svg?style=for-the-badge&logo=codeIgniter&logoColor=white)`                    |
| Context API        | ![Context-API](https://img.shields.io/badge/Context--Api-000000?style=for-the-badge&logo=react)                                                 | `![Context-API](https://img.shields.io/badge/Context--Api-000000?style=for-the-badge&logo=react)`                                                 |
| CUDA               | ![nVIDIA](https://img.shields.io/badge/cuda-000000.svg?style=for-the-badge&logo=nVIDIA&logoColor=green)                                         | `![nVIDIA](https://img.shields.io/badge/cuda-000000.svg?style=for-the-badge&logo=nVIDIA&logoColor=green)`                                                 |
| DaisyUI            | ![DaisyUI](https://img.shields.io/badge/daisyui-5A0EF8?style=for-the-badge&logo=daisyui&logoColor=white) | `![DaisyUI](https://img.shields.io/badge/daisyui-5A0EF8?style=for-the-badge&logo=daisyui&logoColor=white)`                                    |
| Deno JS            | ![Deno JS](https://img.shields.io/badge/deno%20js-000000?style=for-the-badge&logo=deno&logoColor=white)                                         | `![Deno JS](https://img.shields.io/badge/deno%20js-000000?style=for-the-badge&logo=deno&logoColor=white)`                                         |
| Directus           | ![Directus](https://img.shields.io/badge/directus-%2364f.svg?style=for-the-badge&logo=directus&logoColor=white)                                 | `![Directus](https://img.shields.io/badge/directus-%2364f.svg?style=for-the-badge&logo=directus&logoColor=white)`                                 |
| Django             | ![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)                                    | `![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)`                                    |
| DjangoREST         | ![DjangoREST](https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray)     | `![DjangoREST](https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray)`     |
| Drupal             | ![Drupal](https://img.shields.io/badge/drupal-%230678BE.svg?style=for-the-badge&logo=drupal&logoColor=white)                                    | `![Drupal](https://img.shields.io/badge/drupal-%230678BE.svg?style=for-the-badge&logo=drupal&logoColor=white)`                            |
| EJS                | ![EJS](https://img.shields.io/badge/ejs-%23B4CA65.svg?style=for-the-badge&logo=ejs&logoColor=black)                                             | `![EJS](https://img.shields.io/badge/ejs-%23B4CA65.svg?style=for-the-badge&logo=ejs&logoColor=black)`                                             |
| Elasticsearch      | ![Elasticsearch](https://img.shields.io/badge/elasticsearch-%230377CC.svg?style=for-the-badge&logo=elasticsearch&logoColor=white)               | `![Elasticsearch](https://img.shields.io/badge/elasticsearch-%230377CC.svg?style=for-the-badge&logo=elasticsearch&logoColor=white)`               |
| Electron.js        | ![Electron.js](https://img.shields.io/badge/Electron-191970?style=for-the-badge&logo=Electron&logoColor=white)                                  | `![Electron.js](https://img.shields.io/badge/Electron-191970?style=for-the-badge&logo=Electron&logoColor=white)`                                  |
| Ember              | ![Ember](https://img.shields.io/badge/ember-1C1E24?style=for-the-badge&logo=ember.js&logoColor=#D04A37)                                         | `![Ember](https://img.shields.io/badge/ember-1C1E24?style=for-the-badge&logo=ember.js&logoColor=#D04A37)`                                         |
| ESBuild            | ![Esbuild](https://img.shields.io/badge/esbuild-%23FFCF00.svg?style=for-the-badge&logo=esbuild&logoColor=black)                                         | `![Esbuild](https://img.shields.io/badge/esbuild-%23FFCF00.svg?style=for-the-badge&logo=esbuild&logoColor=black)`                                         |
| Expo               | ![Expo](https://img.shields.io/badge/expo-1C1E24?style=for-the-badge&logo=expo&logoColor=#D04A37)                                               | `![Expo](https://img.shields.io/badge/expo-1C1E24?style=for-the-badge&logo=expo&logoColor=#D04A37)`                                               |
| Express.js         | ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)                       | `![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)`                       |
| FastAPI            | ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)                                                        | `![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)`                                                        |
| Fastify            | ![Fastify](https://img.shields.io/badge/fastify-%23000000.svg?style=for-the-badge&logo=fastify&logoColor=white)                                 | `![Fastify](https://img.shields.io/badge/fastify-%23000000.svg?style=for-the-badge&logo=fastify&logoColor=white)`                                 |
| Filament           | ![Filament](https://img.shields.io/badge/Filament-FFAA00?style=for-the-badge&logoColor=%23000000)                                               | `![Filament](https://img.shields.io/badge/Filament-FFAA00?style=for-the-badge&logoColor=%23000000)`                                               |
| Flask              | ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)                                          | `![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)`                                          |
| Flutter            | ![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)                                 | `![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)`                                 |
| Framework7         | ![Framework7](https://img.shields.io/badge/framework7-%23EE350F.svg?style=for-the-badge&logo=framework7&logoColor=white)                        | `![Framework7](https://img.shields.io/badge/framework7-%23EE350F.svg?style=for-the-badge&logo=framework7&logoColor=white)`                                 |
| Gatsby.js          | ![Gatsby](https://img.shields.io/badge/Gatsby-%23663399.svg?style=for-the-badge&logo=gatsby&logoColor=white)                                    | `![Gatsby](https://img.shields.io/badge/Gatsby-%23663399.svg?style=for-the-badge&logo=gatsby&logoColor=white)`                                    |
| Grav               | ![Grav](https://img.shields.io/badge/grav-%23FFFFFF.svg?style=for-the-badge&logo=grav&logoColor=221E1F)                              | `![Grav](https://img.shields.io/badge/grav-%23FFFFFF.svg?style=for-the-badge&logo=grav&logoColor=221E1F)`                              |
| Green Sock         | ![Green Sock](https://img.shields.io/badge/green%20sock-88CE02?style=for-the-badge&logo=greensock&logoColor=white)                              | `![Green Sock](https://img.shields.io/badge/green%20sock-88CE02?style=for-the-badge&logo=greensock&logoColor=white)`                              |
| Gulp               | ![Gulp](https://img.shields.io/badge/GULP-%23CF4647.svg?style=for-the-badge&logo=gulp&logoColor=white)                                          | `![Gulp](https://img.shields.io/badge/GULP-%23CF4647.svg?style=for-the-badge&logo=gulp&logoColor=white)`                                          |
| Gutenberg          | ![Gutenberg](https://img.shields.io/badge/gutenberg-%23077CB2.svg?style=for-the-badge&logo=gutenberg&logoColor=white)                           | `![Gutenberg](https://img.shields.io/badge/gutenberg-%23077CB2.svg?style=for-the-badge&logo=gutenberg&logoColor=white)`                           |
| Insomnia           | ![Insomnia](https://img.shields.io/badge/Insomnia-black?style=for-the-badge&logo=insomnia&logoColor=5849BE)                                     | `![Insomnia](https://img.shields.io/badge/Insomnia-black?style=for-the-badge&logo=insomnia&logoColor=5849BE)`                                     |
| Handlebars         | ![Handlebars](https://img.shields.io/badge/Handlebars-%23000000?style=for-the-badge&logo=Handlebars.js&logoColor=white)                         | `![Handlebars](https://img.shields.io/badge/Handlebars-%23000000?style=for-the-badge&logo=Handlebars.js&logoColor=white)`                         |  
| Hugo| ![Hugo](https://img.shields.io/badge/Hugo-black.svg?style=for-the-badge&logo=Hugo)| `![Hugo](https://img.shields.io/badge/Hugo-black.svg?style=for-the-badge&logo=Hugo)` |
| Ionic              | ![Ionic](https://img.shields.io/badge/Ionic-%233880FF.svg?style=for-the-badge&logo=Ionic&logoColor=white)                               | `![Ionic](https://img.shields.io/badge/Ionic-%233880FF.svg?style=for-the-badge&logo=Ionic&logoColor=white)`                                     |
| Jasmine            | ![Jasmine](https://img.shields.io/badge/jasmine-%238A4182.svg?style=for-the-badge&logo=jasmine&logoColor=white)                                 | `![Jasmine](https://img.shields.io/badge/jasmine-%238A4182.svg?style=for-the-badge&logo=jasmine&logoColor=white)`                                 |
| JavaFx             | ![JavaFX](https://img.shields.io/badge/javafx-%23FF0000.svg?style=for-the-badge&logo=javafx&logoColor=white)                                    | `![JavaFX](https://img.shields.io/badge/javafx-%23FF0000.svg?style=for-the-badge&logo=javafx&logoColor=white)`                                               |
| Jinja            | ![Jinja](https://img.shields.io/badge/jinja-white.svg?style=for-the-badge&logo=jinja&logoColor=black)                                 | `![Jinja](https://img.shields.io/badge/jinja-white.svg?style=for-the-badge&logo=jinja&logoColor=black)`                                 |
| Joomla            | ![Joomla](https://img.shields.io/badge/joomla-%235091CD.svg?style=for-the-badge&logo=joomla&logoColor=white)                         | `![Joomla](https://img.shields.io/badge/joomla-%235091CD.svg?style=for-the-badge&logo=joomla&logoColor=white)`                         |
| jQuery             | ![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white)                                    | `![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white)`                                    |
| JWT/JSON Web Token | ![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)                                                     | `![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)`                                                     |
| Laravel            | ![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white)                                 | `![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white)`                                 |
| Livewire           | ![Livewire](https://img.shields.io/badge/livewire-%234e56a6.svg?style=for-the-badge&logo=livewire&logoColor=white)                                 | `![Livewire](https://img.shields.io/badge/livewire-%234e56a6.svg?style=for-the-badge&logo=livewire&logoColor=white)`                                 |
| Less               | ![Less](https://img.shields.io/badge/less-2B4C80?style=for-the-badge&logo=less&logoColor=white)                                                 | `![Less](https://img.shields.io/badge/less-2B4C80?style=for-the-badge&logo=less&logoColor=white)`                                                 |
| Maven        | ![Maven](https://img.shields.io/badge/apachemaven-C71A36.svg?style=for-the-badge&logo=apachemaven&logoColor=white)                           | `![Maven]((https://img.shields.io/badge/apachemaven-C71A36.svg?style=for-the-badge&logo=apachemaven&logoColor=white))`|
| MUI                | ![MUI](https://img.shields.io/badge/MUI-%230081CB.svg?style=for-the-badge&logo=mui&logoColor=white)                                             | `![MUI](https://img.shields.io/badge/MUI-%230081CB.svg?style=for-the-badge&logo=mui&logoColor=white)`                                             |
| Meteor JS          | ![Metero JS](https://img.shields.io/badge/meteorjs-%23d74c4c.svg?style=for-the-badge&logo=meteor&logoColor=white)                               | `![Meteor JS](https://img.shields.io/badge/meteorjs-%23d74c4c.svg?style=for-the-badge&logo=meteor&logoColor=white)`                               |
| Mantine          | ![Mantine](https://img.shields.io/badge/Mantine-ffffff?style=for-the-badge&logo=Mantine&logoColor=339af0)                               | `![Mantine](https://img.shields.io/badge/Mantine-ffffff?style=for-the-badge&logo=Mantine&logoColor=339af0)`                               |
| MaxCompute         | ![MaxCompute](https://img.shields.io/badge/MaxCompute-%23FF6701?style=for-the-badge&logo=alibabacloud&logoColor=white)                          | `![MaxCompute](https://img.shields.io/badge/MaxCompute-%23FF6701?style=for-the-badge&logo=alibabacloud&logoColor=white)`                          |
| Mediapipe         | ![Mediapipe](https://img.shields.io/badge/mediapipe-0097A7.svg?style=for-the-badge&logo=mediapipe&logoColor=white)                          | `[Mediapipe](https://img.shields.io/badge/mediapipe-0097A7.svg?style=for-the-badge&logo=mediapipe&logoColor=white)`                          |
| NPM                | ![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)                                             | `![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)`                                             |
| NestJS             | ![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white)                                    | `![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white)`                                    |
| Next JS            | ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)                                            | `![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)`                                            |
| Node.js            | ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)                                         | `![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)`                                         |
| Nodemon            | ![Nodemon](https://img.shields.io/badge/NODEMON-%23323330.svg?style=for-the-badge&logo=nodemon&logoColor=%BBDEAD)                               | `![Nodemon](https://img.shields.io/badge/NODEMON-%23323330.svg?style=for-the-badge&logo=nodemon&logoColor=%BBDEAD)`                               |
| Node-RED           | ![Node-RED](https://img.shields.io/badge/Node--RED-%238F0000.svg?style=for-the-badge&logo=node-red&logoColor=white)                            | `![Node-RED](https://img.shields.io/badge/Node--RED-%238F0000.svg?style=for-the-badge&logo=node-red&logoColor=white)`                  |
| Nuxt JS            | ![Nuxt JS](https://img.shields.io/badge/Nuxt-002E3B?style=for-the-badge&logo=nuxt.js&logoColor=#00DC82)                                         | `![Nuxtjs](https://img.shields.io/badge/Nuxt-002E3B?style=for-the-badge&logo=nuxtdotjs&logoColor=#00DC82)`                                        |
| Nx                 | ![Nx](https://img.shields.io/badge/nx-143055?style=for-the-badge&logo=nx&logoColor=white)                                                       | `![Nx](https://img.shields.io/badge/nx-143055?style=for-the-badge&logo=nx&logoColor=white)`                                                       |
| OpenCV             | ![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)                                     | `![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)`                                     |
| OpenGL             | ![OpenGL](https://img.shields.io/badge/OpenGL-%23FFFFFF.svg?style=for-the-badge&logo=opengl)                                                    | `![OpenGL](https://img.shields.io/badge/OpenGL-%23FFFFFF.svg?style=for-the-badge&logo=opengl)`                                                    |
| P5js               | ![P5js](https://img.shields.io/badge/p5.js-ED225D?style=for-the-badge&logo=p5.js&logoColor=FFFFFF)                                              | `![p5js](https://img.shields.io/badge/p5.js-ED225D?style=for-the-badge&logo=p5.js&logoColor=FFFFFF)`                                              |
| Phoenix Framework  | ![Phoenix Framework](https://img.shields.io/badge/phoenixframework-%23FD4F00.svg?style=for-the-badge&logo=phoenixframework&logoColor=black)                                              | `![Phoenix Framework](https://img.shields.io/badge/phoenixframework-%23FD4F00.svg?style=for-the-badge&logo=phoenixframework&logoColor=black)`                                              |
| Plotly Dash | ![Plotly Dash](https://img.shields.io/badge/plotly-3F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)                                             | `![Plotly Dash](https://img.shields.io/badge/plotly-3F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)`                                              |
| PNPM               | ![PNPM](https://img.shields.io/badge/pnpm-%234a4a4a.svg?style=for-the-badge&logo=pnpm&logoColor=f69220)                                              | `![PNPM](https://img.shields.io/badge/pnpm-%234a4a4a.svg?style=for-the-badge&logo=pnpm&logoColor=f69220)`                                              |
|Poetry              |![Poetry](https://img.shields.io/badge/Poetry-%233B82F6.svg?style=for-the-badge&logo=poetry&logoColor=0B3D8D)                                    |`![Poetry](https://img.shields.io/badge/Poetry-%233B82F6.svg?style=for-the-badge&logo=poetry&logoColor=0B3D8D)`                                          |
|Prefect             |![Prefect](https://img.shields.io/badge/Prefect-%23ffffff.svg?style=for-the-badge&logo=prefect&logoColor=white)                                  | `![Prefect](https://img.shields.io/badge/Prefect-%23ffffff.svg?style=for-the-badge&logo=prefect&logoColor=white)`                                 |
| Pug                | ![Pug](https://img.shields.io/badge/Pug-FFF?style=for-the-badge&logo=pug&logoColor=A86454)                                                      | `![Pug](https://img.shields.io/badge/Pug-FFF?style=for-the-badge&logo=pug&logoColor=A86454)`                                                      |
|Pytest              | ![Pytest](https://img.shields.io/badge/pytest-%23ffffff.svg?style=for-the-badge&logo=pytest&logoColor=2f9fe3)|`![Pytest](https://img.shields.io/badge/pytest-%23ffffff.svg?style=for-the-badge&logo=pytest&logoColor=2f9fe3)`|
| Qt                 | ![Qt](https://img.shields.io/badge/Qt-%23217346.svg?style=for-the-badge&logo=Qt&logoColor=white)                                                | `![Qt](https://img.shields.io/badge/Qt-%23217346.svg?style=for-the-badge&logo=Qt&logoColor=white)`                                                |
| Quarkus             | ![Quarkus](https://img.shields.io/badge/quarkus-%234794EB.svg?style=for-the-badge&logo=quarkus&logoColor=white)                                           | `![Quarkus](https://img.shields.io/badge/quarkus-%234794EB.svg?style=for-the-badge&logo=quarkus&logoColor=white)`                                            |
| Quasar             | ![Quasar](https://img.shields.io/badge/Quasar-16B7FB?style=for-the-badge&logo=quasar&logoColor=black)                                           | `![Quasar](https://img.shields.io/badge/Quasar-16B7FB?style=for-the-badge&logo=quasar&logoColor=black)`                                            |
| ROS                | ![ROS](https://img.shields.io/badge/ros-%230A0FF9.svg?style=for-the-badge&logo=ros&logoColor=white)                                             | `![ROS](https://img.shields.io/badge/ros-%230A0FF9.svg?style=for-the-badge&logo=ros&logoColor=white)`                                             |
| RabbitMQ           | ![RabbitMQ](https://img.shields.io/badge/rabbitmq-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)                                     | `![RabbitMQ](https://img.shields.io/badge/Rabbitmq-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)`                                     |
| Radix UI           | ![Radix UI](https://img.shields.io/badge/radix%20ui-161618.svg?style=for-the-badge&logo=radix-ui&logoColor=white)                                     | `![Radix UI](https://img.shields.io/badge/radix%20ui-161618.svg?style=for-the-badge&logo=radix-ui&logoColor=white)`                                     |
| Rails              | ![Rails](https://img.shields.io/badge/rails-%23CC0000.svg?style=for-the-badge&logo=ruby-on-rails&logoColor=white)                               | `![Rails](https://img.shields.io/badge/rails-%23CC0000.svg?style=for-the-badge&logo=ruby-on-rails&logoColor=white)`                               |
| RayLib             | ![RayLib](https://img.shields.io/badge/RAYLIB-FFFFFF?style=for-the-badge&logo=raylib&logoColor=black)                                           | `![RayLib](https://img.shields.io/badge/RAYLIB-FFFFFF?style=for-the-badge&logo=raylib&logoColor=black)`                   |
| React              | ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)                                   | `![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)`                                   |
| React Native       | ![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)                     | `![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)`                     |
| React Query        | ![React Query](https://img.shields.io/badge/-React%20Query-FF4154?style=for-the-badge&logo=react%20query&logoColor=white)                       | `![React Query](https://img.shields.io/badge/-React%20Query-FF4154?style=for-the-badge&logo=react%20query&logoColor=white)`                       |
| React Router       | ![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)                         | `![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)`                         |
| React Hook Form    | ![React Hook Form](https://img.shields.io/badge/React%20Hook%20Form-%23EC5990.svg?style=for-the-badge&logo=reacthookform&logoColor=white)       | `![React Hook Form](https://img.shields.io/badge/React%20Hook%20Form-%23EC5990.svg?style=for-the-badge&logo=reacthookform&logoColor=white)`       |
| Redux              | ![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white)                                       | `![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white)` 
| Remix              | ![Remix](https://img.shields.io/badge/remix-%23000.svg?style=for-the-badge&logo=remix&logoColor=white)                                       | `![Remix](https://img.shields.io/badge/remix-%23000.svg?style=for-the-badge&logo=remix&logoColor=white)`                                       |
| RollupJS           | ![RollupJS](https://img.shields.io/badge/RollupJS-ef3335?style=for-the-badge&logo=rollup.js&logoColor=white)                                      | `![RollupJS](https://img.shields.io/badge/RollupJS-ef3335?style=for-the-badge&logo=rollup.js&logoColor=white)`                                     |
| RxDB               | ![RxDB](https://img.shields.io/badge/rxdb-%238D1F89.svg?style=for-the-badge&logo=rxdb&logoColor=white)                                          | `![RxDB](https://img.shields.io/badge/rxjs-%23B7178C.svg?style=for-the-badge&logo=reactivex&logoColor=white)`                                     |
| RxJS               | ![RxJS](https://img.shields.io/badge/rxjs-%23B7178C.svg?style=for-the-badge&logo=reactivex&logoColor=white)                                     | `![RxJS](https://img.shields.io/badge/rxjs-%23B7178C.svg?style=for-the-badge&logo=reactivex&logoColor=white)`                                     |
| SASS               | ![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white)                                            | `![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white)`                                            |
|Scrapy              |![Scrapy](https://img.shields.io/badge/scrapy-%2360a839.svg?style=for-the-badge&logo=scrapy&logoColor=d1d2d3)|`![Scrapy](https://img.shields.io/badge/scrapy-%2360a839.svg?style=for-the-badge&logo=scrapy&logoColor=d1d2d3)`|
| Semantic UI React  | ![Semantic UI React](https://img.shields.io/badge/Semantic%20UI%20React-%2335BDB2.svg?style=for-the-badge&logo=SemanticUIReact&logoColor=white) | `![Semantic UI React](https://img.shields.io/badge/Semantic%20UI%20React-%2335BDB2.svg?style=for-the-badge&logo=SemanticUIReact&logoColor=white)` |
| Snowflake  | ![Snowflake](https://img.shields.io/badge/snowflake-%2329B5E8.svg?style=for-the-badge&logo=snowflake&logoColor=white) | `![Snowflake](https://img.shields.io/badge/snowflake-%2329B5E8.svg?style=for-the-badge&logo=snowflake&logoColor=white)` |
| Socket.io          | ![Socket.io](https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101)                                 | `![Socket.io](https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101)`                                 |
| SolidJS            | ![SolidJS](https://img.shields.io/badge/SolidJS-2c4f7c?style=for-the-badge&logo=solid&logoColor=c8c9cb)                                         | `![SolidJS](https://img.shields.io/badge/SolidJS-2c4f7c?style=for-the-badge&logo=solid&logoColor=c8c9cb)`                                         |
| Spring             | ![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)                                    | `![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)`                                    |
| Strapi             | ![Strapi](https://img.shields.io/badge/strapi-%232E7EEA.svg?style=for-the-badge&logo=strapi&logoColor=white)                                    | `![Strapi](https://img.shields.io/badge/strapi-%232E7EEA.svg?style=for-the-badge&logo=strapi&logoColor=white)`                                    |
| Streamlit          | ![Streamlit](https://img.shields.io/badge/Streamlit-%23FE4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white) | `![Streamlit](https://img.shields.io/badge/Streamlit-%23FE4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white)` |
| Styled Components  | ![Styled Components](https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white)         | `![Styled Components](https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white)`         |
| Stylus             | ![Stylus](https://img.shields.io/badge/stylus-%23ff6347.svg?style=for-the-badge&logo=stylus&logoColor=white)                                    | `![Stylus](https://img.shields.io/badge/stylus-%23ff6347.svg?style=for-the-badge&logo=stylus&logoColor=white)`                                    |
| Svelte             | ![Svelte](https://img.shields.io/badge/svelte-%23f1413d.svg?style=for-the-badge&logo=svelte&logoColor=white)                                    | `![Svelte](https://img.shields.io/badge/svelte-%23f1413d.svg?style=for-the-badge&logo=svelte&logoColor=white)`                                    |
| SvelteKit          | ![SvelteKit](https://img.shields.io/badge/sveltekit-%23ff3e00.svg?style=for-the-badge&logo=svelte&logoColor=white)                                    | `![Svelte](https://img.shields.io/badge/svelte-%23f1413d.svg?style=for-the-badge&logo=svelte&logoColor=white)`                                    |
| Symfony            | ![Symfony](https://img.shields.io/badge/symfony-%23000000.svg?style=for-the-badge&logo=symfony&logoColor=white)                                 | `![Symfony](https://img.shields.io/badge/symfony-%23000000.svg?style=for-the-badge&logo=symfony&logoColor=white)`                                 |
| TailwindCSS        | ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)                    | `![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)`                    |
| Tauri              | ![Tauri](https://img.shields.io/badge/tauri-%2324C8DB.svg?style=for-the-badge&logo=tauri&logoColor=%23FFFFFF)                                   | `![Tauri](https://img.shields.io/badge/tauri-%2324C8DB.svg?style=for-the-badge&logo=tauri&logoColor=%23FFFFFF)`                                   |
| Three.js           | ![Three js](https://img.shields.io/badge/threejs-black?style=for-the-badge&logo=three.js&logoColor=white)                                       | `![Threejs](https://img.shields.io/badge/threejs-black?style=for-the-badge&logo=three.js&logoColor=white)`                                        |
| Thymeleaf          | ![Thymeleaf](https://img.shields.io/badge/Thymeleaf-%23005C0F.svg?style=for-the-badge&logo=Thymeleaf&logoColor=white)                           | `![Thymeleaf](https://img.shields.io/badge/Thymeleaf-%23005C0F.svg?style=for-the-badge&logo=Thymeleaf&logoColor=white)`                           |
| tRPC               | ![Badge Name](https://img.shields.io/badge/tRPC-%232596BE.svg?style=for-the-badge&logo=tRPC&logoColor=white)                                    | `![tRPC](https://img.shields.io/badge/tRPC-%232596BE.svg?style=for-the-badge&logo=tRPC&logoColor=white)`
| TypeGraphQL        | ![Type-graphql](https://img.shields.io/badge/-TypeGraphQL-%23C04392?style=for-the-badge)                                                        | `![Type-graphql](https://img.shields.io/badge/-TypeGraphQL-%23C04392?style=for-the-badge)`                                                        |
| UnoCSS        | ![UnoCSS](https://img.shields.io/badge/unocss-333333.svg?style=for-the-badge&logo=unocss&logoColor=white)                                                        | `![UnoCSS](https://img.shields.io/badge/unocss-333333.svg?style=for-the-badge&logo=unocss&logoColor=white)`                                                        |
| Vite             | ![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)                              | `![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)`  
| Vue.js             | ![Vue.js](https://img.shields.io/badge/vue.js-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)                              | `![Vue.js](https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)`                               |
| Vuetify            | ![Vuetify](https://img.shields.io/badge/Vuetify-1867C0?style=for-the-badge&logo=vuetify&logoColor=AEDDFF)                                       | `![Vuetify](https://img.shields.io/badge/Vuetify-1867C0?style=for-the-badge&logo=vuetify&logoColor=AEDDFF)`
| Vulkan             | ![Vulkan API](https://img.shields.io/badge/Vulkan-AC162C.svg?style=for-the-badge&logo=vulkan&logoColor=white&logoSize=auto)                                   | `![Vulkan API](https://img.shields.io/badge/Vulkan-AC162C.svg?style=for-the-badge&logo=vulkan&logoColor=white&logoSize=auto)`                       |
| Webflow            | ![Webflow](https://img.shields.io/badge/webflow-%23146EF5.svg?style=for-the-badge&logo=webflow&logoColor=white)                                              | `![Webflow](https://img.shields.io/badge/webflow-%23146EF5.svg?style=for-the-badge&logo=webflow&logoColor=white)`                                              |
| WebGL              | ![WebGL](https://img.shields.io/badge/WebGL-990000?logo=webgl&logoColor=white&style=for-the-badge)                                              | `![WebGL](https://img.shields.io/badge/WebGL-990000?logo=webgl&logoColor=white&style=for-the-badge)`                                              |
| Webpack            | ![Webpack](https://img.shields.io/badge/webpack-%238DD6F9.svg?style=for-the-badge&logo=webpack&logoColor=black)                                 | `![Webpack](https://img.shields.io/badge/webpack-%238DD6F9.svg?style=for-the-badge&logo=webpack&logoColor=black)`                                 |
| Web3.js            | ![Web3.js](https://img.shields.io/badge/web3.js-F16822?style=for-the-badge&logo=web3.js&logoColor=white)                                        | `![Web3.js](https://img.shields.io/badge/web3.js-F16822?style=for-the-badge&logo=web3.js&logoColor=white)`                                        |
| WindiCSS           | ![Windicss](https://img.shields.io/badge/windicss-48B0F1.svg?style=for-the-badge&logo=windi-css&logoColor=white)                                | `![Windicss](https://img.shields.io/badge/windicss-48B0F1.svg?style=for-the-badge&logo=windi-css&logoColor=white)`                                |
| WordPress   | ![WordPress](https://img.shields.io/badge/WordPress-%23117AC9.svg?style=for-the-badge&logo=WordPress&logoColor=white)        | `![WordPress](https://img.shields.io/badge/WordPress-%23117AC9.svg?style=for-the-badge&logo=WordPress&logoColor=white)`        |
| Xamarin            | ![Xamarin](https://img.shields.io/badge/Xamarin-3199DC?style=for-the-badge&logo=xamarin&logoColor=white)                                        | `![Xamarin](https://img.shields.io/badge/Xamarin-3199DC?style=for-the-badge&logo=xamarin&logoColor=white)`                                        |
| Yarn               | ![Yarn](https://img.shields.io/badge/yarn-%232C8EBB.svg?style=for-the-badge&logo=yarn&logoColor=white)                                          | `![Yarn](https://img.shields.io/badge/yarn-%232C8EBB.svg?style=for-the-badge&logo=yarn&logoColor=white)`                                          |
Zod                | ![Zod](https://img.shields.io/badge/zod-%233068b7.svg?style=for-the-badge&logo=zod&logoColor=white)                                             | `![Zod](https://img.shields.io/badge/zod-%233068b7.svg?style=for-the-badge&logo=zod&logoColor=white)`                                             |

[(Back to top)](#table-of-contents)

### 🎮 Gaming

| Name                | Badge                                                                                                                           | Markdown                                                                                                                          |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| AMD            | ![AMD](https://img.shields.io/badge/AMD-%23000000.svg?style=for-the-badge&logo=amd&logoColor=white)                                  | `![AMD](https://img.shields.io/badge/AMD-%23000000.svg?style=for-the-badge&logo=amd&logoColor=white)`                     |
| Analogue            | ![Analogue](https://img.shields.io/badge/Analogue-1A1A1A?style=for-the-badge&logo=Analogue&logoColor=white)                     | `![Analogue](https://img.shields.io/badge/Analogue-1A1A1A?style=for-the-badge&logo=Analogue&logoColor=white)`                     |
| Battle.net          | ![Battle.net](https://img.shields.io/badge/battle.net-%2300AEFF.svg?style=for-the-badge&logo=battle.net&logoColor=white)        | `![Battle.net](https://img.shields.io/badge/battle.net-%2300AEFF.svg?style=for-the-badge&logo=battle.net&logoColor=white)`        |
| Bevy                | ![Bevy](https://img.shields.io/badge/bevy-%23232326.svg?style=for-the-badge&logo=bevy&logoColor=white)                          | `![Bevy](https://img.shields.io/badge/bevy-%23232326.svg?style=for-the-badge&logo=bevy&logoColor=white)`                          |
| EA                  | ![EA](https://img.shields.io/badge/ea-%23000000.svg?style=for-the-badge&logo=ea&logoColor=white)                                | `![EA](https://img.shields.io/badge/ea-%23000000.svg?style=for-the-badge&logo=ea&logoColor=white)`                                |
| Epic Games          | ![Epic Games](https://img.shields.io/badge/epicgames-%23313131.svg?style=for-the-badge&logo=epicgames&logoColor=white)          | `![Epic Games](https://img.shields.io/badge/epicgames-%23313131.svg?style=for-the-badge&logo=epicgames&logoColor=white)`          |
| Godot Engine        | ![Godot Engine](https://img.shields.io/badge/GODOT-%23FFFFFF.svg?style=for-the-badge&logo=godot-engine)                         | `![Godot Engine](https://img.shields.io/badge/GODOT-%23FFFFFF.svg?style=for-the-badge&logo=godot-engine)`                         |
| Humble Bundle       | ![Humble Bundle](https://img.shields.io/badge/HumbleBundle-%23494F5C.svg?style=for-the-badge&logo=HumbleBundle&logoColor=white) | `![Humble Bundle](https://img.shields.io/badge/HumbleBundle-%23494F5C.svg?style=for-the-badge&logo=HumbleBundle&logoColor=white)` |
| Intel               | ![Intel](https://img.shields.io/badge/intel-%230068B5%20.svg?style=for-the-badge&logo=intel&logoColor=white)                    | `![Intel](https://img.shields.io/badge/intel-%230068B5%20.svg?style=for-the-badge&logo=intel&logoColor=white)` |
| Itch.io             | ![Itch.io](https://img.shields.io/badge/Itch-%23FF0B34.svg?style=for-the-badge&logo=Itch.io&logoColor=white)                    | `![Itch.io](https://img.shields.io/badge/Itch-%23FF0B34.svg?style=for-the-badge&logo=Itch.io&logoColor=white)`                    |
| nVIDIA              | ![nVIDIA](https://img.shields.io/badge/nVIDIA-%2376B900.svg?style=for-the-badge&logo=nVIDIA&logoColor=white)                    | `![nVIDIA](https://img.shields.io/badge/nVIDIA-%2376B900.svg?style=for-the-badge&logo=nVIDIA&logoColor=white)`                    |
| OpenGL              | ![OpenGL](https://img.shields.io/badge/OpenGL-white?logo=OpenGL&style=for-the-badge)                                            | `![OpenGL](https://img.shields.io/badge/OpenGL-white?logo=OpenGL&style=for-the-badge)`                                            |
| PlayStation Network | ![PlayStation Network](https://img.shields.io/badge/PSN-%230070D1.svg?style=for-the-badge&logo=Playstation&logoColor=white)     | `![PlayStation Network](https://img.shields.io/badge/PSN-%230070D1.svg?style=for-the-badge&logo=Playstation&logoColor=white)`     |
| Riot Games          | ![Riot Games](https://img.shields.io/badge/riotgames-D32936.svg?style=for-the-badge&logo=riotgames&logoColor=white)             | `![Riot Games](https://img.shields.io/badge/riotgames-D32936.svg?style=for-the-badge&logo=riotgames&logoColor=white)`             |
| Sidequest             | ![Sidequest](https://img.shields.io/badge/sidequest-%23101227.svg?style=for-the-badge&logo=sidequest&logoColor=white)         | `![Sidequest](https://img.shields.io/badge/sidequest-%23101227.svg?style=for-the-badge&logo=sidequest&logoColor=white)`           |
| Square Enix         | ![Square Enix](https://img.shields.io/badge/SquareEnix-%23ED1C24.svg?style=for-the-badge&logo=SquareEnix&logoColor=white)       | `![Square Enix](https://img.shields.io/badge/SquareEnix-%23ED1C24.svg?style=for-the-badge&logo=SquareEnix&logoColor=white)`       |
| Steam               | ![Steam](https://img.shields.io/badge/steam-%23000000.svg?style=for-the-badge&logo=steam&logoColor=white)                       | `![Steam](https://img.shields.io/badge/steam-%23000000.svg?style=for-the-badge&logo=steam&logoColor=white)`                       |
| Ubisoft             | ![Ubisoft](https://img.shields.io/badge/Ubisoft-%23F5F5F5.svg?style=for-the-badge&logo=Ubisoft&logoColor=black)                 | `![Ubisoft](https://img.shields.io/badge/Ubisoft-%23F5F5F5.svg?style=for-the-badge&logo=Ubisoft&logoColor=black)`                 |
| Unity               | ![Unity](https://img.shields.io/badge/unity-%23000000.svg?style=for-the-badge&logo=unity&logoColor=white)                       | `![Unity](https://img.shields.io/badge/unity-%23000000.svg?style=for-the-badge&logo=unity&logoColor=white)`                       |
| Unreal Engine       | ![Unreal Engine](https://img.shields.io/badge/unrealengine-%23313131.svg?style=for-the-badge&logo=unrealengine&logoColor=white) | `![Unreal Engine](https://img.shields.io/badge/unrealengine-%23313131.svg?style=for-the-badge&logo=unrealengine&logoColor=white)` |
| Xbox                | ![Xbox](https://img.shields.io/badge/xbox-%23107C10.svg?style=for-the-badge&logo=xbox&logoColor=white)                          | `![Xbox](https://img.shields.io/badge/xbox-%23107C10.svg?style=for-the-badge&logo=xbox&logoColor=white)`                          |


[(Back to top)](#table-of-contents)

### 🕹️ Game Consoles

| Name             | Badge                                                                                                                                 | Markdown                                                                                                                                |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| 3DS              | ![3DS](https://img.shields.io/badge/3DS-D12228?style=for-the-badge&logo=nintendo-3ds&logoColor=white)                                 | `![3DS](https://img.shields.io/badge/3DS-D12228?style=for-the-badge&logo=nintendo-3ds&logoColor=white)`                                 |
| Gamecube         | ![Gamecube](https://img.shields.io/badge/Gamecube-6A5FBB?style=for-the-badge&logo=nintendo-gamecube&logoColor=white)                  | `![Gamecube](https://img.shields.io/badge/Gamecube-6A5FBB?style=for-the-badge&logo=nintendo-gamecube&logoColor=white)`                  |
| Playstation      | ![Playstation](https://img.shields.io/badge/Playstation-003791?style=for-the-badge&logo=playstation&logoColor=white)                  | `![Playstation](https://img.shields.io/badge/Playstation-003791?style=for-the-badge&logo=playstation&logoColor=white)`                  |
| Playstation 2    | ![Playstation 2](https://img.shields.io/badge/Playstation%202-003791?style=for-the-badge&logo=playstation-2&logoColor=white)          | `![Playstation 2](https://img.shields.io/badge/Playstation%202-003791?style=for-the-badge&logo=playstation-2&logoColor=white)`          |
| Playstation 3    | ![Playstation 3](https://img.shields.io/badge/Playstation%203-003791?style=for-the-badge&logo=playstation-3&logoColor=white)          | `![Playstation 3](https://img.shields.io/badge/Playstation%203-003791?style=for-the-badge&logo=playstation-3&logoColor=white)`          |
| Playstation 4    | ![Playstation 4](https://img.shields.io/badge/Playstation%204-003791?style=for-the-badge&logo=playstation-4&logoColor=white)          | `![Playstation 4](https://img.shields.io/badge/Playstation%204-003791?style=for-the-badge&logo=playstation-4&logoColor=white)`          |
| Playstation 5    | ![Playstation 5](https://img.shields.io/badge/Playstation%205-003791?style=for-the-badge&logo=playstation-5&logoColor=white)          | `![Playstation 5](https://img.shields.io/badge/Playstation%205-003791?style=for-the-badge&logo=playstation-5&logoColor=white)`          |
| Playstation Vita | ![Playstation Vita](https://img.shields.io/badge/Playstation%20Vita-003791?style=for-the-badge&logo=playstation-vita&logoColor=white) | `![Playstation Vita](https://img.shields.io/badge/Playstation%20Vita-003791?style=for-the-badge&logo=playstation-vita&logoColor=white)` |
| Switch           | ![Switch](https://img.shields.io/badge/Switch-E60012?style=for-the-badge&logo=nintendo-switch&logoColor=white)                        | `![Switch](https://img.shields.io/badge/Switch-E60012?style=for-the-badge&logo=nintendo-switch&logoColor=white)`                        |
| Wii              | ![Wii](https://img.shields.io/badge/Wii-8B8B8B?style=for-the-badge&logo=wii&logoColor=white)                                          | `![Wii](https://img.shields.io/badge/Wii-8B8B8B?style=for-the-badge&logo=wii&logoColor=white)`                                          |
| Wii U            | ![Wii U](https://img.shields.io/badge/Wii%20U-8B8B8B?style=for-the-badge&logo=wiiu&logoColor=white)                                   | `![Wii U](https://img.shields.io/badge/Wii%20U-8B8B8B?style=for-the-badge&logo=wiiu&logoColor=white)`                                   |
| Xbox             | ![Xbox](https://img.shields.io/badge/xbox-%23107C10.svg?style=for-the-badge&logo=xbox&logoColor=white)                                | `![Xbox](https://img.shields.io/badge/xbox-%23107C10.svg?style=for-the-badge&logo=xbox&logoColor=white)`                                |

[(Back to top)](#table-of-contents)

### ☁️ Hosting/SaaS

| Name          | Badge                                                                                                                           | Markdown                                                                                                                          |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| Asana | ![Asana](https://img.shields.io/badge/asana-F06A6A.svg?style=for-the-badge&logo=asana&logoColor=white) | `![Asana](https://img.shields.io/badge/asana-F06A6A.svg?style=for-the-badge&logo=asana&logoColor=white)` |
| Alibaba Cloud | ![Alibaba Cloud](https://img.shields.io/badge/AlibabaCloud-%23FF6701.svg?style=for-the-badge&logo=alibabacloud&logoColor=white) | `![Alibaba Cloud](https://img.shields.io/badge/AlibabaCloud-%23FF6701.svg?style=for-the-badge&logo=alibabacloud&logoColor=white)` |
| AWS           | ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)                      | `![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)`                      |
| Azure         | ![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white)              | `![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white)`              |
| Clickup       | ![ClickUp](https://img.shields.io/badge/clickup-7B68EE.svg?style=for-the-badge&logo=clickup&logoColor=white)               | `![ClickUp](https://img.shields.io/badge/clickup-7B68EE.svg?style=for-the-badge&logo=clickup&logoColor=white)`               |
| Cloudflare    | ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white)               | `![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white)`               |
| Codeberg      | ![Codeberg](https://img.shields.io/badge/Codeberg-2185D0?style=for-the-badge&logo=Codeberg&logoColor=white)                     | `![Codeberg](https://img.shields.io/badge/Codeberg-2185D0?style=for-the-badge&logo=Codeberg&logoColor=white)`                     |
| Datadog       | ![Datadog](https://img.shields.io/badge/datadog-%23632CA6.svg?style=for-the-badge&logo=datadog&logoColor=white)                 | `![Datadog](https://img.shields.io/badge/datadog-%23632CA6.svg?style=for-the-badge&logo=datadog&logoColor=white)`                 |
| DigitalOcean  | ![DigitalOcean](https://img.shields.io/badge/DigitalOcean-%230167ff.svg?style=for-the-badge&logo=digitalOcean&logoColor=white)  | `![DigitalOcean](https://img.shields.io/badge/DigitalOcean-%230167ff.svg?style=for-the-badge&logo=digitalOcean&logoColor=white)`  |
| Firebase      | ![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase)                              | `![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase)`                              |
| Github Pages  | ![GithubPages](https://img.shields.io/badge/github%20pages-121013?style=for-the-badge&logo=github&logoColor=white) |`![Github Pages](https://img.shields.io/badge/github%20pages-121013?style=for-the-badge&logo=github&logoColor=white)` |
| Glitch        | ![Glitch](https://img.shields.io/badge/glitch-%233333FF.svg?style=for-the-badge&logo=glitch&logoColor=white)                    | `![Glitch](https://img.shields.io/badge/glitch-%233333FF.svg?style=for-the-badge&logo=glitch&logoColor=white)`                    |
| Google Cloud  | ![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)   | `![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)`   |
| Heroku        | ![Heroku](https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white)                    | `![Heroku](https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white)`                    |
| Linear        | ![Linear](https://img.shields.io/badge/linear-5E6AD2.svg?style=for-the-badge&logo=linear&logoColor=white)                          | `![Linear](https://img.shields.io/badge/linear-5E6AD2.svg?style=for-the-badge&logo=linear&logoColor=white)`                           |
| Linode        | ![Linode](https://img.shields.io/badge/linode-00A95C?style=for-the-badge&logo=linode&logoColor=white)                           | `![Linode](https://img.shields.io/badge/linode-00A95C?style=for-the-badge&logo=linode&logoColor=white)`                           |
| Netlify       | ![Netlify](https://img.shields.io/badge/netlify-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=#00C7B7)               | `![Netlify](https://img.shields.io/badge/netlify-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=#00C7B7)`               |
| Oracle        | ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)                           | `![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)`                           |
| OpenStack     | ![OpenStack](https://img.shields.io/badge/Openstack-%23f01742.svg?style=for-the-badge&logo=openstack&logoColor=white)           | `![OpenStack](https://img.shields.io/badge/Openstack-%23f01742.svg?style=for-the-badge&logo=openstack&logoColor=white)`           |
| OVH           | ![OVH](https://img.shields.io/badge/ovh-%23123F6D.svg?style=for-the-badge&logo=ovh&logoColor=#123F6D)                           | `![OVH](https://img.shields.io/badge/ovh-%23123F6D.svg?style=for-the-badge&logo=ovh&logoColor=#123F6D)`                           |
| PythonAnywhere | ![PythonAnywhere](https://img.shields.io/badge/pythonanywhere-%232F9FD7.svg?style=for-the-badge&logo=pythonanywhere&logoColor=151515)|`![PythonAnywhere](https://img.shields.io/badge/pythonanywhere-%232F9FD7.svg?style=for-the-badge&logo=pythonanywhere&logoColor=151515)`           |
| Proxmox         | ![Proxmox](https://img.shields.io/badge/proxmox-proxmox?style=for-the-badge&logo=proxmox&logoColor=%23E57000&labelColor=%232b2a33&color=%232b2a33)                                          | `![Proxmox](https://img.shields.io/badge/proxmox-proxmox?style=for-the-badge&logo=proxmox&logoColor=%23E57000&labelColor=%232b2a33&color=%232b2a33)`
| Render        | ![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white)                       | `![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white)`                       |
| Scaleway      | ![Scaleway](https://img.shields.io/badge/SCALEWAY-%234f0599.svg?style=for-the-badge&logo=scaleway&logoColor=white)              | `![Scaleway](https://img.shields.io/badge/SCALEWAY-%234f0599.svg?style=for-the-badge&logo=scaleway&logoColor=white)`              |
| Vercel        | ![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)                    | `![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)`                    |
| Vultr         | ![Vultr](https://img.shields.io/badge/Vultr-007BFC.svg?style=for-the-badge&logo=vultr)                                          | `![Vultr](https://img.shields.io/badge/Vultr-007BFC.svg?style=for-the-badge&logo=vultr)`                                         |

[(Back to top)](#table-of-contents)

### 💻 IDEs/Editors

| Name               | Badge                                                                                                                                             | Markdown                                                                                                                                            |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| Android Studio     | ![Android Studio](https://img.shields.io/badge/android%20studio-346ac1?style=for-the-badge&logo=android%20studio&logoColor=white)               | `![Android Studio](https://img.shields.io/badge/android%20studio-346ac1?style=for-the-badge&logo=android%20studio&logoColor=white)`               |
| Atom               | ![Atom](https://img.shields.io/badge/Atom-%2366595C.svg?style=for-the-badge&logo=atom&logoColor=white)                                            | `![Atom](https://img.shields.io/badge/Atom-%2366595C.svg?style=for-the-badge&logo=atom&logoColor=white)`                                            |
| CLion              | ![CLion](https://img.shields.io/badge/CLion-black?style=for-the-badge&logo=clion&logoColor=white)                                                 | `![CLion](https://img.shields.io/badge/CLion-black?style=for-the-badge&logo=clion&logoColor=white)`                                                 |
| CodePen            | ![CodePen](https://img.shields.io/badge/CodePen-white?style=for-the-badge&logo=codepen&logoColor=black)                                           | `![CodePen](https://img.shields.io/badge/CodePen-white?style=for-the-badge&logo=codepen&logoColor=black)`                                           |
| CodeSandbox        | ![CodeSandbox](https://img.shields.io/badge/Codesandbox-040404?style=for-the-badge&logo=codesandbox&logoColor=DBDBDB)                             | `![CodeSandbox](https://img.shields.io/badge/Codesandbox-040404?style=for-the-badge&logo=codesandbox&logoColor=DBDBDB)`                             |
| Doxygen            | ![Doxygen](https://img.shields.io/badge/doxygen-2C4AA8?style=for-the-badge&logo=doxygen&logoColor=white) | `![Doxygen](https://img.shields.io/badge/doxygen-2C4AA8?style=for-the-badge&logo=doxygen&logoColor=white)` |
| Eclipse            | ![Eclipse](https://img.shields.io/badge/Eclipse-FE7A16.svg?style=for-the-badge&logo=Eclipse&logoColor=white)                                      | `![Eclipse](https://img.shields.io/badge/Eclipse-FE7A16.svg?style=for-the-badge&logo=Eclipse&logoColor=white)`                                      |
| Emacs              | ![Emacs](https://img.shields.io/badge/Emacs-%237F5AB6.svg?&style=for-the-badge&logo=gnu-emacs&logoColor=white)                                    | `![Emacs](https://img.shields.io/badge/Emacs-%237F5AB6.svg?&style=for-the-badge&logo=gnu-emacs&logoColor=white)`                                    |
| GoLand             | ![GoLand](https://img.shields.io/badge/GoLand-0f0f0f?&style=for-the-badge&logo=goland&logoColor=white)                                            | `![GoLand](https://img.shields.io/badge/GoLand-0f0f0f?&style=for-the-badge&logo=goland&logoColor=white)`                                            |
| Google Colab       | ![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)                   | `![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)`                   |
| Helix              | ![Helix](https://img.shields.io/badge/Helix-%2328153e.svg?style=for-the-badge&logo=helix&logoColor=white)                                         | `![Helix](https://img.shields.io/badge/Helix-%2328153e.svg?style=for-the-badge&logo=helix&logoColor=white)`
| IntelliJ IDEA      | ![IntelliJ IDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)                     | `![IntelliJ IDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)`                     |
| Jupyter Notebook   | ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)                          | `![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)`                          |
| Neovim             | ![Neovim](https://img.shields.io/badge/NeoVim-%2357A143.svg?&style=for-the-badge&logo=neovim&logoColor=white)                                     | `![Neovim](https://img.shields.io/badge/NeoVim-%2357A143.svg?&style=for-the-badge&logo=neovim&logoColor=white)`                                     |
| NetBeans IDE       | ![NetBeans IDE](https://img.shields.io/badge/NetBeansIDE-1B6AC6.svg?style=for-the-badge&logo=apache-netbeans-ide&logoColor=white)                 | `![NetBeans IDE](https://img.shields.io/badge/NetBeansIDE-1B6AC6.svg?style=for-the-badge&logo=apache-netbeans-ide&logoColor=white)`                 |
| Notepad++       | ![Notepad++](https://img.shields.io/badge/Notepad++-90E59A.svg?style=for-the-badge&logo=notepad%2b%2b&logoColor=black)                 | `![Notepad++](https://img.shields.io/badge/Notepad++-90E59A.svg?style=for-the-badge&logo=notepad%2b%2b&logoColor=black)`                 |
| Obsidian           | ![Obsidian](https://img.shields.io/badge/Obsidian-%23483699.svg?style=for-the-badge&logo=obsidian&logoColor=white)                                | `![Obsidian](https://img.shields.io/badge/Obsidian-%23483699.svg?style=for-the-badge&logo=obsidian&logoColor=white)`                                |
| P5js Editor        | ![P5js Editor](https://img.shields.io/badge/p5.js%20editor-ED225D?style=for-the-badge&logo=p5.js&logoColor=FFFFFF)                                | `![p5js Editor](https://img.shields.io/badge/p5.js-ED225D?style=for-the-badge&logo=p5.js&logoColor=FFFFFF)`                                         |
| PhpStorm           | ![PhpStorm](https://img.shields.io/badge/phpstorm-143?style=for-the-badge&logo=phpstorm&logoColor=black&color=black&labelColor=darkorchid)        | `![PhpStorm](https://img.shields.io/badge/phpstorm-143?style=for-the-badge&logo=phpstorm&logoColor=black&color=black&labelColor=darkorchid)`        |
| PyCharm            | ![PyCharm](https://img.shields.io/badge/pycharm-143?style=for-the-badge&logo=pycharm&logoColor=black&color=black&labelColor=green)                | `![PyCharm](https://img.shields.io/badge/pycharm-143?style=for-the-badge&logo=pycharm&logoColor=black&color=black&labelColor=green)`                |
| Replit             | ![Replit](https://img.shields.io/badge/Replit-DD1200?style=for-the-badge&logo=Replit&logoColor=white)                                             | `![Replit](https://img.shields.io/badge/Replit-DD1200?style=for-the-badge&logo=Replit&logoColor=white)`                                             |
| Rider              | ![Rider](https://img.shields.io/badge/Rider-000000.svg?style=for-the-badge&logo=Rider&logoColor=white&color=black&labelColor=crimson)             | `![Rider](https://img.shields.io/badge/Rider-000000.svg?style=for-the-badge&logo=Rider&logoColor=white&color=black&labelColor=crimson)`             |
| RStudio             | ![RStudio](https://img.shields.io/badge/RStudio-4285F4?style=for-the-badge&logo=rstudio&logoColor=white)                                        | `![RStudio](https://img.shields.io/badge/RStudio-4285F4?style=for-the-badge&logo=rstudio&logoColor=white)`|
| Spyder              | ![Spyder](https://img.shields.io/badge/Spyder-838485?style=for-the-badge&logo=spyder%20ide&logoColor=maroon)                                    | `![Spyder](https://img.shields.io/badge/Spyder-838485?style=for-the-badge&logo=spyder%20ide&logoColor=maroon)`       |
| Stackblitz               | ![Stackblitz](https://img.shields.io/badge/Stackblitz-fff?style=for-the-badge&logo=Stackblitz&logoColor=1389FD)                                                     | `![Stackblitz] (https://img.shields.io/badge/Stackblitz-fff?style=for-the-badge&logo=Stackblitz&logoColor=1389FD)`   
| Sublime Text       | ![Sublime Text](https://img.shields.io/badge/sublime_text-%23575757.svg?style=for-the-badge&logo=sublime-text&logoColor=important)                | `![Sublime Text](https://img.shields.io/badge/sublime_text-%23575757.svg?style=for-the-badge&logo=sublime-text&logoColor=important)`                 |
| Vim                | ![Vim](https://img.shields.io/badge/VIM-%2311AB00.svg?style=for-the-badge&logo=vim&logoColor=white)                                               | `![Vim](https://img.shields.io/badge/VIM-%2311AB00.svg?style=for-the-badge&logo=vim&logoColor=white)`                                               |
| Visual Studio Code | ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white) | `![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)` |
| VS Code Insiders   | ![VS Code Insiders](https://img.shields.io/badge/VS%20Code%20Insiders-35b393.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)     | `![VS Code Insiders](https://img.shields.io/badge/VS%20Code%20Insiders-35b393.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)`     |
| Visual Studio      | ![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91.svg?style=for-the-badge&logo=visual-studio&logoColor=white)                  | `![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91.svg?style=for-the-badge&logo=visual-studio&logoColor=white)`                  |
| WebStorm           | ![WebStorm](https://img.shields.io/badge/webstorm-143?style=for-the-badge&logo=webstorm&logoColor=white&color=black)                              | `![WebStorm](https://img.shields.io/badge/webstorm-143?style=for-the-badge&logo=webstorm&logoColor=white&color=black)`                              |
| Xcode              | ![Xcode](https://img.shields.io/badge/Xcode-007ACC?style=for-the-badge&logo=Xcode&logoColor=white)                                                | `![Xcode](https://img.shields.io/badge/Xcode-007ACC?style=for-the-badge&logo=Xcode&logoColor=white)`                                                |
| Zed               | ![Zed](https://img.shields.io/badge/zedindustries-084CCF.svg?style=for-the-badge&logo=zedindustries&logoColor=white)                                                    | `![Zed](https://img.shields.io/badge/zedindustries-084CCF.svg?style=for-the-badge&logo=zedindustries&logoColor=white)`  
| Zend               | ![Zend](https://img.shields.io/badge/Zend-fff?style=for-the-badge&logo=zend&logoColor=0679EA)                                                     | `![Zend](https://img.shields.io/badge/Zend-fff?style=for-the-badge&logo=zend&logoColor=0679EA)`                                                     |                                                  |
                                                 |

[(Back to top)](#table-of-contents)

### 📋 Languages

| Name             | Badge                                                                                                                                        | Markdown                                                                                                                                         |
| -------------    | --------------------------------------------------------------------------------------------------------------------------------             | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| Apache Groovy    | ![Apache Groovy](https://img.shields.io/badge/Apache%20Groovy-4298B8.svg?style=for-the-badge&logo=Apache+Groovy&logoColor=white)             | `![Apache Groovy](https://img.shields.io/badge/Apache%20Groovy-4298B8.svg?style=for-the-badge&logo=Apache+Groovy&logoColor=white)`               |
| Assembly Script  | ![AssemblyScript](https://img.shields.io/badge/assembly%20script-%23000000.svg?style=for-the-badge&logo=assemblyscript&logoColor=white)      | `![AssemblyScript](https://img.shields.io/badge/assembly%20script-%23000000.svg?style=for-the-badge&logo=assemblyscript&logoColor=white)`    |
| C                | ![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)                                                | `![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)`                                                  |
| C#               | ![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white)                                      | `![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white)`                                        |
| C++              | ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)                                      | `![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)`                                        |
| Clojure          | ![Clojure](https://img.shields.io/badge/Clojure-%23Clojure.svg?style=for-the-badge&logo=Clojure&logoColor=Clojure)                           | `![Clojure](https://img.shields.io/badge/Clojure-%23Clojure.svg?style=for-the-badge&logo=Clojure&logoColor=Clojure)`                             |
| Crystal          | ![Crystal](https://img.shields.io/badge/crystal-%23000000.svg?style=for-the-badge&logo=crystal&logoColor=white)                              | `![Crystal](https://img.shields.io/badge/crystal-%23000000.svg?style=for-the-badge&logo=crystal&logoColor=white)`                                |
| CSS3             | ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)                                       | `![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)`                                         |
| Dart             | ![Dart](https://img.shields.io/badge/dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white)                                       | `![Dart](https://img.shields.io/badge/dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white)`                                         |
| Dgraph             | ![Dgraph](https://img.shields.io/badge/dgraph-%23E50695.svg?style=for-the-badge&logo=dgraph&logoColor=white)                                       | `![Dgraph](https://img.shields.io/badge/dgraph-%23E50695.svg?style=for-the-badge&logo=dgraph&logoColor=white)`                                         |
| Elixir           | ![Elixir](https://img.shields.io/badge/elixir-%234B275F.svg?style=for-the-badge&logo=elixir&logoColor=white)                                 | `![Elixir](https://img.shields.io/badge/elixir-%234B275F.svg?style=for-the-badge&logo=elixir&logoColor=white)`                                   |
| Elm              | ![Elm](https://img.shields.io/badge/Elm-60B5CC?style=for-the-badge&logo=elm&logoColor=white)                                                 | `![Elm](https://img.shields.io/badge/Elm-60B5CC?style=for-the-badge&logo=elm&logoColor=white)`                                                   |
| Erlang           | ![Erlang](https://img.shields.io/badge/Erlang-white.svg?style=for-the-badge&logo=erlang&logoColor=a90533)                                    | `![Erlang](https://img.shields.io/badge/Erlang-white.svg?style=for-the-badge&logo=erlang&logoColor=a90533)`                                      |
| Fortran          | ![Fortran](https://img.shields.io/badge/Fortran-%23734F96.svg?style=for-the-badge&logo=fortran&logoColor=white)                              | `![Fortran](https://img.shields.io/badge/Fortran-%23734F96.svg?style=for-the-badge&logo=fortran&logoColor=white)`                                |
| GDScript         | ![GDScript](https://img.shields.io/badge/GDScript-%2374267B.svg?style=for-the-badge&logo=godotengine&logoColor=white)                        | `![GDScript](https://img.shields.io/badge/GDScript-%2374267B.svg?style=for-the-badge&logo=godotengine&logoColor=white)`                          |
| Go/Golang        | ![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)                                             | `![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)`                                               |
| GraphQL          | ![GraphQL](https://img.shields.io/badge/-GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)                                    | `![GraphQL](https://img.shields.io/badge/-GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)`                                      |
| Haskell          | ![Haskell](https://img.shields.io/badge/Haskell-5e5086?style=for-the-badge&logo=haskell&logoColor=white)                                     | `![Haskell](https://img.shields.io/badge/Haskell-5e5086?style=for-the-badge&logo=haskell&logoColor=white)`                                       |
| HTML5            | ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)                                    | `![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)`                                      |
| Java             | ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)                                       | `![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)`                                         |
| JavaScript       | ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)                 | `![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)`                   |
| Julia            | ![Julia](https://img.shields.io/badge/-Julia-9558B2?style=for-the-badge&logo=julia&logoColor=white)                                          | `![Julia](https://img.shields.io/badge/-Julia-9558B2?style=for-the-badge&logo=julia&logoColor=white)`                                            |
| Kotlin           | ![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)                                 | `![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)`                                   |
| LaTeX            | ![LaTeX](https://img.shields.io/badge/latex-%23008080.svg?style=for-the-badge&logo=latex&logoColor=white)                                    | `![LaTeX](https://img.shields.io/badge/latex-%23008080.svg?style=for-the-badge&logo=latex&logoColor=white)`                                      |
| Lua              | ![Lua](https://img.shields.io/badge/lua-%232C2D72.svg?style=for-the-badge&logo=lua&logoColor=white)                                          | `![Lua](https://img.shields.io/badge/lua-%232C2D72.svg?style=for-the-badge&logo=lua&logoColor=white)`                                            |
| Markdown         | ![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)                           | `![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)`                             |
| Nim              | ![Nim](https://img.shields.io/badge/nim-%23FFE953.svg?style=for-the-badge&logo=nim&logoColor=white)                                          | `![Nim](https://img.shields.io/badge/nim-%23FFE953.svg?style=for-the-badge&logo=nim&logoColor=white)`                                            |
| Nix              | ![Nix](https://img.shields.io/badge/NIX-5277C3.svg?style=for-the-badge&logo=NixOS&logoColor=white)                                          | `![Nix](https://img.shields.io/badge/NIX-5277C3.svg?style=for-the-badge&logo=NixOS&logoColor=white)`                                            |
| Objective-C      | ![Objective-C](https://img.shields.io/badge/OBJECTIVE--C-%233A95E3.svg?style=for-the-badge&logo=apple&logoColor=white)                      | `![Objective-C](https://img.shields.io/badge/OBJECTIVE--C-%233A95E3.svg?style=for-the-badge&logo=apple&logoColor=white)`                        |
| OCaml            | ![OCaml](https://img.shields.io/badge/OCaml-%23E98407.svg?style=for-the-badge&logo=ocaml&logoColor=white)                                    | `![OCaml](https://img.shields.io/badge/OCaml-%23E98407.svg?style=for-the-badge&logo=ocaml&logoColor=white)`                            |
| Octave           | ![Octave](https://img.shields.io/badge/OCTAVE-darkblue?style=for-the-badge&logo=octave&logoColor=fcd683)                                     | `![Octave](https://img.shields.io/badge/OCTAVE-darkblue?style=for-the-badge&logo=octave&logoColor=fcd683)`                                       |
| Org Mode         | ![Org Mode](https://img.shields.io/badge/orgmode-%2377AA99.svg?style=for-the-badge&logo=org&logoColor=white)                                 | `![Org Mode](https://img.shields.io/badge/orgmode-%2377AA99.svg?style=for-the-badge&logo=org&logoColor=white)`                                          |
| Perl             | ![Perl](https://img.shields.io/badge/perl-%2339457E.svg?style=for-the-badge&logo=perl&logoColor=white)                                       | `![Perl](https://img.shields.io/badge/perl-%2339457E.svg?style=for-the-badge&logo=perl&logoColor=white)`                                         |
| PHP              | ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)                                          | `![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)`                                            |
| PowerShell       | ![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white)                      | `![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white)`                      |
| Python           | ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)                                       | `![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)`                                         |
| R                | ![R](https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white)                                                | `![R](https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white)`                                                  |
| ReScript              | ![ReScript](https://img.shields.io/badge/rescript-%2314162c?style=for-the-badge&logo=rescript&logoColor=e34c4c)                                       | `![ReScript](https://img.shields.io/badge/rescript-%2314162c?style=for-the-badge&logo=rescript&logoColor=e34c4c)`                                       |
| Ruby             | ![Ruby](https://img.shields.io/badge/ruby-%23CC342D.svg?style=for-the-badge&logo=ruby&logoColor=white)                                       | `![Ruby](https://img.shields.io/badge/ruby-%23CC342D.svg?style=for-the-badge&logo=ruby&logoColor=white)`                                         |
| Rust             | ![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)                                       | `![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)`                                         |
| Scala            | ![Scala](https://img.shields.io/badge/scala-%23DC322F.svg?style=for-the-badge&logo=scala&logoColor=white)                                    | `![Scala](https://img.shields.io/badge/scala-%23DC322F.svg?style=for-the-badge&logo=scala&logoColor=white)`                                      |
| Bash Script     | ![Bash Script](https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)                   | `![Bash Script](https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)`                     |
| Solidity         | ![Solidity](https://img.shields.io/badge/Solidity-%23363636.svg?style=for-the-badge&logo=solidity&logoColor=white)                           | `![Solidity](https://img.shields.io/badge/Solidity-%23363636.svg?style=for-the-badge&logo=solidity&logoColor=white)`                             |
| Swift            | ![Swift](https://img.shields.io/badge/swift-F54A2A?style=for-the-badge&logo=swift&logoColor=white)                                           | `![Swift](https://img.shields.io/badge/swift-F54A2A?style=for-the-badge&logo=swift&logoColor=white)`                                             |
| TypeScript       | ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)                     | `![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)`                       |
| Typst       | ![Typst](https://img.shields.io/badge/typst-239DAD.svg?style=for-the-badge&logo=typst&logoColor=white)                     | `![Typst](https://img.shields.io/badge/typst-239DAD.svg?style=for-the-badge&logo=typst&logoColor=white)`                       |
| Windows Terminal | ![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=for-the-badge&logo=windows-terminal&logoColor=white) | `![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=for-the-badge&logo=windows-terminal&logoColor=white)` |
|YAML              |![YAML](https://img.shields.io/badge/yaml-%23ffffff.svg?style=for-the-badge&logo=yaml&logoColor=151515)|`![YAML](https://img.shields.io/badge/yaml-%23ffffff.svg?style=for-the-badge&logo=yaml&logoColor=151515)`|
| Zig              | ![Zig](https://img.shields.io/badge/Zig-%23F7A41D.svg?style=for-the-badge&logo=zig&logoColor=white)                                          | `![Zig](https://img.shields.io/badge/Zig-%23F7A41D.svg?style=for-the-badge&logo=zig&logoColor=white)`                                            |

[(Back to top)](#table-of-contents)

### 🖥️ ML/DL

| Name         | Badge                                                                                                                           | Markdown                                                                                                                          |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| Keras        | ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)                       | `![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)`                       |
|Matplotlib        | ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)   | `![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)`  
|mlflow        | ![mlflow](https://img.shields.io/badge/mlflow-%23d9ead3.svg?style=for-the-badge&logo=numpy&logoColor=blue)                      | `![mlflow](https://img.shields.io/badge/mlflow-%23d9ead3.svg?style=for-the-badge&logo=numpy&logoColor=blue)`  
| NumPy        | ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)                       | `![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)`                       |
| Pandas       | ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)                    | `![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)`                    |
| Plotly       | ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)                    | `![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)`                    |
| PyTorch      | ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)                 | `![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)`                 |
| scikit-learn | ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) | `![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)` |
| SciPy        | ![Scipy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)                      | `![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)`                      |
| TensorFlow   | ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)        | `![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)`        |

[(Back to top)](#table-of-contents)

### 🎶 Music

| Name          | Badge                                                                                                                      | Markdown                                                                                                                     |
| ------------- | -------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| Apple Music   | ![Apple Music](https://img.shields.io/badge/Apple_Music-9933CC?style=for-the-badge&logo=apple-music&logoColor=white)       | `![Apple Music](https://img.shields.io/badge/Apple_Music-9933CC?style=for-the-badge&logo=apple-music&logoColor=white)`       |
| Audacity      | ![Audacity](https://img.shields.io/badge/Audacity-0000CC?style=for-the-badge&logo=audacity&logoColor=white)                | `![Audacity](https://img.shields.io/badge/Audacity-0000CC?style=for-the-badge&logo=audacity&logoColor=white)`                |
| Deezer        | ![Deezer](https://img.shields.io/badge/Deezer-FEAA2D?style=for-the-badge&logo=deezer&logoColor=white)                      | `![Deezer](https://img.shields.io/badge/Deezer-FEAA2D?style=for-the-badge&logo=deezer&logoColor=white)`       
| Last.fm        | ![Last.fm](https://img.shields.io/badge/last.fm-D51007?style=for-the-badge&logo=last.fm&logoColor=white)                      | `![Last.fm](https://img.shields.io/badge/last.fm-D51007?style=for-the-badge&logo=last.fm&logoColor=white)`                |
| SoundCloud   | ![SoundCloud](https://img.shields.io/badge/soundcloud-FF5500?style=for-the-badge&logo=soundcloud&logoColor=white)      | `![SoundCloud](https://img.shields.io/badge/soundcloud-FF5500?style=for-the-badge&logo=soundcloud&logoColor=white)`      |
| Spotify       | ![Spotify](https://img.shields.io/badge/Spotify-1ED760?style=for-the-badge&logo=spotify&logoColor=white)                   | `![Spotify](https://img.shields.io/badge/Spotify-1ED760?style=for-the-badge&logo=spotify&logoColor=white)`                   |
| Shazam        | ![Shazam](https://img.shields.io/badge/shazam-1476FE?style=for-the-badge&logo=shazam&logoColor=white)                      | `![Shazam](https://img.shields.io/badge/shazam-1476FE?style=for-the-badge&logo=shazam&logoColor=white)`                      |
| Tidal         | ![Tidal](https://img.shields.io/badge/tidal-00FFFF?style=for-the-badge&logo=tidal&logoColor=black)                         | `![Tidal](https://img.shields.io/badge/tidal-00FFFF?style=for-the-badge&logo=tidal&logoColor=black)`                         |
| YouTube Music | ![YouTube Music](https://img.shields.io/badge/YouTube_Music-FF0000?style=for-the-badge&logo=youtube-music&logoColor=white)                         | `![YouTube Music](https://img.shields.io/badge/YouTube_Music-FF0000?style=for-the-badge&logo=youtube-music&logoColor=white)`                         |
| Musixmatch | ![Musixmatch](https://img.shields.io/badge/Musixmatch-%23FF5353.svg?style=for-the-badge&logo=Musixmatch&logoColor=white) | `![Musixmatch](https://img.shields.io/badge/Musixmatch-%23FF5353.svg?style=for-the-badge&logo=Musixmatch&logoColor=white)`                         |


[(Back to top)](#table-of-contents)

### 🏢 Office

| Name                 | Badge                                                                                                                                            | Markdown                                                                                                                                           |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| LibreOffice          | ![LibreOffice](https://img.shields.io/badge/LibreOffice-%2318A303?style=for-the-badge&logo=LibreOffice&logoColor=white)                          | `![LibreOffice](https://img.shields.io/badge/LibreOffice-%2318A303?style=for-the-badge&logo=LibreOffice&logoColor=white)`                          |
| Microsoft            | ![Microsoft](https://img.shields.io/badge/Microsoft-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)                                   | `![Microsoft](https://img.shields.io/badge/Microsoft-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)`                                   |
| Microsoft Access     | ![Microsoft Access](https://img.shields.io/badge/Microsoft_Access-A4373A?style=for-the-badge&logo=microsoft-access&logoColor=white)              | `![Microsoft Access](https://img.shields.io/badge/Microsoft_Access-A4373A?style=for-the-badge&logo=microsoft-access&logoColor=white)`              |
| Microsoft Excel      | ![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)                 | `![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)`                 |
| Microsoft Office     | ![Microsoft Office](https://img.shields.io/badge/Microsoft_Office-D83B01?style=for-the-badge&logo=microsoft-office&logoColor=white)              | `![Microsoft Office](https://img.shields.io/badge/Microsoft_Office-D83B01?style=for-the-badge&logo=microsoft-office&logoColor=white)`              |
| Microsoft PowerPoint | ![Microsoft PowerPoint](https://img.shields.io/badge/Microsoft_PowerPoint-B7472A?style=for-the-badge&logo=microsoft-powerpoint&logoColor=white)  | `![Microsoft PowerPoint](https://img.shields.io/badge/Microsoft_PowerPoint-B7472A?style=for-the-badge&logo=microsoft-powerpoint&logoColor=white)`  |
| Microsoft SharePoint | ![Microsoft SharePoint ](https://img.shields.io/badge/Microsoft_SharePoint-0078D4?style=for-the-badge&logo=microsoft-sharepoint&logoColor=white) | `![Microsoft SharePoint ](https://img.shields.io/badge/Microsoft_SharePoint-0078D4?style=for-the-badge&logo=microsoft-sharepoint&logoColor=white)` |
| Microsoft Visio      | ![Microsoft Visio ](https://img.shields.io/badge/Microsoft_Visio-3955A3?style=for-the-badge&logo=microsoft-visio&logoColor=white)                | `![Microsoft Visio ](https://img.shields.io/badge/Microsoft_Visio-3955A3?style=for-the-badge&logo=microsoft-visio&logoColor=white)`                |
| Microsoft Word       | ![Microsoft Word](https://img.shields.io/badge/Microsoft_Word-2B579A?style=for-the-badge&logo=microsoft-word&logoColor=white)                    | `![Microsoft Word](https://img.shields.io/badge/Microsoft_Word-2B579A?style=for-the-badge&logo=microsoft-word&logoColor=white)`                    |

[(Back to top)](#table-of-contents)

### 🎛️ Operating System

| Name          | Badge                                                                                                                          | Markdown                                                                                                                         |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------- |
| Alpine Linux  | ![Alpine Linux](https://img.shields.io/badge/Alpine_Linux-%230D597F.svg?style=for-the-badge&logo=alpine-linux&logoColor=white) | `![Alpine Linux](https://img.shields.io/badge/Alpine_Linux-%230D597F.svg?style=for-the-badge&logo=alpine-linux&logoColor=white)` |
| Android       | ![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)                       | `![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)`                       |
| Arch          | ![Arch](https://img.shields.io/badge/Arch%20Linux-1793D1?logo=arch-linux&logoColor=fff&style=for-the-badge)                    | `![Arch](https://img.shields.io/badge/Arch%20Linux-1793D1?logo=arch-linux&logoColor=fff&style=for-the-badge)`                    |
| Cent OS       | ![Cent OS](https://img.shields.io/badge/cent%20os-002260?style=for-the-badge&logo=centos&logoColor=F0F0F0)                     | `![Cent OS](https://img.shields.io/badge/cent%20os-002260?style=for-the-badge&logo=centos&logoColor=F0F0F0)`                     |
| Chrome OS     | ![Chrome OS](https://img.shields.io/badge/chrome%20os-3d89fc?style=for-the-badge&logo=google%20chrome&logoColor=white)         | `![Chrome OS](https://img.shields.io/badge/chrome%20os-3d89fc?style=for-the-badge&logo=google%20chrome&logoColor=white)`         |
| Debian        | ![Debian](https://img.shields.io/badge/Debian-D70A53?style=for-the-badge&logo=debian&logoColor=white)                          | `![Debian](https://img.shields.io/badge/Debian-D70A53?style=for-the-badge&logo=debian&logoColor=white)`                          |
| Deepin        | ![Deepin](https://img.shields.io/badge/Deepin-007CFF?style=for-the-badge&logo=deepin&logoColor=white)                          | `![Deepin](https://img.shields.io/badge/Deepin-007CFF?style=for-the-badge&logo=deepin&logoColor=white)`                          |
| Elementary OS | ![Elementary OS](https://img.shields.io/badge/-elementary%20OS-black?style=for-the-badge&logo=elementary&logoColor=white)      | `![Elementary OS](https://img.shields.io/badge/-elementary%20OS-black?style=for-the-badge&logo=elementary&logoColor=white)`      |
| Fedora        | ![Fedora](https://img.shields.io/badge/Fedora-294172?style=for-the-badge&logo=fedora&logoColor=white)                          | `![Fedora](https://img.shields.io/badge/Fedora-294172?style=for-the-badge&logo=fedora&logoColor=white)`                          |
| FreeBSD       | ![FreeBSD](https://img.shields.io/badge/-FreeBSD-%23870000?style=for-the-badge&logo=freebsd&logoColor=white)                   | `![FreeBSD](https://img.shields.io/badge/-FreeBSD-%23870000?style=for-the-badge&logo=freebsd&logoColor=white)`                   |
| Gentoo        | ![Gentoo](https://img.shields.io/badge/Gentoo-54487A?style=for-the-badge&logo=gentoo&logoColor=white)                          | `![Gentoo](https://img.shields.io/badge/Gentoo-54487A?style=for-the-badge&logo=gentoo&logoColor=white)`                   |
| iOS           | ![iOS](https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=ios&logoColor=white)                                   | `![iOS](https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=ios&logoColor=white)`                                   |
| Kali          | ![Kali](https://img.shields.io/badge/Kali-268BEE?style=for-the-badge&logo=kalilinux&logoColor=white)                           | `![Kali](https://img.shields.io/badge/Kali-268BEE?style=for-the-badge&logo=kalilinux&logoColor=white)`                           |
| Kubuntu       | ![Kubuntu](https://img.shields.io/badge/-KUbuntu-%230079C1?style=for-the-badge&logo=kubuntu&logoColor=white)                   | `![Kubuntu](https://img.shields.io/badge/-KUbuntu-%230079C1?style=for-the-badge&logo=kubuntu&logoColor=white)`                   |
| Linux         | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)                             | `![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)`                             |
| Linux Mint    | ![Linux Mint](https://img.shields.io/badge/Linux%20Mint-87CF3E?style=for-the-badge&logo=Linux%20Mint&logoColor=white)          | `![Linux Mint](https://img.shields.io/badge/Linux%20Mint-87CF3E?style=for-the-badge&logo=Linux%20Mint&logoColor=white)`          |
| Lubuntu       | ![Lubuntu](https://img.shields.io/badge/-Lubuntu-%230065C2?style=for-the-badge&logo=lubuntu&logoColor=white)                   | `![Lubuntu](https://img.shields.io/badge/-Lubuntu-%230065C2?style=for-the-badge&logo=lubuntu&logoColor=white)`                   |
| Lineageos     | ![Lineageos](https://img.shields.io/badge/lineageos-167C80?style=for-the-badge&logo=lineageos&logoColor=white)                 | `![Lineageos](https://img.shields.io/badge/lineageos-167C80?style=for-the-badge&logo=lineageos&logoColor=white)`                  |
| Manjaro       | ![Manjaro](https://img.shields.io/badge/Manjaro-35BF5C?style=for-the-badge&logo=Manjaro&logoColor=white)                       | `![Manjaro](https://img.shields.io/badge/Manjaro-35BF5C?style=for-the-badge&logo=Manjaro&logoColor=white)`                       |
| MX Linux      | ![MX Linux](https://img.shields.io/badge/-MX%20Linux-%23000000?style=for-the-badge&logo=MXlinux&logoColor=white)               | `![MX Linux](https://img.shields.io/badge/-MX%20Linux-%23000000?style=for-the-badge&logo=MXlinux&logoColor=white)`               |
| macOS         | ![macOS](https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=macos&logoColor=F0F0F0)                        | `![macOS](https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=macos&logoColor=F0F0F0)`                        |
| NixOS         | ![NixOS](https://img.shields.io/badge/NIXOS-5277C3.svg?style=for-the-badge&logo=NixOS&logoColor=white)                        | `![NixOS](https://img.shields.io/badge/NIXOS-5277C3.svg?style=for-the-badge&logo=NixOS&logoColor=white)`                        |
| OpenWRT       | ![OpenWRT](https://img.shields.io/badge/OpenWrt-00B5E2?style=for-the-badge&logo=OpenWrt&logoColor=white)                       | `![Openwrt](https://img.shields.io/badge/OpenWRT-00B5E2?style=for-the-badge&logo=OpenWrt&logoColor=white)`                       |
| OpenBSD       | ![OpenBSD](https://img.shields.io/badge/-OpenBSD-%23FCC771?style=for-the-badge&logo=openbsd&logoColor=black)                   | `![OpenBSD](https://img.shields.io/badge/-OpenBSD-%23FCC771?style=for-the-badge&logo=openbsd&logoColor=black)`                   |
| openSUSE      | ![openSUSE](https://img.shields.io/badge/openSUSE-%2364B345?style=for-the-badge&logo=openSUSE&logoColor=white)                 | `![openSUSE](https://img.shields.io/badge/openSUSE-%2364B345?style=for-the-badge&logo=openSUSE&logoColor=white)`                 |
| Pop!\_OS       | ![Pop!\_OS](https://img.shields.io/badge/Pop!_OS-48B9C7?style=for-the-badge&logo=Pop!_OS&logoColor=white)                       | `![Pop!\_OS](https://img.shields.io/badge/Pop!_OS-48B9C7?style=for-the-badge&logo=Pop!_OS&logoColor=white)`                       |
| Red Hat       | ![Red Hat](https://img.shields.io/badge/Red%20Hat-EE0000?style=for-the-badge&logo=redhat&logoColor=white)                      | `![Red Hat](https://img.shields.io/badge/Red%20Hat-EE0000?style=for-the-badge&logo=redhat&logoColor=white)`                      |
| Rocky Linux   | ![Rocky Linux](https://img.shields.io/badge/-Rocky%20Linux-%2310B981?style=for-the-badge&logo=rockylinux&logoColor=white)      | `![Rocky Linux](https://img.shields.io/badge/-Rocky%20Linux-%2310B981?style=for-the-badge&logo=rockylinux&logoColor=white)`      |
| Solus          | ![Solus](https://img.shields.io/badge/Solus-%23f2f2f2.svg?style=for-the-badge&logo=solus&logoColor=5294E2)                    | `![Solus](https://img.shields.io/badge/Solus-%23f2f2f2.svg?style=for-the-badge&logo=solus&logoColor=5294E2)` 
| SUSE          | ![SUSE](https://img.shields.io/badge/SUSE-0C322C?style=for-the-badge&logo=SUSE&logoColor=white)                                | `![Suse](https://img.shields.io/badge/SUSE-0C322C?style=for-the-badge&logo=SUSE&logoColor=white)`                                |
| Slackware     | ![Slackware](https://img.shields.io/badge/-Slackware-%231357BD?style=for-the-badge&logo=slackware&logoColor=white)             | `![Slackware](https://img.shields.io/badge/-Slackware-%231357BD?style=for-the-badge&logo=slackware&logoColor=white)`             |
| Tails         | ![Tails](https://img.shields.io/badge/Tails%20-56347C?&style=for-the-badge&logo=tails&logoColor=white)                         | `![Tails](https://img.shields.io/badge/Tails%20-56347C?&style=for-the-badge&logo=tails&logoColor=white)`                         |
| Ubuntu        | ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)                          | `![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)`                          |
| Ubuntu MATE   | ![Ubuntu MATE](https://img.shields.io/badge/Ubuntu%20MATE-84A454.svg?style=for-the-badge&logo=Ubuntu-MATE&logoColor=white)     | `![Ubuntu MATE](https://img.shields.io/badge/Ubuntu%20MATE-84A454.svg?style=for-the-badge&logo=Ubuntu-MATE&logoColor=white)`     |
| Unraid        | ![Unraid](https://img.shields.io/badge/unraid-%23F15A2C.svg?style=for-the-badge&logo=unraid&logoColor=white)                   | `![Unraid](https://img.shields.io/badge/unraid-%23F15A2C.svg?style=for-the-badge&logo=unraid&logoColor=white)`                   |
| Wear OS       | ![Wear OS](https://img.shields.io/badge/-Wear%20OS-4285F4?style=for-the-badge&logo=wear-os&logoColor=white)                    | `![Wear OS](https://img.shields.io/badge/-Wear%20OS-4285F4?style=for-the-badge&logo=wear-os&logoColor=white)`                    |
| Windows       | ![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)                       | `![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)`                       |
| Windows 11    | ![Windows 11](https://img.shields.io/badge/Windows%2011-%230079d5.svg?style=for-the-badge&logo=Windows%2011&logoColor=white)                       | `![Windows 11](https://img.shields.io/badge/Windows%2011-%230079d5.svg?style=for-the-badge&logo=Windows%2011&logoColor=white)`                       |
| Windows 95    | ![Windows 95](https://img.shields.io/badge/Windows%2095-008484?style=for-the-badge&logo=windows95&logoColor=white)             | `![Windows 95](https://img.shields.io/badge/Windows%2095-008484?style=for-the-badge&logo=windows95&logoColor=white)`             |
| Windows XP    | ![Windows XP](https://img.shields.io/badge/Windows%20xp-003399?style=for-the-badge&logo=windowsxp&logoColor=white)             | `![Windows XP](https://img.shields.io/badge/Windows%20xp-003399?style=for-the-badge&logo=windowsxp&logoColor=white)`             |
| Zorin OS      | ![Zorin OS](https://img.shields.io/badge/-Zorin%20OS-%2310AAEB?style=for-the-badge&logo=zorin&logoColor=white)                 | `![Zorin OS](https://img.shields.io/badge/-Zorin%20OS-%2310AAEB?style=for-the-badge&logo=zorin&logoColor=white)`                 |

[(Back to top)](#table-of-contents)

### 🎋 ORM

| Name      | Badge                                                                                                          | Markdown                                                                                                         |
| --------- | -------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| Hibernate    | ![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white)          | `![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white)`          |
| Prisma    | ![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)          | `![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)`          |
| Sequelize | ![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=Sequelize&logoColor=white) | `![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=Sequelize&logoColor=white)` |
| TypeORM  | ![TypeORM](https://img.shields.io/badge/TypeORM-FE0803.svg?style=for-the-badge&logo=typeorm&logoColor=white)          | `![TypeORM](https://img.shields.io/badge/TypeORM-FE0803.svg?style=for-the-badge&logo=typeorm&logoColor=white)`          |
| Quill     | ![Quill](https://img.shields.io/badge/Quill-52B0E7?style=for-the-badge&logo=apache&logoColor=white)            | `![Quill](https://img.shields.io/badge/Quill-52B0E7?style=for-the-badge&logo=apache&logoColor=white)`            |

[(Back to top)](#table-of-contents)

### 🥅 Other

| Name           | Badge                                                                                                                                  | Markdown                                                                                                                                 |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------| ---------------------------------------------------------------------------------------------------------------------------------------- |
| Accessibility  | ![Accessibility](https://img.shields.io/badge/Accessibility-%230170EA.svg?style=for-the-badge&logo=Accessibility&logoColor=white)     | `![Accessibility](https://img.shields.io/badge/Accessibility-%230170EA.svg?style=for-the-badge&logo=Accessibility&logoColor=white)`   |
| Airbnb         | ![Airbnb](https://img.shields.io/badge/Airbnb-%23ff5a5f.svg?style=for-the-badge&logo=Airbnb&logoColor=white)                            | `![Airbnb](https://img.shields.io/badge/Airbnb-%23ff5a5f.svg?style=for-the-badge&logo=Airbnb&logoColor=white)`                           |
| Alfred         | ![Alfred](https://img.shields.io/badge/alfred-%235C1F87.svg?style=for-the-badge&logo=alfred)                                           | `![Alfred](https://img.shields.io/badge/alfred-%235C1F87.svg?style=for-the-badge&logo=alfred)`                                           |
| Ansible        | ![Ansible](https://img.shields.io/badge/ansible-%231A1918.svg?style=for-the-badge&logo=ansible&logoColor=white)                        | `![Ansible](https://img.shields.io/badge/ansible-%231A1918.svg?style=for-the-badge&logo=ansible&logoColor=white)`                        |
| Aqua Sec       | ![AquaSec](https://img.shields.io/badge/aqua-%231904DA.svg?style=for-the-badge&logo=aqua&logoColor=#0018A8)                            | `![AquaSec](https://img.shields.io/badge/aqua-%231904DA.svg?style=for-the-badge&logo=aqua&logoColor=#0018A8)`                            |
| Arduino        | ![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white)                              | `![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white)`                              |
| Babel          | ![Babel](https://img.shields.io/badge/Babel-F9DC3e?style=for-the-badge&logo=babel&logoColor=black)                                     | `![Babel](https://img.shields.io/badge/Babel-F9DC3e?style=for-the-badge&logo=babel&logoColor=black)`                                     |
| Bitwarden      | ![Bitwarden](https://img.shields.io/badge/bitwarden-%23175DDC.svg?style=for-the-badge&logo=bitwarden&logoColor=white)                  | `![Bitwarden](https://img.shields.io/badge/bitwarden-%23175DDC.svg?style=for-the-badge&logo=bitwarden&logoColor=white)`                  |
| Cisco         | ![Cisco](https://img.shields.io/badge/cisco-%23049fd9.svg?style=for-the-badge&logo=cisco&logoColor=black)                              | `![Cisco](https://img.shields.io/badge/cisco-%23049fd9.svg?style=for-the-badge&logo=cisco&logoColor=black)`                              |
| CMake          | ![CMake](https://img.shields.io/badge/CMake-%23008FBA.svg?style=for-the-badge&logo=cmake&logoColor=white)                              | `![CMake](https://img.shields.io/badge/CMake-%23008FBA.svg?style=for-the-badge&logo=cmake&logoColor=white)`                              |
| CodeCov        | ![CodeCov](https://img.shields.io/badge/codecov-%23ff0077.svg?style=for-the-badge&logo=codecov&logoColor=white)                        | `![CodeCov](https://img.shields.io/badge/codecov-%23ff0077.svg?style=for-the-badge&logo=codecov&logoColor=white)`                        |
| Confluence     | ![Confluence](https://img.shields.io/badge/confluence-%23172BF4.svg?style=for-the-badge&logo=confluence&logoColor=white)               | `![Confluence](https://img.shields.io/badge/confluence-%23172BF4.svg?style=for-the-badge&logo=confluence&logoColor=white)`               |
| Crowdin     | ![Crowdin](https://img.shields.io/badge/Crowdin-2E3340.svg?style=for-the-badge&logo=Crowdin&logoColor=white)               | `![Crowdin](https://img.shields.io/badge/Crowdin-2E3340.svg?style=for-the-badge&logo=Crowdin&logoColor=white)`               |
| Docker         | ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)                           | `![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)`                           |
| ESLint         | ![ESLint](https://img.shields.io/badge/ESLint-4B3263?style=for-the-badge&logo=eslint&logoColor=white)                                  | `![ESLint](https://img.shields.io/badge/ESLint-4B3263?style=for-the-badge&logo=eslint&logoColor=white)`                                  |
| ElasticSearch  | ![ElasticSearch](https://img.shields.io/badge/-ElasticSearch-005571?style=for-the-badge&logo=elasticsearch)                            | `![ElasticSearch](https://img.shields.io/badge/-ElasticSearch-005571?style=for-the-badge&logo=elasticsearch)`                            |
| Espressif      | ![Espressif](https://img.shields.io/badge/espressif-E7352C.svg?style=for-the-badge&logo=espressif&logoColor=white)                                                                                                                                          |`![Espressif](https://img.shields.io/badge/espressif-E7352C.svg?style=for-the-badge&logo=espressif&logoColor=white)`                     |
| FFmpeg         | ![FFmpeg](https://shields.io/badge/FFmpeg-%23171717.svg?logo=ffmpeg&style=for-the-badge&labelColor=171717&logoColor=5cb85c)            | `![FFmpeg](https://shields.io/badge/FFmpeg-%23171717.svg?logo=ffmpeg&style=for-the-badge&labelColor=171717&logoColor=5cb85c)`
| Google TalkBack| ![Google TalkBack](https://img.shields.io/badge/Google%20TalkBack-%236636B4.svg?style=for-the-badge&logo=GoogleTalkBack&logoColor=white) | `![Google TalkBack](https://img.shields.io/badge/Google%20TalkBack-%236636B4.svg?style=for-the-badge&logo=GoogleTalkBack&logoColor=white)`   |
| Gradle         | ![Gradle](https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white)                              | `![Gradle](https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white)`                              |
| Grafana        | ![Grafana](https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)                        | `![Grafana](https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)`                        |
| Home Assistant | ![Home Assistant](https://img.shields.io/badge/home%20assistant-%2341BDF5.svg?style=for-the-badge&logo=home-assistant&logoColor=white) | `![Home Assistant](https://img.shields.io/badge/home%20assistant-%2341BDF5.svg?style=for-the-badge&logo=home-assistant&logoColor=white)` |
| Homebridge     | ![Homebridge](https://img.shields.io/badge/homebridge-%23491F59.svg?style=for-the-badge&logo=homebridge&logoColor=white)               | `![Homebridge](https://img.shields.io/badge/homebridge-%23491F59.svg?style=for-the-badge&logo=homebridge&logoColor=white)`               |
| JAWS           | ![JAWS](https://img.shields.io/badge/JAWS-%231962AA.svg?style=for-the-badge&logo=JAWS&logoColor=white)                                 | `![JAWS](https://img.shields.io/badge/JAWS-%231962AA.svg?style=for-the-badge&logo=JAWS&logoColor=white)`                |
| Jellyfin       | ![Jellyfin](https://img.shields.io/badge/jellyfin-%23000B25.svg?style=for-the-badge&logo=Jellyfin&logoColor=00A4DC)                    | `![Jellyfin](https://img.shields.io/badge/jellyfin-%23000B25.svg?style=for-the-badge&logo=Jellyfin&logoColor=00A4DC)`                    |
| Jira           | ![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white)                                 | `![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white)`                                 |
| Kubernetes     | ![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)               | `![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)`               |
| Meta           | ![Meta](https://img.shields.io/badge/Meta-%230467DF.svg?style=for-the-badge&logo=Meta&logoColor=white)                                 | `![Meta](https://img.shields.io/badge/Meta-%230467DF.svg?style=for-the-badge&logo=Meta&logoColor=white)`                                        |
| Mosquitto      | ![Mosquitto](https://img.shields.io/badge/mosquitto-%233C5280.svg?style=for-the-badge&logo=eclipsemosquitto&logoColor=white)           | `![Mosquitto](https://img.shields.io/badge/mosquitto-%233C5280.svg?style=for-the-badge&logo=eclipsemosquitto&logoColor=white)`           |
| Narrator       | ![Narrator](https://img.shields.io/badge/Narrator-%230771D0.svg?style=for-the-badge&logo=Narrator&logoColor=white)                     | `![Narrator](https://img.shields.io/badge/Narrator-%230771D0.svg?style=for-the-badge&logo=Narrator&logoColor=white)`   |
| Notion         | ![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)                           | `![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)`                           |
| NVDA           | ![NVDA](https://img.shields.io/badge/NVDA-%23630093.svg?style=for-the-badge&logo=NVDA&logoColor=white)                                 | `![NVDA](https://img.shields.io/badge/NVDA-%23630093.svg?style=for-the-badge&logo=NVDA&logoColor=white)`               |
| OpenAPI Specification         | ![OpenAPI Specification](https://img.shields.io/badge/openapiinitiative-%23000000.svg?style=for-the-badge&logo=openapiinitiative&logoColor=white)                           | `![openapi initiative](https://img.shields.io/badge/openapiinitiative-%23000000.svg?style=for-the-badge&logo=openapiinitiative&logoColor=white)`                           |
| OpenSea        | ![OpenSea](https://img.shields.io/badge/OpenSea-%232081E2.svg?style=for-the-badge&logo=opensea&logoColor=white)                        | `![OpenSea](https://img.shields.io/badge/OpenSea-%232081E2.svg?style=for-the-badge&logo=opensea&logoColor=white)`                        |
| OpenTelemetry  | ![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-FFFFFF?&style=for-the-badge&logo=opentelemetry&logoColor=black)           | `![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-FFFFFF?&style=for-the-badge&logo=opentelemetry&logoColor=black)`        |
| Packer         | ![Packer](https://img.shields.io/badge/packer-%23E7EEF0.svg?style=for-the-badge&logo=packer&logoColor=%2302A8EF)                       | `![Packer](https://img.shields.io/badge/packer-%23E7EEF0.svg?style=for-the-badge&logo=packer&logoColor=%2302A8EF)`                       |
| Pi-Hole        | ![Pi-Hole](https://img.shields.io/badge/pihole-%2396060C.svg?style=for-the-badge&logo=pi-hole&logoColor=white)                         | `![Pi-Hole](https://img.shields.io/badge/pihole-%2396060C.svg?style=for-the-badge&logo=pi-hole&logoColor=white)`                         |
| PlatformIO     | ![PlatformIO](https://img.shields.io/badge/PlatformIO-%23222.svg?style=for-the-badge&logo=platformio&logoColor=%23f5822a)              | `![PlatformIO](https://img.shields.io/badge/PlatformIO-%23222.svg?style=for-the-badge&logo=platformio&logoColor=%23f5822a)`               |
| Plex           | ![Plex](https://img.shields.io/badge/plex-%23E5A00D.svg?style=for-the-badge&logo=plex&logoColor=white)                                 | `![Plex](https://img.shields.io/badge/plex-%23E5A00D.svg?style=for-the-badge&logo=plex&logoColor=white)`                                 |
| Portfolio      | ![Portfolio](https://img.shields.io/badge/Portfolio-%23000000.svg?style=for-the-badge&logo=firefox&logoColor=#FF7139)                  | `![Portfolio](https://img.shields.io/badge/Portfolio-%23000000.svg?style=for-the-badge&logo=firefox&logoColor=#FF7139)`                  |
| Postman        | ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)                               | `![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)`                               |
| Power BI        | ![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)                               | `![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)`                               |
| Prettier        | ![Prettier](https://img.shields.io/badge/prettier-%23F7B93E.svg?style=for-the-badge&logo=prettier&logoColor=black)                               | `![Prettier](https://img.shields.io/badge/prettier-%23F7B93E.svg?style=for-the-badge&logo=prettier&logoColor=black)`                               |
| Prezi          | ![Prezi](https://img.shields.io/badge/Prezi-%23000000.svg?style=for-the-badge&logo=Prezi&logoColor=white)                              | `![Prezi](https://img.shields.io/badge/Prezi-%23000000.svg?style=for-the-badge&logo=Prezi&logoColor=white)`                              |
| Prometheus     | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white)                      | `![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white)`                      |
|PyPi                | ![PyPi](https://img.shields.io/badge/pypi-%23ececec.svg?style=for-the-badge&logo=pypi&logoColor=1f73b7)|`![PyPi](https://img.shields.io/badge/pypi-%23ececec.svg?style=for-the-badge&logo=pypi&logoColor=1f73b7)`|
| Rancher        | ![Rancher](https://img.shields.io/badge/rancher-%230075A8.svg?style=for-the-badge&logo=rancher&logoColor=white)                        | `![Rancher](https://img.shields.io/badge/rancher-%230075A8.svg?style=for-the-badge&logo=rancher&logoColor=white)`                        |
| Raspberry Pi   | ![Raspberry Pi](https://img.shields.io/badge/-Raspberry_Pi-C51A4A?style=for-the-badge&logo=Raspberry-Pi)                                | `![Raspberry Pi](https://img.shields.io/badge/-Raspberry_Pi-C51A4A?style=for-the-badge&logo=Raspberry-Pi)`                                |
| SonarLint         | ![SonarLint](https://img.shields.io/badge/SonarLint-CB2029?style=for-the-badge&logo=SONARLINT&logoColor=white)                      | `![SonarLint](https://img.shields.io/badge/SonarLint-CB2029?style=for-the-badge&logo=SONARLINT&logoColor=white)`                           |
| SonarQube         | ![SonarQube](https://img.shields.io/badge/SonarQube-black?style=for-the-badge&logo=sonarqube&logoColor=4E9BCD)                      | `![SonarQube](https://img.shields.io/badge/SonarQube-black?style=for-the-badge&logo=sonarqube&logoColor=4E9BCD)`                           |
| Splunk         | ![Splunk](https://img.shields.io/badge/splunk-%23000000.svg?style=for-the-badge&logo=splunk&logoColor=white)                           | `![Splunk](https://img.shields.io/badge/splunk-%23000000.svg?style=for-the-badge&logo=splunk&logoColor=white)`                           |
| Swagger        | ![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white)                          | `![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white)`                          |
| Tampermonkey   | ![Tampermonkey](https://img.shields.io/badge/tampermonkey-%2300485B.svg?style=for-the-badge&logo=tampermonkey&logoColor=white)         | `![Tampermonkey](https://img.shields.io/badge/tampermonkey-%2300485B.svg?style=for-the-badge&logo=tampermonkey&logoColor=white)`         |
| TOR            | ![TOR](https://img.shields.io/badge/tor-%237E4798.svg?style=for-the-badge&logo=tor-project&logoColor=white)                            | `![TOR](https://img.shields.io/badge/tor-%237E4798.svg?style=for-the-badge&logo=tor-project&logoColor=white)`                            |
| Terraform      | ![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)                  | `![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)`                  |
| Trello         | ![Trello](https://img.shields.io/badge/Trello-%23026AA7.svg?style=for-the-badge&logo=Trello&logoColor=white)                           | `![Trello](https://img.shields.io/badge/Trello-%23026AA7.svg?style=for-the-badge&logo=Trello&logoColor=white)`                           |
| Twilio         | ![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=for-the-badge&logo=Twilio&logoColor=white) | `![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=for-the-badge&logo=Twilio logoColor=white)`                           |
| Uber           | ![Uber](https://img.shields.io/badge/Uber-%23000000.svg?style=for-the-badge&logo=Uber&logoColor=white)                                 | `![Uber](https://img.shields.io/badge/Uber-%23000000.svg?style=for-the-badge&logo=Uber&logoColor=white)`                                 |
| Ubiquiti       | ![Ubiquiti](https://img.shields.io/badge/ubiquiti-%230559C9.svg?style=for-the-badge&logo=ubiquiti&logoColor=white)                     | `![Ubiquiti](https://img.shields.io/badge/ubiquiti-%230559C9.svg?style=for-the-badge&logo=ubiquiti&logoColor=white)`                     |
| Vagrant        | ![Vagrant](https://img.shields.io/badge/vagrant-%231563FF.svg?style=for-the-badge&logo=vagrant&logoColor=white)                        | `![Vagrant](https://img.shields.io/badge/vagrant-%231563FF.svg?style=for-the-badge&logo=vagrant&logoColor=white)`                        |
| VoiceOver      | ![VoiceOver](https://img.shields.io/badge/VoiceOver-%23484848.svg?style=for-the-badge&logo=VoiceOver&logoColor=white)                  | `![VoiceOver](https://img.shields.io/badge/VoiceOver-%23484848.svg?style=for-the-badge&logo=VoiceOver&logoColor=white)`                  |
| WCAG           | ![WCAG](https://img.shields.io/badge/WCAG-%23015A69.svg?style=for-the-badge&logo=WCAG&logoColor=white)                                 | `![WCAG](https://img.shields.io/badge/WCAG-%23015A69.svg?style=for-the-badge&logo=WCAG&logoColor=white)`                                 |
| Wireguard      | ![Wireguard](https://img.shields.io/badge/wireguard-%2388171A.svg?style=for-the-badge&logo=wireguard&logoColor=white)                  | `![Wireguard](https://img.shields.io/badge/wireguard-%2388171A.svg?style=for-the-badge&logo=wireguard&logoColor=white)`                  |
| XFCE           | ![XFCE](https://img.shields.io/badge/XFCE-%232284F2.svg?style=for-the-badge&logo=xfce&logoColor=white)                                 | `![XFCE](https://img.shields.io/badge/XFCE-%232284F2.svg?style=for-the-badge&logo=xfce&logoColor=white)`                                 |
| Zigbee         | ![Zigbee](https://img.shields.io/badge/zigbee-%23EB0443.svg?style=for-the-badge&logo=zigbee&logoColor=white)                           | `![Zigbee](https://img.shields.io/badge/zigbee-%23EB0443.svg?style=for-the-badge&logo=zigbee&logoColor=white)`                           |

[(Back to top)](#table-of-contents)

### 🖥️ Quantum Programming Frameworks and Libraries

| Name   | Badge                                                                                                        | Markdown                                                                                                       |
| ------ | ------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------- |
| Qiskit | ![Qiskit](https://img.shields.io/badge/Qiskit-%236929C4.svg?style=for-the-badge&logo=Qiskit&logoColor=white) | `![Qiskit](https://img.shields.io/badge/Qiskit-%236929C4.svg?style=for-the-badge&logo=Qiskit&logoColor=white)` |

[(Back to top)](#table-of-contents)

### 🔍 Search Engines

| Name       | Badge                                                                                                                   | Markdown                                                                                                                  |
| ---------- | ----------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| Baidu      | ![Baidu](https://img.shields.io/badge/Baidu-2932E1?style=for-the-badge&logo=Baidu&logoColor=white)                      | `![Baidu](https://img.shields.io/badge/Baidu-2932E1?style=for-the-badge&logo=Baidu&logoColor=white)`                      |
| Bing       | ![Bing](https://img.shields.io/badge/Microsoft%20Bing-258FFA?style=for-the-badge&logo=Microsoft%20Bing&logoColor=white) | `![Bing](https://img.shields.io/badge/Microsoft%20Bing-258FFA?style=for-the-badge&logo=Microsoft%20Bing&logoColor=white)` |
| DuckDuckGo | ![DuckDuckGo](https://img.shields.io/badge/DuckDuckGo-DE5833?style=for-the-badge&logo=DuckDuckGo&logoColor=white)       | `![DuckDuckGo](https://img.shields.io/badge/DuckDuckGo-DE5833?style=for-the-badge&logo=DuckDuckGo&logoColor=white)`       |
| Google     | ![Google](https://img.shields.io/badge/google-4285F4?style=for-the-badge&logo=google&logoColor=white)                   | `![Google](https://img.shields.io/badge/google-4285F4?style=for-the-badge&logo=google&logoColor=white)`                   |
| Yahoo!     | ![Yahoo!](https://img.shields.io/badge/Yahoo!-6001D2?style=for-the-badge&logo=Yahoo!&logoColor=white)                   | `![Yahoo!](https://img.shields.io/badge/Yahoo!-6001D2?style=for-the-badge&logo=Yahoo!&logoColor=white)`                   |

[(Back to top)](#table-of-contents)

### 🗄️ Servers

| Name           | Badge                                                                                                                               | Markdown                                                                                                                              |
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| Apache         | ![Apache](https://img.shields.io/badge/apache-%23D42029.svg?style=for-the-badge&logo=apache&logoColor=white)                        | `![Apache](https://img.shields.io/badge/apache-%23D42029.svg?style=for-the-badge&logo=apache&logoColor=white)`                        |
| Apache Airflow | ![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=Apache%20Airflow&logoColor=white)   | `![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=Apache%20Airflow&logoColor=white)`   |
| Apache Ant     | ![Apache Ant](https://img.shields.io/badge/Apache%20Ant-A81C7D?style=for-the-badge&logo=Apache%20Ant&logoColor=white)               | `![Apache Ant](https://img.shields.io/badge/Apache%20Ant-A81C7D?style=for-the-badge&logo=Apache%20Ant&logoColor=white)`               |
| Apache Flink   | ![Apache Flink](https://img.shields.io/badge/Apache%20Flink-E6526F?style=for-the-badge&logo=Apache%20Flink&logoColor=white)         | `![Apache Flink](https://img.shields.io/badge/Apache%20Flink-E6526F?style=for-the-badge&logo=Apache%20Flink&logoColor=white)`         |
| Apache Maven   | ![Apache Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white)         | `![Apache Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white)`         |
| Apache Tomcat  | ![Apache Tomcat](https://img.shields.io/badge/apache%20tomcat-%23F8DC75.svg?style=for-the-badge&logo=apache-tomcat&logoColor=black) | `![Apache Tomcat](https://img.shields.io/badge/apache%20tomcat-%23F8DC75.svg?style=for-the-badge&logo=apache-tomcat&logoColor=black)` |
| Gunicorn       | ![Gunicorn](https://img.shields.io/badge/gunicorn-%298729.svg?style=for-the-badge&logo=gunicorn&logoColor=white)                    | `![Gunicorn](https://img.shields.io/badge/gunicorn-%298729.svg?style=for-the-badge&logo=gunicorn&logoColor=white)`                    |
| Jenkins        | ![Jenkins](https://img.shields.io/badge/jenkins-%232C5263.svg?style=for-the-badge&logo=jenkins&logoColor=white)                     | `![Jenkins](https://img.shields.io/badge/jenkins-%232C5263.svg?style=for-the-badge&logo=jenkins&logoColor=white)`                     |
| Nginx          | ![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)                           | `![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)`                           |

[(Back to top)](#table-of-contents)

### 💬 Social

| Name        | Badge                                                                                                                        | Markdown                                                                                                                       |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| Airtable    | ![Airtable](https://img.shields.io/badge/Airtable-18BFFF?style=for-the-badge&logo=Airtable&logoColor=white)                  | `![Airtable](https://img.shields.io/badge/Airtable-18BFFF?style=for-the-badge&logo=Airtable&logoColor=white)`                  |
| Bluesky     | ![Bluesky](https://img.shields.io/badge/Bluesky-0285FF?style=for-the-badge&logo=Bluesky&logoColor=white)                     | `![Bluesky](https://img.shields.io/badge/Bluesky-0285FF?style=for-the-badge&logo=Bluesky&logoColor=white)`                     |
| Discord     | ![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white)         | `![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white)`         |
| Element     | ![Element](https://img.shields.io/badge/element-0DBD8B.svg?style=for-the-badge&logo=element&logoColor=white)         | `![Element](https://img.shields.io/badge/element-0DBD8B.svg?style=for-the-badge&logo=element&logoColor=white)`         |
| Facebook    | ![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?style=for-the-badge&logo=Facebook&logoColor=white)           | `![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?style=for-the-badge&logo=Facebook&logoColor=white)`           |
| Gmail       | ![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)                           | `![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)`                           |
| Goodreads   | ![Goodreads](https://img.shields.io/badge/Goodreads-F3F1EA?style=for-the-badge&logo=goodreads&logoColor=372213)              | `![Goodreads](https://img.shields.io/badge/Goodreads-F3F1EA?style=for-the-badge&logo=goodreads&logoColor=372213)`              |
| Google Meet | ![Google Meet](https://img.shields.io/badge/Google%20Meet-00897B?style=for-the-badge&logo=google-meet&logoColor=white)       | `![Google Meet](https://img.shields.io/badge/Google%20Meet-00897B?style=for-the-badge&logo=google-meet&logoColor=white)`       |
| Instagram   | ![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)        | `![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)`        |
| KakaoTalk   | ![KakaoTalk](https://img.shields.io/badge/kakaotalk-ffcd00.svg?style=for-the-badge&logo=kakaotalk&logoColor=000000)          | `![KakaoTalk](https://img.shields.io/badge/kakaotalk-ffcd00.svg?style=for-the-badge&logo=kakaotalk&logoColor=000000)`          |
| Line        | ![Line](https://img.shields.io/badge/Line-00C300?style=for-the-badge&logo=line&logoColor=white)                              | `![Line](https://img.shields.io/badge/Line-00C300?style=for-the-badge&logo=line&logoColor=white)`                              |
| LinkedIn    | ![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)           | `![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)`           |
| Linktree    | ![Linktree](https://img.shields.io/badge/linktree-1de9b6?style=for-the-badge&logo=linktree&logoColor=white)                  | `![Linktree](https://img.shields.io/badge/linktree-1de9b6?style=for-the-badge&logo=linktree&logoColor=white)`                  |
| Meetup      | ![Meetup](https://img.shields.io/badge/Meetup-f64363?style=for-the-badge&logo=meetup&logoColor=white)                        | `![Meetup](https://img.shields.io/badge/Meetup-f64363?style=for-the-badge&logo=meetup&logoColor=white)`                        |
| Messenger   | ![Messenger](https://img.shields.io/badge/Messenger-00B2FF?style=for-the-badge&logo=messenger&logoColor=white)               | `![Messenger](https://img.shields.io/badge/Messenger-00B2FF?style=for-the-badge&logo=messenger&logoColor=white)`               |
| Mastodon    | ![Mastodon](https://img.shields.io/badge/-MASTODON-%232B90D9?style=for-the-badge&logo=mastodon&logoColor=white)              | `![Mastodon](https://img.shields.io/badge/-MASTODON-%232B90D9?style=for-the-badge&logo=mastodon&logoColor=white)`              |
| Outlook     | ![Outlook](https://img.shields.io/badge/Microsoft_Outlook-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white) | `![Outlook](https://img.shields.io/badge/Microsoft_Outlook-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white)` |
| Odysee      | ![OutOdyseelook](https://img.shields.io/badge/odysee-EF1970?style=for-the-badge&logo=Odysee&logoColor=white)                 | `![Odysee](https://img.shields.io/badge/odysee-EF1970?style=for-the-badge&logo=Odysee&logoColor=white)`                        |
| Pinterest   | ![Pinterest](https://img.shields.io/badge/Pinterest-%23E60023.svg?style=for-the-badge&logo=Pinterest&logoColor=white)        | `![Pinterest](https://img.shields.io/badge/Pinterest-%23E60023.svg?style=for-the-badge&logo=Pinterest&logoColor=white)`        |
| Protonmail  | ![Protonmail](https://img.shields.io/badge/ProtonMail-8B89CC?style=for-the-badge&logo=protonmail&logoColor=white)            | `![Protonmail](https://img.shields.io/badge/ProtonMail-8B89CC?style=for-the-badge&logo=protonmail&logoColor=white)`            |
| Polywork    | ![Polywork](https://img.shields.io/badge/Polywork-543DE0?style=for-the-badge&logo=polywork&logoColor=black)                  | `![Polywork](https://img.shields.io/badge/Polywork-543DE0?style=for-the-badge&logo=polywork&logoColor=black)`                  |
| Reddit      | ![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)                        | `![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)`                        |
| Session     | ![Session](https://img.shields.io/badge/Session-%23000000.svg?style=for-the-badge&logo=Session&logoColor=02f780)             | `![Session](https://img.shields.io/badge/Session-%23000000.svg?style=for-the-badge&logo=Session&logoColor=02f780)`             |
| Signal      | ![Signal](https://img.shields.io/badge/Signal-%23039BE5.svg?style=for-the-badge&logo=Signal&logoColor=white)                 | `![Signal](https://img.shields.io/badge/Signal-%23039BE5.svg?style=for-the-badge&logo=Signal&logoColor=white)`                 |
| Skype       | ![Skype](https://img.shields.io/badge/Skype-%2300AFF0.svg?style=for-the-badge&logo=Skype&logoColor=white)                    | `![Skype](https://img.shields.io/badge/Skype-%2300AFF0.svg?style=for-the-badge&logo=Skype&logoColor=white)`                    |
| Slack       | ![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)                           | `![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)`                           |
| Snapchat    | ![Snapchat](https://img.shields.io/badge/Snapchat-%23FFFC00.svg?style=for-the-badge&logo=Snapchat&logoColor=black)           | `![Snapchat](https://img.shields.io/badge/Snapchat-%23FFFC00.svg?style=for-the-badge&logo=Snapchat&logoColor=white)`           |
| TeamSpeak   | ![TeamSpeak](https://img.shields.io/badge/TeamSpeak-2580C3?style=for-the-badge&logo=teamspeak&logoColor=white)               | `![TeamSpeak](https://img.shields.io/badge/TeamSpeak-2580C3?style=for-the-badge&logo=teamspeak&logoColor=white)`               |
| Telegram    | ![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)                  | `![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)`                  |
| Tencent QQ  | ![Tencent QQ](https://img.shields.io/badge/Tencent%23QQ-%2312B7F5?style=for-the-badge&logo=tencentqq&logoColor=white)        | `![Tencent QQ](https://img.shields.io/badge/Tencent%23QQ-%2312B7F5?style=for-the-badge&logo=tencentqq&logoColor=white)`        |
| TikTok      | ![TikTok](https://img.shields.io/badge/TikTok-%23000000.svg?style=for-the-badge&logo=TikTok&logoColor=white)                 | `![TikTok](https://img.shields.io/badge/TikTok-%23000000.svg?style=for-the-badge&logo=TikTok&logoColor=white)`                 |
| Thunderbird | ![Thunderbird](https://img.shields.io/badge/Thunderbird-0A84FF.svg?style=for-the-badge&logo=Thunderbird&logoColor=white)     | `![Thunderbird](https://img.shields.io/badge/Thunderbird-0A84FF.svg?style=for-the-badge&logo=Thunderbird&logoColor=white)`                 |
| Tumblr      | ![Tumblr](https://img.shields.io/badge/Tumblr-%2336465D.svg?style=for-the-badge&logo=Tumblr&logoColor=white)                 | `![Tumblr](https://img.shields.io/badge/Tumblr-%2336465D.svg?style=for-the-badge&logo=Tumblr&logoColor=white)`                 |
| Tutanota    | ![Tutanota](https://img.shields.io/badge/Tutanota-840010?style=for-the-badge&logo=Tutanota&logoColor=white)                  | `![Tutanota](https://img.shields.io/badge/Tutanota-840010?style=for-the-badge&logo=Tutanota&logoColor=white)`                  |
| Twitch      | ![Twitch](https://img.shields.io/badge/Twitch-%239146FF.svg?style=for-the-badge&logo=Twitch&logoColor=white)                 | `![Twitch](https://img.shields.io/badge/Twitch-%239146FF.svg?style=for-the-badge&logo=Twitch&logoColor=white)`                 |
| Viber       | ![Viber](https://img.shields.io/badge/Viber-8B66A9?style=for-the-badge&logo=viber&logoColor=white)                           | `![Viber](https://img.shields.io/badge/Viber-8B66A9?style=for-the-badge&logo=viber&logoColor=white)`                           |
| WeChat      | ![WeChat](https://img.shields.io/badge/WeChat-07C160?style=for-the-badge&logo=wechat&logoColor=white)                        | `![WeChat](https://img.shields.io/badge/WeChat-07C160?style=for-the-badge&logo=wechat&logoColor=white)`                        |
| WhatsApp    | ![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)                  | `![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)`                  |
| Wire        | ![Wire](https://img.shields.io/badge/Wire-B71C1C?style=for-the-badge&logo=wire&logoColor=white)                              | `![Wire](https://img.shields.io/badge/Wire-B71C1C?style=for-the-badge&logo=wire&logoColor=white)`                              |
| X     | ![X](https://img.shields.io/badge/X-%23000000.svg?style=for-the-badge&logo=X&logoColor=white)              | `![X](https://img.shields.io/badge/X-%23000000.svg?style=for-the-badge&logo=X&logoColor=white)`              |
| Xbox        | ![Xbox](https://img.shields.io/badge/Xbox-%23107C10.svg?style=for-the-badge&logo=Xbox&logoColor=white)                       | `![Xbox](https://img.shields.io/badge/Xbox-%23107C10.svg?style=for-the-badge&logo=Xbox&logoColor=white)`                       |
| XING        | ![XING](https://img.shields.io/badge/xing-%23006567.svg?style=for-the-badge&logo=xing&logoColor=white)                       | `![XING](https://img.shields.io/badge/xing-%23006567.svg?style=for-the-badge&logo=xing&logoColor=white)`                       |
| YouTube     | ![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)              | `![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)`              |
| Zoom        | ![Zoom](https://img.shields.io/badge/Zoom-2D8CFF?style=for-the-badge&logo=zoom&logoColor=white)                              | `![Zoom](https://img.shields.io/badge/Zoom-2D8CFF?style=for-the-badge&logo=zoom&logoColor=white)`                              |
| Threads        | ![Threads](https://img.shields.io/badge/Threads-000000?style=for-the-badge&logo=Threads&logoColor=white)                       | `![Threads](https://img.shields.io/badge/Threads-000000?style=for-the-badge&logo=Threads&logoColor=white)`                       |

[(Back to top)](#table-of-contents)

### 📱 Smartphone Brands

| Name       | Badge                                                                                                                 | Markdown                                                                                                                |
| ---------- | --------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| Apple      | ![Apple](https://img.shields.io/badge/Apple-%23000000.svg?style=for-the-badge&logo=apple&logoColor=white)             | `![Apple](https://img.shields.io/badge/Apple-%23000000.svg?style=for-the-badge&logo=apple&logoColor=white)`             |
| ASUS       | ![ASUS](https://img.shields.io/badge/asus-000080.svg?style=for-the-badge&logo=asus&logoColor=white)                   | `![ASUS](https://img.shields.io/badge/asus-000080.svg?style=for-the-badge&logo=asus&logoColor=white)`                   |
| BlackBerry | ![BlackBerry](https://img.shields.io/badge/blackberry-808080.svg?style=for-the-badge&logo=blackberry&logoColor=white) | `![BlackBerry](https://img.shields.io/badge/blackberry-808080.svg?style=for-the-badge&logo=blackberry&logoColor=white)` |
| Huawei     | ![Huawei](https://img.shields.io/badge/Huawei-%23FF0000.svg?style=for-the-badge&logo=huawei&logoColor=white)          | `![Huawei](https://img.shields.io/badge/Huawei-%23FF0000.svg?style=for-the-badge&logo=huawei&logoColor=white)`          |
| Lenovo     | ![Lenovo](https://img.shields.io/badge/lenovo-E2231A?style=for-the-badge&logo=lenovo&logoColor=white)                 | `![Lenovo](https://img.shields.io/badge/lenovo-E2231A?style=for-the-badge&logo=lenovo&logoColor=white)`                 |
| LG         | ![LG](https://img.shields.io/badge/lg-a50034.svg?style=for-the-badge&logo=lg&logoColor=white)                         | `![LG](https://img.shields.io/badge/lg-a50034.svg?style=for-the-badge&logo=lg&logoColor=white)`                         |
| OnePlus    | ![OnePlus](https://img.shields.io/badge/OnePlus-%23F5010C.svg?style=for-the-badge&logo=oneplus&logoColor=white)       | `![OnePlus](https://img.shields.io/badge/OnePlus-%23F5010C.svg?style=for-the-badge&logo=oneplus&logoColor=white)`       |
| Motorola   | ![Motorola](https://img.shields.io/badge/Motorola-%23E1140A.svg?style=for-the-badge&logo=motorola&logoColor=white)    | `![Motorola](https://img.shields.io/badge/Motorola-%23E1140A.svg?style=for-the-badge&logo=motorola&logoColor=white)`    |
| Nokia      | ![Nokia](https://img.shields.io/badge/Nokia-%23124191.svg?style=for-the-badge&logo=nokia&logoColor=white)             | `![Nokia](https://img.shields.io/badge/Nokia-%23124191.svg?style=for-the-badge&logo=nokia&logoColor=white)`             |
| Samsung    | ![Samsung](https://img.shields.io/badge/Samsung-%231428A0.svg?style=for-the-badge&logo=samsung&logoColor=white)       | `![Samsung](https://img.shields.io/badge/Samsung-%231428A0.svg?style=for-the-badge&logo=samsung&logoColor=white)`       |
| Xiaomi     | ![Xiaomi](https://img.shields.io/badge/Xiaomi-%23FF6900.svg?style=for-the-badge&logo=xiaomi&logoColor=white)          | `![Xiaomi](https://img.shields.io/badge/Xiaomi-%23FF6900.svg?style=for-the-badge&logo=xiaomi&logoColor=white)`          |
| Oppo     | ![Oppo](https://img.shields.io/badge/Oppo-%231EA366.svg?style=for-the-badge&logo=oppo&logoColor=white)          | `![Oppo](https://img.shields.io/badge/Oppo-%231EA366.svg?style=for-the-badge&logo=oppo&logoColor=white)`          |
| Vivo     | ![Vivo](https://img.shields.io/badge/Vivo-%2300BFFF.svg?style=for-the-badge&logo=vivo&logoColor=black)          | `![Vivo](https://img.shields.io/badge/Vivo-%2300BFFF.svg?style=for-the-badge&logo=vivo&logoColor=black)`          |


[(Back to top)](#table-of-contents)

### 🛍️ Store

| Name       | Badge                                                                                                               | Markdown                                                                                                              |
| ---------- | ------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| App Store  | ![App Store](https://img.shields.io/badge/App_Store-0D96F6?style=for-the-badge&logo=app-store&logoColor=white)      | `![App Store](https://img.shields.io/badge/App_Store-0D96F6?style=for-the-badge&logo=app-store&logoColor=white)`      |
| AppGallery | ![AppGallery](https://img.shields.io/badge/AppGallery-C80A2D?style=for-the-badge&logo=huawei&logoColor=white) | `![AppGallery](https://img.shields.io/badge/AppGallery-C80A2D?style=for-the-badge&logo=huawei&logoColor=white)` |
| F-Droid    | ![F Droid](https://img.shields.io/badge/F_Droid-1976D2?style=for-the-badge&logo=f-droid&logoColor=white)            | `![F Droid](https://img.shields.io/badge/F_Droid-1976D2?style=for-the-badge&logo=f-droid&logoColor=white)`            |
| Shopify | ![Shopify](https://img.shields.io/badge/shopify-7AB55C.svg?style=for-the-badge&logo=shopify&logoColor=white) | `![Shopify](https://img.shields.io/badge/shopify-7AB55C.svg?style=for-the-badge&logo=shopify&logoColor=white)` |
| AppGallery | ![AppGallery](https://img.shields.io/badge/AppGallery-C80A2D?style=for-the-badge&logo=huawei&logoColor=white) | `![AppGallery](https://img.shields.io/badge/AppGallery-C80A2D?style=for-the-badge&logo=huawei&logoColor=white)` |

[(Back to top)](#table-of-contents)

### 📺 Streaming

| Name            | Badge                                                                                                                             | Markdown                                                                                                                            |
| --------------- | --------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| Amazon Prime    | ![Amazon Prime](https://img.shields.io/badge/Amazon%20Prime-0F79AF?style=for-the-badge&logo=amazonprime&logoColor=white)          | `![Amazon Prime](https://img.shields.io/badge/Amazon%20Prime-0F79AF?style=for-the-badge&logo=amazonprime&logoColor=white)`          |
| Bilibili       | ![Bilibili](https://img.shields.io/badge/bilibili-00A1D6.svg?style=for-the-badge&logo=bilibili&logoColor=white)                   | `![Bilibili](https://img.shields.io/badge/bilibili-00A1D6.svg?style=for-the-badge&logo=bilibili&logoColor=white)`                   |
| Apple TV        | ![Apple TV](https://img.shields.io/badge/Apple%20TV-000000?style=for-the-badge&logo=Apple%20TV&logoColor=white)                   | `![Apple TV](https://img.shields.io/badge/Apple%20TV-000000?style=for-the-badge&logo=Apple%20TV&logoColor=white)`                   |
| Crunchyroll     | ![Crunchroll](https://img.shields.io/badge/Crunchyroll-F47521?style=for-the-badge&logo=crunchyroll&logoColor=white)               | `![Crunchyroll](https://img.shields.io/badge/Crunchyroll-F47521?style=for-the-badge&logo=crunchyroll&logoColor=white)`              |
| Facebook Gaming | ![Facebook Gaming](https://img.shields.io/badge/Facebook%20Gaming-015BE5?style=for-the-badge&logo=facebookgaming&logoColor=white) | `![Facebook Gaming](https://img.shields.io/badge/Facebook%20Gaming-015BE5?style=for-the-badge&logo=facebookgaming&logoColor=white)` |
| Facebook Live   | ![Facebook Live](https://img.shields.io/badge/Facebook%20Live-ED4242?style=for-the-badge&logo=Facebook%20Live&logoColor=white)    | `![Facebook Live](https://img.shields.io/badge/Facebook%20Live-ED4242?style=for-the-badge&logo=Facebook%20Live&logoColor=white)`    |
| Fandango At Home | ![Fandango At Home](https://img.shields.io/badge/Fandango%20At%20Home-3478C1?style=for-the-badge&logo=fandango&logoColor=white)  | `![Fandango At Home](https://img.shields.io/badge/Fandango%20At%20Home-3478C1?style=for-the-badge&logo=fandango&logoColor=white)`   | 
| Fire TV         | ![Fire TV](https://img.shields.io/badge/fire%20tv-fc3b2d?style=for-the-badge&logo=amazon%20fire%20tv&logoColor=white)             | `![Fire TV](https://img.shields.io/badge/fire%20tv-fc3b2d?style=for-the-badge&logo=amazon%20fire%20tv&logoColor=white)`             |
| Fubo            | ![Fubo](https://img.shields.io/badge/Fubo-E64526?style=for-the-badge&logo=fubo&logoColor=white)                                   | `![Fubo](https://img.shields.io/badge/Fubo-E64526?style=for-the-badge&logo=fubo&logoColor=white)`                                   | 
| Hulu            | ![Hulu](https://img.shields.io/badge/hulu-1CE783?style=for-the-badge&logo=hulu&logoColor=white)                                   | `![Hulu](https://img.shields.io/badge/hulu-1CE783?style=for-the-badge&logo=hulu&logoColor=white)`                                   |
| Kick            | ![Kick](https://img.shields.io/badge/kick-53FC18?style=for-the-badge&logo=kick&logoColor=white)                                   | `![Kick](https://img.shields.io/badge/kick-53FC18?style=for-the-badge&logo=kick&logoColor=white)`                                   |
| Netflix         | ![Netflix](https://img.shields.io/badge/Netflix-E50914?style=for-the-badge&logo=netflix&logoColor=white)                          | `![Netflix](https://img.shields.io/badge/Netflix-E50914?style=for-the-badge&logo=netflix&logoColor=white)`                          |
| Roku  | ![Roku](https://img.shields.io/badge/roku-6f1ab1?style=for-the-badge&logo=roku&logoColor=white)    | `![Roku](https://img.shields.io/badge/roku-6f1ab1?style=for-the-badge&logo=roku&logoColor=white)`    |
| Tubi            | ![Tubi](https://img.shields.io/badge/Tubi-6A18F5?style=for-the-badge&logo=tubi&logoColor=white)                                   | `![Tubi](https://img.shields.io/badge/Tubi-6A18F5?style=for-the-badge&logo=tubi&logoColor=white)`                                   | 
| Twitch          | ![Twitch](https://img.shields.io/badge/Twitch-9347FF?style=for-the-badge&logo=twitch&logoColor=white)                             | `![Twitch](https://img.shields.io/badge/Twitch-9347FF?style=for-the-badge&logo=twitch&logoColor=white)`                             |
| Youtube Gaming  | ![Youtube Gaming](https://img.shields.io/badge/Youtube%20Gaming-FF0000?style=for-the-badge&logo=Youtubegaming&logoColor=white)    | `![Youtube Gaming](https://img.shields.io/badge/Youtube%20Gaming-FF0000?style=for-the-badge&logo=Youtubegaming&logoColor=white)`    |
| Disney  | ![Disney](https://img.shields.io/badge/Disney-%23006E99.svg?style=for-the-badge&logo=disney&logoColor=white)    | `![Disney](https://img.shields.io/badge/Disney-%23006E99.svg?style=for-the-badge&logo=disney&logoColor=white)`    |


[(Back to top)](#table-of-contents)

### 🧪 Testing

| Name            | Badge                                                                                                                               | Markdown                                                                                                                              |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| Cypress         | ![Cypress](https://img.shields.io/badge/-cypress-%23E5E5E5?style=for-the-badge&logo=cypress&logoColor=058a5e)                       | `![cypress](https://img.shields.io/badge/-cypress-%23E5E5E5?style=for-the-badge&logo=cypress&logoColor=058a5e)`                       |
| Jasmine         | ![Jasmine](https://img.shields.io/badge/-Jasmine-%238A4182?style=for-the-badge&logo=Jasmine&logoColor=white)                        | `![Jasmine](https://img.shields.io/badge/-Jasmine-%238A4182?style=for-the-badge&logo=Jasmine&logoColor=white)`                        |
| Jest            | ![Jest](https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white)                                 | `![Jest](https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white)`                                 |
| Mocha           | ![Mocha](https://img.shields.io/badge/-mocha-%238D6748?style=for-the-badge&logo=mocha&logoColor=white)                              | `![Mocha](https://img.shields.io/badge/-mocha-%238D6748?style=for-the-badge&logo=mocha&logoColor=white)`                              |
| Playwright           | ![Playwright](https://img.shields.io/badge/-playwright-%232EAD33?style=for-the-badge&logo=playwright&logoColor=white)                              | `![Playwright](https://img.shields.io/badge/-playwright-%232EAD33?style=for-the-badge&logo=playwright&logoColor=white)`                              |
| Puppeteer       | ![Puppeteer](https://img.shields.io/badge/Puppeteer-%2340B5A4.svg?style=for-the-badge&logo=Puppeteer&logoSize=auto&logoColor=black) | `![Puppeteer](https://img.shields.io/badge/Puppeteer-white.svg?style=for-the-badge&logo=Puppeteer&logoColor=black)`                   |
| Selenium        | ![Selenium](https://img.shields.io/badge/-selenium-%43B02A?style=for-the-badge&logo=selenium&logoColor=white)                       | `![Selenium](https://img.shields.io/badge/-selenium-%43B02A?style=for-the-badge&logo=selenium&logoColor=white)`                       |
| Sentry | ![Sentry](https://img.shields.io/badge/sentry-%23362D59.svg?style=for-the-badge&logo=sentry&logoColor=white) | `![Sentry](https://img.shields.io/badge/sentry-%23362D59.svg?style=for-the-badge&logo=sentry&logoColor=white)` |
| Testing Library | ![Testing-Library](https://img.shields.io/badge/-TestingLibrary-%23E33332?style=for-the-badge&logo=testing-library&logoColor=white) | `![Testing-Library](https://img.shields.io/badge/-TestingLibrary-%23E33332?style=for-the-badge&logo=testing-library&logoColor=white)` |
| Vitest | ![Vitest](https://img.shields.io/badge/-Vitest-252529?style=for-the-badge&logo=vitest&logoColor=FCC72B) | `![Vitest](https://img.shields.io/badge/-Vitest-252529?style=for-the-badge&logo=vitest&logoColor=FCC72B)` |

[(Back to top)](#table-of-contents)

### 🕓 Version Control

| Name           | Badge                                                                                                                      | Markdown                                                                                                                     |
| -------------- | -------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| Apache Subversion      | ![Apache Subversion](https://img.shields.io/badge/subversion-%23809CC9.svg?style=for-the-badge&logo=subversion&logoColor=white)      | `![Apache Subversion](https://img.shields.io/badge/subversion-%23809CC9.svg?style=for-the-badge&logo=subversion&logoColor=white)`      |
| Bitbucket      | ![Bitbucket](https://img.shields.io/badge/bitbucket-%230047B3.svg?style=for-the-badge&logo=bitbucket&logoColor=white)      | `![Bitbucket](https://img.shields.io/badge/bitbucket-%230047B3.svg?style=for-the-badge&logo=bitbucket&logoColor=white)`      |
| Forgejo        | ![Forgejo](https://img.shields.io/badge/forgejo-%23FB923C.svg?style=for-the-badge&logo=forgejo&logoColor=white)      | `![Forgejo](https://img.shields.io/badge/forgejo-%23FB923C.svg?style=for-the-badge&logo=forgejo&logoColor=white)`      |
| Git            | ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)                        | `![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)`                        |
| Gitea          | ![Gitea](https://img.shields.io/badge/Gitea-34495E?style=for-the-badge&logo=gitea&logoColor=5D9425)                        | `![Gitea](https://img.shields.io/badge/Gitea-34495E?style=for-the-badge&logo=gitea&logoColor=5D9425)`                        |
| Gitee          | ![Gitee](https://img.shields.io/badge/Gitee-C71D23?style=for-the-badge&logo=gitee&logoColor=white)                         | `![Gitee](https://img.shields.io/badge/Gitee-C71D23?style=for-the-badge&logo=gitee&logoColor=white)`                         |
| GitHub         | ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)               | `![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)`               |
| GitLab         | ![GitLab](https://img.shields.io/badge/gitlab-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white)               | `![GitLab](https://img.shields.io/badge/gitlab-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white)`               |
| Gitpod         | ![Gitpod](https://img.shields.io/badge/gitpod-f06611.svg?style=for-the-badge&logo=gitpod&logoColor=white)                  | `![Gitpod](https://img.shields.io/badge/gitpod-f06611.svg?style=for-the-badge&logo=gitpod&logoColor=white)`                  |
| Mercurial      | ![Mercurial](https://img.shields.io/badge/mercurial-999999.svg?style=for-the-badge&logo=mercurial&logoColor=white)         | `![Mercurial](https://img.shields.io/badge/mercurial-999999.svg?style=for-the-badge&logo=mercurial&logoColor=white)`         |
| Perforce Helix | ![Perforce Helix](https://img.shields.io/badge/-PERFORCE%20HELIX-404040?style=for-the-badge&logo=Perforce&logoColor=white) | `![Perforce Helix](https://img.shields.io/badge/-PERFORCE%20HELIX-00AEEF?style=for-the-badge&logo=Perforce&logoColor=white)` |

[(Back to top)](#table-of-contents)

### ⌚️ Wearables

| Name       | Badge                                                                                                                 | Markdown                                                                                                                |
| ---------- | --------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| Fitbit      | ![Fitbit](https://img.shields.io/badge/fitbit-00B0B9?style=for-the-badge&logo=fitbit&logoColor=white)             | `![Fitbit](https://img.shields.io/badge/fitbit-00B0B9?style=for-the-badge&logo=fitbit&logoColor=white)`             |

[(Back to top)](#table-of-contents)

### 💼 Work/Jobs

| Name         | Badge                                                                                                                      | Markdown                                                                                                                     |
| ------------ | -------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| AngelList    | ![AngelList](https://img.shields.io/badge/AngelList-%23D4D4D4.svg?style=for-the-badge&logo=AngelList&logoColor=black)      | `![AngelList](https://img.shields.io/badge/AngelList-%23D4D4D4.svg?style=for-the-badge&logo=AngelList&logoColor=black)`      |
| Behance      | ![Behance](https://img.shields.io/badge/Behance-1769ff?style=for-the-badge&logo=behance&logoColor=white)                   | `![Behance](https://img.shields.io/badge/Behance-1769ff?style=for-the-badge&logo=behance&logoColor=white)`                   |
| Freelancer   | ![Freelancer](https://img.shields.io/badge/Freelancer-29B2FE?style=for-the-badge&logo=Freelancer&logoColor=white)          | `![Freelancer](https://img.shields.io/badge/Freelancer-29B2FE?style=for-the-badge&logo=Freelancer&logoColor=white)`          |
| Glassdoor    | ![Glassdoor](https://img.shields.io/badge/Glassdoor-00A162?style=for-the-badge&logo=Glassdoor&logoColor=white)             | `![Glassdoor](https://img.shields.io/badge/Glassdoor-00A162?style=for-the-badge&logo=Glassdoor&logoColor=white)`
| Hacker Earth | ![HackerEarth](https://img.shields.io/badge/HackerEarth-%232C3454.svg?style=for-the-badge&logo=HackerEarth&logoColor=Blue) | `![HackerEarth](https://img.shields.io/badge/HackerEarth-%232C3454.svg?style=for-the-badge&logo=HackerEarth&logoColor=Blue)` |
| HackerRank   | ![HackerRank](https://img.shields.io/badge/-Hackerrank-2EC866?style=for-the-badge&logo=HackerRank&logoColor=white)         | `![HackerRank](https://img.shields.io/badge/-Hackerrank-2EC866?style=for-the-badge&logo=HackerRank&logoColor=white)`         |
| Indeed       | ![Indeed](https://img.shields.io/badge/indeed-003A9B?style=for-the-badge&logo=indeed&logoColor=white)                      | `![Indeed](https://img.shields.io/badge/indeed-003A9B?style=for-the-badge&logo=indeed&logoColor=white)`                      |
| Upwork       | ![Upwork](https://img.shields.io/badge/UpWork-6FDA44?style=for-the-badge&logo=Upwork&logoColor=white)                      | `![Upwork](https://img.shields.io/badge/UpWork-6FDA44?style=for-the-badge&logo=Upwork&logoColor=white)`                      |


[(Back to top)](#table-of-contents)


- [Badges shields](https://github.com/badges/shields)

[def]: #como-usar-os-badges-shields

</details>

---

## Creating GIFs

Embedding an animated gif in your README quickly demonstrates what your project does and catches the reader's eye. Here are a few programs that can help you quickly create gifs for your project:

- [Gifski](https://github.com/sindresorhus/Gifski#readme) - **FREE** - More vivid colors than the rest, but still keeps size low.
- [Giphy Capture](https://giphy.com/apps/giphycapture) - **FREE** - Easy to upload to giphy.com, with a slightly annoying UX.
- [LICEcap](https://www.cockos.com/licecap/) - **FREE** - Less intuitive, but with more features.
- [Peek](https://github.com/phw/peek#readme) - **FREE** - Simple and easy to use for Linux users.
- [ScreenToGif](https://github.com/NickeManarin/ScreenToGif/) - **FREE** - Open source, with a customizable UI and easily editable GIFs, easy to get started.
- [terminalizer](https://github.com/faressoft/terminalizer) - **FREE** - Record your terminal and generate animated GIF images or share a web player.
- [ttystudio](https://github.com/chjj/ttystudio#readme) - **FREE** - For command-line tools, a terminal-to-GIF recorder minus the headaches.
- [vhs](https://github.com/charmbracelet/vhs) - **FREE** - Generate beautiful terminal GIFs with a simple scripting language
---

## How to Use

Hi, I'm **Tobias**. I created this project so anyone can have a cool, professional, and viral README.
Here's how to use it:

1. Fork or clone this repository.
2. Check out the templates in the Advanced Templates section.
3. Choose the badges that represent you (languages, frameworks, tools).
4. Add your stats.
5. Customize sections like "About Me," "Contact," or add your projects.
6. Upload your new README to your profile or repository.
7. Like this repo if it helped you.

Tip: You can combine it with memes, GIFs, code, or whatever represents you. The README is yours, make it unique.

---

##  Examples 

| Perfil | README |
|--------|--------|
| @tobiager | [Ver ejemplo](https://github.com/tobiager) |


---
## Why This Exists

I'm tired of seeing READMEs that are lame or have millions of meaningless emojis.
README Builder gives you everything in one place, ready to copy, customize, and paste.
It works whether you're just starting out or already in code ninja mode.

---

## License

MIT — use it, modify it, and share it.
But if you liked it, give it a star and follow me.

---

##  Top Contributors

Thanks to everyone who's helping this project grow. Your contribution can also be included here!

<a href="https://github.com/tobiager/readme-builder/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=tobiager/readme-builder" />
</a>

---

<p align="center">
  <a href="https://github.com/tobiager" target="_blank">
    <img src="jagerlogo.gif" alt="Jagermeister Logo" width="180" />
  </a>
</p>

<p align="center"><b>Built with ❤️ by <a href="https://github.com/tobiager">Tobias</a></b></p>
