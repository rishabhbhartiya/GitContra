<div align="center">

<img src="./screenshots/gitcity.svg" alt="GitCity" width="90%" />

<br/><br/>

<a href="https://gitcity.natrajx.in">
  <img src="./screenshots/login.gif" alt="GitCity — Login and City Generation" width="90%" />
</a>

<br/>
<br/><br/>

[![LIVE DEMO](https://readmeforge.natrajx.in/api/badge?label=LIVE+DEMO&metal=vintage-green&shape=rounded&theme=dark&value=https%3A%2F%2Fgitcity.natrajx.in)](https://gitcity.natrajx.in)
[![MADE BY:](https://readmeforge.natrajx.in/api/badge?label=MADE+BY%3A&metal=vintage-green&shape=rounded&theme=dark&value=NATRAJ-X)](https://natrajx.in)
[![Ko-fi](https://img.shields.io/badge/Support%20on-Ko--fi-FF5E5B?logo=ko-fi&logoColor=white&style=flat-square)](https://ko-fi.com/rishabhbhartiya)

</div>

<table align="center">
<tr>
<td align="center">
<a href="https://peerpush.com/p/gitcity" target="_blank" rel="noopener">
  <img
    src="https://peerpush.com/p/gitcity/badge.png"
    alt="GitCity on PeerPush"
    width="180"
  />
</a>
</td>

<td align="center">
<a href="https://www.producthunt.com/products/gitcity/launches/gitcity?embed=true&utm_source=badge-featured&utm_medium=badge&utm_campaign=badge-gitcity"
   target="_blank" rel="noopener noreferrer">
  <img
    src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=1113209&theme=light"
    alt="Featured on Product Hunt"
    width="210"
  />
</a>
</td>

<td align="center">
<a href="https://www.producthunt.com/products/gitcity/reviews/new?utm_source=badge-product_review&utm_medium=badge&utm_campaign=badge-gitcity"
   target="_blank" rel="noopener">
  <img
    src="https://api.producthunt.com/widgets/embed-image/v1/product_review.svg?product_id=1195254&theme=light"
    alt="Review GitCity on Product Hunt"
    width="210"
  />
</a>
</td>
</tr>
</table>

## What is GitCity?

GitCity fetches your **entire GitHub contribution history** via the GitHub GraphQL API and renders it as an interactive 3D city — no token required, no login, no paywall.

<p align="center">
  <img src="https://readmeforge.natrajx.in/api/card-glass?glassTheme=neon&metal=electric&width=238&height=134&title=&value=Isometric&subtitle=&icon=" alt="Isometric" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://readmeforge.natrajx.in/api/card-glass?glassTheme=neon&metal=electric&width=187&height=134&title=&value=Heatmap&subtitle=&icon=" alt="Heatmap" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://readmeforge.natrajx.in/api/card-glass?glassTheme=neon&metal=electric&width=259&height=134&title=&value=Simulation&subtitle=&icon=" alt="Simulation" />
</p>



---
## Embed API

Drop a live, always-updated skyline anywhere — README, portfolio, blog post.

<p align="center">
  <img src="https://readmeforge.natrajx.in/api/text-anim?text=See+it+live-+Your+Skyline+in+one+Line&effect=explode&metal=material-green&width=597&size=32&theme=dark" />
</p>

```markdown
[![My GitCity Skyline](https://gitcity.natrajx.in/api/svg?u=YOUR_USERNAME)](https://gitcity.natrajx.in/YOUR_USERNAME)
```


**HTML — full control**

```html
<a href="https://gitcity.natrajx.in/YOUR_USERNAME">
  <img src="https://gitcity.natrajx.in/api/svg?u=YOUR_USERNAME&theme=aurora"
       alt="My GitHub Skyline" width="100%" />
</a>
```

**iframe — interactive, for portfolios**

```html
<iframe
  src="https://gitcity.natrajx.in/YOUR_USERNAME/isometric"
  width="100%" height="500"
  frameborder="0"
  title="GitHub Contribution Skyline">
</iframe>
```

---

## Quick Start

<div>
<h3>Option A</h3>

![Terminal](https://readmeforge.natrajx.in/api/terminal?title=Hosted+%28recommended%29&lines=https%3A%2F%2Fgitcity.natrajx.in%2FYOUR_USERNAME&theme=blue&metal=obsidian&width=650)

<h3>Option B</h3>

![Terminal](https://readmeforge.natrajx.in/api/terminal?title=Self-hosts&lines=%23+Clone%0A%7Cgit+clone+https%3A%2F%2Fgithub.com%2Fnatrajx%2Fgitcity%0A%7Ccd+gitcity%0A%7C%0A%7C%23+Install%0A%7Cnpm+install%0A%7C%0A%7C%23+Set+your+GitHub+token%0A%7Cecho+%22GITHUB_TOKEN%3Dghp_your_token_here%22+%3E+.env.local%0A%7C%0A%7C%23+Run+locally%0A%7Cvercel+dev++++++++++%23+with+%2Fapi+serverless+functions%0A%7C%23+OR%0A%7Cnpm+run+dev+++++++++%23+Vite+only+%28uses+hosted+API%29%0A%7C%0A%7C%23+Deploy%0A%7Cvercel+--prod&theme=blue&metal=obsidian&width=650)

</div>

![Table](https://readmeforge.natrajx.in/api/table?type=stats&metal=material-blue&width=600&theme=dark&title=Environment+variables&headers=Variable%2CRequired%2CDescription&rows=GITHUB_TOKEN%09%2CYes%09%2CGitHub+PAT+with+read)

## Contributing

PRs welcome. Open an issue first for major changes.

<p align="center">
  <img
    src="https://readmeforge.natrajx.in/api/terminal?title=Contributing&lines=git+checkout+-b+feat%2Fyour-feature%0A%7Cgit+commit+-m+%22feat%3A+your+feature%22%0A%7Cgit+push+origin+feat%2Fyour-feature%0A%7C%23+open+PR+-%3E+main&theme=blue&metal=obsidian&width=500"
    alt="Terminal"
  />
</p>

---

## Support

GitCity is free and open-source — no login, no paywall, no token required for the hosted version.

If it made your README cooler or your portfolio stand out, consider a coffee. It goes toward hosting, GPU time, and building more free tools.

<a href="https://ko-fi.com/rishabhbhartiya">
  <img src="https://ko-fi.com/img/githubbutton_sm.svg" alt="Support on Ko-fi" />
</a>

---

## FAQ

**Is this the same as thegitcity.com?**  
No — completely different project. See [COMPARISON.md](./COMPARISON.md) for a full breakdown.

**Do I need a GitHub token?**  
No. The hosted version at `gitcity.natrajx.in` handles auth server-side. Token only needed for self-hosting.

**Can I share someone else's city?**  
Yes — just use their username in the URL. All data is public GitHub contribution data.

---

<div align="center">

Made with coffee by **[Rishabh Bhartiya](https://rishabhbhartiya.natrajx.in)**

</div>
