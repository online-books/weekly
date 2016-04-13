优秀文章汇总  
========  

**The Definitive Guide to Linux System Calls**  
http://blog.packagecloud.io/eng/2016/04/05/the-definitive-guide-to-linux-system-calls/  
This blog post explains how Linux programs call functions in the Linux kernel. It will outline several different methods of making systems calls, how to handcraft your own assembly to make system calls (examples included), kernel entry points into system calls, kernel exit points from system calls, glibc wrappers, bugs, and much, much more.

**编程的智慧**  
http://www.yinwang.org/blog-cn/2015/11/21/programming-philosophy  
编程是一种创造性的工作，是一门艺术。精通任何一门艺术，都需要很多的练习和领悟，所以这里提出的“智慧”，并不是号称一天瘦十斤的减肥药，它并不能代替你自己的勤奋。然而由于软件行业喜欢标新立异，喜欢把简单的事情搞复杂，我希望这些文字能给迷惑中的人们指出一些正确的方向，让他们少走一些弯路，基本做到一分耕耘一分收获。

**What if we had a great standard library in JavaScript?**  
https://medium.com/@thomasfuchs/what-if-we-had-a-great-standard-library-in-javascript-52692342ee3f  
Micro.js http://microjs.com/ 发起者对 JS 生态思考。A standard library would make it a lot easier to write JavaScript by eliminating the need to come up with similar or same solutions to small issues.

**The Deep Roots of Javascript Fatigue**  
https://segment.com/blog/the-deep-roots-of-js-fatigue/  
https://news.ycombinator.com/item?id=11294218  
Like it or not, Javascript is evolving at a faster rate than any widespread language in the history of computing. Most of the tools we use today didn’t even really exist a year ago: React, JSX, Flux, Redux, ES6, Babel, etc. Even setting up a ‘modern’ project requires installing a swath of dependencies and build tools that are all new. No other language does anything remotely resembling that kind of thing. It’s enough to even warrant a “State of the Art” post so everyone knows what to use. So, why does Javascript change so much? 

**~2015 in review**  
https://medium.com/@sebmck/2015-in-review-51ac7035e272  
This started off as a generic year in review but as I was writing it became a lot more personal. This is my story of how I dealt with going from high school to moving to another country and working in big tech in a little over a year. 

**Why I No Longer Use MVC Frameworks**
http://www.infoq.com/articles/no-more-mvc-frameworks
The worst part of my job these days is designing APIs for front-end developers. The conversation goes inevitably as:Dev – So, this screen has data element x,y,z… could you please create an API with the response format {x: , y:, z: } Me – Ok. I don’t even argue anymore. Projects end up with a gazillion APIs tied to screens that change often, which, by “design” require changes in the API and before you know it, you end up with lots of APIs and for each API many form factors and platform variants. A couple of months ago, I started a journey to understand why we ended up here and what could be done about it, a journey that lead me to question the strongest dogma in application architecture, MVC, and where I touched the sheer power of reactive and functional programming, a journey focused on simplicity and scraping the bloat that our industry is so good at producing.
文章的信息量很大，索引了很多优质文章，对 React、Angular、MVC、GraphQL 等的分析还是挺不错的，对比了各种 Web应用 开发方式后，提出了一种叫 SAM 的模式，值得认真阅读。

**The Error Model**  
http://joeduffyblog.com/2016/02/07/the-error-model/  
The basic question an Error Model seeks to answer is: how do “errors” get communicated to programmers and users of the system? Pretty simple, no? So it seems. This journey was long and winding. To tell the tale, I’ve broken this post into six major areas:  
- Ambitions and Learnings  
- Bugs Aren’t Recoverable Errors!  
- Reliability, Fault-Tolerance, and Isolation  
- Bugs: Abandonment, Assertions, and Contracts  
- Recoverable Errors: Type-Directed Exceptions  
- Retrospective and Conclusions  

**Rooms and Mazes: A Procedural Dungeon Generator**  
http://journal.stuffwithstuff.com/2014/12/21/rooms-and-mazes/  
地牢生成算法

