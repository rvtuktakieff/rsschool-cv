# [rsschool-cv](https://rvtuktakieff.github.io/rsschool-cv/cv)

---

## Роман Туктакиев

---

### Контакты

* **Город**: Пермь
* **Email**: [rvtuktakieff@gmail.com](mailto:rvtuktakieff@gmail.com)
* **Telegram**: [@rvtuktakieff](https://t.me/@rvtuktakieff)
* **Github**: [rvtuktakieff](https://github.com/rvtuktakieff)

---

### О себе

Меня интересует программирование, потому что можно создать продукт, который будет приносить пользу людям.
Моя цель — научиться верстать и освоить React/Angular, что бы создавать качественные проекты. Я стараюсь расширять свои навыки в разных областях.

---

### Навыки

* HTML5, CSS3 (Basics)
* JavaScript (Basics)
* Git, Github
* VS Code

---

### Примеры кода

* *[Ruby + JSON RESTful API: приложение с объявлениями о работе](https://github.com/rvtuktakieff/job_advertisement_site)*

* Мемоизация

```javascript
function memoize(fn) {
    const cache = new Map();

    return function(...args) {
        const key = args.toString();
        if (cache.has(key)) {
            return cache.get(key);
        } else {
            const result = fn (...args);
            cache.set(key, result);
            return result
        }
    }
}
```
