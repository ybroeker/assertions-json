[![Build Status](https://travis-ci.org/ybroeker/assertions.svg?branch=master)](https://travis-ci.org/ybroeker/assertions)
[![Maintainability](https://api.codeclimate.com/v1/badges/1f948b7bad12dbe6e093/maintainability)](https://codeclimate.com/github/ybroeker/assertions/maintainability)

## Usage

### assertions-json

```java
import static de.ybroeker.assertions.json.JsonAssert.*;

assertThat("{\"field\":\"value\"}").jsonPathAsString("$.field").isEqualTo("value");
```



## Dependency


```xml
<dependency>
  <groupId>de.ybroeker</groupId>
  <artifactId>assertions-json</artifactId>
  <version>0.1</version>
</dependency>
```
