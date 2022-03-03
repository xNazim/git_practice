### git_practice

### date of creation: 03.03.2022

### author: Nazim Mukhtarbekov

![alt text](https://www.google.com/url?sa=i&url=https%3A%2F%2Fhabr.com%2Fru%2Fsandbox%2F142332%2F&psig=AOvVaw38TsYOPwZA2RGr4Dz4KdrU&ust=1646379087317000&source=images&cd=vfe&ved=0CAgQjRxqFwoTCOCVtZy2qfYCFQAAAAAdAAAAABAD)

```java
package com.example.springboot;

import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RestController;

@RestController
public class HelloController {

	@GetMapping("/")
	public String index() {
		return "Greetings from Spring Boot!";
	}

}
```

