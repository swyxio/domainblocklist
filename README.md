# domainblocklist

domains that are mostly just automated reposts of content sites like CSS Tricks. (apparently this is called [spun content](https://twitter.com/monicalent/status/1344194349446393856?s=20) - [full context here](https://twitter.com/swyx/status/1344095187098685440))

you are welcome to contribute, swyx will vet!

```js
  let blocklist = [
    'http://gadgetsearcher.com',
    'https://pixallus.com',
    'http://programming.yourworldin90seconds.com',
    'https://programming.nichedomain.news',
    'https://marketingsolution.com.au',
    'https://programming.aplus-review.com',
    'https://digitalapexgroup.com',
    'https://technologynews.biz',
    'https://worldtech.news',
    'https://programming.webcloning.com',
    'https://www.sacramentowebdesigngroup.com',
    'https://htmltreehouse.com',
    'https://1dmx.org',
    'https://websitedesign-usa.com',
    'https://techupd.com',
    'https://fancyhints.com',
    'https://techalertnews.com',
    'https://buzzedly.com',
    'https://dztechno.com',
    'https://graphicdon.com',
    'https://www.newsgosspis.com',
    'http://www.digitasbuzz.in',
    'https://gotutoral.com',
    'https://wpguynews.com',
    'https://www.klobal.net',
    'http://www.webmastersgallery.com',
    'https://pikopong.com',
    'https://keren.link',
    'https://ntdln.com',
    'https://jczh.xyz',
    'https://pazukong.wordpress.com',
    'https://fullstackfeed.com',
    'https://thebrandingstore.net',
    'https://development-tools.net',
    'https://itdirectory.my',
    'https://www.sacramentowebdesigngroup.com',
    'https://engrmks.com.ng',
    'https://www.xspdf.com',
    'http://isokunoffice.club', 
    'http://dinezh.com', 
    'http://www.makemoneyupdaters.com', 
    'http://clicknow.in', 
    'http://nexstair.com', 
    'http://kovtonyuk.inf.ua', 
    'http://postheaven.net', 
    'http://www.legendstrivia.co.uk', 
    'http://squareblogs.net', 
    'http://www.fourthcity.net', 
    'http://www.engrmks.com.ng', 
    'http://711web.com', 
    'http://techupd.com', 
    'http://www.67nj.org', 
    'http://tipsxd.com', 
    'http://www.new.pixel-forge.ca', 
    'http://pixallus.com', 
    'http://wpnewshub.com', 
    'http://tecriter.wordpressarena.com', 
    'http://reddits.contractwebsites.com', 
    'http://wawas-kingdom.com', 
    'http://dztechno.com', 
    'http://wpguynews.com', 
    'http://www.digitasbuzz.in', 
    'http://watchfvsslive.co', 
    'http://gotutoral.com', 
    'http://techfans.co.uk', 
    'http://pikopong.com', 
    'http://marketingsolution.com.au',
    'https://reportwire.org',
    'https://www.codeificant.com',
    'https://tipsxd.com',
    'https://wpdesigns.live',
    'https://gigatechnews.com',
    'https://blogs.thebitx.com',
    'https://updatetech.xyz',
    'https://neoweb4u.com',
    'https://www.websjohn.com',
    'https://www.webhostpolice.com',
    'https://lzomedia.com',
    'https://jateng.co',
    'https://news.priviw.com',
    'https://movilgadget.com',
    'https://kitdeveloper.ru',
    '.thats.im',     // 'https://bdbloger.thats.im', 'https://mdsohel.thats.im/', 'https://sazelab.thats.im/'
    '.cu.ma', // 'https://bdbloger.cu.ma', 'https://mdsazel.cu.ma/'
    'https://reactjsexample.com',
    'https://dentedreality.com.au',
    'https://platoblockchain.net',
    'http://aayugcreation.com',
    'https://www.67nj.org',
    'https://wpnewshub.com',
    'https://codinghindi.in',
    'https://programmer.chimpymail.com',
    'https://sayed.work'
    // dont end any of these with  trailing slashes, as the DOM's URL.origin api doesnt give it to you so it will fail to filter
  ]
```

## Why do i need this

because if you do any sort of link monitoring this happens: https://webmention.io/api/mentions?page=0&per-page=20&target=https://www.swyx.io/svelte-sites-react-apps/

([example from Max Bock](https://twitter.com/mxbck/status/1379793156494012417?s=20))

<details>
<summary>
list of spam results
</summary>

```json
{
  "links": [
    {
      "source": "http://gadgetsearcher.com/its-always-year-zero/",
      "verified": true,
      "verified_date": "2020-12-19T17:10:39+00:00",
      "id": 954465,
      "private": false,
      "data": {
        "url": "http://gadgetsearcher.com/its-always-year-zero/",
        "name": null,
        "content": null,
        "published": null,
        "published_ts": null
      },
      "activity": {
        "type": "link",
        "sentence": "http://gadgetsearcher.com/its-always-year-zero/ posted '' linking to https://www.swyx.io/svelte-sites-react-apps/",
        "sentence_html": "<a href=\"http://gadgetsearcher.com/its-always-year-zero/\">someone</a> posted '' linking to <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">https://www.swyx.io/svelte-sites-react-apps/</a>"
      },
      "rels": {
        "canonical": "http://gadgetsearcher.com/its-always-year-zero/"
      },
      "target": "https://www.swyx.io/svelte-sites-react-apps/"
    },
    {
      "source": "https://pixallus.com/its-always-year-zero/",
      "verified": true,
      "verified_date": "2020-12-17T19:32:39+00:00",
      "id": 952083,
      "private": false,
      "data": {
        "url": "https://pixallus.com/its-always-year-zero/",
        "name": null,
        "content": null,
        "published": null,
        "published_ts": null
      },
      "activity": {
        "type": "link",
        "sentence": "https://pixallus.com/its-always-year-zero/ posted '' linking to https://www.swyx.io/svelte-sites-react-apps/",
        "sentence_html": "<a href=\"https://pixallus.com/its-always-year-zero/\">someone</a> posted '' linking to <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">https://www.swyx.io/svelte-sites-react-apps/</a>"
      },
      "target": "https://www.swyx.io/svelte-sites-react-apps/"
    },
    {
      "source": "http://programming.yourworldin90seconds.com/programming/its-always-year-zero/",
      "verified": true,
      "verified_date": "2020-12-17T16:51:22+00:00",
      "id": 952002,
      "private": false,
      "data": {
        "url": "http://programming.yourworldin90seconds.com/programming/its-always-year-zero/",
        "name": null,
        "content": "December 16, 2020\n\n             | <a href=\"http://programming.yourworldin90seconds.com/programming/its-always-year-zero/#respond\">No Comments</a>\n\n            \n        \n\t\t<img src=\"http://programming.yourworldin90seconds.com/wp-content/uploads/2020/12/npressfetimg-258.png\" alt=\"\" />        \n<p>In the short term, opinions about technology often follow a compressed form of <a href=\"https://signalvnoise.com/posts/2474-lavers-law-of-fashion\">Laver’s Law</a>:</p>\n<ul><li>Everything just before me was completely broken.</li>\n<li>Everything that comes after me is completely unnecessary.</li>\n<li>Everything I use right now is perfectly fine; stop changing things.</li>\n</ul><p>We tend to judge things based on where we started, our personal “Year Zeros.” But what’s “Year Zero” for us isn’t “Year Zero” for others. And in the fullness of time, the good ideas win out and hindsight judges them retrospectively obvious.</p>\n<p><span></span></p>\n<h3>\n<a href=\"http://programming.yourworldin90seconds.com/programming/its-always-year-zero/#in-2020-i-learned-that-its-always-year-zero-when-it-comes-to-building-websites\"></a><strong>In 2020, I learned that it’s always Year Zero when it comes to building websites.</strong>\n</h3>\n<p>In <a href=\"https://www.swyx.io/js-third-age/\">“The Third Age of JavaScript”</a> I speculated about a new wave of web developer tools enabled by the confluence of multiple trends:</p>\n<p>In this framing, 2020 was Year Zero of the Third Age. But what happens in 2021? 2022? What makes me so sure that 2020 was some clear dividing line?</p>\n<p>Nothing. There’s always room for innovation. New libraries, new frameworks, new build tools, even new languages. Yes, most of these will go nowhere, and yes, <a href=\"https://twitter.com/swyx/status/1260022224351723521\">we swing back and forth a lot</a>. But it’s the people who believe that web development isn’t done yet that make the future happen. Not those who play armchair quarterback, nor those who <a href=\"https://www.goodreads.com/quotes/42814-you-are-not-superior-just-because-you-see-the-world\">see everything in an odious light</a>. I’d rather side with the people who believe it can be Year Zero than the people who believe Year Zero has passed.</p>\n<img width=\"1024\" height=\"512\" src=\"https://i0.wp.com/css-tricks.com/wp-content/uploads/2020/12/year-zero.png?resize=1024%2C512&amp;ssl=1\" alt=\"\" /><img width=\"1024\" height=\"512\" src=\"https://i0.wp.com/css-tricks.com/wp-content/uploads/2020/12/year-zero.png?resize=1024%2C512&amp;ssl=1\" alt=\"\" /><p>“Year Zero” to me also means keeping a beginner’s mindset and constantly re-examining what I think I know. When I first learned web development, I was told that React was the best framework to build sites, <a href=\"https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0\">Presentational and Container Components</a> was the right way to do React, and that <a href=\"http://getbem.com/introduction/\">BEM</a> was the right way to structure CSS. As a newcomer at Year Zero, I assumed that any discomfort I felt with the orthodoxy was my fault. Flash forward to this year and and my most popular articles are about <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">Svelte</a> and <a href=\"https://dev.to/swyx/why-tailwind-css-2o8f\">Tailwind</a> questioning that conventional wisdom. No one gave me permission to do that. It took <em>years</em> to learn that I could dare to disagree with my mentors and give that permission to myself.</p>\n<p>I feel this most of all for the newcomers to our industry. Every year there are about <a href=\"https://en.wikipedia.org/wiki/FreeCodeCamp#Reception\">~350k freeCodeCamp</a>, <a href=\"https://nces.ed.gov/programs/digest/d19/tables/dt19_322.10.asp?current=yes\">~100k university</a> and <a href=\"https://careerkarma.com/blog/bootcamp-market-report-2020/\">~35k bootcamp</a> grads. It’s Year Zero for them. Or how about our end users — the millions of non-developers who every year have more of their world <a href=\"https://a16z.com/2011/08/20/why-software-is-eating-the-world/\">consumed</a> by the buggy, slow software we make? It’s Year Zero for them.</p>\n<p>It’s also Year Zero for web development in the broader arc of human history. The web is only 30 years old. We’ve had over 300 years refining modern physics, and yet there are still things we know we don’t know. It is <em>such</em> early days for the web.</p>\n<p>Let’s stop pretending what we know is absolute truth and that what we have is the end state of things. <strong>It’s Always Year Zero.</strong></p>\n\n                \n            <a href=\"http://programming.yourworldin90seconds.com/category/programming/\" title=\"View all posts in Programming\">Programming</a>",
        "published": null,
        "published_ts": null
      },
      "activity": {
        "type": "link",
        "sentence": "http://programming.yourworldin90seconds.com/programming/its-always-year-zero/ posted 'December 16, 2020               | No Comments                        \t\t         ...' linking to https://www.swyx.io/svelte-sites-react-apps/",
        "sentence_html": "<a href=\"http://programming.yourworldin90seconds.com/programming/its-always-year-zero/\">someone</a> posted 'December 16, 2020               | No Comments                        \t\t         ...' linking to <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">https://www.swyx.io/svelte-sites-react-apps/</a>"
      },
      "rels": {
        "canonical": "http://programming.yourworldin90seconds.com/programming/its-always-year-zero/"
      },
      "target": "https://www.swyx.io/svelte-sites-react-apps/"
    },
    {
      "source": "https://programming.nichedomain.news/2020/12/16/its-always-year-zero/",
      "verified": true,
      "verified_date": "2020-12-17T15:08:59+00:00",
      "id": 951895,
      "private": false,
      "data": {
        "url": "https://programming.nichedomain.news/2020/12/16/its-always-year-zero/",
        "name": null,
        "content": "December 16, 2020\n\n             | <a href=\"https://programming.nichedomain.news/2020/12/16/its-always-year-zero/#respond\">No Comments</a>\n\n            \n        \n\t\t<img src=\"https://programming.nichedomain.news/wp-content/uploads/2020/12/npressfetimg-429.png\" alt=\"\" />        \n<p>In the short term, opinions about technology often follow a compressed form of <a href=\"https://signalvnoise.com/posts/2474-lavers-law-of-fashion\">Laver’s Law</a>:</p>\n<ul><li>Everything just before me was completely broken.</li>\n<li>Everything that comes after me is completely unnecessary.</li>\n<li>Everything I use right now is perfectly fine; stop changing things.</li>\n</ul><p>We tend to judge things based on where we started, our personal “Year Zeros.” But what’s “Year Zero” for us isn’t “Year Zero” for others. And in the fullness of time, the good ideas win out and hindsight judges them retrospectively obvious.</p>\n<p><span></span></p>\n<h3>\n<a href=\"https://programming.nichedomain.news/2020/12/16/its-always-year-zero/#in-2020-i-learned-that-its-always-year-zero-when-it-comes-to-building-websites\"></a><strong>In 2020, I learned that it’s always Year Zero when it comes to building websites.</strong>\n</h3>\n<p>In <a href=\"https://www.swyx.io/js-third-age/\">“The Third Age of JavaScript”</a> I speculated about a new wave of web developer tools enabled by the confluence of multiple trends:</p>\n<p>In this framing, 2020 was Year Zero of the Third Age. But what happens in 2021? 2022? What makes me so sure that 2020 was some clear dividing line?</p>\n<p>Nothing. There’s always room for innovation. New libraries, new frameworks, new build tools, even new languages. Yes, most of these will go nowhere, and yes, <a href=\"https://twitter.com/swyx/status/1260022224351723521\">we swing back and forth a lot</a>. But it’s the people who believe that web development isn’t done yet that make the future happen. Not those who play armchair quarterback, nor those who <a href=\"https://www.goodreads.com/quotes/42814-you-are-not-superior-just-because-you-see-the-world\">see everything in an odious light</a>. I’d rather side with the people who believe it can be Year Zero than the people who believe Year Zero has passed.</p>\n<img width=\"1024\" height=\"512\" src=\"https://i0.wp.com/css-tricks.com/wp-content/uploads/2020/12/year-zero.png?resize=1024%2C512&amp;ssl=1\" alt=\"\" /><img width=\"1024\" height=\"512\" src=\"https://i0.wp.com/css-tricks.com/wp-content/uploads/2020/12/year-zero.png?resize=1024%2C512&amp;ssl=1\" alt=\"\" /><p>“Year Zero” to me also means keeping a beginner’s mindset and constantly re-examining what I think I know. When I first learned web development, I was told that React was the best framework to build sites, <a href=\"https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0\">Presentational and Container Components</a> was the right way to do React, and that <a href=\"http://getbem.com/introduction/\">BEM</a> was the right way to structure CSS. As a newcomer at Year Zero, I assumed that any discomfort I felt with the orthodoxy was my fault. Flash forward to this year and and my most popular articles are about <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">Svelte</a> and <a href=\"https://dev.to/swyx/why-tailwind-css-2o8f\">Tailwind</a> questioning that conventional wisdom. No one gave me permission to do that. It took <em>years</em> to learn that I could dare to disagree with my mentors and give that permission to myself.</p>\n<p>I feel this most of all for the newcomers to our industry. Every year there are about <a href=\"https://en.wikipedia.org/wiki/FreeCodeCamp#Reception\">~350k freeCodeCamp</a>, <a href=\"https://nces.ed.gov/programs/digest/d19/tables/dt19_322.10.asp?current=yes\">~100k university</a> and <a href=\"https://careerkarma.com/blog/bootcamp-market-report-2020/\">~35k bootcamp</a> grads. It’s Year Zero for them. Or how about our end users — the millions of non-developers who every year have more of their world <a href=\"https://a16z.com/2011/08/20/why-software-is-eating-the-world/\">consumed</a> by the buggy, slow software we make? It’s Year Zero for them.</p>\n<p>It’s also Year Zero for web development in the broader arc of human history. The web is only 30 years old. We’ve had over 300 years refining modern physics, and yet there are still things we know we don’t know. It is <em>such</em> early days for the web.</p>\n<p>Let’s stop pretending what we know is absolute truth and that what we have is the end state of things. <strong>It’s Always Year Zero.</strong></p>\n\n                \n            <a href=\"https://programming.nichedomain.news/category/programming/\" title=\"View all posts in Programming\">Programming</a>",
        "published": null,
        "published_ts": null
      },
      "activity": {
        "type": "link",
        "sentence": "https://programming.nichedomain.news/2020/12/16/its-always-year-zero/ posted 'December 16, 2020               | No Comments                        \t\t         ...' linking to https://www.swyx.io/svelte-sites-react-apps/",
        "sentence_html": "<a href=\"https://programming.nichedomain.news/2020/12/16/its-always-year-zero/\">someone</a> posted 'December 16, 2020               | No Comments                        \t\t         ...' linking to <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">https://www.swyx.io/svelte-sites-react-apps/</a>"
      },
      "rels": {
        "canonical": "https://programming.nichedomain.news/2020/12/16/its-always-year-zero/"
      },
      "target": "https://www.swyx.io/svelte-sites-react-apps/"
    },
    {
      "source": "https://marketingsolution.com.au/its-always-year-zero/",
      "verified": true,
      "verified_date": "2020-12-17T07:23:59+00:00",
      "id": 951584,
      "private": false,
      "data": {
        "url": "https://marketingsolution.com.au/its-always-year-zero/",
        "name": null,
        "content": "<h1>It’s Always Year Zero</h1>\n<ul><li>December 17, 2020</li>\n<li><a href=\"https://marketingsolution.com.au/category/web-development/\">Web Development</a></li>\n</ul>\n\n\n\n\n\n\nNo Comments\n\n\n\n\n\n\n\n\n\n\n\n\n\n<p>In the short term, opinions about technology often follow a compressed form of <a href=\"https://signalvnoise.com/posts/2474-lavers-law-of-fashion\">Laver’s Law</a>:</p>\n<ul><li>Everything just before me was completely broken.</li>\n<li>Everything that comes after me is completely unnecessary.</li>\n<li>Everything I use right now is perfectly fine; stop changing things.</li>\n</ul><p>We tend to judge things based on where we started, our personal “Year Zeros.” But what’s “Year Zero” for us isn’t “Year Zero” for others. And in the fullness of time, the good ideas win out and hindsight judges them retrospectively obvious.</p>\n<p><span></span></p>\n<h3><strong>In 2020, I learned that it’s always Year Zero when it comes to building websites.</strong></h3>\n<p>In <a href=\"https://www.swyx.io/js-third-age/\">“The Third Age of JavaScript”</a> I speculated about a new wave of web developer tools enabled by the confluence of multiple trends:</p>\n<ul><li>The end of “JavaScript tools in JavaScript” (and the rise of TypeScript/Rust/Go)</li>\n<li>\n<a href=\"https://www.swyx.io/writing/collapsing-layers/\">Collapsing layers</a> of tooling</li>\n<li>Neo-isomorphic JavaScript (make it <em>easy</em> to move JavaScript between client/server/build contexts)</li>\n<li>ES Modules everywhere</li>\n<li><a href=\"https://www.swyx.io/writing/ie11-eol/\">The long, slow end of life of Internet Explorer 11</a></li>\n</ul><p>In this framing, 2020 was Year Zero of the Third Age. But what happens in 2021? 2022? What makes me so sure that 2020 was some clear dividing line?</p>\n<p>Nothing. There’s always room for innovation. New libraries, new frameworks, new build tools, even new languages. Yes, most of these will go nowhere, and yes, <a href=\"https://twitter.com/swyx/status/1260022224351723521\">we swing back and forth a lot</a>. But it’s the people who believe that web development isn’t done yet that make the future happen. Not those who play armchair quarterback, nor those who <a href=\"https://www.goodreads.com/quotes/42814-you-are-not-superior-just-because-you-see-the-world\">see everything in an odious light</a>. I’d rather side with the people who believe it can be Year Zero than the people who believe Year Zero has passed.</p>\n<img width=\"1024\" height=\"512\" src=\"https://i0.wp.com/css-tricks.com/wp-content/uploads/2020/12/year-zero.png?resize=1024%2C512&amp;ssl=1\" alt=\"\" /><p>“Year Zero” to me also means keeping a beginner’s mindset and constantly re-examining what I think I know. When I first learned web development, I was told that React was the best framework to build sites, <a href=\"https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0\">Presentational and Container Components</a> was the right way to do React, and that <a href=\"http://getbem.com/introduction/\">BEM</a> was the right way to structure CSS. As a newcomer at Year Zero, I assumed that any discomfort I felt with the orthodoxy was my fault. Flash forward to this year and and my most popular articles are about <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">Svelte</a> and <a href=\"https://dev.to/swyx/why-tailwind-css-2o8f\">Tailwind</a> questioning that conventional wisdom. No one gave me permission to do that. It took <em>years</em> to learn that I could dare to disagree with my mentors and give that permission to myself.</p>\n<p>I feel this most of all for the newcomers to our industry. Every year there are about <a href=\"https://en.wikipedia.org/wiki/FreeCodeCamp#Reception\">~350k freeCodeCamp</a>, <a href=\"https://nces.ed.gov/programs/digest/d19/tables/dt19_322.10.asp?current=yes\">~100k university</a> and <a href=\"https://careerkarma.com/blog/bootcamp-market-report-2020/\">~35k bootcamp</a> grads. It’s Year Zero for them. Or how about our end users — the millions of non-developers who every year have more of their world <a href=\"https://a16z.com/2011/08/20/why-software-is-eating-the-world/\">consumed</a> by the buggy, slow software we make? It’s Year Zero for them.</p>\n<p>It’s also Year Zero for web development in the broader arc of human history. The web is only 30 years old. We’ve had over 300 years refining modern physics, and yet there are still things we know we don’t know. It is <em>such</em> early days for the web.</p>\n<p>Let’s stop pretending what we know is absolute truth and that what we have is the end state of things. <strong>It’s Always Year Zero.</strong></p>\n<p>The post <a href=\"https://css-tricks.com/its-always-year-zero/\">It’s Always Year Zero</a> appeared first on <a href=\"https://css-tricks.com/\">CSS-Tricks</a>.</p>\n<p>You can support CSS-Tricks by being an <a href=\"https://css-tricks.com/product/mvp-supporter/\">MVP Supporter</a>.</p>\n\n\n\n\n\n\n<ul><li> <a href=\"https://marketingsolution.com.au/author/jamie/\">Jamie Scott</a>\n</li></ul>\n<p></p>\n\n\n\n\n\n\n\n\n<h2>About us and this blog</h2>\n<p>We are a digital marketing company with a focus on helping our customers achieve great results across several key areas.</p>\n\n <a href=\"https://marketingsolution.com.au/about/\"> <span></span> <span>Learn more about us</span> </a>\n\n\n\n\n\n\n <span></span>\n\n\n<h4>Request a free quote</h4>\n<p>We offer professional SEO services that help websites increase their organic search score drastically in order to compete for the highest rankings even when it comes to highly competitive keywords.</p>\n <a href=\"https://marketingsolution.com.au/contact-us/\"> <span></span> <span> Contact now </span> </a>\n\n\n\n\n\n\n\n<h2>Subscribe to our newsletter!</h2>\n  Notice: JavaScript is required for this content.\n  \n\n\n\n\n\n\n\n\n\n\n\n\n\n<h2>More from our blog</h2> <span><a href=\"https://marketingsolution.com.au/its-always-year-zero/#\">See all posts</a></span>\n\n\n\n\n\n <a href=\"https://marketingsolution.com.au/automattic-awarded-coveted-spot-on-forbes-cloud-100-list/\"><img src=\"https://marketingsolution.com.au/wp-content/uploads/a8c_product_logos-HrNEMN-400x330.png\" alt=\"\" title=\"Automattic Awarded Coveted Spot on Forbes Cloud 100 List\" /></a>\n\n\n<h2><a href=\"https://marketingsolution.com.au/automattic-awarded-coveted-spot-on-forbes-cloud-100-list/\">Automattic Awarded Coveted Spot on Forbes Cloud 100 List</a></h2>\n Automattic — a leader in publishing and e-commerce software and the parent…\n <a href=\"https://marketingsolution.com.au/automattic-awarded-coveted-spot-on-forbes-cloud-100-list/\"> <span></span> Continue reading </a>\n\n\n\n\n <a href=\"https://marketingsolution.com.au/introducing-patterns-prebuilt-blocks-for-beautifully-designed-websites/\"><img src=\"https://marketingsolution.com.au/wp-content/uploads/wordpress-gutenberg-block-patterns-KBLh6Z-400x330.png\" alt=\"\" title=\"Introducing Patterns: Prebuilt Blocks for Beautifully Designed Websites\" /></a>\n\n\n<h2><a href=\"https://marketingsolution.com.au/introducing-patterns-prebuilt-blocks-for-beautifully-designed-websites/\">Introducing Patterns: Prebuilt Blocks for Beautifully Designed Websites</a></h2>\n The WordPress Editor is a powerful tool that can help bring your…\n <a href=\"https://marketingsolution.com.au/introducing-patterns-prebuilt-blocks-for-beautifully-designed-websites/\"> <span></span> Continue reading </a>\n\n\n\n\n <a href=\"https://marketingsolution.com.au/expert-advice-how-to-improve-remote-education-collaboration/\"><img src=\"https://marketingsolution.com.au/wp-content/uploads/header-3-pB3xIZ-400x330.jpeg\" alt=\"\" title=\"Expert Advice: How to Improve Remote Education Collaboration\" /></a>\n\n\n<h2><a href=\"https://marketingsolution.com.au/expert-advice-how-to-improve-remote-education-collaboration/\">Expert Advice: How to Improve Remote Education Collaboration</a></h2>\n As we’re witnessing with schools and learning communities around the world, education…\n <a href=\"https://marketingsolution.com.au/expert-advice-how-to-improve-remote-education-collaboration/\"> <span></span> Continue reading </a>\n\n\n\n\n <a href=\"https://marketingsolution.com.au/the-spearhead-theme-a-minimal-design-and-clean-slate-for-all-content-creators-2/\"><img src=\"https://marketingsolution.com.au/wp-content/uploads/spearhead-light-2-61adq3-400x330.png\" alt=\"\" title=\"The Spearhead Theme: A Minimal Design and Clean Slate for All Content Creators\" /></a>\n\n\n<h2><a href=\"https://marketingsolution.com.au/the-spearhead-theme-a-minimal-design-and-clean-slate-for-all-content-creators-2/\">The Spearhead Theme: A Minimal Design and Clean Slate for All Content Creators</a></h2>\n When AngelList and Venture Hacks co-founder Babak Nivi came to us and…\n <a href=\"https://marketingsolution.com.au/the-spearhead-theme-a-minimal-design-and-clean-slate-for-all-content-creators-2/\"> <span></span> Continue reading </a>\n\n\n\n\n <a href=\"https://marketingsolution.com.au/learn-from-the-experts-create-a-successful-blog-with-our-brand-new-course-2/\"><img src=\"https://marketingsolution.com.au/wp-content/uploads/courses-feature-image-3402x-zuyaTq-scaled-400x330.jpeg\" alt=\"\" title=\"Learn from the experts: Create a successful blog with our brand new course\" /></a>\n\n\n<h2><a href=\"https://marketingsolution.com.au/learn-from-the-experts-create-a-successful-blog-with-our-brand-new-course-2/\">Learn from the experts: Create a successful blog with our brand new course</a></h2>\n WordPress.com is excited to announce our newest offering: a course just for…\n <a href=\"https://marketingsolution.com.au/learn-from-the-experts-create-a-successful-blog-with-our-brand-new-course-2/\"> <span></span> Continue reading </a>\n\n\n\n\n <a href=\"https://marketingsolution.com.au/join-us-in-honoring-transgender-day-of-remembrance-2/\"><img src=\"https://marketingsolution.com.au/wp-content/uploads/remembrance-transgender-2020-1-jIPRJJ-scaled-400x330.jpeg\" alt=\"\" title=\"Join Us in Honoring Transgender Day of Remembrance\" /></a>\n\n\n<h2><a href=\"https://marketingsolution.com.au/join-us-in-honoring-transgender-day-of-remembrance-2/\">Join Us in Honoring Transgender Day of Remembrance</a></h2>\n Today, November 20th, people around the world pause to bear witness to…\n <a href=\"https://marketingsolution.com.au/join-us-in-honoring-transgender-day-of-remembrance-2/\"> <span></span> Continue reading </a>\n\n\n\n\n <a href=\"https://marketingsolution.com.au/run-with-us-join-the-2020-wwwp5k-movement-2/\"><img src=\"https://marketingsolution.com.au/wp-content/uploads/running-feet-tJjg1q-400x330.jpeg\" alt=\"\" title=\"Run With Us! Join the 2020 wwwp5K Movement\" /></a>\n\n\n<h2><a href=\"https://marketingsolution.com.au/run-with-us-join-the-2020-wwwp5k-movement-2/\">Run With Us! Join the 2020 wwwp5K Movement</a></h2>\n If you’re like us, you’re eager to send 2020 off to the…\n <a href=\"https://marketingsolution.com.au/run-with-us-join-the-2020-wwwp5k-movement-2/\"> <span></span> Continue reading </a>\n\n\n\n\n <a href=\"https://marketingsolution.com.au/recommended-reads-for-international-day-of-disabled-persons-2/\"><img src=\"https://marketingsolution.com.au/wp-content/uploads/disabledandhere-047-1-URuzys-scaled-400x330.jpeg\" alt=\"\" title=\"Recommended Reads for International Day of Disabled Persons\" /></a>\n\n\n<h2><a href=\"https://marketingsolution.com.au/recommended-reads-for-international-day-of-disabled-persons-2/\">Recommended Reads for International Day of Disabled Persons</a></h2>\n WordPress.com, as my colleague Anne recently wrote, continues to be a space…\n <a href=\"https://marketingsolution.com.au/recommended-reads-for-international-day-of-disabled-persons-2/\"> <span></span> Continue reading </a>\n\n\n\n\n\n\n\n\n\n\n\n\n <a href=\"https://marketingsolution.com.au/old-is-solid-new-gets-talked-about/\"> <span></span> <span>Prev. Post</span> </a>\n\n <a href=\"https://marketingsolution.com.au\"> <span></span> <span>All Posts</span> </a>\n\n <a href=\"https://marketingsolution.com.au/how-redux-reducers-work/\"> <span></span> <span>Next Post</span> </a>\n\n\n<ul><li><span title=\"Total:\"><span>Total: </span><span>0</span></span></li>\n<li> <a href=\"https://www.facebook.com/sharer/sharer.php?u=https://marketingsolution.com.au/its-always-year-zero/&amp;t=It%E2%80%99s+Always+Year+Zero\" title=\"\"><span></span><span><span>0</span></span></a>\n</li>\n<li> <a href=\"https://marketingsolution.com.au/its-always-year-zero/#\" title=\"\"><span></span><span><span>0</span></span></a>\n</li>\n<li> <a href=\"https://plus.google.com/share?url=https://marketingsolution.com.au/its-always-year-zero/\" title=\"\"><span></span><span><span>0</span></span></a>\n</li>\n<li> <a href=\"https://marketingsolution.com.au/its-always-year-zero/#\" title=\"\"><span></span><span><span>0</span></span></a>\n</li>\n<li> <a href=\"https://www.linkedin.com/shareArticle?mini=true&amp;ro=true&amp;trk=EasySocialShareButtons&amp;title=It%E2%80%99s+Always+Year+Zero&amp;url=https://marketingsolution.com.au/its-always-year-zero/\" title=\"\"><span></span><span><span>0</span></span></a>\n</li>\n</ul>\n\n\n\n\n\n\nNo Comments\n\n\n\n\n\n\n\n<h3><span>Recent Posts</span></h3>\n<ul><li> <a href=\"https://marketingsolution.com.au/automattic-awarded-coveted-spot-on-forbes-cloud-100-list/\">Automattic Awarded Coveted Spot on Forbes Cloud 100 List</a> <span>December 17, 2020</span>\n</li>\n<li> <a href=\"https://marketingsolution.com.au/introducing-patterns-prebuilt-blocks-for-beautifully-designed-websites/\">Introducing Patterns: Prebuilt Blocks for Beautifully Designed Websites</a> <span>December 17, 2020</span>\n</li>\n<li> <a href=\"https://marketingsolution.com.au/expert-advice-how-to-improve-remote-education-collaboration/\">Expert Advice: How to Improve Remote Education Collaboration</a> <span>December 17, 2020</span>\n</li>\n</ul>\n\n<h3><span>All Website Tags</span></h3>\n\n<a href=\"https://marketingsolution.com.au/tag/absolute/\" style=\"font-size:8pt;\">absolute</a> <a href=\"https://marketingsolution.com.au/tag/all/\" style=\"font-size:8pt;\">all</a> <a href=\"https://marketingsolution.com.au/tag/anchor/\" style=\"font-size:8pt;\">anchor</a> <a href=\"https://marketingsolution.com.au/tag/any/\" style=\"font-size:8pt;\">any</a> <a href=\"https://marketingsolution.com.au/tag/back-links/\" style=\"font-size:8pt;\">back-links</a> <a href=\"https://marketingsolution.com.au/tag/branding/\" style=\"font-size:8pt;\">branding</a> <a href=\"https://marketingsolution.com.au/tag/can/\" style=\"font-size:8pt;\">can</a> <a href=\"https://marketingsolution.com.au/tag/company/\" style=\"font-size:8pt;\">company</a> <a href=\"https://marketingsolution.com.au/tag/discounts/\" style=\"font-size:8pt;\">discounts</a> <a href=\"https://marketingsolution.com.au/tag/engine/\" style=\"font-size:22pt;\">engine</a> <a href=\"https://marketingsolution.com.au/tag/google/\" style=\"font-size:8pt;\">google</a> <a href=\"https://marketingsolution.com.au/tag/hurt/\" style=\"font-size:8pt;\">hurt</a> <a href=\"https://marketingsolution.com.au/tag/images/\" style=\"font-size:8pt;\">images</a> <a href=\"https://marketingsolution.com.au/tag/importance/\" style=\"font-size:8pt;\">importance</a> <a href=\"https://marketingsolution.com.au/tag/in/\" style=\"font-size:8pt;\">in</a> <a href=\"https://marketingsolution.com.au/tag/inbound/\" style=\"font-size:8pt;\">inbound</a> <a href=\"https://marketingsolution.com.au/tag/incorporation/\" style=\"font-size:8pt;\">incorporation</a> <a href=\"https://marketingsolution.com.au/tag/linking/\" style=\"font-size:8pt;\">linking</a> <a href=\"https://marketingsolution.com.au/tag/links/\" style=\"font-size:22pt;\">links</a> <a href=\"https://marketingsolution.com.au/tag/my/\" style=\"font-size:8pt;\">my</a> <a href=\"https://marketingsolution.com.au/tag/of/\" style=\"font-size:8pt;\">of</a> <a href=\"https://marketingsolution.com.au/tag/optimization/\" style=\"font-size:8pt;\">optimization</a> <a href=\"https://marketingsolution.com.au/tag/ranking/\" style=\"font-size:8pt;\">ranking</a> <a href=\"https://marketingsolution.com.au/tag/reciprocal/\" style=\"font-size:8pt;\">reciprocal</a> <a href=\"https://marketingsolution.com.au/tag/relative/\" style=\"font-size:8pt;\">relative</a> <a href=\"https://marketingsolution.com.au/tag/search/\" style=\"font-size:22pt;\">search</a> <a href=\"https://marketingsolution.com.au/tag/search-engine-submission/\" style=\"font-size:8pt;\">search engine submission</a> <a href=\"https://marketingsolution.com.au/tag/seo/\" style=\"font-size:8pt;\">seo</a> <a href=\"https://marketingsolution.com.au/tag/strategic/\" style=\"font-size:8pt;\">strategic</a> <a href=\"https://marketingsolution.com.au/tag/submission/\" style=\"font-size:8pt;\">submission</a> <a href=\"https://marketingsolution.com.au/tag/text/\" style=\"font-size:8pt;\">text</a> <a href=\"https://marketingsolution.com.au/tag/the/\" style=\"font-size:8pt;\">the</a> <a href=\"https://marketingsolution.com.au/tag/vs/\" style=\"font-size:8pt;\">vs</a>\n\n\n\n\n\n\n\n<h3>Leave a Comment <a href=\"https://marketingsolution.com.au/its-always-year-zero/#respond\">cancel</a>\n</h3>\n\n\n\n\n\n<p>Save my name, email, and website in this browser for the next time I comment.</p>\n\n<p></p>",
        "published": null,
        "published_ts": null
      },
      "activity": {
        "type": "link",
        "sentence": "https://marketingsolution.com.au/its-always-year-zero/ posted 'It’s Always Year Zero    December 17, 2020   Web Development          No Comment...' linking to https://www.swyx.io/svelte-sites-react-apps/",
        "sentence_html": "<a href=\"https://marketingsolution.com.au/its-always-year-zero/\">someone</a> posted 'It’s Always Year Zero    December 17, 2020   Web Development          No Comment...' linking to <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">https://www.swyx.io/svelte-sites-react-apps/</a>"
      },
      "rels": {
        "canonical": "https://marketingsolution.com.au/its-always-year-zero/"
      },
      "target": "https://www.swyx.io/svelte-sites-react-apps/"
    },
    {
      "source": "https://programming.aplus-review.com/2020/12/16/its-always-year-zero/",
      "verified": true,
      "verified_date": "2020-12-17T00:11:10+00:00",
      "id": 951274,
      "private": false,
      "data": {
        "url": "https://programming.aplus-review.com/2020/12/16/its-always-year-zero/",
        "name": null,
        "content": "December 16, 2020\n\n             | <a href=\"https://programming.aplus-review.com/2020/12/16/its-always-year-zero/#respond\">No Comments</a>\n\n            \n        \n\t\t<img src=\"https://programming.aplus-review.com/wp-content/uploads/2020/12/npressfetimg-306.png\" alt=\"\" />        \n<p>In the short term, opinions about technology often follow a compressed form of <a href=\"https://signalvnoise.com/posts/2474-lavers-law-of-fashion\">Laver’s Law</a>:</p>\n<ul><li>Everything just before me was completely broken.</li>\n<li>Everything that comes after me is completely unnecessary.</li>\n<li>Everything I use right now is perfectly fine; stop changing things.</li>\n</ul><p>We tend to judge things based on where we started, our personal “Year Zeros.” But what’s “Year Zero” for us isn’t “Year Zero” for others. And in the fullness of time, the good ideas win out and hindsight judges them retrospectively obvious.</p>\n<p><span></span></p>\n<h3>\n<a href=\"https://programming.aplus-review.com/2020/12/16/its-always-year-zero/#in-2020-i-learned-that-its-always-year-zero-when-it-comes-to-building-websites\"></a><strong>In 2020, I learned that it’s always Year Zero when it comes to building websites.</strong><br /></h3>\n<p>In <a href=\"https://www.swyx.io/js-third-age/\">“The Third Age of JavaScript”</a> I speculated about a new wave of web developer tools enabled by the confluence of multiple trends:</p>\n<p>In this framing, 2020 was Year Zero of the Third Age. But what happens in 2021? 2022? What makes me so sure that 2020 was some clear dividing line?</p>\n<p>Nothing. There’s always room for innovation. New libraries, new frameworks, new build tools, even new languages. Yes, most of these will go nowhere, and yes, <a href=\"https://twitter.com/swyx/status/1260022224351723521\">we swing back and forth a lot</a>. But it’s the people who believe that web development isn’t done yet that make the future happen. Not those who play armchair quarterback, nor those who <a href=\"https://www.goodreads.com/quotes/42814-you-are-not-superior-just-because-you-see-the-world\">see everything in an odious light</a>. I’d rather side with the people who believe it can be Year Zero than the people who believe Year Zero has passed.</p>\n<img width=\"1024\" height=\"512\" src=\"https://i0.wp.com/css-tricks.com/wp-content/uploads/2020/12/year-zero.png?resize=1024%2C512&amp;ssl=1\" alt=\"\" /><img width=\"1024\" height=\"512\" src=\"https://i0.wp.com/css-tricks.com/wp-content/uploads/2020/12/year-zero.png?resize=1024%2C512&amp;ssl=1\" alt=\"\" /><p>“Year Zero” to me also means keeping a beginner’s mindset and constantly re-examining what I think I know. When I first learned web development, I was told that React was the best framework to build sites, <a href=\"https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0\">Presentational and Container Components</a> was the right way to do React, and that <a href=\"http://getbem.com/introduction/\">BEM</a> was the right way to structure CSS. As a newcomer at Year Zero, I assumed that any discomfort I felt with the orthodoxy was my fault. Flash forward to this year and and my most popular articles are about <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">Svelte</a> and <a href=\"https://dev.to/swyx/why-tailwind-css-2o8f\">Tailwind</a> questioning that conventional wisdom. No one gave me permission to do that. It took <em>years</em> to learn that I could dare to disagree with my mentors and give that permission to myself.</p>\n<p>I feel this most of all for the newcomers to our industry. Every year there are about <a href=\"https://en.wikipedia.org/wiki/FreeCodeCamp#Reception\">~350k freeCodeCamp</a>, <a href=\"https://nces.ed.gov/programs/digest/d19/tables/dt19_322.10.asp?current=yes\">~100k university</a> and <a href=\"https://careerkarma.com/blog/bootcamp-market-report-2020/\">~35k bootcamp</a> grads. It’s Year Zero for them. Or how about our end users — the millions of non-developers who every year have more of their world <a href=\"https://a16z.com/2011/08/20/why-software-is-eating-the-world/\">consumed</a> by the buggy, slow software we make? It’s Year Zero for them.</p>\n<p>It’s also Year Zero for web development in the broader arc of human history. The web is only 30 years old. We’ve had over 300 years refining modern physics, and yet there are still things we know we don’t know. It is <em>such</em> early days for the web.</p>\n<p>Let’s stop pretending what we know is absolute truth and that what we have is the end state of things. <strong>It’s Always Year Zero.</strong></p>\n\n                \n            <a href=\"https://programming.aplus-review.com/category/programming/\" title=\"View all posts in Programming\">Programming</a>",
        "published": null,
        "published_ts": null
      },
      "activity": {
        "type": "link",
        "sentence": "https://programming.aplus-review.com/2020/12/16/its-always-year-zero/ posted 'December 16, 2020               | No Comments                        \t\t         ...' linking to https://www.swyx.io/svelte-sites-react-apps/",
        "sentence_html": "<a href=\"https://programming.aplus-review.com/2020/12/16/its-always-year-zero/\">someone</a> posted 'December 16, 2020               | No Comments                        \t\t         ...' linking to <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">https://www.swyx.io/svelte-sites-react-apps/</a>"
      },
      "rels": {
        "canonical": "https://programming.aplus-review.com/2020/12/16/its-always-year-zero/"
      },
      "target": "https://www.swyx.io/svelte-sites-react-apps/"
    },
    {
      "source": "https://digitalapexgroup.com/its-always-year-zero/",
      "verified": true,
      "verified_date": "2020-12-16T22:08:27+00:00",
      "id": 951232,
      "private": false,
      "data": {
        "url": "https://digitalapexgroup.com/its-always-year-zero/",
        "name": null,
        "content": null,
        "published": null,
        "published_ts": null
      },
      "activity": {
        "type": "link",
        "sentence": "https://digitalapexgroup.com/its-always-year-zero/ posted '' linking to https://www.swyx.io/svelte-sites-react-apps/",
        "sentence_html": "<a href=\"https://digitalapexgroup.com/its-always-year-zero/\">someone</a> posted '' linking to <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">https://www.swyx.io/svelte-sites-react-apps/</a>"
      },
      "target": "https://www.swyx.io/svelte-sites-react-apps/"
    },
    {
      "source": "https://technologynews.biz/its-always-year-zero-css-tricks/",
      "verified": true,
      "verified_date": "2020-12-16T11:32:38+00:00",
      "id": 950771,
      "private": false,
      "data": {
        "url": "https://technologynews.biz/its-always-year-zero-css-tricks/",
        "name": null,
        "content": null,
        "published": null,
        "published_ts": null
      },
      "activity": {
        "type": "link",
        "sentence": "https://technologynews.biz/its-always-year-zero-css-tricks/ posted '' linking to https://www.swyx.io/svelte-sites-react-apps/",
        "sentence_html": "<a href=\"https://technologynews.biz/its-always-year-zero-css-tricks/\">someone</a> posted '' linking to <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">https://www.swyx.io/svelte-sites-react-apps/</a>"
      },
      "target": "https://www.swyx.io/svelte-sites-react-apps/"
    },
    {
      "source": "https://worldtech.news/its-always-year-zero-css-tricks/",
      "verified": true,
      "verified_date": "2020-12-16T11:09:41+00:00",
      "id": 950762,
      "private": false,
      "data": {
        "url": "https://worldtech.news/its-always-year-zero-css-tricks/",
        "name": null,
        "content": null,
        "published": null,
        "published_ts": null
      },
      "activity": {
        "type": "link",
        "sentence": "https://worldtech.news/its-always-year-zero-css-tricks/ posted '' linking to https://www.swyx.io/svelte-sites-react-apps/",
        "sentence_html": "<a href=\"https://worldtech.news/its-always-year-zero-css-tricks/\">someone</a> posted '' linking to <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">https://www.swyx.io/svelte-sites-react-apps/</a>"
      },
      "target": "https://www.swyx.io/svelte-sites-react-apps/"
    },
    {
      "source": "https://programming.webcloning.com/2020/12/16/its-always-year-zero/",
      "verified": true,
      "verified_date": "2020-12-16T09:47:27+00:00",
      "id": 950716,
      "private": false,
      "data": {
        "url": "https://programming.webcloning.com/2020/12/16/its-always-year-zero/",
        "name": null,
        "content": "December 16, 2020\n\n             | <a href=\"https://programming.webcloning.com/2020/12/16/its-always-year-zero/#respond\">No Comments</a>\n\n            \n        \n\t\t<img src=\"https://programming.webcloning.com/wp-content/uploads/2020/12/npressfetimg-719.png\" alt=\"\" />        \n<p>In the short term, opinions about technology often follow a compressed form of <a href=\"https://signalvnoise.com/posts/2474-lavers-law-of-fashion\">Laver’s Law</a>:</p>\n<ul><li>Everything just before me was completely broken.</li>\n<li>Everything that comes after me is completely unnecessary.</li>\n<li>Everything I use right now is perfectly fine; stop changing things.</li>\n</ul><p>We tend to judge things based on where we started, our personal “Year Zeros.” But what’s “Year Zero” for us isn’t “Year Zero” for others. And in the fullness of time, the good ideas win out and hindsight judges them retrospectively obvious.</p>\n<p><span></span></p>\n<h3>\n<a href=\"https://programming.webcloning.com/2020/12/16/its-always-year-zero/#in-2020-i-learned-that-its-always-year-zero-when-it-comes-to-building-websites\"></a><strong>In 2020, I learned that it’s always Year Zero when it comes to building websites.</strong><br /></h3>\n<p>In <a href=\"https://www.swyx.io/js-third-age/\">“The Third Age of JavaScript”</a> I speculated about a new wave of web developer tools enabled by the confluence of multiple trends:</p>\n<p>In this framing, 2020 was Year Zero of the Third Age. But what happens in 2021? 2022? What makes me so sure that 2020 was some clear dividing line?</p>\n<p>Nothing. There’s always room for innovation. New libraries, new frameworks, new build tools, even new languages. Yes, most of these will go nowhere, and yes, <a href=\"https://twitter.com/swyx/status/1260022224351723521\">we swing back and forth a lot</a>. But it’s the people who believe that web development isn’t done yet that make the future happen. Not those who play armchair quarterback, nor those who <a href=\"https://www.goodreads.com/quotes/42814-you-are-not-superior-just-because-you-see-the-world\">see everything in an odious light</a>. I’d rather side with the people who believe it can be Year Zero than the people who believe Year Zero has passed.</p>\n<img width=\"1024\" height=\"512\" src=\"https://i0.wp.com/css-tricks.com/wp-content/uploads/2020/12/year-zero.png?resize=1024%2C512&amp;ssl=1\" alt=\"\" /><img width=\"1024\" height=\"512\" src=\"https://i0.wp.com/css-tricks.com/wp-content/uploads/2020/12/year-zero.png?resize=1024%2C512&amp;ssl=1\" alt=\"\" /><p>“Year Zero” to me also means keeping a beginner’s mindset and constantly re-examining what I think I know. When I first learned web development, I was told that React was the best framework to build sites, <a href=\"https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0\">Presentational and Container Components</a> was the right way to do React, and that <a href=\"http://getbem.com/introduction/\">BEM</a> was the right way to structure CSS. As a newcomer at Year Zero, I assumed that any discomfort I felt with the orthodoxy was my fault. Flash forward to this year and and my most popular articles are about <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">Svelte</a> and <a href=\"https://dev.to/swyx/why-tailwind-css-2o8f\">Tailwind</a> questioning that conventional wisdom. No one gave me permission to do that. It took <em>years</em> to learn that I could dare to disagree with my mentors and give that permission to myself.</p>\n<p>I feel this most of all for the newcomers to our industry. Every year there are about <a href=\"https://en.wikipedia.org/wiki/FreeCodeCamp#Reception\">~350k freeCodeCamp</a>, <a href=\"https://nces.ed.gov/programs/digest/d19/tables/dt19_322.10.asp?current=yes\">~100k university</a> and <a href=\"https://careerkarma.com/blog/bootcamp-market-report-2020/\">~35k bootcamp</a> grads. It’s Year Zero for them. Or how about our end users — the millions of non-developers who every year have more of their world <a href=\"https://a16z.com/2011/08/20/why-software-is-eating-the-world/\">consumed</a> by the buggy, slow software we make? It’s Year Zero for them.</p>\n<p>It’s also Year Zero for web development in the broader arc of human history. The web is only 30 years old. We’ve had over 300 years refining modern physics, and yet there are still things we know we don’t know. It is <em>such</em> early days for the web.</p>\n<p>Let’s stop pretending what we know is absolute truth and that what we have is the end state of things. <strong>It’s Always Year Zero.</strong></p>\n\n                \n            <a href=\"https://programming.webcloning.com/category/programming/\" title=\"View all posts in Programming\">Programming</a>",
        "published": null,
        "published_ts": null
      },
      "activity": {
        "type": "link",
        "sentence": "https://programming.webcloning.com/2020/12/16/its-always-year-zero/ posted 'December 16, 2020               | No Comments                        \t\t         ...' linking to https://www.swyx.io/svelte-sites-react-apps/",
        "sentence_html": "<a href=\"https://programming.webcloning.com/2020/12/16/its-always-year-zero/\">someone</a> posted 'December 16, 2020               | No Comments                        \t\t         ...' linking to <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">https://www.swyx.io/svelte-sites-react-apps/</a>"
      },
      "rels": {
        "canonical": "https://programming.webcloning.com/2020/12/16/its-always-year-zero/"
      },
      "target": "https://www.swyx.io/svelte-sites-react-apps/"
    },
    {
      "source": "https://www.sacramentowebdesigngroup.com/content-curation/its-always-year-zero",
      "verified": true,
      "verified_date": "2020-12-16T08:24:15+00:00",
      "id": 950671,
      "private": false,
      "data": {
        "url": "https://www.sacramentowebdesigngroup.com/content-curation/its-always-year-zero",
        "name": null,
        "content": null,
        "published": null,
        "published_ts": null
      },
      "activity": {
        "type": "link",
        "sentence": "https://www.sacramentowebdesigngroup.com/content-curation/its-always-year-zero posted '' linking to https://www.swyx.io/svelte-sites-react-apps/",
        "sentence_html": "<a href=\"https://www.sacramentowebdesigngroup.com/content-curation/its-always-year-zero\">someone</a> posted '' linking to <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">https://www.swyx.io/svelte-sites-react-apps/</a>"
      },
      "target": "https://www.swyx.io/svelte-sites-react-apps/"
    },
    {
      "source": "https://htmltreehouse.com/its-always-year-zero-css-tricks/",
      "verified": true,
      "verified_date": "2020-12-16T06:57:20+00:00",
      "id": 950596,
      "private": false,
      "data": {
        "url": "https://htmltreehouse.com/its-always-year-zero-css-tricks/",
        "name": null,
        "content": null,
        "published": null,
        "published_ts": null
      },
      "activity": {
        "type": "link",
        "sentence": "https://htmltreehouse.com/its-always-year-zero-css-tricks/ posted '' linking to https://www.swyx.io/svelte-sites-react-apps/",
        "sentence_html": "<a href=\"https://htmltreehouse.com/its-always-year-zero-css-tricks/\">someone</a> posted '' linking to <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">https://www.swyx.io/svelte-sites-react-apps/</a>"
      },
      "target": "https://www.swyx.io/svelte-sites-react-apps/"
    },
    {
      "source": "https://1dmx.org/cest-toujours-lannee-zero-astuces-css/",
      "verified": true,
      "verified_date": "2020-12-16T06:33:27+00:00",
      "id": 950579,
      "private": false,
      "data": {
        "url": "https://1dmx.org/cest-toujours-lannee-zero-astuces-css/",
        "name": null,
        "content": null,
        "published": null,
        "published_ts": null
      },
      "activity": {
        "type": "link",
        "sentence": "https://1dmx.org/cest-toujours-lannee-zero-astuces-css/ posted '' linking to https://www.swyx.io/svelte-sites-react-apps/",
        "sentence_html": "<a href=\"https://1dmx.org/cest-toujours-lannee-zero-astuces-css/\">someone</a> posted '' linking to <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">https://www.swyx.io/svelte-sites-react-apps/</a>"
      },
      "target": "https://www.swyx.io/svelte-sites-react-apps/"
    },
    {
      "source": "https://websitedesign-usa.com/its-always-year-zero/",
      "verified": true,
      "verified_date": "2020-12-16T05:47:46+00:00",
      "id": 950549,
      "private": false,
      "data": {
        "url": "https://websitedesign-usa.com/its-always-year-zero/",
        "name": "It’s Always Year No",
        "content": "<p>In the short-term, viewpoints about innovation frequently follow a compressed type of <a href=\"https://signalvnoise.com/posts/2474-lavers-law-of-fashion\">Laver’s Law</a>:</p>\n<ul><li>Whatever right before me was totally broken.Everything that follows me is totally unnecessary.Everything I utilize today is completely great; stop altering things. We tend to evaluate things based upon where we began, our individual”Year Nos.</li>\n</ul><p>“What’s “Year No”for us isn’t “Year No”for others. And in the fullness of time, the great concepts triumph and hindsight judges them retrospectively apparent. h3 id =\"h-in-2020-i-learned-that-it-s-always-year-zero-when-it-comes-to-building-websites \"&gt;<br /><span></span></p>\n<h3>\n<a href=\"https://css-tricks.com/its-always-year-zero/#in-2020-i-learned-that-its-always-year-zero-when-it-comes-to-building-websites\"></a><strong> course fill-rule =\"evenodd\"d=\"M4 9h1v1H4c-1.5 0-3-1.69 -3 -3.5 S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41 -.91 2.72-2 3.25 V8.59 c. 58 -.45 1-1.27 1-2.09 C10</strong>\n</h3>\n<p>5.22 8.98 4 8 <a href=\"https://www.swyx.io/js-third-age/\">4H4c -.98 0-2 1.22-2 2.5 S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5 S13.98 12 13 12H9c -.98 0-2-1.22 -2 -2.5 0 -.83.42 -1.64 1-2.09 V6.25c-1.09.53 -2 1.84-2 3.25 C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5 S14.5 6 13 6z”</a>/ &gt; In 2020, I discovered that it’s constantly Year Absolutely no when it pertains to constructing sites. In “The Third Age of JavaScript “I hypothesized about a new age of web designer tools allowed by the confluence of numerous patterns: In this framing, 2020 was Year Absolutely No of the Third Age. What takes place in 2021? 2022? What makes me so sure that 2020 was some clear dividing line?</p>\n<p>Absolutely nothing. There’s constantly space for development. New libraries, brand-new structures, brand-new develop tools, even brand-new languages. Yes, the majority of these will go no place, and yes, <a href=\"https://twitter.com/swyx/status/1260022224351723521\">we swing backward and forward a lot</a>. It’s the individuals who think that web advancement isn’t done yet that make the future occur. Not those who play armchair quarterback, nor those who <a href=\"https://www.goodreads.com/quotes/42814-you-are-not-superior-just-because-you-see-the-world\">see whatever in a repellent light</a>. I ‘d rather agree individuals who think it can be Year No than individuals who think Year Absolutely no has actually passed.</p>\n<p>“Year No”to me likewise suggests keeping a novice’s frame of mind and continuously re-examining what I believe I understand. When I initially discovered web advancement, I was informed that React was the very best structure to develop websites, <a href=\"https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0\">Presentational and Container Elements</a> was properly to do Respond, which <a href=\"http://getbem.com/introduction/\">BEM</a> was properly to structure CSS. As a newbie at Year Absolutely no, I presumed that any pain I felt with the orthodoxy was my fault. Flash forward to this year and my most popular short articles have to do with <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">Svelte</a> and <a href=\"https://dev.to/swyx/why-tailwind-css-2o8f\">Tailwind</a> questioning that traditional knowledge. Nobody provided me authorization to do that. It took <em>years</em> to discover that I might attempt to disagree with my coaches and consider that approval to myself.</p>\n<p>I feel this many of all for the beginners to our market. Every year there have to do with <a href=\"https://en.wikipedia.org/wiki/FreeCodeCamp#Reception\">~ 350k freeCodeCamp</a>, <a href=\"https://nces.ed.gov/programs/digest/d19/tables/dt19_322.10.asp?current=yes\">~ 100k university</a> and <a href=\"https://careerkarma.com/blog/bootcamp-market-report-2020/\">~ 35k bootcamp</a> graduates. It’s Year No for them. Or how about our end users– the countless non-developers who every year have more of their world <a href=\"https://a16z.com/2011/08/20/why-software-is-eating-the-world/\">taken in</a> by the buggy, sluggish software application we make? It’s Year No for them.</p>\n<p>It’s likewise Year No for web advancement in the more comprehensive arc of human history. The web is just thirty years old. We have actually had more than 300 years fine-tuning contemporary physics, and yet there are still things we understand we do not understand. It is <em>such</em> early days for the web.</p>\n<p>Let’s stop pretending what we understand is outright reality which what we have is completion state of things. <strong>It’s Always Year Absolutely No.</strong></p>\n\n\t\n\t\n\n\n<a title=\"Share on WhatsApp\"><i></i></a><a href=\"https://www.facebook.com/sharer.php?u=https://websitedesign-usa.com/its-always-year-zero/\" title=\"Share on Facebook\"><i></i></a><a href=\"https://twitter.com/share?url=https://websitedesign-usa.com/its-always-year-zero/\" title=\"Share on Twitter\"><i></i></a><a href=\"mailto:enteryour@addresshere.com?subject=It%26%238217%3Bs%20Always%20Year%20No&amp;body=Check%20this%20out:%20https://websitedesign-usa.com/its-always-year-zero/\" title=\"Email to a Friend\"><i></i></a><a href=\"https://pinterest.com/pin/create/button/?url=https://websitedesign-usa.com/its-always-year-zero/&amp;media=https://websitedesign-usa.com/wp-content/uploads/2020/12/its-always-year-no-700x350.png&amp;description=It%26%238217%3Bs%20Always%20Year%20No\" title=\"Pin on Pinterest\"><i></i></a><a href=\"https://www.linkedin.com/shareArticle?mini=true&amp;url=https://websitedesign-usa.com/its-always-year-zero/&amp;title=It%26%238217%3Bs%20Always%20Year%20No\" title=\"Share on LinkedIn\"><i></i></a>",
        "published": "2020-12-15T19:05:00-05:00",
        "published_ts": 1608077100
      },
      "activity": {
        "type": "link",
        "sentence": "https://websitedesign-usa.com/its-always-year-zero/ posted 'In the short-term, viewpoints about innovation frequently follow a compressed ty...' linking to https://www.swyx.io/svelte-sites-react-apps/",
        "sentence_html": "<a href=\"https://websitedesign-usa.com/its-always-year-zero/\">someone</a> posted 'In the short-term, viewpoints about innovation frequently follow a compressed ty...' linking to <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">https://www.swyx.io/svelte-sites-react-apps/</a>"
      },
      "rels": {
        "canonical": "https://websitedesign-usa.com/its-always-year-zero/"
      },
      "target": "https://www.swyx.io/svelte-sites-react-apps/"
    },
    {
      "source": "https://techupd.com/its-always-year-zero-css-tricks/",
      "verified": true,
      "verified_date": "2020-12-16T05:44:38+00:00",
      "id": 950547,
      "private": false,
      "data": {
        "url": "https://techupd.com/its-always-year-zero-css-tricks/",
        "name": null,
        "content": null,
        "published": null,
        "published_ts": null
      },
      "activity": {
        "type": "link",
        "sentence": "https://techupd.com/its-always-year-zero-css-tricks/ posted '' linking to https://www.swyx.io/svelte-sites-react-apps/",
        "sentence_html": "<a href=\"https://techupd.com/its-always-year-zero-css-tricks/\">someone</a> posted '' linking to <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">https://www.swyx.io/svelte-sites-react-apps/</a>"
      },
      "target": "https://www.swyx.io/svelte-sites-react-apps/"
    },
    {
      "source": "https://fancyhints.com/its-always-year-zero/",
      "verified": true,
      "verified_date": "2020-12-16T04:55:31+00:00",
      "id": 950502,
      "private": false,
      "data": {
        "url": "https://fancyhints.com/its-always-year-zero/",
        "name": null,
        "content": null,
        "published": null,
        "published_ts": null
      },
      "activity": {
        "type": "link",
        "sentence": "https://fancyhints.com/its-always-year-zero/ posted '' linking to https://www.swyx.io/svelte-sites-react-apps/",
        "sentence_html": "<a href=\"https://fancyhints.com/its-always-year-zero/\">someone</a> posted '' linking to <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">https://www.swyx.io/svelte-sites-react-apps/</a>"
      },
      "target": "https://www.swyx.io/svelte-sites-react-apps/"
    },
    {
      "source": "https://techalertnews.com/its-always-year-zero-css-tricks/",
      "verified": true,
      "verified_date": "2020-12-16T04:52:57+00:00",
      "id": 950500,
      "private": false,
      "data": {
        "url": "https://techalertnews.com/its-always-year-zero-css-tricks/",
        "name": null,
        "content": null,
        "published": null,
        "published_ts": null
      },
      "activity": {
        "type": "link",
        "sentence": "https://techalertnews.com/its-always-year-zero-css-tricks/ posted '' linking to https://www.swyx.io/svelte-sites-react-apps/",
        "sentence_html": "<a href=\"https://techalertnews.com/its-always-year-zero-css-tricks/\">someone</a> posted '' linking to <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">https://www.swyx.io/svelte-sites-react-apps/</a>"
      },
      "target": "https://www.swyx.io/svelte-sites-react-apps/"
    },
    {
      "source": "https://buzzedly.com/?p=84658",
      "verified": true,
      "verified_date": "2020-12-16T02:54:41+00:00",
      "id": 950349,
      "private": false,
      "data": {
        "url": "https://buzzedly.com/?p=84658",
        "name": null,
        "content": "<p>In the short term, opinions about technology often follow a compressed form of <a href=\"https://signalvnoise.com/posts/2474-lavers-law-of-fashion\">Laver’s Law</a>:</p>\n<ul><li>Everything just before me was completely broken.</li>\n<li>Everything that comes after me is completely unnecessary.</li>\n<li>Everything I use right now is perfectly fine; stop changing things.</li>\n</ul><p>We tend to judge things based on where we started, our personal “Year Zeros.” But what’s “Year Zero” for us isn’t “Year Zero” for others. And in the fullness of time, the good ideas win out and hindsight judges them retrospectively obvious.</p>\n<p><span></span></p>\n<h3>\n<a href=\"https://buzzedly.com/?p=84658#in-2020-i-learned-that-its-always-year-zero-when-it-comes-to-building-websites\"></a><strong>In 2020, I learned that it’s always Year Zero when it comes to building websites.</strong>\n</h3>\n<p>In <a href=\"https://www.swyx.io/js-third-age/\">“The Third Age of JavaScript”</a> I speculated about a new wave of web developer tools enabled by the confluence of multiple trends:</p>\n<p>In this framing, 2020 was Year Zero of the Third Age. But what happens in 2021? 2022? What makes me so sure that 2020 was some clear dividing line?</p>\n<p>Nothing. There’s always room for innovation. New libraries, new frameworks, new build tools, even new languages. Yes, most of these will go nowhere, and yes, <a href=\"https://twitter.com/swyx/status/1260022224351723521\">we swing back and forth a lot</a>. But it’s the people who believe that web development isn’t done yet that make the future happen. Not those who play armchair quarterback, nor those who <a href=\"https://www.goodreads.com/quotes/42814-you-are-not-superior-just-because-you-see-the-world\">see everything in an odious light</a>. I’d rather side with the people who believe it can be Year Zero than the people who believe Year Zero has passed.</p>\n<img width=\"1024\" height=\"512\" src=\"https://i0.wp.com/css-tricks.com/wp-content/uploads/2020/12/year-zero.png?resize=1024%2C512&amp;ssl=1\" alt=\"\" /><img width=\"1024\" height=\"512\" src=\"https://i0.wp.com/css-tricks.com/wp-content/uploads/2020/12/year-zero.png?resize=1024%2C512&amp;ssl=1\" alt=\"\" /><p>“Year Zero” to me also means keeping a beginner’s mindset and constantly re-examining what I think I know. When I first learned web development, I was told that React was the best framework to build sites, <a href=\"https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0\">Presentational and Container Components</a> was the right way to do React, and that <a href=\"http://getbem.com/introduction/\">BEM</a> was the right way to structure CSS. As a newcomer at Year Zero, I assumed that any discomfort I felt with the orthodoxy was my fault. Flash forward to this year and and my most popular articles are about <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">Svelte</a> and <a href=\"https://dev.to/swyx/why-tailwind-css-2o8f\">Tailwind</a> questioning that conventional wisdom. No one gave me permission to do that. It took <em>years</em> to learn that I could dare to disagree with my mentors and give that permission to myself.</p>\n<p>I feel this most of all for the newcomers to our industry. Every year there are about <a href=\"https://en.wikipedia.org/wiki/FreeCodeCamp#Reception\">~350k freeCodeCamp</a>, <a href=\"https://nces.ed.gov/programs/digest/d19/tables/dt19_322.10.asp?current=yes\">~100k university</a> and <a href=\"https://careerkarma.com/blog/bootcamp-market-report-2020/\">~35k bootcamp</a> grads. It’s Year Zero for them. Or how about our end users — the millions of non-developers who every year have more of their world <a href=\"https://a16z.com/2011/08/20/why-software-is-eating-the-world/\">consumed</a> by the buggy, slow software we make? It’s Year Zero for them.</p>\n<p>It’s also Year Zero for web development in the broader arc of human history. The web is only 30 years old. We’ve had over 300 years refining modern physics, and yet there are still things we know we don’t know. It is <em>such</em> early days for the web.</p>\n<p>Let’s stop pretending what we know is absolute truth and that what we have is the end state of things. <strong>It’s Always Year Zero.</strong></p>",
        "published": null,
        "published_ts": null
      },
      "activity": {
        "type": "link",
        "sentence": "https://buzzedly.com/?p=84658 posted 'In the short term, opinions about technology often follow a compressed form of L...' linking to https://www.swyx.io/svelte-sites-react-apps/",
        "sentence_html": "<a href=\"https://buzzedly.com/?p=84658\">someone</a> posted 'In the short term, opinions about technology often follow a compressed form of L...' linking to <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">https://www.swyx.io/svelte-sites-react-apps/</a>"
      },
      "rels": {
        "canonical": "https://buzzedly.com/?p=84658"
      },
      "target": "https://www.swyx.io/svelte-sites-react-apps/"
    },
    {
      "source": "https://dztechno.com/its-always-year-zero-css-tricks-dztechno/",
      "verified": true,
      "verified_date": "2020-12-16T02:49:18+00:00",
      "id": 950342,
      "private": false,
      "data": {
        "url": "https://dztechno.com/its-always-year-zero-css-tricks-dztechno/",
        "name": null,
        "content": null,
        "published": null,
        "published_ts": null
      },
      "activity": {
        "type": "link",
        "sentence": "https://dztechno.com/its-always-year-zero-css-tricks-dztechno/ posted '' linking to https://www.swyx.io/svelte-sites-react-apps/",
        "sentence_html": "<a href=\"https://dztechno.com/its-always-year-zero-css-tricks-dztechno/\">someone</a> posted '' linking to <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">https://www.swyx.io/svelte-sites-react-apps/</a>"
      },
      "rels": {
        "canonical": "https://dztechno.com/its-always-year-zero-css-tricks-dztechno/"
      },
      "target": "https://www.swyx.io/svelte-sites-react-apps/"
    },
    {
      "source": "https://graphicdon.com/2020/12/16/its-always-year-zero-css-tricks/",
      "verified": true,
      "verified_date": "2020-12-16T02:40:14+00:00",
      "id": 950333,
      "private": false,
      "data": {
        "url": "https://graphicdon.com/2020/12/16/its-always-year-zero-css-tricks/",
        "name": null,
        "content": null,
        "published": null,
        "published_ts": null
      },
      "activity": {
        "type": "link",
        "sentence": "https://graphicdon.com/2020/12/16/its-always-year-zero-css-tricks/ posted '' linking to https://www.swyx.io/svelte-sites-react-apps/",
        "sentence_html": "<a href=\"https://graphicdon.com/2020/12/16/its-always-year-zero-css-tricks/\">someone</a> posted '' linking to <a href=\"https://www.swyx.io/svelte-sites-react-apps/\">https://www.swyx.io/svelte-sites-react-apps/</a>"
      },
      "target": "https://www.swyx.io/svelte-sites-react-apps/"
    }
  ]
}
```

</details>

## example usage



```js
  function getMentions() {
    const fetches = _targets.map((target) =>
      fetch(`https://webmention.io/api/mentions?page=${page}&per-page=20&target=${target}/`).then((x) => x.json())
    )
    return Promise.all(fetches)
      .then((arr) => arr.map((x) => x.links).flat())
      .then(x => x.filter(link => !blocklist.includes(new URL(link.source).origin)))
  }
```

i use this on my blog https://github.com/sw-yx/swyxdotio/blob/master/src/components/WebMentions/WebMentions.svelte
