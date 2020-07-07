# PDF Resume with Relaxed.JS (mnjul's design)

This directory contains a sample resume edited with ReLaXed.

> Master document: [``cv.pug``](https://github.com/IllusiveBagel/CV/cv.pug). <br/>
Stylesheet: [``cv.scss``](https://github.com/IllusiveBagel/CV/cv.scss).

<p align=center><img src="https://github.com/IllusiveBagel/CV/cv_screenshot.png"/></p>

While web-based resumes are increasingly popular, some employers still require a PDF document. PDF CVs can be created from Word or LaTeX templates, HTML/CSS layouts are more diverse and sometimes better looking.

In this example, we are converting [this project](https://github.com/mnjul/html-resume), a clean and beautiful HTML CV designed for printing by Min-Zhong "John" Lu (@mnjul on github).

Some highlights:

- Since the resume is composed of *item* sections with similar structures, we define an ``item`` mixin, which makes the final source much less verbose.
- Have a look at the SCSS file: we are stealing all the styling from the internet (Google fonts, Font-Awesome, and of course @mnjul's CSS stylesheet). We only write two lines of specific CSS to fix some glitches in Google Chrome
- It's nice that PDFs don't carry the weight of the CSS/JS libraries they use. The end result has a super-small size (30k)
