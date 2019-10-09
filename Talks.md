### Safe Refactoring
----

Presenter - [Jakub Pilimon](https://springoneplatform.io/2019/speakers/jakub-pilimon)

_Code refactoring is the process of restructuring existing computer code—changing the factoring—without changing its external behavior - Martin Fowler_

Few of the reasons to refactor:
* Code is hard to maintain
* Business value being lost due to developer productivity or inability to perfrom frequent deployments etc

**Refactoring strategies**
1. Incremental refactoring
2. Blue/Green refactoring 

**Option 1**
* Hard to rollback

**Option 2**
* Old version remains untouched
* Easy rollback
* Need to maintain both versions
* Use Feature toggles to switch between versions (additional overhead)

Source Code: [Big Ball Of Mud](https://github.com/pilloPl/bigballofmud)
