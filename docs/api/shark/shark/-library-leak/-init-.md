[shark](../../index.md) / [shark](../index.md) / [LibraryLeak](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`LibraryLeak(className: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, leakTrace: `[`LeakTrace`](../-leak-trace/index.md)`, retainedHeapByteSize: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?, pattern: `[`ReferencePattern`](../-reference-pattern/index.md)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)`

A leak found by [HeapAnalyzer](../-heap-analyzer/index.md), where the only path to the leaking object required going
through a reference matched by [pattern](pattern.md), as provided to a [LibraryLeakReferenceMatcher](../-library-leak-reference-matcher/index.md)
instance. This is a known leak in library code that is beyond your control.

