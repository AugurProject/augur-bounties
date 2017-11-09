# Augur Bounties

Bounties put fourth by the Augur team for Ethereum/Solidity tooling.

## <a id="bounty-one"/> Bounty #1: Safe Solidity Solium Rules

**50 REP** bounty **per** rule added to [Solium](https://github.com/duaraghav8/Solium).

 - [required] Prohibit loops without fixed bounds
 - [required] Prohibit unreachable code
 - [required] Prohibit use of continue statement
 - **[optional]** Restrict functions to a user-specified number of lines of code
 - [required] Prohibit use of selfdestruct/suicide
 - [required] Prohibit use of assembly
 - [required] Prohibit use of tx.origin
 - [required] Prohibit use of integer types smaller than 256 bits
 - [required] Prohibit bitshifts and bit operators
- [required] Prohibit fixedpoint (fixed and ufixed) types
- [required] Prohibit modification of for loop iteration counting variables in the loop body
- [required] Prohibit use of var / all variable types must be explicitly stated
- [required] Prohibit use of named parameters in [function calls](https://solidity.readthedocs.io/en/develop/control-structures.html#named-calls-and-anonymous-function-parameters).
- [required] Prohibit use of inheritance
- [required] Prohibit function overriding
- [required] Prohibit abstract functions
- [required] Functions must have an explicit return statement
- **[optional]** Functions must have a single return at the end of the function
- [required] An else clause must be included after else if
- [required] Only one break statement allowed per loop
- [required] Prohibit use of send
- **[optional]** Prohibit use of call.value
- **[optional]** Prohibit use of user-defined modifiers

## <a id="bounty-two"/> Bounty #2: Portable Solidity Debugger

**2000 REP** bounty for a Solidity debugger which is portable / provided as a library.  

The debugger should have the following features:

- Set breakpoints in Solidity
- Inspect variables when those breakpoints are hit
- Execute Solidity from the context of a bremakpoint and see the result/failure
- Library that can be integrated into editors/IDEs
- VSCode integration
- Should work on any OS
- Should work with TestRPC

*Desired workflow:* set breakpoint in Solidity code, run tests (e.g., using Mocha or Pyethereum tester), drop into debugging environment.  See local variables, step forwards and backwards, see storage, etc.

## Claiming Bounties

Once your rule has been accepted to Solium, or you believe your library to be up to par with the requirements, reach out to us on [Twitter](twitetr.com/AugurProject) or via [email](mailto:team@augur.net)!