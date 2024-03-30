1. Reduce the amount third party library but if removing a third party library is not feasible try other alternatives with reduced bundled size.
2. code splitting through lazy loading. Lazy loading helps to reduce the initial bundle of the website, lazy loading is the process of deferring the loading of a part of our page until the user performs an event.
3. Inline the critical, defer the non-critical.
	CSS is a render blocking resource i.e. it must be processed before the page is rendered. So inlining the critical and deferring the non-critical would increase website performance.
4. Apply lazy-loading/code-splitting techniques to load third party libraries using different React loading patterns