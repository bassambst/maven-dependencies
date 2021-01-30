# maven-dependencies
Maven Multi Module Project - Dependencies

- Parent POM has 3 modules.
- mod-a depends on mod-b, mod-b depends on mod-c. (a > b > c).
- mod-a has direct dependency on mod-b and transitive dependency on mod-c. 
- mod-a has dependency on lombok.
- Only mod-a can use lombok while mod-b and mod-c cannot. 

#### ** change to other branch for different use case.
