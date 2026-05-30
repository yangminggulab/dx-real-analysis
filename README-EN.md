## Overall Roadmap

Following Sheldon Axler's Measure, Integration & Real Analysis, the measure-theoretic part of real analysis starts from the limitations of Riemann integration and moves toward measure, measurable functions, Lebesgue integration, convergence theorems, and product measures. This repository currently covers set foundations, measure, measurable functions, and Lebesgue integration.

```text
Real Analysis = using measure and integration to handle general limit problems
|
+-- The central problems
|   +-- Which sets can be assigned a reasonable size?
|   |   +-- Use outer measure, measurable sets, and Lebesgue measure to extend length.
|   +-- Which functions can be integrated reasonably?
|   |   +-- Use measurable functions, simple functions, and nonnegative functions.
|   +-- When can limits and integrals be exchanged?
|       +-- Use convergence theorems for function sequences, integral convergence, and error control.
|
+-- Tool 1: set foundations -> language for measure theory
|   +-- Limits of set sequences describe upper and lower limits of changing sets
|   +-- Open and closed sets connect point-set structure with measurability
|   +-- Countable and uncountable sets distinguish many from countably many
|   +-- Completeness keeps the real line's limit structure reliable
|
+-- Tool 2: measure -> from length to general size
|   +-- Lebesgue measure extend interval length to more complicated sets
|   +-- Outer measure estimate size through external covers
|   +-- Measurable sets select sets compatible with outer measure
|   +-- Constructing measurable sets use open, closed, and countable operations
|   +-- Nonmeasurable sets reveal the boundary of measure theory
|
+-- Tool 3: measurable functions -> the language of integrable functions
|   +-- Closure properties keep measurability under operations and limits
|   +-- Simple functions approximate general functions with step-like objects
|   +-- Convergence of function sequences compare pointwise, a.e., and in-measure convergence
|
+-- Tool 4: Lebesgue integration -> measuring area by slicing function values
    +-- Integrals of nonnegative measurable functions handle the non-canceling part first
    +-- General measurable functions split into positive and negative parts
    +-- Convergence theorems control when limits and integrals commute
    +-- Multiple and iterated integrals extend integration to several variables
```

# dx's Real Analysis

## Preface

This is a book I care about deeply. It is not only a course notebook, but also my first serious attempt to retell a mathematics course according to how I actually understood it.

Real analysis taught me another way to integrate and a deeper way to think about sets. It trains us to ask where an object lives, what a limit is being taken over, and whether a conclusion depends on algebraic operations or measure-theoretic structure.

## Why This Book Is Written This Way

I did not want real analysis to become a notebook made only of definitions and theorems. The subject can feel difficult because every statement looks correct, but it is not always clear why it appears at that point.

The notes therefore preserve many short construction-oriented tips: when to construct from an arbitrary object, when boundedness plus infinitude suggests a sequence, and how unions and intersections correspond to quantifiers.

## What This Book Keeps

The first chapter builds the language of sets, open and closed sets, countability, and completeness. The second chapter develops measure through outer measure, measurable sets, and nonmeasurable sets. The third and fourth chapters connect measurable functions, simple-function approximation, modes of convergence, and Lebesgue integration.

The whole book follows one line: when functions, sets, limits, and integration are placed in a more general framework, scattered tricks become a coherent structure.

## Intended Readers

This book is for readers meeting real analysis for the first time and for readers returning to reorganize it. It tries to slow down the proof actions enough for the subject to become a road rather than a wall.

## Repository Notes

- The main entry is `main.tex`.
- The body is currently concentrated in one main document covering sets, measure, measurable functions, and Lebesgue integration.
- Figures, videos, and auxiliary images are kept for use with the text.
- For local compilation, running `xelatex main.tex` twice is usually enough.
