# tdd-project
Project to set up and explore TDD

## Initial Notes
I want to set up a basic web app with a stack of React / .NET / SQL.

Goals will be to use tests and modern testing frameworks to practice test-driven development (TDD) along the way.

### Steps taken thus far

#### Initialization
- `dotnet new gitignore`
    - Actually, I deleted this when I ran `dotnet new react` just below
- `dotnet new sln --name TddProject`
    - QUESTION:  Was this necessary?  What is the .sln file doing?
    - I'm actually going to delete this now, because the next command seems more robust
- `dotnet new react`
    - This made a bunch of stuff.
    - Controllers, classes, bunch of react basics.
    - TODO:  I can probably run this app already.  Need to figure out how to do that, and expand it into being a proper fullstack app.
    - TODO:  I see it has a test but it's not being run by my vitest extension.  I assume because it's not written in Vitest.  Investigate + verify.