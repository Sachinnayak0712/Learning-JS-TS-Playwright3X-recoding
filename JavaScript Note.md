 # JavaScript Keywords

JavaScript **keywords** are reserved words with a special meaning in the language. They form statements, declare variables and functions, control program flow, and perform operations. They generally cannot be used as ordinary variable or function names. A few words are reserved only in certain contexts, and some older reserved words are kept for compatibility.

## Core keywords and their purposes

| Keyword(s) | Purpose |
|---|---|
| `break`, `continue` | Exit a loop or switch, or skip to the next loop iteration. |
| `if`, `else`, `switch`, `case`, `default` | Choose which code to run based on conditions or a value. |
| `for`, `while`, `do` | Repeat code in loops. |
| `try`, `catch`, `finally`, `throw` | Raise and handle errors; `finally` runs after the try/catch sequence. |
| `debugger` | Pause execution when a debugger is attached. |
| `var`, `let`, `const` | Declare variables. `let` and `const` are block-scoped; `const` prevents reassignment. `var` is function-scoped (or global-scoped). |
| `function`, `return` | Declare a function and return a value from it. |
| `class`, `extends`, `super` | Define a class, inherit from another class, and access its parent implementation. |
| `new` | Create an object using a constructor. |
| `this` | Refer to the current receiver/context (its value depends on how a function is called). |
| `import`, `export` | Use and expose module bindings. |
| `async`, `await` | Work with promises in asynchronous functions. `async` is contextual; `await` is restricted by context. |
| `yield` | Pause a generator function and optionally produce or receive a value. |
| `in`, `instanceof` | Test for a property in an object, or whether an object matches a constructor's prototype chain. |
| `typeof`, `delete`, `void` | Get a value's type as a string, remove an object property, or evaluate an expression to `undefined`. |
| `with` | Extends name lookup using an object's properties; discouraged and unavailable in strict mode. |

## Complete keyword and reserved-word list

The list below includes standard JavaScript keywords, literal tokens, context-dependent keywords, and legacy reserved words. Whether some contextual or legacy words are permitted as identifiers depends on syntax and strict mode.

| Group | Words |
|---|---|
| Control flow and exceptions | `break`, `case`, `catch`, `continue`, `default`, `do`, `else`, `finally`, `for`, `if`, `return`, `switch`, `throw`, `try`, `while`, `with` |
| Declarations, functions, and classes | `class`, `const`, `extends`, `function`, `let`, `var`, `yield` |
| Modules and asynchronous code | `async`, `await`, `export`, `import` |
| Operators and object-related operations | `delete`, `in`, `instanceof`, `new`, `super`, `this`, `typeof`, `void` |
| Other statement | `debugger` |
| Literal tokens | `false`, `null`, `true` |
| Reserved for future use / legacy reserved words | `enum`, `implements`, `interface`, `package`, `private`, `protected`, `public`, `static` |
| Additional legacy reserved words (primarily Java-like) | `abstract`, `boolean`, `byte`, `char`, `double`, `final`, `float`, `goto`, `int`, `long`, `native`, `short`, `synchronized`, `throws`, `transient`, `volatile` |

**Note:** `of`, `get`, `set`, and `from` have special meanings in particular syntactic forms, but are not generally reserved keywords. `NaN` and `undefined` are also not keywords; they are global values/identifiers.
s