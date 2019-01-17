# neo-cheatsheet
Cheat sheet and best practices for writing smart contracts for NEO-VM in TypeScript

## Overview
This cheatsheet for users of the **NEO•ONE** smart contract framework on the **NEO** blockchain.

This reference is not intended to teach you TypeScript or blockchain principles from the ground up, but rather as a guide to developers with a basic understanding of blockchain and awareness of JavaScript or other programming language.

### It might be helpful if...
 * ***Having a working knowledge of JavaScript or TypeScript** will help when reading this document.  
 * ***NEO•ONE Development tools** are installed as this is the framework we'll use; it has simplified and includes mix-ins for making basic smart contracts with best practices in mind.  


## Table of Contents
- [NEO-ONE Cheatsheet and Best practices](#neo-cheatsheet-and-best-practices)
 * [Overview](#overview)
 * [Table of contents](#table-of-contents)
 * [Importing Files](#importing-files)

## Importing files
    import * as symbolName from "filename";
    import {symbol1 as alias, symbol2} from "filename";

## Types

### Boolean
    interface MyInterface {
        readonly const aBoolean: boolean;
    }

