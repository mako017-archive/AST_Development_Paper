# Are you Swiping, or Just Marking? Development and Evaluation of the Attention Swiping Task

## Introduction

The Attention Swiping Task (AST) was developed as a computer-based test of sustained attention that can be administered on any mobile device without the need for dedicated hard- or software on the client-side.

Traditional tests of sustained attention usually require the test takers to mark targets (i.e., stimuli to which pre-learned rules apply) by either crossing them out or drawing lines beneath them. While these approaches have repeatedly been shown to result in highly reliable and valid psychological measurment instruments, they don't feel natural on mobile devices.

This repository contains the source code of the AST as it was administered by [Koch et al. (submitted)](#blank).

## Measured variables

The variables that can be exported for each participant are:

1. Response data for each item (i.e., hits, false alarms, misses, correct rejections)
2. Reaction times for each item
3. Number of mistakes during the familarization period
4. Number of repetions of the instructions

For the article by [Koch et al. (submitted)](#blank) we focused on the analysis of the data from the second category and computed the following indices:

- G = total number of items attempted within the time limit
- FV = number of misses
- FA = number of false alarms
- L = attentive performance; L = G - 2 x (FV + FA)
- Q = performance quality; Q = L / G

## References

Koch, M., Moeller, C., & Spinath, F.M. (submitted). Are you Swiping, or Just Marking? Development and Evaluation of the Attention Swiping Task
