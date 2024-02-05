# Combobox.dev

> An interactive book exploring the [combobox](https://www.w3.org/WAI/ARIA/apg/patterns/combobox/), exploring not only the W3C recommendations but implementation details from popular component libraries.

## Topics/Table of Contents

- Why I'm writing this
- Why you're reading this
- What a combobox can be
- Conundrums of a combobox
- What role="combobox" means
- How the simplest combox works: the `<select>` element
- What an autocomplete combobox looks like
- How HTML attributes connect everything together
- Building our own combobox
- What to look for in an open source combobox
- What we've learned about accesibility that lives in everything we build

## Preface

Even the simplest UI components bring surprising complexity, but there are two components in particular that epitomize this notion: the data grid and the combobox. I've built component implementations for both, but it was the combobox that I started with and also worked with most recently. Around 2010 I published a jQuery plugin called `mc-select`, which showed a multi-column dropdown when the input was opened. Then in 2023 my team published a combobox in our open source UI library, and it was my responsibility to communicate its value and usefulness to thousands of other developers.

Even after working in design systems since 2020 and teaching others full-time on how our compound components enabled UI components that worked very many different ways, I was still overwhelmed by possible permutations of how a combobox could be constructed. My understanding of accessibility in particular was challenged, and ultimately, greatly improved after a short time. I was joyful to find that there were so many lessons to share not just about building components in React -- or any library for that matter -- but in our old friend HTML.

I paired with developers on several teams and gave a workshop sharing how to use our compound component in a variety of ways. Several months after this experience, I find myself still _curious_ to explore this component pattern more deeply. This resource's main goal is to share what I've learned with you, but it's secret objective is to increase my own expertise. I expect I will learn along with you, as sharing lessons also means constructing a stronger foundation in the teacher's mind, and sometimes, making new discoveries along the way.

If you are reading this, I hope this will serve as a practical guide in composing user experiences encompassing the combobox, which will certainly happen many times. I also hope you will find that _just enough_ understanding of HTML and accessibility is _not enough_. Fortunately, you will also grow in your expertise to become invaluable to any team and product you build for.
