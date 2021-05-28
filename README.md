# Smart Contract Security Packages

 
 
Visualization

Static and Dynamic Analysi

Weakness OSSClassifcation & Test Cases

Test Coverage

Linters and Formatters

Security Tools

Visualization¶

Solidity Visual Auditor - This extension contributes security centric syntax and semantic highlighting, a detailed class outline and advanced Solidity code insights to Visual Studio Code

Sūrya - Utility tool for smart contract systems, offering a number of visual outputs and information about the contracts' structure. Also supports querying the function call graph.

Solgraph - Generates a DOT graph that visualizes function control flow of a Solidity contract and highlights potential security vulnerabilities.

EVM Lab - Rich tool package to interact with the EVM. Includes a VM, Etherchain API, and a trace-viewer.

ethereum-graph-debugger - A graphical EVM debugger. Displays the entire program control flow graph.

Piet - Web application helping understand smart contract architectures. Offers graphical representation and inspection of smart contracts as well as a markdown documentation generator.

Static and Dynamic Analysis¶

MythX - MythX is a professional-grade cloud service that uses symbolic analysis and input fuzzing to detect common security bugs and verify the correctness of smart contract code. Using MythX requires an API key from mythx.io.

Mythril - The Swiss army knife for smart contract security
.
Slither - Static analysis framework with detectors for many common Solidity issues. It has taint and value tracking capabilities and is written in Python.

Contract-Library - Decompiler and security analysis tool for all deployed contracts.

Echidna - The only available fuzzer for Ethereum software. Uses property testing to generate malicious inputs that break smart contracts.

Manticore - Dynamic binary analysis tool with EVM support.

Oyente - Analyze Ethereum code to find common vulnerabilities, based on this paper.

Securify - Fully automated online static analyzer for smart contracts, providing a security report based on vulnerability patterns.

SmartCheck - Static analysis of Solidity source code for security vulnerabilities and best practices.

Octopus - Security Analysis tool for Blockchain Smart Contracts with support of EVM and (e)WASM.


sFuzz - Efficient fuzzer inspired from AFL to find common vulnerabilities.

Vertigo - Mutation Testing for Ethereum Smart Contracts.

Weakness OSSClassifcation & Test Cases¶

SWC-registry - SWC definitions and a large repository of crafted and real-world samples of vulnerable smart contracts.

SWC Pages - The SWC-registry repo published on Github Pages
Test Coverage¶

solidity-coverage - Code coverage for Solidity testing.

Linters and Formatters¶

Linters improve code quality by enforcing rules for style and composition, making code easier to read and review.

Ethlint - Yet another Solidity linting.
Solhint - A linter for Solidity that provides both Security and Style Guide validations.
Prettier + Solidity Plugin - Prettier enforces basic style conventions in your code.
