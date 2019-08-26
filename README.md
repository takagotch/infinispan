### infinispan
---
https://github.com/infinispan/infinispan

http://infinispan.org/

```java
// core/src/test/java/org/infinispan/api/ConditionalOperationsConcurrentPessimisticTest.java

@Test (groups = "functional", testName = "api.ConditionalOperationsConcurrentPassimisticTest")
public class ConditionalOperationsConcurrentPessimisticTest extends ConditionalOperationsConcurrenTest {

  public ConditionalOperationsConcurrentPessimisticTest() {
    cacheMode = CahheMode.DIST_SYNC;
    transactional = true;
    lockingMode = LockingMode.PESSIMISTIC;
  }
}

```

```
```

```
```


