# Aries Interoperability Information


This web site shows the current status of Aries Interoperability between Aries frameworks and agents. While
not yet included in these results, we have a working prototype for testing Aries mobile wallets using the
same tests.

The latest interoperability test results are below. Each row is a test agent, its columns
the results of tests executed in combination with other test agents.
The last column ("All Tests") shows the results of all tests run for the given test agent in any role. The link on each test
agent name provides more details about results for all test combinations for that test agent. On
that page are links to a full history of the test runs and full details on every executed test. 

The following test agents are currently supported:

- [Aries Cloud Agent Python](https://github.com/hyperledger/aries-cloudagent-python) (ACA-Py)
- [Aries Framework JavaScript](https://github.com/hyperledger/aries-framework-javascript) (AFJ)
- [AriesVCX](https://github.com/hyperledger/aries-vcx) (VCX)

Want to add your Aries component to this page? You need to add a runset to the
[Aries Agent Test Harness](https://github.com/hyperledger/aries-agent-test-harness).

## Latest Interoperability Results

| Test Agent | Scope | Exceptions | ACA-Py | AFJ | VCX | **All Tests** |
| ----- | ----- | ----- | :----: | :----: | :----: | :----: |
| [ACA-Py](acapy.md)| AIP 1, 2 | None | 96 / 96<br>100% | 49 / 67<br>73% | 0 / 56<br>0% | **145 / 219<br>66%** |
| [AFJ](javascript.md)| AIP 1 | Revocation | 49 / 67<br>73% | 12 / 28<br>42% | 3 / 18<br>16% | **64 / 113<br>56%** |
| [VCX](aries-vcx.md)| AIP 1 | Revocation | 0 / 56<br>0% | 3 / 18<br>16% | 0 / 32<br>0% | **3 / 106<br>2%** |

- Where the row and column are the same Test Agent, the results include only the tests where the Test Agent plays ALL of the roles (ACME, Bob, Faber and Mallory)
- The results in the "All Tests" column include tests involving the "Test Agent" in ANY of the roles.
- Wondering what the results mean? Please read the brief [introduction to Aries interoperability](aries-interop-intro.md) for some background.
- Select the "Test Agent" links to drill down into the tests being run for each Test Agent.


*Results last updated: Fri Aug 16 21:42:06 UTC 2024*

