Sputnik Dao Contracts (in AssemblyScript)
==========================================

A [smart contract] written in [AssemblyScript] for an app initialized with [create-near-app].  One of the NEAR Protocol contracts and part of the series covering [NEAR Contracts written in AssemblyScript](https://vitalpoint.ai/course/sputnikdao-contract/) 


Quick Start
===========

Before you compile this code, you will need to install [Node.js] ≥ 12


Exploring The Code
==================

1. The main smart contract code lives in `assembly/index.ts`. You can compile
   it with the `./compile` script.
2. Tests: You can run smart contract tests with the `./test` script. This runs
   standard AssemblyScript tests using [as-pect].