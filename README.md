### Проблема:
**Затруднительный обзор второго монитора, нет возможности видеть что транслируется на второй монитор или проектор**

В современных рабочих и образовательных средах часто используется несколько мониторов или проекторов для презентаций, демонстраций и совместной работы. Однако возникает проблема, когда пользователь не может легко видеть, что отображается на втором мониторе или проекторе. Это может быть особенно затруднительно в следующих ситуациях:

1. **Презентации и лекции**: Лектор может не видеть, что отображается на экране перед аудиторией, что затрудняет синхронизацию слов с визуальными материалами.
2. **Работа с несколькими экранами**: Пользователи, работающие с несколькими экранами, могут испытывать трудности при переключении внимания между экранами, что снижает продуктивность.
3. **Удаленная работа и обучение**: В условиях удаленной работы и обучения важно иметь возможность следить за тем, что видят другие участники.

### Решение:

Для решения этой проблемы можно использовать технологию Screen Capture API, которая позволяет захватывать изображение с экрана и транслировать его в браузер. Это дает возможность пользователю видеть содержимое второго монитора или проектора на своем основном рабочем пространстве. Вот как это можно реализовать:

**Использование Screen Capture API**:
1. **Запрос разрешения**: Браузер запросит у пользователя разрешение на захват экрана.
2. **Выбор экрана**: Пользователь выбирает экран или окно, которое он хочет транслировать.
3. **Захват и трансляция**: Изображение захваченного экрана передается в браузерное окно.

### Преимущества:
- **Удобство**: Пользователь может видеть содержимое второго монитора без необходимости физически поворачивать голову или переключаться между экранами.
- **Эффективность**: Повышается продуктивность за счет уменьшения времени на переключение внимания.
- **Гибкость**: Решение подходит как для локальной работы, так и для удаленной работы и обучения.

### Заключение:
Использование Screen Capture API для мониторинга содержимого второго монитора или проектора на основном рабочем пространстве является эффективным решением проблемы затруднительного обзора. Это позволяет пользователям работать более продуктивно и комфортно, независимо от того, где они находятся.

### Начать использовать:
https://ilushinvanya.github.io/fullscreen-capture/

### Ссылка на оригинальный пример кода
https://developer.mozilla.org/en-US/docs/Web/API/Screen_Capture_API/Using_Screen_Capture
