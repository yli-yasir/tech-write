## Programming Language Implementations

Q: **🙋‍♂️Is language x compiled or interpreted?**

A: 💡It depends on the implementation, and implementations can involve both approaches.

### The difference between a programming language and its implementation

A language is a means to express ideas or meaning. A programming language is about **what you want to communicate to the computer**. It's not about how it ends up being executed by the computer.

An **implementation of a programming language** is a system which dictates **how the ideas you have communicated end up being executed** by the machine. Compilation and interpretation are approaches of language implementations.

> 💡 A language can have multiple implementations. 
>
> * The most popular implementation of Python is CPython (written in C). Code is compiled ahead-of-time behind the scenes to bytecode then interpreted at runtime.
> * Another implementation of Python is PyPy (written in RPython). What sets this implementation apart is that it uses JIT compilation which can make it up to 4 times faster than CPython.



### ❓What's a programming language compiler?

A compiler translates a programming language code to other programming language code. Work can be done ahead-of-time (**AOT** compilation) or just in time (**JIT** compilation). This can be done to improve performance or to enable programs to be run somewhere else.

> 🗒️Examples:
>
> * Code is not always compiled to lower level code. 
>   * TypeScript is compiled to JavaScript to be run by the browser.
> * Code may be compiled to bytecode which is then interpreted. 
>   * Java code is compiled into bytecode that is interpreted and run by the JVM.
>   * Python code is compiled into bytecode then interpreted and run by the PVM.
>   * C# code is compiled into the common intermediary language (CIL) bytecode then run by the .NET runtime.

### ❓What's a programming language interpreter?

It's software that has the responsibility of executing bytecode or high level source code by translating it to real-machine code. The job is done during runtime.  

> 🗒️ Some notes:
>
> * The interpreter may achieve its goal in different ways.
> * Some interpreters use JIT compilation.
>   * Modern implementations of JavaScript use JIT compilation.
