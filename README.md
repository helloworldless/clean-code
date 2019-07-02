# Clean Code

Clean code and architecture reference

*See my Medium post annoucing the launch of this repo: [Clean Code and Architecture](https://medium.com/@davidagood/clean-code-and-architecture-53c1bdb423c7)*

## Motivation
1. Spread awareness and promote clean code and archiecture and other best practices
2. Document my own journey and observations on the discipline
3. Create a repository of examples which can be used as a reference

## Analogies

### Physical Archeticture

**Compare (Good)**:
> A house where you simply unscrew the bulb from the socket and screw in a new one

**To (Bad)**: 
> A house where, in order to replace a lightbulb, you have to rip out the ceiling, replace the bulb,
> and then reconstruct the ceiling

### Writing

**Compare (Good)**:
> Maybe we should go out and buy a cheeseburger

**To (Bad)**: 
> me and you, we may 
> 
> well ouhgt To &nbsp; go outside---that is, not inside ,but out where their is lite of day and ANIMOS--and buyy
> 
> &nbsp; &nbsp; a grilled beef patty served w Cheese on bread.wE reaaaaally may want to

## Code Examples

### Experimental Formatting/Whitespace

**Don't:** Use experimental formatting or whitespace

**Do:** Follow your chosen style guide's on formatting and whitespace

**Don't:**

```
public int calculateScore(int base
                          , int dailyBonus
                          , int weeklyBonus) {
  ...
  ...
}
```

**Do:**

```
public int calculateScore(int base, int dailyBonus, int weeklyBonus) {
  ...
  ...
}
```
