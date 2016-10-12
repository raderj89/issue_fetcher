# GitHub Issues Fetcher

A simple CLI app written in Elixir that fetches and prints GitHub issues.

This project is included in [Programming Elixir](https://pragprog.com/book/elixir13/programming-elixir-1-3).

### Use it

- Make sure you've got Erlang installed.
- Clone the repo: `git clone git@github.com:raderj89/issue_fetcher.git`
- `cd issue_fetcher`
- Run the app from the command line: `$ ./issues <github-username> <repo> <number-of-issues default=4>`
  - e.g.: `$ ./issues elixir-lang elixir 10`
  - if you leave out a number, the app defaults the number of issues to 4
