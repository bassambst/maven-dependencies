# maven-dependencies
Maven Multi Module Project - Dependencies

- Parent POM has 3 modules.
- mod-a depends on mod-b, mod-b depends on mod-c. (a > b > c).
- mod-a has direct dependency on mod-b and transitive dependency on mod-c. 
- mod-b has dependency on lombok.
- That results in:
  - mod-b can use lombok because of the direct dependency on it.
  - mod-a can use lombok as well; because of the transitive dependency on lombok thru mod-b.
  - Failure to build mod-c

#### ** change to other branch for different use case.
