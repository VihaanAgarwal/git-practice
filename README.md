# Git Practice

## Small code changes

Article: [Small CLs — Google Engineering Practices](https://google.github.io/eng-practices/review/developer/small-cls.html)

The interesting part of this article is how the size of a code change affects the feedback it gets. A small change is easier to review carefully, so bugs are less likely to get missed. Google's advice to keep cleanup separate from bug fixes makes sense: renaming things while fixing a bug makes it harder to see what actually fixed it.

## Additional Comment from [Dan Yong](https://github.com/dansyong)

I think this was interesting to consider since I find myself commiting massive changes at a time because I often forget to pause. I also end up finishing a whole section of what I'm working on before commiting, but throughout that process, I also find bugs and fix a bunch of other things that I should've waited to address. I liked how they included a bit on how CLs should "include related test code." I think writing tests is something that I want to work on in the future.