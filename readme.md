# 请仔细阅读此文
```java
public class Test{
    List<Integer> list = Lists.asList(1,2,3);
    list.stream().filter(x->x>20).sorted().forEach(System.out::println);
}
```
# 清单列表