**Coding is boring, unless…**  
https://blog.enki.com/coding-is-boring-unless-4e496720d664#.xarhhx5ug  

**The [real] problem with JavaScript**
https://medium.com/unhandled-exception/the-real-problem-with-javascript-6b78cad97b6e
https://medium.com/@wob/the-sad-state-of-web-development-1603a861d29f
讨论 JS 、Web 开发、前端生态，起因是第2篇文章，观点挺偏激的，引发了激烈的讨论，不过的确指出了 Web 生态圈面临的一些问题。第1篇文章比较中肯，指出了关键点在于：选择和集成成本太高，作者也在试图建立一个知识库来解决技术选型问题，这是他采集信息的一个调研： [Should I Use](https://alterx.typeform.com/to/ASrKf9)。这两个文章还引申出两个有意思的东西：[Magpie Developer](http://blog.codinghorror.com/the-magpie-developer/)、[The programming language cycle](http://quoderat.megginson.com/2006/03/06/programming-languages-of-distinction/)。
相比之下，最近由 [真阿当-当我说前端基础时，我在说什么](http://weibo.com/p/1001603933000810243086) 引发的国内前端界大讨论就平和多了：
- [知乎-如何评价-当我说前端基础时...](https://www.zhihu.com/question/39659757)
- [Vue.js 作者-谈谈前端新技术](http://weibo.com/p/1001603934708609234550)
- [为这几天前端方向所撕的逼做个大总结](http://weibo.com/ttarticle/p/show?id=2309403934449430569795)
- http://weibo.com/1693534972/DeAL1tRvy
前端是一个年轻的生态，我们的路还很长，怀着敬畏和谦逊之心、脚踏实地去解决路上的各种问题才是正道。

**How one developer just broke Node, Babel and thousands of projects in 11 lines of JavaScript**  
http://www.theregister.co.uk/2016/03/23/npm_left_pad_chaos/  
http://blog.npmjs.org/post/141577284765/kik-left-pad-and-npm  
一个函数引发的血案： A couple of hours ago, Azer Koçulu unpublished more than 250 of his modules from NPM, which is a popular package manager used by JavaScript projects to install dependencies.  Unfortunately, one of those dependencies was left-pad.  With left-pad removed from NPM, these applications and widely used bits of open-source infrastructure were unable to obtain the dependency, and thus fell over.
另外之前还有人讨论过，npm 是有安全隐患的，比如万一依赖最高的那个包 lodash 被盗号了，通过 npm 脚本就可以做任何事，所以希望能尽快改进，加上签名机制，不然迟早会出事。这个问题引发的讨论和思考还是挺值得关注的，相关阅读：
http://lucumr.pocoo.org/2016/3/24/open-source-trust-scaling/  
http://www.haneycodes.net/npm-left-pad-have-we-forgotten-how-to-program/  
https://medium.com/@azerbike/i-ve-just-liberated-my-modules-9045c06be67c#.u61t28o05  
https://medium.freecodecamp.com/npm-package-hijacking-from-the-hijackers-perspective-af0c48ab9922#.to7j5qyy0
http://blog.npmjs.org/post/141702881055/package-install-scripts-vulnerability  
http://blog.h5jun.com/post/left-pad.html
http://left-pad.io/


**JavaScript web apps considered valuable**
http://molily.de/javascript-web-apps/
Recalling best practices for web applications that make heavy use of client-side JavaScript. The solution for bad JavaScript web apps is not to abandon them altogether, but to make better ones. We need to stop excluding JavaScript apps from “the web as it was intended”. JavaScript apps are “on the web” just like other sites. The potential of the web is enormous and we have just started.

**Front-end Application Libraries and Component Architectures**  
http://developer.telerik.com/featured/front-end-application-frameworks-component-architectures/  
Component architectures are an important part of ever modern front-end framework. In this article, I’m going to dissect Polymer, React, Rio.js, Vue.js, Aurelia and Angular 2 components. The goal is to make the commonalities between each solution obvious. Hopefully, this will convince you that learning one or the other isn’t all that complex, given that everyone has somewhat settled on a component architecture.

**What can we learn from how jQuery symbiotically pushed the Web Platform forward?**  
https://medium.com/ben-and-dion/what-can-we-learn-from-how-jquery-symbiotically-pushed-the-web-platform-forward-ce6b20cd4e98  
One of the great things about jQuery was that it had a simple, powerful idea. It’s entire mindset was “find these items in the DOM, and attach these events to them”. The fluent style of API probably opened peoples minds up in a way that only helped us with promises and rethinking APIs such as XHR vs. fetch. 
All in all jQuery has evolved along with the Web platform, helping improve things beyond itself.

**JavaScript At Scale — Achieving High Velocity**  
https://labs.mlssoccer.com/javascript-at-scale-achieving-high-velocity-160c7d78af03  
Many companies choose JavaScript because it is touted as flexible and fast. While this may be true, that same flexibility and speed can get you in a few traps if you are not thoughtful in how you build your JavaScript ecosystem.

**房间和迷宫：一个地牢生成算法**  
http://indienova.com/indie-game-development/rooms-and-mazes-a-procedural-dungeon-generator/  
几个月之前，我承诺要针对之前的一篇针对我的 Roguelike 游戏的 blog：回合制的游戏主循环（turn-based game loops）。然后我就投入到我自己发行的新书：《游戏编程模式（Game Programming Patterns）》中去，并且把这件事情彻底忘掉了。我把大家扔在一边了～～好，今天我终于有时间再思考一下我的 Roguelike 了，那么，忘掉游戏主循环，让我们来研究一下 Roguelike 游戏最有趣也是最有挑战的部分：生成地牢！

**The Zen of Erlang**  
http://ferd.ca/the-zen-of-erlang.html  
I assume most people here have never used Erlang, have possibly heard of it, maybe just the name. As such, this presentation will only cover the high level concepts of Erlang, in such a way that it may be useful to you in your work or side projects even if you never touch the language.

**Why do we work so hard?**  
https://www.1843magazine.com/features/why-do-we-work-so-hard  
Maybe it’s because work is satisfying. Maybe it’s because we’re trapped. Or maybe, as Ryan Avent suspects, it’s because of a troubling combination of the two

### Things  

**The only framework that makes responsive-email easy**  
https://github.com/mjmlio  
https://mjml.io/  
MJML is a markup language designed to reduce the pain of coding a responsive email. Its semantic syntax makes it easy and straightforward and its rich standard components library speeds up your development time and lightens your email codebase. MJML’s open-source engine generates high quality responsive HTML compliant with best practices.

**Computer Science Field Guide**  
http://www.csfieldguide.org.nz/en/index.html  
An online interactive resource for high school students learning about computer science.  

**RemixOS – Android for the desktop**  
http://www.jide.com/en/remixos  

**Chirimen, a Firefox OS-Powered IoT Single-Board Computer Developed by Mozilla**  
http://mozopenhard.mozillafactory.org/  

**How to C in 2016**  
https://matt.sh/howto-c  

**Caja is a tool for safely embedding third party HTML, CSS and JavaScript in your website**  
https://github.com/google/caja  

**WICG: 从头开始设计新一代Web**  
http://siusin.github.io/translation/WICG/blog/index.html  

**Web Pages Will Soon Load Even Faster in Google Chrome**
http://www.omgchrome.com/brotli-http-compression-coming-to-chrome/  
https://www.chromestatus.com/feature/5420797577396224  
http://google-opensource.blogspot.fr/2015/09/introducing-brotli-new-compression.html  
采用一种叫 Brotli https://github.com/google/brotli 的压缩技术来提升资源传输效率，Brotli (shortname "br") is used in WOFF 2.0 web fonts with great success. This is about making it available as an HTTP content-encoding method (e.g. Accept-Encoding: br). Advantages of Brotli over gzip: - significantly better compression density - comparable decompression speed。  