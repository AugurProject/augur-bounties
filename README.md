# Augur Bounties

Bounties put fourth by the Augur team for Ethereum/Solidity tooling.

## <a id="bounty-one"/> Bounty #1: Safe Solidity Solium Rules

**50 REP** bounty **per** rule added to [Solium](https://github.com/duaraghav8/Solium).

### Open Bounties (03 of 30)

- [required] Prohibit use of multiple inheritance but allow interfaces
- [required] Prohibit use of inheritance but allow interfaces
- [required] Do not assign to parameters

### Completed & Merged (16 of 30)

- [required] Prohibit unreachable code [[@solium-plugin]](https://github.com/duaraghav8/solium-plugin-security)
- [required] Prohibit use of assembly [[@solium-plugin]](https://github.com/duaraghav8/solium-plugin-security)
- [required] Prohibit use of tx.origin [[@solium-plugin]](https://github.com/duaraghav8/solium-plugin-security)
- **[optional]** Prohibit use of call.value [[@solium-plugin]](https://github.com/duaraghav8/solium-plugin-security)
- **[optional]** Prohibit use of delegatecall [[@solium-plugin]](https://github.com/duaraghav8/solium-plugin-security)
- [required] Prohibit use of selfdestruct/suicide [[@beaugunderson]](https://github.com/duaraghav8/solium-plugin-security/pull/1)
- [required] Prohibit bitshifts and bit operators [[@beaugunderson]](https://github.com/duaraghav8/solium-plugin-security/pull/1)
- [required] Prohibit fixedpoint (fixed and ufixed) types [[@beaugunderson]](https://github.com/duaraghav8/solium-plugin-security/pull/1)
- [required] Prohibit use of integer types smaller than 256 bits [[@beaugunderson]](https://github.com/duaraghav8/solium-plugin-security/pull/1)
- [required] Prohibit use of var / all variable types must be explicitly stated [[@beaugunderson]](https://github.com/duaraghav8/solium-plugin-security/pull/1)
- [required] Prohibit use of named parameters in function calls [[@beaugunderson]](https://github.com/duaraghav8/solium-plugin-security/pull/1)
- **[optional]** Prohibit use of user-defined modifiers [[@beaugunderson]](https://github.com/duaraghav8/solium-plugin-security/pull/1)
- **[optional]** Restrict functions to a user-specified number of lines of code [[@beaugunderson]](https://github.com/duaraghav8/solium-plugin-security/pull/1)
- [required] Prohibit unreachable code [[@beaugunderson]](https://github.com/duaraghav8/solium-plugin-security/pull/1)
- [required] Prohibit use of continue statement [[@Cisplatin]](https://github.com/duaraghav8/solium-plugin-security/pull/2)
- [required] Only one break statement allowed per loop [[@artemlitch]](https://github.com/duaraghav8/solium-plugin-security/pull/3)


### Pending Merge: (11 of 30)

- [required] An else clause must be included after else if [[@mpokrass]](https://github.com/duaraghav8/solium-plugin-security/pull/4)
- [required] Prohibit use of send
 [[TristanH]](https://github.com/duaraghav8/solium-plugin-security/pull/5)
- [required] Prohibit modification of for loop iteration counting variables in the loop body 
 [[nfeignon]](https://github.com/duaraghav8/solium-plugin-security/pull/7)
- [required] Prohibit use of inheritance [[@nfeignon]](https://github.com/duaraghav8/solium-plugin-security/pull/8)
- [required] Prohibit use of multiple inheritance [[@nfeignon]](https://github.com/duaraghav8/solium-plugin-security/pull/8)
- [required] Prohibit abstract functions
[[@nfeignon]](https://github.com/duaraghav8/solium-plugin-security/pull/9)
- [required] Functions must have an explicit return statement [[@nfeignon]](https://github.com/duaraghav8/solium-plugin-security/pull/10)
- [required] Prohibit loops without fixed bounds [[@nfeignon]](https://github.com/duaraghav8/solium-plugin-security/pull/11)
- **[optional]** Functions must have a single return at the end of the function [[@Cisplatin]](https://github.com/duaraghav8/solium-plugin-security/pull/12)
- [required] Functions must have a declared return type (i.e., no void returns) [[@nfeignon]](https://github.com/duaraghav8/solium-plugin-security/pull/13)
- [required] Prohibit function overriding [[@nfeignon]](https://github.com/duaraghav8/solium-plugin-security/pull/16)


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