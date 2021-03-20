# Preventing human mistakes

I am convinced that the best way to avoid making software development mistakes
is to **never write code alone**. Always have someone look at the changes you
are making, and try to hear them out if they were kind enough to provide you
with their feedback, no matter how hard that is. Only humans are capable of
writing good code, otherwise we all would be out of our jobs by now, replaced by
robots in all the greedy corporations that want to save every dime.

## Get a friend

Human friends are hard to get, so we'll start with a couple of easier options -
let's bring an imaginary friend and a robot-friend on-board first.

### Imaginary friend

This one doesn't require any effort to get... Jokes aside, this actually
describes what security teams keep asking software engineers to do, by adding
items like security requirements and threat modelling in your development
process: get an imaginary friend that would be asking all those unexpected
scenario questions like "What if my name is
[Robert'); DROP TABLE students;--](https://www.explainxkcd.com/wiki/index.php/Little_Bobby_Tables)?",
or " [What if I supply a negative value in the number of products in my shopping
cart?](https://owasp.org/www-community/attacks/Web_Parameter_Tampering)".

One can have as many imaginary friends as they want (until they start mentioning
that to someone else).

Want to know who's my imaginary friend?
[Batman](https://arstechnica.com/information-technology/2017/07/how-i-learned-to-stop-worrying-mostly-and-love-my-threat-model/),
of course.

### Robot friend

Everybody wanted to have a robot friend when we were kids (until we learned that
they want to replace us, right). And in software development, we can make that
come true.

If I was asked a single advice I'd give to software engineers, that would be to
**always use [SonarLint](https://www.sonarlint.org/)**. It takes seconds to
install it with most popular editors, and it completely changes entire
development experience. Certainly is an excellent robot-friend to have.

There's many code quality tools and
[linter](https://en.wikipedia.org/wiki/Lint_%28software%29) presets available
for any programming language. E.g. I am writing mostly in Java, JavaScript and
Bash these days, and I got SonarLint and
[Intellij IDEA](https://www.jetbrains.com/help/idea/code-inspection.html). Can't
imagine writing any code without these two anymore, they add an incredible
amount of value every day.

One can start using code quality tools in their editor, then, in time, add them
to build scripts, then extend toolset with
[static](https://en.wikipedia.org/wiki/Static_program_analysis) and even
[dynamic](https://en.wikipedia.org/wiki/Dynamic_program_analysis) analysis tools
\- the more the better, depending on the budget.

Want a short list of my best robot-friends? Here it is:
* [Intellij IDEA](https://www.jetbrains.com/help/idea/code-inspection.html) -
  Everything-code
* [SonarLint](https://www.sonarlint.org/)
  ([SonarQube](https://www.sonarqube.org/)) - Code Quality
* [Snyk](https://snyk.io) -
  ([Software Composition Analysis](https://snyk.io/blog/what-is-software-composition-analysis-sca-and-does-my-company-need-it/))
* [OWASP ZAP](https://www.zaproxy.org) -

### Human friend

But nothing can replace teaming up with another human being. One can't really
rely on robots and imaginary friends if they want to step out of the sandbox.
And that's where we face all these challenges, like the need to get along with
other people who are convinced they are better than you are.
