### git_practice

### date of creation: 03.03.2022

### author: Nazim Mukhtarbekov

![photo](https://i.morioh.com/dd054f30db.png)

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

