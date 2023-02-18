[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-f4981d0f882b2a3f0472912d15f9806d57e124e0fc890972558857b51b24a6f9.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=9973051)
# Виконання пр на 4 бали

## Завдання 1. Створення та запуск першої програми (сорочки)

1. **клонуйте** створений для вас репозиторій в Netbeans (детальна інструкція з картинками є [тут](https://netbeans.org/kb/docs/ide/git.html)), **відкрийте** в [Repl.It](https://repl.it/) ([ось](https://repl.it/talk/learn/Configuring-GitHub-repos-to-run-on-Replit-and-contributing-back/23948) покрокова інструкція з картинками) або **просто завантажте** його вміст у ZIP-форматі (скориставшись кнопкою "Code" > "Download ZIP") і відкрийте в IDE за вашим вибором
2. створіть в теці **src** новий файл **Shirt.java**, в якому наберіть наступний текст (коментарі можна не писати - вони тут наведені лише для вас):

``` java
public class Shirt {
  public int shirtID = 0; // стандартне значення номера моделі сорочки
  public String description = "-description required-"; // стандартний опис сорочки
  // коди кольорів: R=червоний, B=синій, G=зелений, U=невідомо
  public char colorCode = 'U';
  public double price = 0.0; // стандартна вартість сорочки
  public int quantityInStock = 0; // стандартна кількість на складі
  
  // цей метод просто виводить всю інформацію про сорочку на екран
  public void displayShirtInformation() {
    System.out.println("Shirt ID: " + shirtID);
    System.out.println("Shirt description:" + description);
    System.out.println("Color Code: " + colorCode);
    System.out.println("Shirt price: $" + price);
    System.out.println("Quantity in stock: " + quantityInStock);
  } // кінець методу displayShirtInformation
} // кінець опису класу
```

3. **збережіть** файл, у разі необхідності (аби "навести красу" з відступами) скористайтесь швидким форматуванням - <kbd>ALT</kbd>+<kbd>SHIFT</kbd>+<kbd>F</kbd>
4. відкрийте файл **ShirtTest.java** з цього репозиторію
5. **запустіть** його (<kbd>F6</kbd> у NetBeans для запуску головного виконуваного файлу, <kbd>SHIFT</kbd>+<kbd>F6</kbd> - для запуску поточного файлу)
6. зробіть та збережіть (тека **Solution**) у файл task1.1.png **скріншот** результатів роботи програми 
![Снимок экрана (1194)](https://user-images.githubusercontent.com/114742171/219899731-f19c0b3c-f028-4bb1-8e2b-04f85adbe978.png)
7. замініть у файлі **Shirt.java** номер сорочки, її опис та вартість довільними значеннями 
8. запустіть файл повторно
9. зробіть та збережіть у файл task1.2.png **скріншот** нових результатів роботи програми 
11. додайте до репозиторію (тека **Solution**) обидва скріншоти
10. створіть (теж у теці **Solution**) файл **task1.md** і додайте туди ці скріншоти (УВАГА! Має бути видно код програми!). якщо потрібна допомога з Markdown, прочитайте [це](https://github.com/sandino/Markdown-Cheatsheet)

## Завдання 2. Створення та запуск іншої програми (цитати)

1. додайте в проект (до теки **src**) файл **Quotation.java** з таким вмістом:

``` java
public class Quotation {
  String quote = "Welcome to Sun!";
  public void display() {
    System.out.println(quote);
  }
}
```
2. **збережіть** файл, у разі необхідності (аби "навести красу" з відступами) скористайтесь швидким форматуванням - <kbd>ALT</kbd>+<kbd>SHIFT</kbd>+<kbd>F</kbd>
3. відкрийте файл **QuotationTest.java** з цього репозиторію
4. **запустіть** його  (<kbd>F6</kbd> у NetBeans для запуску головного виконуваного файлу, <kbd>SHIFT</kbd>+<kbd>F6</kbd> - для запуску поточного файлу)
5. зробіть та збережіть (тека **Solution**) у файл task2.1.png **скріншот** результатів роботи програми 
![Снимок экрана (1196)](https://user-images.githubusercontent.com/114742171/219899791-44990aef-3051-4b28-aa56-c2390cd45e9e.png)
6. замініть у файлі **Quotation.java** текст довільною цитатою, знайденою в Мережі (ось, наприклад, [100 кращих цитат всіх часів](https://pakwired.com/100-best-quotes-time/), можете скористатись ними:wink:)
7. запустіть файл повторно
8. зробіть та збережіть (тека **Solution**) у файл task2.2.png **скріншот** нових результатів роботи програми 
9. додайте до репозиторію обидва скріншоти
10. створіть (теж у теці **Solution**) файл **task2.md** і додайте туди ці скріншоти (УВАГА! Має бути видно код програми!). якщо потрібна допомога з Markdown, прочитайте [це](https://github.com/sandino/Markdown-Cheatsheet)
