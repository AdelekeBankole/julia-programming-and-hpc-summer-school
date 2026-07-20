# Introduction to Julia Programming and High Performance Computing (HPC)

This repository contains course materials for the julia programming language and HPC course delivered at the Data Science Africa 2026 summer school, Makerere University, Kampala, Uganda. The materials are available such that learners can follow the content in their own pace and time.

# Learning Objectives

In session 1, we will cover:
- Fundamentals of the Julia programming language
- Multiple dispatch and code specialization
- Julia's type systems and data structures
- Putting these ideas to use in your models

In session 2, we will shortly cover:
- Introduction to HPC and workflows
- Distributed and Shared Parallelism
- GPU programming

# Installation and setup

Get Julia via juliaup. For macOS and Linux distribution

```
curl -fsSL https://install.julialang.org | sh
```
and for Windows in the powershell
```
winget install --name Julia --id 9NJNWW8PVKMN -e -s msstore
```
Follow the instructions and restart your terminal to register all environment variables. Next is to add Pluto to your environment, start Julia, in the Julia prompt, enter the package manager mode by pressing ```]``` Then type ```add Pluto``` and press Enter. Once it finishes installing, press Backspace to return to the standard Julia prompt. Start the notebook by running the commands
```
using Pluto
Pluto.run()
```
Pluto will open up in your default browser to the pluto welcome page.

# Prerequisites
- Julia installation
- Basic understanding of mathematical operations
- Undergraduate knowledge of calculus, linear algebra 
- Writing and using functions
- Working with Pluto, or Jupyter nptebooks

# License Information

The code material in this course is licensed under the MIT License.


