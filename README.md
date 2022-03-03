### git_practice

### date of creation: 03.03.2022

### author: Nazim Mukhtarbekov

![alt text](https://www.google.com/url?sa=i&url=https%3A%2F%2Fitnext.io%2Fspring-boot-apprentice-cookbook-61db5a3f6450&psig=AOvVaw1IDj6QdIdSkwJ7cOM8sbqm&ust=1646378070465000&source=images&cd=vfe&ved=0CAgQjRxqFwoTCJCN37WyqfYCFQAAAAAdAAAAABAD)

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

