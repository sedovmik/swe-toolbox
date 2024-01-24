- ### **Inbox**
	- https://news.ycombinator.com/item?id=38499134
	- https://bencher.dev/docs/reference/prior-art/
- ### Design
	- Algorithms and Data Structures
		- Collections
			- [Competitive programming](https://cp-algorithms.com/)
			- [Algorithmica (ru)](https://ru.algorithmica.org/)
			- [Algorithms for Modern Hardware](https://en.algorithmica.org/hpc/)
		- Algorithms
			- Rating: [TrueSkill](https://trueskill.org/), [OpenSkill](https://openskill.me/en/stable/)
			- Ternary search ([link](https://en.wikipedia.org/wiki/Ternary_search))
			- [Kalman filter](https://www.bzarg.com/p/how-a-kalman-filter-works-in-pictures/)
			- Functional Optics
			- Peak Exponentially Weighted Moving Average
				- [Load Balancing](https://samwho.dev/load-balancing/)
				- [Moving averages](https://gregorygundersen.com/blog/2022/06/04/moving-averages/)
			- [Operational Transformation](https://medium.com/@amberovsky/operational-transformations-as-an-algorithm-for-automatic-conflict-resolution-3bf8920ea447)
				- [Visualisation](https://operational-transformation.github.io/)
			- [Marching squares (cubes)](https://www.youtube.com/watch?v=6oMZb3yP_H8)
			- [Peterson's algorithm](https://en.wikipedia.org/wiki/Peterson%27s_algorithm)  
				Allows two or more processes to share a single-use resource without conflict, using only shared memory
			- [Metaphone](https://en.wikipedia.org/wiki/Metaphone)  
				a phonetic algorithm that maps similar-sounding words to the same pronunciation. Example: [transciptions for wines](https://vikramoberoi.com/helping-sommeliers-inventory-wine-faster-with-whisper-duckdb-and-metaphone/)
			- Bits
				- Gray code
				- [Number of leading zeros](https://en.wikipedia.org/wiki/Find_first_set)
			- Regex
				- `/^1?$|^(11+?)\1+$/` check for prime ("1" times 'num'), [see](https://www.noulakaz.net/2007/03/18/a-regular-expression-to-check-for-prime-numbers/)
			- [Karnaugh map](https://en.wikipedia.org/wiki/Karnaugh_map): boolean
			- [S3-FIFO](https://blog.jasony.me/system/cache/2023/08/01/s3fifo) (LRU Cache eviction)
				- [SIEVE](https://cachemon.github.io/SIEVE-website/blog/2023/12/17/sieve-is-simpler-than-lru/) (simpler, more efficient than LRU)
			- Rubik's Cube
				- [State-of-art algorithms](https://en.wikipedia.org/wiki/Optimal_solutions_for_the_Rubik%27s_Cube)
				- [God's number is 20](http://cube20.org/)
				- [Meet in the middle](https://en.wikipedia.org/wiki/Meet-in-the-middle_attack) - space-tradeoff when number of paths in a graph grows exponentially
			- [FSRS](https://github.com/open-spaced-repetition/fsrs4anki/wiki/ABC-of-FSRS) - a modern spaced repetition
		- Data Structures
			- Compressed BitSet: [Roaring Bitmap](https://roaringbitmap.org/about/)
			- Probabilistic data structures
				- Membership: Bloom Filter, Cuckoo Filter (removes are possible)
					- [murmur hashing + bloom filter](https://www.sderosiaux.com/articles/2017/08/26/the-murmur3-hash-function--hashtables-bloom-filters-hyperloglog/)
					- Chi-Square
				- Counting/Cardinality: HyperLogLog, HLL++ from Google
					- [Explainer](https://www.youtube.com/watch?v=lJYufx0bfpw&lc=UgxjGYRN4VrlfSqYxr94AaABAg)
				- Frequence: Count-Min Sketch
				- Similarity: MinHash, SimHash
				- Rank: q-digest, t-digest
			- Data-oriented design
				- [D-O-D book](https://www.dataorienteddesign.com/dodbook/dodmain.html)
			- Skip list
			- Union find (connected components)
			- Splay Tree (effective caching)
			- [Piece table](https://darrenburns.net/posts/piece-table/)
				- [Text Buffer Reimplementation](https://code.visualstudio.com/blogs/2018/03/23/text-buffer-reimplementation)
			- E-Graph: [youtube intro](https://www.youtube.com/watch?v=ap29SzDAzP0) to [Rust lib egg](https://egraphs-good.github.io/)
			- [Uber's H3 geo](https://h3geo.org/) (geo-index)
		- Functional Programming
			- GADTs
			- [fp-course](https://github.com/system-f/fp-course)
			- Category theory
				- [yoneda lemma](https://www.math3ma.com/blog/the-yoneda-perspective)
		- Patterns
			- ActionCard, Uber ([link](https://www.uber.com/en-SE/blog/developing-the-actioncard-design-pattern/))
			- Out of the Tar Pit ([link](https://curtclifton.net/papers/MoseleyMarks06a.pdf))
			- Unidirectional
				- Mobius
				- MVI
				- CashApp arch: [Circuit](app://dynalist.io/slackhq.github.io/circuit/)
				- Square Workflow ([link](https://square.github.io/workflow/))
		- Formal
			- Z3 Solver
			- Busy Beaver
				- Gögel's incompleteness ([link](https://busy-beavers.tigyog.app/incompleteness))
				- Rice's theorem ([link](https://busy-beavers.tigyog.app/rice))
			- TLA: [learntla](https://learntla.com/)
			- Zero Knowledge Proof ([link](https://en.wikipedia.org/wiki/Zero-knowledge_proof#The_Ali_Baba_cave))
			- [Prusti](https://www.pm.inf.ethz.ch/research/prusti.html)  
				A static verifier for Rust
			- [Alloy 6](https://haslab.github.io/formal-software-design/index.html)
	- Hall of Fame
		- Dynamic proxy
		- Code generation, annotation processing
			- javapoet, kotlinpoet
			- [google/compile-testing](https://github.com/google/compile-testing): Annotation processors testing
		- Redis
	- Architecture
		- [Transitional architecture](https://martinfowler.com/articles/patterns-legacy-displacement/transitional-architecture.html)
		- [Napkin-math](https://github.com/sirupsen/napkin-math) (numbers for system design)
		- [Zalando API guide](https://opensource.zalando.com/restful-api-guidelines/)
	- Domain
		- [Payments 101](https://github.com/juspay/hyperswitch/wiki/Payments-101-for-a-Developer)
		- [Falsehoods](https://github.com/kdeldycke/awesome-falsehood)
			- [Time](https://infiniteundo.com/post/25326999628/falsehoods-programmers-believe-about-time)
			- [Names](https://www.kalzumeus.com/2010/06/17/falsehoods-programmers-believe-about-names/)
		- A/B Testing
			- [Common mistakes](https://posthog.com/blog/ab-testing-mistakes)
- ### Communication
	- Visualization, Explanations
		- [C4 Model](https://c4model.com/)
		- [Excalidraw](https://excalidraw.com/)
		- graphviz
		- [D2](https://github.com/terrastruct/d2)
		- [A periodic table of visualization methods](https://www.visual-literacy.org/periodic_table/periodic_table.html)
		- Presentations
			- [Marp](https://marp.app/)
			- [Deckset](https://www.deckset.com/) ($)
			- [Motion Canvas](https://motioncanvas.io/docs/presentation/)
			- 3b1b's [Manim](https://github.com/3b1b/manim)
	- Frameworks
		- SMART  
			Specific, Measurable, Assignable, Realistic, Time-related
		- STAR  
			Situation, Task, Action, Result
		- [ADEPT](https://betterexplained.com/articles/adept-method/)  
			Analogy, Diagram, Example, Plain-English, Technical
		- [CIA Phoenix List](https://dynalist.io/d/Ww0BR0J0gqVBF2YR9cmEdKmi)  
			How the CIA approaches problem solving
		- [Technical discussion questions](https://dynalist.io/d/9H3H0l23NikJKPtTRQjhyedO)
		- BLUF (Bottom line up front), Mynto Pyramid
		- Product Frameworks ([link](https://www.product-frameworks.com/index.html))
			- [DIBB](https://blog.crisp.se/2016/06/08/henrikkniberg/spotify-rhythm?ref=https://product-frameworks.com)  
				Data, Insight, Belief, Bet
			- [Kano Model](https://www.product-frameworks.com/kano-model.html)
			- Amazon's [Working Backwards](https://www.product-frameworks.com/Amazon-Working-Backwards.html)
			- [Goals, Signals, Metrics](https://linkedin.github.io/dph-framework/goals-signals-metrics.html)
	- [Narrative scripting](https://www.inklestudios.com/ink/)
	- Mental Models
		- [Logical fallacies](https://bitcoinprimeapp.de/logicalfallacies/)
		- [Tools for better thinking](https://untools.co/)
	- [Awesome list on leadership](https://github.com/LappleApple/awesome-leading-and-managing)
- ### Development
	- Languages
		- [Dhall](https://dhall-lang.org/)  
			configuration files
		- [Copilot](https://copilot-language.github.io/)  
			Haskell, which generates C
		- [Zig](https://ziglang.org/)
		- Lua (LuaJIT)
		- [Koka](https://koka-lang.github.io/koka/doc/index.html)  
			Language with Effect Types and Handlers
	- Code Navigation/Exploration
		- [Semgrep](https://semgrep.dev/docs/supported-languages/)
		- [Code Churn](https://engineering.ramp.com/what-matters-suffers)  
			```  
			git log --name-only --pretty=format: | sort | uniq -c | sort -nr | head -n 30  
			```
		- Structural [Diff](https://github.com/Wilfred/difftastic)  
			```[diff]  
			external = difft```
		- [Trustfall](https://github.com/obi1kenobi/trustfall)  
			Join/Query any datasources
		- [Kythe.io](https://kythe.io/examples/)
		- [Quicktype](https://github.com/quicktype/quicktype)  
			Generate types and converters from JSON, Schema, and GraphQL
		- [Typesense](https://typesense.org/docs/)  
			C++ search engine,
	- Static Analysis
		- difflint, soon
		- [Compose Rules](https://twitter.github.io/compose-rules/)
	- Code Review
		- [Conventional comments](https://conventionalcomments.org/)
		- [Checklist for commit messages](https://kychua.github.io/commit-message-guide)
		- [Checklist for Java Concurrency](https://github.com/code-review-checklists/java-concurrency)
	- Libraries
		- Android
			- [Code search](https://cs.android.com/)
			- Libraries
				- Request prio for OkHttp: [link](https://google.github.io/horologist/network-awareness/)
			- UI
				- [Cycler](https://github.com/square/cycler)
				- [Appyx navigation](https://bumble-tech.github.io/appyx/)
			- Testing
				- [Maestro](https://maestro.mobile.dev/)
				- Security analysis: [Mariana Trench](https://github.com/facebook/mariana-trench)
			- Tooling
				- Debug.(start|stop)MethodTracing(name)  
					adb pull /storage/self/primary/Android/data/[package]/files/[name].trace  
					dmtracedump -o [name].trace
		- Web
			- [Svelte](https://svelte.dev/)
			- [PETAL](https://changelog.com/posts/petal-the-end-to-end-web-stack)
				- [Tailwindcss](https://tailwindcss.com/)
			- [Icons](https://heroicons.com/)
		- Backend
			- Databases
				- [Memgraph](https://memgraph.com/)
				- [sqlite](https://sqlite.org/index.html)
					- Hosting DB, making http range requests ([link](https://phiresky.github.io/blog/2021/hosting-sqlite-databases-on-github-pages/))
				- [Apache Arrow](https://arrow.apache.org/)  
					A language-independent columnar memory format for flat and hierarchical data, organized for efficient analytic operations on modern hardware like CPUs and GPUs
				- [Ibis](https://ibis-project.org/): DB interop
				- [Malloy](https://www.malloydata.dev/language): Higher-level SQL by Google
		- Exotic
			- Rule engines
				- [GoRules](https://gorules.io/) (Rust, Node.js, Web Editor)
				- [Evrete](https://www.evrete.org/guides/#showcase) (JVM)
			- OCaml [Incremental](https://opensource.janestreet.com/incremental/)  
				How to recalculate a spreadsheet ([link](https://lord.io/spreadsheets/))
		- General
			- io_uring ([pdf](https://kernel.dk/io_uring.pdf))
				- [Awesome list](https://github.com/espoal/awesome-iouring)
			- WASM
			- [eBPF](https://ebpf.io/)
			- CRDT
				- [Intro](https://vlcn.io/articles/intro-to-crdts)
				- Web: [yjs](https://github.com/yjs/yjs)
				- Rust: [automerge](https://automerge.org/), [cola](https://nomad.foo/blog/cola)
			- SIMD
			- mmap
				- [100x faster using mmap() instead of stdio](https://justine.lol/mmap/)
			- [libphonenumber](https://github.com/google/libphonenumber)
			- [resilience4j](https://resilience4j.readme.io/v1.7.0/docs/circuitbreaker): CircuitBreaker, RateLimiter, ..
			- [cosmopolitan libc](https://justine.lol/cosmopolitan/): build-once run-anywhere
				- [rust + cosmopolitan](https://ahgamut.github.io/2022/07/27/ape-rust-example/)
				- [debugging using --ftrace and --strace](https://ahgamut.github.io/2022/10/23/debugging-c-with-cosmo/)
- ### Building
	
	- In-depth comparison: [diffoscope](https://diffoscope.org/)  
		And other docs/tools from [reproducible-builds.org](https://reproducible-builds.org/tools/)
	- Gradle:
		- [Gradle Profiler](https://github.com/gradle/gradle-profiler)
		- [Affected modules by commit](https://github.com/dropbox/AffectedModuleDetector)
	- Ninja
		- [Intro](https://jvns.ca/blog/2020/10/26/ninja--a-simple-way-to-do-builds/)
		- [Meson](https://mesonbuild.com/Tutorial.html) generates ninja
	- [entr](http://eradman.com/entrproject/): run arbitrary commands when files change
		- [watchman](https://facebook.github.io/watchman/) as well
- ### Testing
	
	- Quickcheck: [java](https://github.com/pholser/junit-quickcheck)
		- [Debugging C with Haskell's Divisible](http://www.michaelburge.us/2017/09/27/delta-debugging-in-haskell.html?utm_source=pocket_saves)
	- GraphWalker: [java](https://graphwalker.github.io/)
	- [awaitility](https://github.com/awaitility/awaitility)  
      > await().atMost(5, SECONDS).until(..)
	- [Chaos Engineering](https://en.wikipedia.org/wiki/Chaos_engineering)
	- [Pact.io](https://pact.io/)
	- [MockNeat](https://www.mockneat.com/tutorial/): Mock data java generator  
		Ints, Bools, Addresses, Names, Credit Cards, Dates, Emails, Hosts,
	- Articles
		- [Test Desiderata](https://kentbeck.github.io/TestDesiderata/)
		- On Tests (why, flakiness, limits): [link](https://abseil.io/resources/swe-book/html/ch11.html)
		- We need to talk about testing: [link](https://dannorth.net/2021/07/26/we-need-to-talk-about-testing/)
		- Testing without mocks: [link](https://www.jamesshore.com/v2/projects/nullables/testing-without-mocks)
		- No more E2E: [link](https://testing.googleblog.com/2015/04/just-say-no-to-more-end-to-end-tests.html)
	- Test Data
		- [Big list of naugthy strings](https://github.com/minimaxir/big-list-of-naughty-strings)
		- [RFC 8259 compliant JSON](https://github.com/nst/JSONTestSuite)
- ### Runtime
	- Performance
		- [Perfetto](https://perfetto.dev/)
		- [Async-profiler](https://github.com/async-profiler/async-profiler)
		- perf, simple-perf
		- [getrusage](https://justine.lol/rusage/)
		- [coz](https://github.com/plasma-umass/coz): Casual Profilling
		- [Firefox Profiler](https://profiler.firefox.com/docs/#/)
			- [Beyond the web](https://mostlynerdless.de/blog/2023/01/31/firefox-profiler-beyond-the-web/)
		- [eatmydata](https://manpages.debian.org/testing/eatmydata/eatmydata.1.en.html)
	- Networking
		- Protobuf
	- Debugging
		- [Sanitizers](https://github.com/google/sanitizers): ASAN, TSAN, ..
		- Valgrind
		- Mozilla RR: [link](https://rr-project.org/)
			- [Chaos Mode](https://robert.ocallahan.org/2016/02/introducing-rr-chaos-mode.html)
		- Fuzzing
		- strace/ltrace/ktrace/ftrace/atrace
		- Facebook Flipper
		- LD_PRELOAD  
			Unrandomize, bullet time, record/monitor IO, sandbox apps, [uncompress files](http://www.zlibc.linux.lu/index.html), fix bugs, access own memory
		- Acticles
			- [What a good debugger can do](https://werat.dev/blog/what-a-good-debugger-can-do/)
			- State of Debugging ([video](https://www.youtube.com/watch?v=yCK0-vWmAsk))
			- [Debugging guide](https://www.robotsforroboticists.com/debugging-guide/)  
				Divide and conquer, Change one thing at the time, Keep an audit trail, Check the obvious things, Get a fresh view, Avoid making things worse
			- [Browser debugging tricks](https://alan.norbauer.com/articles/browser-debugging-tricks)
	- Reverse Engineering
		- [Frida](https://frida.re/)
			- [Awesome list](https://github.com/dweinstein/awesome-frida)
		- [RE on Android](https://mobile-security.gitbook.io/mobile-security-testing-guide/android-testing-guide/0x05c-reverse-engineering-and-tampering)
- ### Productivity
	- MacOS
		- [Raycast](app://dynalist.io/raycast.com)
		- [Syncthing](https://syncthing.net/)
		- [Obsidian](https://obsidian.md/)
		- Dato
		- BitWarden
		- Tuple ($)
		- [rcmd ($)](https://lowtechguys.com/rcmd/)
		- [Maccy](https://formulae.brew.sh/cask/maccy)
		- [Shottr](https://shottr.cc/)
	- Command Line
		- fzf
		- jq ([jj](https://github.com/tidwall/jj) - streaming alternative for large files)
		- [fq](https://github.com/wader/fq) (jq for binary)
		- ripgrep
		- [Miller](https://github.com/johnkerl/miller): jq for csv
		- [DuckDB](https://duckdb.org/2023/03/03/json.html): sql for json, csv
			- [CMD IDE](https://harlequin.sh/)
		- Media: ImageMagick, ffmpeg
		- rsync
		- nc
		- tcpdump
		- wireshark
- ### Collections
	- [The book of secret knowledge](https://github.com/trimstray/the-book-of-secret-knowledge)  
		A similar list of tools
	- [Online playgrounds](https://jvns.ca/blog/2023/04/17/a-list-of-programming-playgrounds/)
