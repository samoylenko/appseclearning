# Preventing human mistakes

I am convinced that the best way to avoid making software development mistakes
is to **never write code alone**. Always have someone look at the changes you
are making.

## Get a friend

Human friends are hard to get, so we'll start with a couple of easier options -
let's bring a robot-friend and an imaginary friend on-board first.

### Robot friend

Everybody wanted to have a robot friend when we were kids. And in software
development, we can make that come true.

If I was asked a single advice I'd give to software engineers, that would be to
**always use [SonarLint](https://www.sonarlint.org/)**. It takes seconds to
install it with any IDE, and it completely changes entire development
experience. Certainly is an excellent robot friend to have.

There's many code quality tools and
[linter](https://en.wikipedia.org/wiki/Lint_%28software%29) presets available
for any programming language. E.g. I am writing mostly in Java, JavaScript and
Bash these days, and I got SonarLint and Intellij IDEA. The latter has one of
best
[code inspections in the industry](https://www.jetbrains.com/help/idea/code-inspection.html)
in my opinion. Can't imagine writing any code without these two anymore, they
add an incredible amount of value every day.

### Imaginary friend

Jokes aside, this actually describes what security teams keep asking software
engineers to do: get an imaginary friend that would be asking all those
unexpected scenario questions like "What if my name is
[Robert'); DROP TABLE students;--](https://www.explainxkcd.com/wiki/index.php/Little_Bobby_Tables)?",
or " [What if I supply a negative value in the number of products in my shopping
cart?](https://owasp.org/www-community/attacks/Web_Parameter_Tampering)"
