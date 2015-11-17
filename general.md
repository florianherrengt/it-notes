### Design pattern ###

- How much of this architecture is instantly re-usable?
- Can single modules exist on their own independently? Are they self-contained?
- How much do modules depend on other modules in the system? Are they tightly coupled?
- If specific parts of your application fail, can it still function?
- How easily can you test individual modules?
- Who is to say that in 2-3 years something better doesn't come out that you'll want to switch to?
- Is it flexible enough to support not caring about the libraries being used in modules can be of great benefit?
- Could a decision to switch libraries be made without rewriting your entire application?

### Data driven ###
When your code is data driven, everyone can work off the same built-in value map.

### Find string in files ###

    grep -rnw '/path/to/somewhere/' -e "pattern"

