public class Main {
        public static void main(String[] args) {

            int eaters = 5; // сколько людей будут есть

            int water = 3000; // миллилитров воды
            int potatoes = 5; // картофелин
            int chicken = 6; // куриных бёдер
            int spices = 10; // ложек специй

            System.out.println("Сварили суп. На одного человека вышло:");
            System.out.println((water / eaters) + " миллилитров воды");
            System.out.println((potatoes / eaters) + " картофелин(а)");
            System.out.println((chicken / eaters) + " куриных(ое) бёдер(ро)");
            System.out.println((spices / eaters) + " ложек(ка) специй");


        }
    }

    C:\Users\DNK\.jdks\corretto-11.0.15\bin\java.exe "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2022.1.1\lib\idea_rt.jar=50951:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2022.1.1\bin" -Dfile.encoding=UTF-8 -classpath C:\Users\DNK\IdeaProjects\untitled\out\production\untitled Main
Сварили суп. На одного человека вышло:
600 миллилитров воды
1 картофелин(а)
1 куриных(ое) бёдер(ро)
2 ложек(ка) специй

Process finished with exit code 0