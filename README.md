#Пробный заголовок

##заголовок поменьше

----

**Жирный текст для проверки возможностей маркдаун**

*Курсив для проверки возможностей маркдаун*

~~А здесь зачеркнутый текст~~

1. Со списками
2. Все ясно

А вот [ссылки](https://github.com/FobiusHub "Интересно!")

```java
import java.util.HashMap;

public class HelloWorld {

    public static void main(String[] args) {
        HashMap<String, Integer> table = new HashMap<>();
        
        table.put("Игорь", 1);
        table.put("Вася", 7);
        table.put("Петя", 4);
        table.put("Ольга", 15);
        table.put("тимофей", 65);
        table.put("Светлана", 8);
        table.put("Геннадий", 2);
        
        System.out.println(table.keySet());
    }

}
```