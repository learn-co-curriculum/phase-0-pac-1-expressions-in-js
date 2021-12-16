# Expressions in JavaScript

## Learning Goals

- Define "Expression"
- Define "Evaluation"
- Expression and Evaluation with JavaScript
- Identify the Parts of an Expression
- Identify Core Operators in JavaScript

## Introduction

Previously, we saw a tool that allowed us to have a conversation with
JavaScript. This tool is known as a REPL, short for [Read Evaluate Print
Loop][repl]. Code written in the top box will be read and evaluated. The
response, whatever is returned, will appear in the bottom box. For example,
below we have a REPL with a math equation, `10 + 10`, prewritten inside. If you
click the button with the play symbol `▶` above the equation, you should see
`20` appear in the bottom box.

<iframe height="400px" width="100%" src="https://repl.it/@MaxwellBenton2/BumpySereneMicroinstruction?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>

> **Note:** We encourage you to experiment with this and other code examples
> provided in the REPL. In order to do so, you will need to click "open in
> repl.it" in the upper right corner of the REPL window, which will open it in a
> new browser tab. You will also need to create a free account. Once you've done
> that, you will be able to fork the REPL to your account and make changes to
> try things out.

Conversations, we've seen, are the things that result when two individuals — be
they human or machine — communicate _expressions_ to one another.

We've been imprecise in defining "expression" while we were getting the hang of
it. Let's propose formal definitions for _expression_ and _evaluation_.

## Define "Expression"

An expression in a programming language is like a sentence in a spoken language.

Some sentences are simple: "Hello, world." Some sentences are complex: "Only by
learning to live in harmony with your contradictions can you keep it all
afloat."[-Audrey Lorde](https://www.poetryfoundation.org/poets/audre-lorde)

Some expressions are simple: `2`. Some expressions are complex `1 + 2`. Some
expressions are _really_ complex: `10 + (3 * ( (-1) ** 3) + 2) / 18`.

> **Definition**: Expression: A combination of information, called _data_, and
> _symbols_ indicating how to combine _data_, called _operators_.

## Define "Evaluation"

_Evaluation_ is the process of interpreting an expression, according to rules,
to produce a return value.

## Expression and Evaluation with JavaScript

These definitions should align with your experience of having a conversation
with REPLs so far. Think about `255 / 5`. Which parts of the expression are
_data_? Which parts are _operators_?

> **Pro-tip**: Think it through yourself. Which is a given thing (_data_) and
> which parts tell you how to combine things (_operators_)? When reading
> technical documents you can't simply read the answers, you **_have to think
> along_** in order to learn. Active participation tells your brain that this
> stuff is important!

## Identify the Parts of an Expression

The _data_ are: `255` and `5`

The _operator_: is `/`

In this example, there is only one operator. It's certainly possible for
expressions to have multiple operators like `100 + 10 - 3`. In this example, the
_operators_ are `+` and `-`.

## Identify Core Operators in JavaScript

Here's a table of other operators and their operations. While some of the
symbols used are different from their mathematical counterparts, the operations
work in the familiar way.

| Operator | Operation      | Note                                                                                 |
| -------- | -------------- | ------------------------------------------------------------------------------------ |
| `+`      | Addition       |                                                                                      |
| `-`      | Subtraction    |                                                                                      |
| `*`      | Multiplication | We use `*` instead of `×` because it looks like x-the-letter                         |
| `/`      | Division       | We use `/` instead of `÷` because that's not on a keyboard                           |
| `**`     | Exponentiation | We use `**` instead of `^` because `^` means something else in programming languages |
| `()`     | Association    | Expressions inside of `()` get evaluated earlier                                     |

## Conclusion

In the next few lessons, we're going to introduce the **Essential Three
Expressions**:

![Three Essential Expression](https://curriculum-content.s3.amazonaws.com/phase-0/expressions-in-javascript/essential-3-expressions.jpg)

1. The constant expression
2. The assignment expression (variable assignment)
3. The variable lookup expression

**_All expressions, which are the core of every programming language, are built
on these Essential Three Expressions._**

## Resources

- MDN
  - [Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#Expressions)
- [Read-evaluate-print loop][repl]

[repl]: https://en.wikipedia.org/wiki/Read%E2%80%93eval%E2%80%93print_loop
