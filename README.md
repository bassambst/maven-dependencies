# maven-dependencies
Maven Multi Module Project - Dependencies

- Parent POM has 3 modules.
- mod-a depends on mod-b, mod-b depends on mod-c. (a > b > c).
- mod-a has direct dependency on mod-b and transitive dependency on mod-c. 
- Parent POM has dependency on lombok.
- That results in  each of the modules can use lombok. 

#### ** change to other branch for different use case.
