# V8 Resources

These are some resources I've gathered while trying to learn V8 internals (with a security focus), feel free to suggest a resource using a pull request.

## Articles

- [[2012/06/03] - Explaining JavaScript VMs in JavaScript - Inline Caches](https://mrale.ph/blog/2012/06/03/explaining-js-vms-in-js-inline-caches.html) ✅
- [[2015/01/11] - What's up with monomorphism?](https://mrale.ph/blog/2015/01/11/whats-up-with-monomorphism.html) ✅
- [[2015/10/08] - Sea of Nodes](https://darksi.de/d.sea-of-nodes/)
- [[2014/12/14] - Google Chrome Exploitation – A Case Study](https://unit42.paloaltonetworks.com/google-chrome-exploitation-case-study/)
- [[2017/03/01] - V8: Behind the Scenes (February Edition feat. A tale of TurboFan)](https://benediktmeurer.de/2017/03/01/v8-behind-the-scenes-february-edition)
- [[2017/08/16] - Understanding V8’s Bytecode](https://medium.com/dailyjs/understanding-v8s-bytecode-317d46c94775) ✅
- [[2018/12/08] - All Functions are Closures: Discussing Scope and Closure in JS](https://blog.huli.tw/2018/12/08/en/javascript-closure/)
- [[2019/01/22] - Exploiting the Magellan bug on 64-bit Chrome Desktop](https://blog.exodusintel.com/2019/01/22/exploiting-the-magellan-bug-on-64-bit-chrome-desktop/)
- [[2019/04/29] - Don't Follow The Masses: Bug Hunting in JavaScript Engines](https://labs.bluefrostsecurity.de/blog/2019/04/29/dont-follow-the-masses-bug-hunting-in-javascript-engines/)
- [[2019/05/09] - Circumventing Chrome's hardening of typer bugs](https://doar-e.github.io/blog/2019/05/09/circumventing-chromes-hardening-of-typer-bugs/)
- [[2019/07/04] - V8 Optimize: Reduce Node && Inline](https://p1umer.github.io/2019/07/04/V8-Optimize-Reduce-Node-Inline/)
- [[2019/07/03] - V8 Optimize: FrameState](https://p1umer.github.io/2019/07/03/V8-Optimize-FrameState/)
- [[2019/08/06] - V8 function optimization](https://erdem.pl/2019/08/v-8-function-optimization)
- [[2019/08/28] - Notes about GraphReducer in V8](https://mem2019.github.io/jekyll/update/2019/08/28/V8-GraphReducer-Notes.html) ✅
- [[2019/08/28] - Redundancy Elimination Reducer in V8 and 34C3 CTF V9](https://mem2019.github.io/jekyll/update/2019/08/28/V8-Redundancy-Elimination.html) ✅
- [[2020/02/--] - Pointer Compression in V8](https://blog.infosectcbr.com.au/2020/02/pointer-compression-in-v8.html) ✅
- [[2020/08/27] - [V8 Deep Dives] Understanding Map Internals](https://itnext.io/v8-deep-dives-understanding-map-internals-45eb94a183df) ✅
- [[2020/11/17] - Modern attacks on the Chrome browser : optimizations and deoptimizations](https://doar-e.github.io/blog/2020/11/17/modern-attacks-on-the-chrome-browser-optimizations-and-deoptimizations/)
- [[2021/01/12] - In-the-Wild Series: Chrome Infinity Bug](https://googleprojectzero.blogspot.com/2021/01/in-wild-series-chrome-infinity-bug.html)
- [[2021/04/21] - Exploit Development: Browser Exploitation on Windows - Understanding Use-After-Free Vulnerabilities](https://connormcgarr.github.io/browser1/)
- [[2021/04/02] - [V8 Deep Dives] Random Thoughts on Math.random()](https://apechkurov.medium.com/v8-deep-dives-random-thoughts-on-math-random-fb155075e9e5)
- [[2021/10/05] - Phrack: Exploiting Logic Bugs in JavaScript JIT Engines](http://phrack.org/issues/70/9.html#article) ✅
- [[2021/12/28] - V8 Heap pwn and /dev/memes - WebOS Root LPE](https://www.da.vidbuchanan.co.uk/blog/webos-wampage.html)
- [[2022/01/23] - Fuzzing Chromes JavaScript Engine v8](https://apt29a.blogspot.com/2022/01/fuzzing-chromes-javascript-engine-v8.html)
- [[2022/05/20] - Rooting Samsung Q60T Smart TV](https://www.synacktiv.com/sites/default/files/2022-05/Sthack2022_Rooting_Samsung_Q60T_Smart_TV.pdf)
- [[2022/06/29] - The Chromium super (inline cache) type confusion](https://github.blog/security/vulnerability-research/the-chromium-super-inline-cache-type-confusion/)
- [[2022/07/28] - JavaScript Bytecode – v8 Ignition Instructions](https://www.alibabacloud.com/blog/javascript-bytecode-v8-ignition-instructions_599188) ✅
- [[2022/08/29] - Understand WebAssembly in One Article](https://www.alibabacloud.com/blog/understand-webassembly-in-one-article_599282)
- [[2022/09/20] - From Leaking TheHole to Chrome Renderer RCE](https://medium.com/numen-cyber-labs/from-leaking-thehole-to-chrome-renderer-rce-183dcb6f3078) ✅
- [[2022/10/22] - Chrome Browser Exploitation, Part 1: Introduction to V8 and JavaScript Internals](https://jhalon.github.io/chrome-browser-exploitation-1/)
- [[2022/11/27] - Code Execution in Chromium’s V8 Heap Sandbox](https://anvbis.au/posts/code-execution-in-chromiums-v8-heap-sandbox/) ✅
- [[2023/02/23] - Exploring Historical V8 Heap Sandbox Escapes I](https://anvbis.au/posts/exploring-historical-v8-heap-sandbox-escapes-i/)
- [[2023/05/16] - Google Chrome V8 ArrayShift Race Condition Remote Code Execution](https://blog.exodusintel.com/2023/05/16/google-chrome-v8-arrayshift-race-condition-remote-code-execution/)
- [[2023/10/17] - Getting RCE in Chrome with incomplete object initialization in the Maglev compiler](https://github.blog/security/vulnerability-research/getting-rce-in-chrome-with-incomplete-object-initialization-in-the-maglev-compiler/)
- [[2023/12/11] - Safari, Hold Still for NaN Minutes!](https://blog.exodusintel.com/2023/12/11/safari-hold-still-for-nan-minutes/)
- [[2023/12/12] - Abusing Liftoff assembly and efficiently escaping from sbx](https://retr0.zip/blog/abusing-Liftoff-assembly-and-efficiently-escaping-from-sbx.html) ✅
- [[2024/01/09] - A Brief JavaScriptCore RCE Story](https://qriousec.github.io/post/jsc-uninit/)
- [[2024/01/25] - A Deep Dive into V8 Sandbox Escape Technique Used in In-The-Wild Exploit](https://theori.io/blog/a-deep-dive-into-v8-sandbox-escape-technique-used-in-in-the-wild-exploit)
- [[2024/02/21] - Summary of WebAssembly Security Research](https://mp.weixin.qq.com/s/cPUaDQaCWpZiBEgZqbqvPg)
- [[2024/05/--] - From the Vulnerability to the Victory: A Chrome Renderer 1-Day Exploit’s Journey to v8CTF Glory](https://insuyun.github.io/publication/lee-v-8-ctf/) ✅
- [[2024/06/05] - An Introduction to Chrome Exploitation - Maglev Edition](https://www.matteomalvica.com/blog/2024/06/05/intro-v8-exploitation-maglev/)
- [[2024/06/26] - Attack of the clones: Getting RCE in Chrome’s renderer with duplicate object properties](https://github.blog/security/vulnerability-research/attack-of-the-clones-getting-rce-in-chromes-renderer-with-duplicate-object-properties/)
- [[2024/08/13] - From object transition to RCE in the Chrome renderer](https://github.blog/security/vulnerability-research/from-object-transition-to-rce-in-the-chrome-renderer/)
- [[2024/08/19] - Phrack: Allocating new exploits](http://phrack.org/issues/71/10.html#article)
- [[2024/09/05] - Miscellaneous Series 2 — A Script Kiddie Diary in v8 Exploit Research Part 1](https://medium.com/@INTfinitySG/miscellaneous-series-2-a-script-kiddie-diary-in-v8-exploit-research-part-1-5b0bab211f5a)
- [[2024/10/25] - A deep dive into Linux’s new mseal syscall](https://blog.trailofbits.com/2024/10/25/a-deep-dive-into-linuxs-new-mseal-syscall/) ✅
- [[2024/11/03] - Mind the v8 patch gap: Electron's Context Isolation is insecure](https://s1r1us.ninja/posts/electron-contextbridge-is-insecure/)
- [[2024/12/09] - Miscellaneous Series 3— A Script Kiddie Diary in v8 Exploit Research Part 2](https://medium.com/@INTfinitySG/miscellaneous-series-3-a-script-kiddie-diary-in-v8-exploit-research-part-2-585bd3f0a833)
- [[2025/01/02] - Overview of WebAssembly Type Confusion in JavaScript Engines Exploitation](https://xia0.sh/blog/overview-of-wasm-in-jsengine-exploit)
- [[2025/01/20] - Miscellaneous Series 4— A Script Kiddie Diary in v8 Exploit Research Part 3](https://medium.com/@INTfinitySG/miscellaneous-series-4-a-script-kiddie-diary-in-v8-exploit-research-part-3-4a3ba2da256d)
- [[2025/02/01] - Overview of Map Exploitation in v8](https://xia0.sh/blog/visit-the-map/visit-the-map)
- [[2025/04/11] - Intro V8](https://w1redch4d.github.io/post/intro-v8/)
- [[2025/04/12] - Compiler Design 1](https://w1redch4d.github.io/post/compiler-design-1/)
- [[2025/04/12] - Compiler Design Principles in V8](https://w1redch4d.github.io/post/compiler-design-principles-in-v8/)
- [[2025/04/13] - Lexical Analysis](https://w1redch4d.github.io/post/lexical-analysis/)
- [[2025/04/14] - Parser Workflow](https://w1redch4d.github.io/post/parser-workflow/)
- [[----/--/--] - V8 Overview](https://deepwiki.com/v8/v8)

## Official Docs/Blogs

- [[2015/12/17] - There’s Math.random(), and then there’s Math.random()](https://v8.dev/blog/math-random)
- [[2017/09/12] - Elements kinds in V8](https://v8.dev/blog/elements-kinds) ✅
- [[2017/10/05] - Optimizing ES2015 proxies in V8](https://v8.dev/blog/optimizing-proxies)
- [[2017/11/16] - Taming architecture complexity in V8 — the CodeStubAssembler](https://v8.dev/blog/csa) ✅
- [[2017/12/13] - JavaScript code coverage](https://v8.dev/blog/javascript-code-coverage)
- [[2018/06/18] - JavaScript modules](https://v8.dev/features/modules)
- [[2018/08/14] - Embedded builtins](https://v8.dev/blog/embedded-builtins)
- [[2018/09/18] - Improving DataView performance in V8](https://v8.dev/blog/dataview)
- [[2019/01/03] - Trash talk: the Orinoco garbage collector](https://v8.dev/blog/trash-talk)
- [[2019/01/07] - Zero-cost async stack traces](https://docs.google.com/document/d/13Sy_kBIJGP0XT34V1CV3nkWya4TwYx9L3Yv45LdGB6Q)
- [[2019/04/23] - A year with Spectre: a V8 perspective](https://v8.dev/blog/spectre) ✅
- [[2019/09/11] - Compressed pointers in V8](https://docs.google.com/document/d/10qh2-b4C5OtSg-xLwyZpEI5ZihVBPtn1xwKBbQC26yI)
- [[2020/03/30] - Pointer Compression in V8](https://v8.dev/blog/pointer-compression)
- [[2021/07/--] - V8 Sandbox](https://docs.google.com/document/d/1FM4fQmIhEqPG8uGp5o9A-mnPB5BOeScZYpkHjo0KKA8) ✅
- [[2022/02/--] - V8 Sandbox - Address Space](https://docs.google.com/document/d/1PM4Zqmlt8ac5O8UNQfY7fOsem-6MhbsB-vjFI-9XK6w) ✅
- [[2022/02/--] - V8 Sandbox - Sandboxed Pointers](https://docs.google.com/document/d/1HSap8-J3HcrZvT7-5NsbYWcjfc0BVoops5TDHZNsnko)
- [[2022/07/--] - V8 Sandbox - External Pointer Sandboxing](https://docs.google.com/document/d/1V3sxltuFjjhp_6grGHgfqZNK57qfzGzme0QTk0IXDHk)
- [[2022/12/--] - V8 Sandbox - Code Pointer Sandboxing](https://docs.google.com/document/d/1CPs5PutbnmI-c5g7e_Td9CNGh5BvpLleKCqUnqmD82k) ✅
- [[2023/02/11] - Turboshaft Frontend - Preliminary Design Elements](https://docs.google.com/document/d/1vL1_1g4sY4WbTgbirKBq-40_zsrhI-zM0ZiioC_ahl8)
- [[2023/10/09] - Control-flow Integrity in V8](https://v8.dev/blog/control-flow-integrity) ✅
- [[2023/10/--] - V8 Sandbox - Trusted Space](https://docs.google.com/document/d/1IrvzL4uX_Zv0k2Iakdp_q_z33bj-qlYF5IesGpXW0fM)
- [[2023/10/03] - Turboshaft JS Inlining and In-place Mutations](https://docs.google.com/document/d/1_L3TWgREnlm6QUTca27jN-TLyxo_Jy-AbicVhzmEHwM)
- [[2023/11/01] - A new way to bring garbage collected programming languages efficiently to WebAssembly](https://v8.dev/blog/wasm-gc-porting)
- [[2023/11/27] - Maglev with the Reducer Framework (Preliminary Investigation)](https://docs.google.com/document/d/1i1GJ6tIDRBe_Dolwhdkm1vVSiLwSKC5CB88-u9pPjVo)
- [[2023/12/14] - V8 is Faster and Safer than Ever!](https://v8.dev/blog/holiday-season-2023)
- [[2024/01/--] - Const tracking lets](https://docs.google.com/document/d/18F1syu8314lcz1pm9e2LNi3pYzp5t1ah5EpmR4mE4Tg) ✅
- [[2024/02/--] - Maglev as a Frontend for Turboshaft](https://docs.google.com/document/d/1BatjXtg-Iv9mHgce_pa1L8MaCHShekQEg4jJ83IXd4o)
- [[2024/02/--] - V8 Sandbox - Hardware Support](https://docs.google.com/document/d/12MsaG6BYRB-jQWNkZiuM3bY8X2B2cAsCMLLdgErvK4c) ✅
- [[2024/04/04] - The V8 Sandbox](https://v8.dev/blog/sandbox) ✅
- [[2024/07/--] - V8 Sandbox + Leaptiering](https://docs.google.com/document/d/1WkyEynMluvIr0LBmrapyF7MiE8wIHFHnlP5B6FFhQuA)
- [[2025/03/25] - Land ahoy: leaving the Sea of Nodes](https://v8.dev/blog/leaving-the-sea-of-nodes)
- [[----/--/--] - Maps (Hidden Classes) in V8](https://v8.dev/docs/hidden-classes)
- [[----/--/--] - Stack trace API](https://v8.dev/docs/stack-trace-api) ✅
- [[----/--/--] - V8 Torque user manual](https://v8.dev/docs/torque) ✅
- [[----/--/--] - V8 Torque builtins](https://v8.dev/docs/torque-builtins)
- [[----/--/--] - CodeStubAssembler builtins](https://v8.dev/docs/csa-builtins)
- [[----/--/--] - Built-in functions](https://v8.dev/docs/builtin-functions) ✅
- [[----/--/--] - Investigating memory leaks](https://v8.dev/docs/memory-leaks)
- [[----/--/--] - The Rule Of 2](https://chromium.googlesource.com/chromium/src/+/refs/heads/main/docs/security/rule-of-2.md)
- [[----/--/--] - CHECK(), DCHECK() and NOTREACHED()](https://chromium.googlesource.com/chromium/src/+/main/styleguide/c++/checks.md) ✅

## CVEs Walkthrough

- [[2021/06/09] - CVE-2021-30551: Chrome Type Confusion in V8](https://googleprojectzero.github.io/0days-in-the-wild/0day-RCAs/2021/CVE-2021-30551.html)
- [[2021/08/16] - Exploiting CVE-2021-21225 and disabling W^X](https://tiszka.com/blog/CVE_2021_21225_exploit.html)
- [[2021/08/16] - A Bug's Life: CVE-2021-21225](https://tiszka.com/blog/CVE_2021_21225.html)
- [[2022/03/11] - Exploit Development: Browser Exploitation on Windows - CVE-2019-0567, A Microsoft Edge Type Confusion Vulnerability](https://connormcgarr.github.io/type-confusion-part-1/)
- [[2022/06/12] - Root Cause Analysis of CVE-2021-21224](https://anvbis.au/posts/root-cause-analysis-of-cve-2021-21224/)
- [[2022/12/06] - TheHole New World - how a small leak will sink a great browser (CVE-2021-38003)](https://starlabs.sg/blog/2022/12-the-hole-new-world-how-a-small-leak-will-sink-a-great-browser-cve-2021-38003/) ✅
- [[2024/01/19] - Google Chrome V8 CVE-2024-0517 Out-of-Bounds Write Code Execution](https://blog.exodusintel.com/2024/01/19/google-chrome-v8-cve-2024-0517-out-of-bounds-write-code-execution/)
- [[2024/02/24] - Analyzing the Google Chrome V8 CVE-2024-0517 Out-of-Bounds Code Execution Vulnerability](https://dev.to/tutorialboy/analyzing-the-google-chrome-v8-cve-2024-0517-out-of-bounds-code-execution-vulnerability-28i3)
- [[2024/05/02] - CVE-2024-2887: A Pwn2Own Winning Bug in Google Chrome](https://www.zerodayinitiative.com/blog/2024/5/2/cve-2024-2887-a-pwn2own-winning-bug-in-google-chrome)
- [[2024/08/14] - V8 CVE-2021-21224 Renderer RCE Root Cause Analysis](https://s1r1us.ninja/posts/v8-rca/)
- [[2024/08/14] - CVE-2024-0517 Chrome V8 Out of Bounds Write](https://bnovkebin.github.io/blog/CVE-2024-0517/)
- [[2024/08/30] - CVE-2024-5274: A Minor Flaw in V8 Parser Leading to Catastrophes](https://www.darknavy.org/blog/cve_2024_5274_a_minor_flaw_in_v8_parser_leading_to_catastrophes/)
- [[2024/09/19] - Zooming in on CVE‑2024‑7965](https://bi.zone/eng/expertise/blog/analiz-uyazvimosti-cve-2024-7965/)
- [[2024/11/14] - Firefox Animation CVE-2024-9680](https://dimitrifourny.github.io/2024/11/14/firefox-animation-cve-2024-9680.html) ✅
- [[2024/12/12] - CVE-2024-12695 Incorrect implementation of the fast path in Object.assign() lead to memory corruption](https://issues.chromium.org/issues/383647255)
- [[2025/06/20] - CVE-2025-5959](https://linz04.github.io/2025/06/20/CVE-2025-5959/)
- [[2025/08/--] - CVE-2025-6554](https://gist.github.com/mistymntncop/37c652c2bf7373b4aa33bb50f52ee0f2) ✅
- [[----/--/--] - CVE-2024-0517 (Out of Bounds Write in V8)](https://cwresearchlab.co.kr/entry/CVE-2024-0517-Out-of-Bounds-Write-in-V8?category=1154737)

## Presentations

- [[2016/11/11] - Turbofan IR](https://docs.google.com/presentation/d/1Z9iIHojKDrXvZ27gRX51UxHD-bKf1QcPzSijntpMJBM)
- [[2019/--/--] - Attacking Turbofan TyphoonCon 2019 - Seoul](https://doar-e.github.io/presentations/typhooncon2019/AttackingTurboFan_TyphoonCon_2019.pdf) ✅
- [[2021/--/--] - CS 253: Web Security Browser architecture, Writing secure code](https://web.stanford.edu/class/cs253/lectures/Lecture%2020.pdf)
- [[2022/11/11] - Time-Traveling JIT Bugs](https://powerofcommunity.net/assets/v0/poc2022/ManfredPaul.pdf)
- [[2024/08/--] - Achilles' Heel of JS Engines: Exploiting Modern Browsers During WASM Execution](https://i.blackhat.com/BH-US-24/Presentations/US24-Liu-Achilles-Heel-of-JS-Engines-Exploiting-Modern-Browsers-During-WASM-Execution.pdf)
- [[2024/08/--] - Super Hat Trick Exploit Chrome and Firefox Four Times](https://i.blackhat.com/BH-US-24/Presentations/US24-Xiao-Super-Hat-Trick-Exploit-Chrome-and-Firefox.pdf)
- [[2024/11/--] - WebAssembly Is All You Need - Exploiting Chrome and the V8 Sandbox 10+ times with WASM](https://github.com/leesh3288/talks/blob/main/poc2024%2F%5BPOC2024%5D%20WebAssembly%20Is%20All%20You%20Need%20-%20Exploiting%20Chrome%20and%20the%20V8%20Sandbox%2010%2B%20times%20with%20WASM.pdf)
- [[2024/12/04] - V8 WebAssemploit](https://docs.google.com/presentation/d/13DvdxMV_go5z-QMSKjMoXeNvk1JWDXJRIudMUsRbV_0)
- [[2024/--/--] - Fuzzing for complex bugs across languages in JS Engines](https://powerofcommunity.net/assets/v0/poc2024/Carl%20Smith,%20Fuzzing%20for%20complex%20bugs%20across%20languages%20in%20JavaScript%20Engines.pdf)
- [[2024/--/--] - Fake it till you make it: Bypassing V8 Sandbox by constructing a fake Isolate](https://powerofcommunity.net/assets/v0/poc2024/Jaewon%20Min%20&%20Kaan%20Ezder,%20Fake%20it%20till%20you%20make%20it%20-%20Bypassing%20V8%20Sandbox%20by%20constructing%20a%20fake%20Isolate.pdf)
- [[----/--/--] - TurboFan JIT Design](https://docs.google.com/presentation/d/1sOEF4MlF7LeO7uq-uThJSulJlTh--wgLeaVibsbb3tc)

## Talks

- [[2008/09/15] - V8: an open source JavaScript engine](https://youtu.be/hWhMKalEicY?feature=shared)
- [[2009/06/02] - Google I/O 2009 - V8: ..High Performance JavaScript Engine](https://youtu.be/FrufJFBSoQY?feature=shared)
- [[2017/05/16] - Franziska Hinkelmann: JavaScript engines - how do they even? | JSConf EU](https://youtu.be/p-iiEDtpy6I?si=9_dzr7djvr9rBYB2) ✅
- [[2018/04/26] - Fuzzing Javascript Engines for Fun and Pwnage - Areum Lee & Jeonghoon Shin](https://youtu.be/1WWb2HOqjcU?si=EPEOrxxIScu4sHp9)
- [[2018/06/14] - JavaScript Engines: The Good Parts™ - Mathias Bynens & Benedikt Meurer - JSConf EU 2018](https://youtu.be/5nmpokoRaZI?si=Ak_La989B_4s8E4k) ✅
- [[2018/11/06] - Orinoco: The new V8 Garbage Collector Peter Marshall](https://youtu.be/Scxz6jVS4Ls?feature=shared)
- [[2020/04/06] - Practical Exploitation of Math.random on V8](https://youtu.be/_Iv6fBrcbAM?feature=shared) ✅
- [[2020/12/01] - Chromium University](https://www.youtube.com/playlist?list=PL9ioqAuyl6ULp1f36EEjIN1vSBEfsb-0a)
- [[2021/01/16] - HackTheBox - Rope2](https://www.youtube.com/watch?v=m6Fpc3zxrJg) ✅
- [[2022/11/17] - Breaking the Chrome Sandbox with Mojo](https://www.youtube.com/watch?v=qhhJCLy0YBA)
- [[2023/05/30] - OffensiveCon23 - Samuel Groß & Carl Smith - Advancements in JavaScript Engine Fuzzing](https://youtu.be/Yd9m7e9-pG0?feature=shared)
- [[2023/10/23] - #OBTS v6.0: "Safari, Hold Still for NaN Minutes!" - Javier Jimenez & Vignesh Rao](https://youtu.be/k1wEJFqirT8)
- [[2024/06/04] - OffensiveCon24 - Samuel Groß - The V8 Heap Sandbox](https://youtu.be/5otAw81AHQ0?si=Bkovbqrg9YhN8Mt) ✅
- [[2024/10/14] - Chrome Browser Exploitation: from zero to heap sandbox escape](https://www.youtube.com/live/VwWPzRceCgs?si=6oP3o1De9Cqaa_Cs&t=5821) ✅
- [[2024/10/29] - Attacking V8, Ayman - BSides Canberra 2024](https://youtu.be/cTvbFGhcTgs?si=c_-kCKBZS9n9LpgN)
- [[2024/11/01] - Introduction to JavaScript and V8 for Browser Exploitation](https://www.youtube.com/watch?v=ctKCfXOgZ-M)
- [[2025/04/11] - WebAssembly Is All You Need:Exploiting Chrome and the V8 Sandbox 10+ times with WASM](https://www.youtube.com/watch?v=nb1so4P-4J8)
- [[2024/08/31] - Off-By-One 2024 Day 1- Exploring WebKit’s Just In Time Compilation: Vignesh S Rao](https://youtu.be/9rt9ErQKnf8?feature=shared)

## CTFs Writeups

- [[2019/01/02] - Exploiting Chrome V8: Krautflare (35C3 CTF 2018)](https://www.jaybosamiya.com/blog/2019/01/02/krautflare/)
- [[2019/01/02] - Exploiting the Math.expm1 typing bug in V8](https://abiondo.me/2019/01/02/exploiting-math-expm1-v8/)
- [[2019/01/28] - Introduction to TurboFan](https://doar-e.github.io/blog/2019/01/28/introduction-to-turbofan/) ✅
- [[2019/12/13] - Exploiting v8: \*CTF 2019 oob-v8](https://faraz.faith/2019-12-13-starctf-oob-v8-indepth/) ✅
- [[2020/09/28] - DownUnderCTF 2020: Is this pwn or web?](https://seb-sec.github.io/2020/09/28/ductf2020-pwn-or-web.html) ✅
- [[2021/04/06] - Turboflan PicoCTF 2021 Writeup (v8 + introductory turbofan pwnable)](https://www.willsroot.io/2021/04/turboflan-picoctf-2021-writeup-v8.html) ✅
- [[2021/08/23] - corCTF 2021 - outfoxed](https://ret2.life/posts/corCTF-2021/)
- [[2021/--/--] - HITCON CTF 2021: Hole](https://hoefler.dev/articles/hole.html)
- [[2022/02/06] - DiceCTF 2022 - memory hole](https://blog.kylebot.net/2022/02/06/DiceCTF-2022-memory-hole/) ✅
- [[2022/02/06] - Dice CTF Memory Hole: Breaking V8 Heap Sandbox](https://mem2019.github.io/jekyll/update/2022/02/06/DiceCTF-Memory-Hole.html)
- [[2022/07/03] - Google CTF 2022 d8: From V8 Bytecode to Code Execution](https://mem2019.github.io/jekyll/update/2022/07/03/Google-CTF.html)
- [[2022/11/28] - HITCON CTF 2022 -- Fourchain - Browser](https://bruce30262.github.io/hitcon-ctf-2022-fourchain-browser/)
- [[2022/12/24] - KITCTFCTF 2022 V8 Heap Sandbox Escape](https://ju256.de/posts/kitctfctf22-date/) ✅
- [[2023/08/--] - Writeup for v8box](https://github.com/google/google-ctf/tree/main/2023/quals/sandbox-v8box/solution) ✅
- [[2023/12/07] - Start Your Engines - Capturing the First Flag in Google's New v8CTF](https://www.madstacks.dev/posts/Start-Your-Engines-Capturing-the-First-Flag-in-Google%27s-New-v8CTF/)
- [[2023/12/30] - ASIS CTF Finals 2023: isWebP.js](https://chovid99.github.io/posts/asis-ctf-finals-2023/)
- [[2024/03/02] - v8 CTF out of bounds 2019: Installing v8 Part 1](https://medium.com/@ndsetobol/v8-ctf-out-of-bounds-2019-installing-v8-e5cd21cbf2de) ✅
- [[2024/03/12] - v8 CTF out of bounds 2019 Part 2: What they don’t tell you about setting up your GDB.](https://medium.com/@ndsetobol/v8-ctf-out-of-bounds-2019-part-2-what-they-dont-tell-you-about-setting-up-your-gdb-541411cb8f53) ✅
- [[2024/05/26] - Exploiting V8 at openECSC](https://lyra.horse/blog/2024/05/exploiting-v8-at-openecsc/) ✅
- [[2024/07/14] - Breaking V8 Sandbox with Trusted Pointer Table](https://mem2019.github.io/jekyll/update/2024/07/14/HITCON.html)
- [[2024/10/--] - openECSC 2024 - Final Round: Backfired](https://github.com/ECSC2024/openECSC-2024/blob/main/round-4/pwn03/writeup.md)
- [[2024/12/24] - BackdoorCTF 2024 - V8Box](https://linz04.github.io/2024/12/24/BackdoorCTF-2024-V8Box/) ✅
- [[2024/--/--] - AliyunCTF 2024 - BadApple](https://zhuanlan.zhihu.com/p/694555241)
- [[2025-05-14] - DEF CON CTF Quals 2025 memorybank Write-Up: Investigating V8 Garbage Collector](https://ouuan.moe/post/2025/04/memorybank)
- [[2025/06/05] - Advanced CTF Challenge Write-up: "Chrome Sandbox Escape via V8 JIT Compiler Vulnerability"](https://blog.csdn.net/2402_86373248/article/details/148432633) ✅

## Papers

- [[2013/10/28] - An Intermediate Representation for Speculative Optimizations in a Dynamic Compiler](https://dl.acm.org/doi/10.1145/2542142.2542143)
- [[2014/06/12] - Allocation Folding Based on Dominance](https://static.googleusercontent.com/media/research.google.com/ko//pubs/archive/42478.pdf)
- [[2015/--/--] - The Security Architecture of the Chromium Browser](https://seclab.stanford.edu/websec/chromium/chromium-security-architecture.pdf)
- [[2020/05/21] - Repairing and Mechanising the JavaScript Relaxed Memory Model](https://www.cl.cam.ac.uk/~jp622/repairing_javascript.pdf)
- [[2022/11/--] - DUMPLING: Fine-grained Differential JavaScript Engine Fuzzing](https://nebelwelt.net/files/25NDSS2.pdf)
- [[2024/02/19] - CovRL: Fuzzing JavaScript Engines with Coverage-Guided Reinforcement Learning for LLM-based Mutation](https://arxiv.org/pdf/2402.12222)
- [[2024/08/--] - White Paper (Super Hat Trick: Exploit Chrome and Firefox Four Times)](https://i.blackhat.com/BH-US-24/Presentations/US24-Xiao-Super-Hat-Trick-Exploit-Chrome-and-Firefox-Four-Times-wp.pdf) ✅

## More

- [V8 Resources](https://mrale.ph/v8/resources.html)
- [Understanding Chrome V8](https://hackernoon.com/u/huidou)
- [learning-v8](https://github.com/danbev/learning-v8)
- [v8-perf](https://github.com/thlorenz/v8-perf)

P.S: Note that I don't support Google, nor do I condone [Google’s support of Israel](https://www.aljazeera.com/news/2024/4/23/what-is-project-nimbus-and-why-are-google-workers-protesting-israel-deal) in its ethnic cleansing of Palestinian people. This is simply me researching an open-source project that is widely used in various applications.

P.S.S: The articles listed above are included solely for their technical content; the views, backgrounds, or actions of the authors do not reflect my endorsement.
