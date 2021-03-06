# Advent of APL

[Advent of Code](https://adventofcode.com/) solutions written in [Dyalog APL](https://www.dyalog.com/), organized into Acre projects

## Notes

This repo will contain solutions to all problems of AoC 2015 onwards, and the progress will likely be VERY slow.
Please don't expect up-to-date solutions for the latest AoC event.
(It's partially because I'm often busy with every-day job, and partially because I don't really like time-constrained competition.)

The solutions (and test cases) are organized as Acre projects, so that the source code is readable without the Dyalog interpreter.
Each solution will be fully annotated with comments.

You can try out the solutions without installing Dyalog APL, by [opening this repo on Gitpod](https://gitpod.io/#https://github.com/Bubbler-4/advent-of-apl).
If you want detailed instructions on how to use it (or use it better), please open an issue.
Also, any suggestions to improve the solutions (regarding performance, style, whatever) are welcome.

## Current progress

### AoC 2015

* `★P` means that the solution exploits a `P`attern in the input (and is therefore not a general solution of the problem as described).
* Day 4: Skipped since it requires an MD5 function implementation.
* Day 11: Solved without code.

| AoC 2015  | 1 | 2 | 3 | 4 | 5 |
| :---:     |:-:|:-:|:-:|:-:|:-:|
| **01~05** | [☆][15D01S] [★][15D01G] | [☆][15D02S] [★][15D02G] | [☆][15D03S] [★][15D03G] | Skip | [☆][15D05S] [★][15D05G] |
| **06~10** | [☆][15D06S] [★][15D06G] | [Circuit][15D07] [☆][15D07S] [★][15D07G] | [☆][15D08S] [★][15D08G] | [DistanceSums][15D09] [☆][15D09S] [★][15D09G] | [LookSay][15D10] [☆][15D10S] [★][15D10G] |
| **11~15** | Skip | [☆][15D12S] [★][15D12G] | [HappyTable][15D13] [☆][15D13S] [★][15D13G] | [Distance][15D14S1] [☆][15D14S] <br> [Movements][15D14G1] [★][15D14G] | [Partitions][15D15] [☆][15D15S] [★][15D15G] |
| **16~20** | [☆][15D16S] [★][15D16G] | [☆][15D17S] [★][15D17G] | [GoL][15D18S1] [☆][15D18S] <br> [GoLStuck][15D18G1] [★][15D18G] | [SubEach][15D19S1] [☆][15D19S] <br> [★][15D19G1] [★P][15D19G] | [DivisorSum][15D20S1] [☆][15D20S] [☆P][15D20S2] <br> [DivisorLimit][15D20G1] [★][15D20G] [★P][15D20G2] |
| **21~25** | [Fight][15D21S1] [☆][15D21S] [★][15D21G] |   | [RunPgm][15D23S1] [☆][15D23S] [★][15D23G] | [Solve][15D24S1] [☆P][15D24S] [★P][15D24G] |   |

[15D01S]: AoC2015/APLSource/Day01.apln#L2
[15D01G]: AoC2015/APLSource/Day01.apln#L7
[15D02S]: AoC2015/APLSource/Day02.apln#L2
[15D02G]: AoC2015/APLSource/Day02.apln#L8
[15D03S]: AoC2015/APLSource/Day03.apln#L2
[15D03G]: AoC2015/APLSource/Day03.apln#L8
[15D05S]: AoC2015/APLSource/Day05.apln#L2
[15D05G]: AoC2015/APLSource/Day05.apln#L10

[15D06S]: AoC2015/APLSource/Day06.apln#L5
[15D06G]: AoC2015/APLSource/Day06.apln#L19
[15D07]:  AoC2015/APLSource/Day07.apln#L2
[15D07S]: AoC2015/APLSource/Day07.apln#L59
[15D07G]: AoC2015/APLSource/Day07.apln#L65
[15D08S]: AoC2015/APLSource/Day08.apln#L2
[15D08G]: AoC2015/APLSource/Day08.apln#L13
[15D09]:  AoC2015/APLSource/Day07.apln#L2
[15D09S]: AoC2015/APLSource/Day07.apln#L14
[15D09G]: AoC2015/APLSource/Day07.apln#L18
[15D10]:  AoC2015/APLSource/Day07.apln#L2
[15D10S]: AoC2015/APLSource/Day07.apln#L22
[15D10G]: AoC2015/APLSource/Day07.apln#L26

[15D12S]: AoC2015/APLSource/Day12.apln#L2
[15D12G]: AoC2015/APLSource/Day12.apln#L14
[15D13]:  AoC2015/APLSource/Day13.apln#L2
[15D13S]: AoC2015/APLSource/Day13.apln#L17
[15D13G]: AoC2015/APLSource/Day13.apln#L18
[15D14S1]: AoC2015/APLSource/Day14.apln#L2
[15D14S]: AoC2015/APLSource/Day14.apln#L9
[15D14G1]: AoC2015/APLSource/Day14.apln#L14
[15D14G]: AoC2015/APLSource/Day14.apln#L19
[15D15]:  AoC2015/APLSource/Day15.apln#L4
[15D15S]: AoC2015/APLSource/Day15.apln#L12
[15D15G]: AoC2015/APLSource/Day15.apln#L16

[15D16S]: AoC2015/APLSource/Day16.apln#L4
[15D16G]: AoC2015/APLSource/Day16.apln#L10
[15D17S]: AoC2015/APLSource/Day17.apln#L4
[15D17G]: AoC2015/APLSource/Day17.apln#L10
[15D18S1]: AoC2015/APLSource/Day18.apln#L2
[15D18S]: AoC2015/APLSource/Day18.apln#L5
[15D18G1]: AoC2015/APLSource/Day18.apln#L9
[15D18G]: AoC2015/APLSource/Day18.apln#L14
[15D19S1]: AoC2015/APLSource/Day19.apln#L4
[15D19S]: AoC2015/APLSource/Day19.apln#L11
[15D19G1]: AoC2015/APLSource/Day19.apln#L15
[15D19G]: AoC2015/APLSource/Day19.apln#L27
[15D20S1]: AoC2015/APLSource/Day20.apln#L2
[15D20S]: AoC2015/APLSource/Day20.apln#L8
[15D20S2]: AoC2015/APLSource/Day20.apln#L13
[15D20G1]: AoC2015/APLSource/Day20.apln#L18
[15D20G]: AoC2015/APLSource/Day20.apln#L22
[15D20G2]: AoC2015/APLSource/Day20.apln#L27

[15D21S1]: AoC2015/APLSource/Day21.apln#L7
[15D21S]: AoC2015/APLSource/Day21.apln#L23
[15D21G]: AoC2015/APLSource/Day21.apln#L30
[15D23S1]: AoC2015/APLSource/Day23.apln#L14
[15D23S]: AoC2015/APLSource/Day23.apln#L20
[15D23G]: AoC2015/APLSource/Day23.apln#L24
[15D24S1]: AoC2015/APLSource/Day24.apln#L4
[15D24S]: AoC2015/APLSource/Day24.apln#L16
[15D24G]: AoC2015/APLSource/Day24.apln#L18

### AoC 2016

| AoC 2016  | 1 | 2 | 3 | 4 | 5 |
| :---:     |:-:|:-:|:-:|:-:|:-:|
| **01~05** |   |   |   |   |   |
| **06~10** |   |   |   |   |   |
| **11~15** |   |   |   |   |   |
| **16~20** |   |   |   |   |   |
| **21~25** |   |   |   |   |   |

### AoC 2017

| AoC 2017  | 1 | 2 | 3 | 4 | 5 |
| :---:     |:-:|:-:|:-:|:-:|:-:|
| **01~05** |   |   |   |   |   |
| **06~10** |   |   |   |   |   |
| **11~15** |   |   |   |   |   |
| **16~20** |   |   |   |   |   |
| **21~25** |   |   |   |   |   |

### AoC 2018

| AoC 2018  | 1 | 2 | 3 | 4 | 5 |
| :---:     |:-:|:-:|:-:|:-:|:-:|
| **01~05** |   |   |   |   |   |
| **06~10** |   |   |   |   |   |
| **11~15** |   |   |   |   |   |
| **16~20** |   |   |   |   |   |
| **21~25** |   |   |   |   |   |

### AoC 2019

| AoC 2019  | 1 | 2 | 3 | 4 | 5 |
| :---:     |:-:|:-:|:-:|:-:|:-:|
| **01~05** |   |   |   |   |   |
| **06~10** |   |   |   |   |   |
| **11~15** |   |   |   |   |   |
| **16~20** |   |   |   |   |   |
| **21~25** |   |   |   |   |   |
