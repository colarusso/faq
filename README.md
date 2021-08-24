# FAQ
A collection of QnAs to encode some of my professional know how. Everything is available through [Colarusso's FAQ "Bot"](https://colarusso.github.io/faq/), but some of the QnAs are moduarlized. You can access these component QnAs directly at:
- ~~[Coding The Law Syllabus "Bot"](https://colarusso.github.io/faq/ctl.html)~~
- ~~[LIT Lab Syllabus "Bot"](https://colarusso.github.io/faq/litlab.html)~~
- ~~[LIT Fellows Handbook "Bot"](https://colarusso.github.io/faq/litfellows.html)~~
- [Cats Stub](https://colarusso.github.io/faq/cats.html)

There's also a stand-alone cold call version for folks I don't know who aren't members of the Suffolk community. 
- [Cold Calls](https://colarusso.github.io/faq/coldcall.html)

These references are made using the `loadQnA()` function, defined in [sripts.js](https://github.com/colarusso/faq/blob/master/js_bin/scripts.js). Currently, this works only with `A` tags, and you must reference a QnA on the same domain as the one calling it. FWIW, the `A` call looks like this: 
`A:[javascript:loadQnA('https://colarusso.github.io/faq/cats.html',this.innerHTML)] Can I have cat videos?`
