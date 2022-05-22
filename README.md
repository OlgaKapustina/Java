# Рассчёт распределения ингредиентов на порцию

public class Main {
1. public static void main(String[] args) {
1. int eaters = 5; // сколько людей будут есть
1. int water = 3000; // миллилитров воды
1. int potatoes = 5; // картофелин
1. int chicken = 6; // куриных бёдер
1. int spices = 10; // ложек специй

System.out.println("Сварили суп. На одного человека вышло:");<br/>
System.out.println((water / eaters) + " миллилитров воды");<br/>
System.out.println((potatoes / eaters) + " картофелин(а)");<br/>
System.out.println((chicken / eaters) + " куриных(ое) бёдер(ро)");<br/>
System.out.println((spices / eaters) + " ложек(ка) специй");<br/>


        }
    }

    C:\Users\DNK\.jdks\corretto-11.0.15\bin\java.exe "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2022.1.1\lib\idea_rt.jar=50951:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2022.1.1\bin" -Dfile.encoding=UTF-8 -classpath C:\Users\DNK\IdeaProjects\untitled\out\production\untitled Main

## Сварили суп. На одного человека вышло:<br/>
1. 600 миллилитров воды
1. 1 картофелин(а)
1. 1 куриных(ое) бёдер(ро)
1. 2 ложек(ка) специй

### Process finished with exit code 0