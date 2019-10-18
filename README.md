[![Build Status](https://travis-ci.org/ybroeker/assertions-json.svg?branch=master)](https://travis-ci.org/ybroeker/assertions-json)
[![Maintainability](https://api.codeclimate.com/v1/badges/2abb3778018a85f051e8/maintainability)](https://codeclimate.com/github/ybroeker/assertions-json/maintainability)

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
