Виконання 25. Складачі програми (part 2)

1. Створити бібліотеку з вирішення базових математичних завданнь (операції можна взяти з класу java.util.Math)

Потрібний клас створений, працює (протестований). 


2. Переробити ДЗ про "Систему логування" під Maven-проект.

ДЗ "Система логування" була повністю перероблена, у т.ч. під maven проект. Також я додав resouces\logback.xml та використав org.slf4j
Зараз не створюються на диску зайвих файлів, створюються тільки потрібні з таймстемпом:
log_20230722-212820_1690050500501.txt
log_20230722-212820_1690050501165.txt
log_20230722-212820_1690050501934.txt
log_20230722-212820_1690050502591.txt


3. Покрити класи системи unit-тестами (щонайменше 2 класи). Під час складання проект повинні враховуватися результати виконаних тестів, незалежно від успішності виконання (див. матеріал уроку - maven-surefire-plugin)

Були покрити тестами два класи - BasicMathTest та FileLoggerTest. 


4. Зібрати програму у вигляді JAR-файлу. Це буде просто бібліотека для використання, тому Main-Class не потрібен.

Jar файл створив, він знаходиться у структурі проекта:
osemes.javapro/out/artifacts/osemes_java_pro_jar/osemes_javapro.jar
