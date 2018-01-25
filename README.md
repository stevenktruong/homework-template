# Homework Template

A template for writing homework in LaTeX.

## What's Inside

| Environment | Description |
| ----------- | ----------- |
| `proofcase` | Helps you organize your proof into cases |
| `multipart` | Helps you type out problems with multiple parts |

| Command | Description |
| ------- | ----------- |
| `\qed`  | A simple command for placing a symbol at the end of a proof |

## Multiple Cases
The `proofcase` environment provides a simple way to organize your solution into cases. It takes one argument, which is the name of the case.

It places the name of the case, and all things within the environment will be indented slightly.

## Multipart Cases
The `multipart` environment is a modified `enumerate` environment. Everything is flush left with some minor spacing adjustments. Currently, the item labels will be lowercase letters of the alphabet by default.

## QED Command
In a math environment, you can use the `\qed` to place a black square flush right on the page.

