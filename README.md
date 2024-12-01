# Niini does Advent of Code

My solutions to [Advent of Code](https://adventofcode.com/) puzzles using
my own programming languages (mostly Meow), and with the added constraint
that when solving part 2 I cannot touch any of the code I wrote for part 1.

Input files are not included here, but they're expected to be in
`aoc2024/assets/day<N>.txt`. Where `<N>` is the specific day number.

Ideally just run it from the repl: `meow repl aoc2024`, then:

```
>>> day1.solution part1;
```

But there's an executable entrypoint, so running from the shell also works:

```
$ meow run aoc2024 -- 1 1
```
