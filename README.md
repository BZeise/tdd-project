# tdd-project
Project to set up and explore TDD

## Initial Notes
I want to set up a basic web app with a stack of React / .NET / SQL.
- Tool notes:  Will use Node, but also will use Vite as the task runner instead of Webpack

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
        - run with `dotnet run`
        - takes a bit, use ctrl+click on the address shown to view in browser
    - TODO:  I see it has a test but it's not being run by my vitest extension.  I assume because it's not written in Vitest.  Investigate + verify.
    - TODO:  Ah, I have verified that `dotnet new react` creates a new React app based on the `create-react-app` command.
        - I have heard many times from various sources that this pattern is deprecated.
        - Apparently, it's based on webpack which can be slow, and have problems scaling.
        - Vite is a super-fast compiler.  It's been recommended even over Next.js.
        - This also works with my recent practice on Vitest.