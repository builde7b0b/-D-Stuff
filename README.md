# -D-Stuff
D Lang



The D Programming Language
	Modern convenience. Modeling power. Native efficiency.
  
  
  
  
  D is a language with C-like syntax and static typing. It pragmatically combines efficiency, control, and modeling power, with safety and programmer productivity.
  
Convenience
D allows writing large code fragments without redundantly specifying types, like dynamic languages do. On the other hand, static inference deduces types and other code properties, giving the best of both the static and the dynamic worlds. See example.

Automatic memory management makes for safe, simple, and robust code. D also supports scoped resource management (aka the RAII idiom) and scope statements for deterministic transactional code that is easy to write and read. See example.

Built-in linear and associative arrays, slices, and ranges make daily programming simple and pleasant for tasks, both small and large. See example.


Power
The best paradigm is to not impose something at the expense of others. D offers classic polymorphism, value semantics, functional style, generics, generative programming, contract programming, and more—all harmoniously integrated. See example.

D offers an innovative approach to concurrency, featuring true immutable data, message passing, no sharing by default, and controlled mutable sharing across threads. Read more.

From simple scripts to large projects, D has the breadth to scale with any application's needs: unit testing, information hiding, refined modularity, fast compilation, precise interfaces. Read more.


Efficiency
D compiles naturally to efficient native code.

D is designed such that most "obvious" code is fast and safe. On occasion a function might need to escape the confines of type safety for ultimate speed and control. For such rare cases D offers native pointers, type casts, access to any C function without any intervening translation, manual memory management, custom allocators and even inline assembly code. See example.

The @safe, @trusted, and @system function attributes allow the programmer to best decide the safety-efficiency tradeoffs of an application, and have the compiler check for consistency. Read more.
