# Clean Code

Clean code and architecture reference

*See my post annoucing the launch of this repo: [Clean Code and Architecture](https://medium.com/@davidagood/clean-code-and-architecture-53c1bdb423c7)*

*Pull requests welcome!*

## Motivation

1. Spread awareness and promote clean code and archiecture and other best practices
2. Document my own journey and observations on the discipline
3. Create a repository of examples which can be used as a reference

## Analogies

### Physical Archeticture

**Bad**:
> A house where, in order to replace a lightbulb, you have to rip out the ceiling, replace the bulb,
> and then reconstruct the ceiling

**Good**:
> A house where, in order to replace a lightbulb, you simply unscrew the bulb from the socket and screw in a new one

**Note:** Don't forget to update your lightbulb's firmware!

### Writing

**Bad**:
> me and you, we may
>
> &nbsp; &nbsp; well ouhgt To &nbsp; go outside---that is, not inside ,but out where their is lite of day and ANIMOS--and buyy
>
> a grilled beef patty served w Cheese on bread.wE reaaaaally may want to

**Good**:
> Maybe we should go out and buy a cheeseburger

### Direct Analogies and Other Descriptors

- > ...letting junior engineers code without senior engineers to review their work and guide them is equivalent to stashing time bombs all over the codebase
([Source](https://medium.com/javascript-scene/why-cutting-costs-is-expensive-how-9-hour-software-engineers-cost-boeing-billions-b76dbe571957))
- > You can call it beautiful code when the code also makes it look like the language was made for the problem (Source: Clean Code by Robert C. Martin)

## Code Examples

### Experimental Formatting/Whitespace

**Don't:** Use experimental formatting or whitespace

```java
public int calculateScore(int base
                          , int dailyBonus
                          , int weeklyBonus) {
  ...
  ...
}
```

**Do:** Follow your chosen style guide's recommendations on formatting and whitespace

```java
public int calculateScore(int base, int dailyBonus, int weeklyBonus) {
  ...
  ...
}
```

## References

### Books

- [Effective Java](https://www.oreilly.com/library/view/effective-java-3rd/9780134686097/)
- [Clean Code](https://www.oreilly.com/library/view/clean-code/9780136083238/)

### Articles

- [Why Cutting Costs is Expensive: How $9/Hour Software Engineers Cost Boeing Billions](https://medium.com/javascript-scene/why-cutting-costs-is-expensive-how-9-hour-software-engineers-cost-boeing-billions-b76dbe571957)
