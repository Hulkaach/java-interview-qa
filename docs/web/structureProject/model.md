### Model
Тут хранятся модели проекта. 
**Модели — это описание самих объектов.** 
Например, если у нас есть объект User в проекте, то он может выглядеть так:
```
public class User {
private Long id;
private String name;

public Long getId() {
return id;
}

public void setId(Long id) {
this.id = id;
}

public String getName() {
return name;
}

public void setName(String name) {
this.name = name;
}
}
```
В классе User присутствуют поля id и name, присущие этому объекту, 
а также get- и set-методы для получения и изменения значений этих полей.