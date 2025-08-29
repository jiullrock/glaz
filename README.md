# GLAZ — Eye Trainer / Тренажёр для глаз

[📢 Telegram](https://t.me/glaz_reg) | [🇺🇸 English](#english) | [🇷🇺 Русский](#русский)

---

## English

**GLAZ** is an advanced web-based eye training application designed to improve visual focus, depth perception, and eye muscle coordination through scientifically-inspired exercises.

### 📋 Recommendations

The essence of all exercises is concentration on sharp details.

- Keep the screen so that sharp details are clearly visible
- 3-4 modes per session, several times a day
- Screen should be bright, clean and without defects
- ❗️Do not use when eyes are sleepy or tired❗️

### 🎯 Features

#### Training Modes
- **Symbols** — Dynamic geometric shapes with drawing animations to enhance visual tracking
- **Target** — Concentric circles with progressive focus training from outer to inner rings
- **Words** — Multi-language text movement exercises for reading comprehension and eye coordination
- **Emoji** — Animated emoji characters with depth layering for visual focus training
- **Dance** — Animated particle patterns simulating chaotic movement for peripheral vision training
- **Stars** — Static dot patterns for sustained focus and concentration exercises

#### Audio Features
- **Spatial Audio** — 3D positioned white noise during Rain/Stars modes
- **Focus Feedback** — Subtle audio cues (disabled for noise modes per specifications)
- **Sound Toggle** — Complete audio control with persistent settings

#### Interface
- **Bilingual Support** — Full Russian/English localization
- **Responsive Design** — Optimized for desktop and mobile devices
- **Persistence** — Automatic saving of user preferences (language, sound, mode selections)
- **Accessibility** — Screen reader friendly with ARIA labels

### 🚀 Quick Start

1. **Open** `glaz.html` in any modern web browser
2. **Select** your preferred language (Русский/English)
3. **Choose** training modes by checking/unchecking options
4. **Enable** sound if desired
5. **Click** "Start" to begin training

### 🎮 How to Use

#### Training Session
1. **Focus Phase** — Look at the highlighted elements, following focus changes between layers
2. **Rest Phase** — Take breaks between sessions as prompted
3. **Continue** — Click anywhere during rest to start the next session

#### Depth Training
- **Three Layers** — Back, middle, and front depth planes
- **Dynamic Focus** — Automatic switching between layers every few seconds
- **No Repetition** — System prevents consecutive focus on the same layer

### ⚙️ Technical Specifications

#### Browser Support
- Chrome 88+
- Firefox 85+
- Safari 14+
- Edge 88+

#### Features Used
- **Web Audio API** — For spatial audio effects
- **Canvas 2D** — For particle rendering in Rain/Stars modes
- **CSS Grid** — For responsive layout
- **LocalStorage** — For preference persistence
- **requestAnimationFrame** — For smooth animations

#### Performance
- **60fps** target for all animations
- **Optimized rendering** with hardware acceleration
- **Memory efficient** particle systems
- **Battery friendly** with wake lock API

### 🔧 Customization

#### Mode Configuration
Each training mode can be enabled/disabled independently. At least one mode must remain active.

#### Audio Settings
- **Layered Noise** — Three frequency bands (300Hz, 1000Hz, 2000Hz+)
- **Spatial Positioning** — Left (-0.3), Center (0), Right (+0.3) panning
- **Volume Levels** — Calibrated gains (0.15, 0.12, 0.08)

#### Visual Parameters
- **Layer Densities** — Back (15), Mid (25), Front (35) dots per area
- **Dot Sizes** — Back (1.5), Mid (2.5), Front (4.0) relative units
- **Timing** — Focus switches every 2-5 seconds with randomization

### 📱 Mobile Support

- **Touch Optimized** — Large touch targets and gesture support
- **Viewport Meta** — Proper scaling for mobile devices
- **Responsive Layout** — Adapts to portrait/landscape orientations
- **Battery Efficient** — Optimized rendering for mobile hardware

### 🔒 Privacy

- **No External Connections** — Fully offline application
- **Local Storage Only** — Preferences saved locally in browser
- **No Tracking** — No analytics or user data collection
- **Self-Contained** — Single HTML file with embedded resources

### 🛠️ Development

#### File Structure
```
glaz/
├── glaz.html          # Main application file
├── README.md          # This documentation
└── copy/              # Development versions and backups
```

#### Contributing
1. Fork the repository
2. Create feature branch
3. Test across browsers
4. Submit pull request

---

## Русский

**GLAZ** — продвинутое веб-приложение для тренировки глаз, предназначенное для улучшения визуальной фокусировки, восприятия глубины и координации глазных мышц через научно обоснованные упражнения.

### 📋 Рекомендации

Суть всех упражнений - концентрация на резких деталях.

- Держать экран так, чтобы резкие детали были хорошо видны
- 3-4 Режима за подход, несколько раз в сутки
- Экран должен быть ярким, чистым и без дефектов
- ❗️Не пользоваться сонными или утомленными глазами❗️

### 🎯 Возможности

#### Режимы тренировки
- **Символы** — Динамические геометрические фигуры с анимацией рисования для улучшения визуального отслеживания
- **Мишень** — Концентрические круги с прогрессивной тренировкой фокуса от внешних к внутренним кольцам
- **Слова** — Упражнения движения многоязычного текста для понимания чтения и координации глаз
- **Эмодзи** — Анимированные символы эмодзи с многослойной глубиной для тренировки визуальной фокусировки
- **Танец** — Анимированные паттерны частиц, имитирующие хаотичное движение для тренировки периферического зрения
- **Звёзды** — Статичные точечные паттерны для упражнений устойчивой фокусировки и концентрации

#### Аудио функции
- **Пространственное аудио** — 3D позиционированный белый шум в режимах Дождь/Звёзды
- **Обратная связь фокуса** — Тонкие аудио сигналы (отключены для шумовых режимов согласно спецификации)
- **Переключатель звука** — Полный контроль аудио с сохранением настроек

#### Интерфейс
- **Двуязычная поддержка** — Полная локализация на русский/английский
- **Адаптивный дизайн** — Оптимизировано для настольных и мобильных устройств
- **Сохранение данных** — Автоматическое сохранение пользовательских предпочтений (язык, звук, выбор режимов)
- **Доступность** — Совместимость с программами чтения экрана и ARIA метками

### 🚀 Быстрый старт

1. **Откройте** `glaz.html` в любом современном веб-браузере
2. **Выберите** предпочитаемый язык (Русский/English)
3. **Выберите** режимы тренировки, отмечая/снимая галочки
4. **Включите** звук при желании
5. **Нажмите** "Старт" для начала тренировки

### 🎮 Как использовать

#### Тренировочная сессия
1. **Фаза фокуса** — Смотрите на выделенные элементы, следуя изменениям фокуса между слоями
2. **Фаза отдыха** — Делайте перерывы между сессиями по подсказкам
3. **Продолжение** — Кликните в любом месте во время отдыха для начала следующей сессии

#### Тренировка глубины
- **Три слоя** — Задний, средний и передний планы глубины
- **Динамический фокус** — Автоматическое переключение между слоями каждые несколько секунд
- **Без повторений** — Система предотвращает последовательную фокусировку на одном слое

### ⚙️ Технические характеристики

#### Поддержка браузеров
- Chrome 88+
- Firefox 85+
- Safari 14+
- Edge 88+

#### Используемые технологии
- **Web Audio API** — Для пространственных аудио эффектов
- **Canvas 2D** — Для рендеринга частиц в режимах Дождь/Звёзды
- **CSS Grid** — Для адаптивной разметки
- **LocalStorage** — Для сохранения предпочтений
- **requestAnimationFrame** — Для плавных анимаций

#### Производительность
- **60fps** цель для всех анимаций
- **Оптимизированный рендеринг** с аппаратным ускорением
- **Эффективное использование памяти** в системах частиц
- **Экономия батареи** с API блокировки сна

### 🔧 Настройка

#### Конфигурация режимов
Каждый режим тренировки может быть включён/отключён независимо. Как минимум один режим должен оставаться активным.

#### Настройки аудио
- **Многослойный шум** — Три частотных диапазона (300Гц, 1000Гц, 2000Гц+)
- **Пространственное позиционирование** — Левый (-0.3), Центр (0), Правый (+0.3) панорамирование
- **Уровни громкости** — Калиброванные усиления (0.15, 0.12, 0.08)

#### Визуальные параметры
- **Плотность слоёв** — Задний (15), Средний (25), Передний (35) точек на область
- **Размеры точек** — Задний (1.5), Средний (2.5), Передний (4.0) относительных единиц
- **Тайминг** — Переключение фокуса каждые 2-5 секунд с рандомизацией

### 📱 Поддержка мобильных устройств

- **Оптимизация касаний** — Большие цели касания и поддержка жестов
- **Viewport Meta** — Правильное масштабирование для мобильных устройств
- **Адаптивная разметка** — Адаптация к портретной/альбомной ориентации
- **Экономия батареи** — Оптимизированный рендеринг для мобильного оборудования

### 🔒 Конфиденциальность

- **Без внешних соединений** — Полностью офлайн приложение
- **Только локальное хранилище** — Предпочтения сохраняются локально в браузере
- **Без отслеживания** — Никакой аналитики или сбора пользовательских данных
- **Самодостаточное** — Единый HTML файл со встроенными ресурсами

### 🛠️ Разработка

#### Структура файлов
```
glaz/
├── glaz.html          # Основной файл приложения
├── README.md          # Эта документация
└── copy/              # Версии разработки и резервные копии
```

#### Вклад в проект
1. Сделайте форк репозитория
2. Создайте ветку функции
3. Протестируйте в разных браузерах
4. Отправьте pull request

---

## License / Лицензия

This project is open source and available under the [MIT License](LICENSE).

Этот проект имеет открытый исходный код и доступен под [лицензией MIT](LICENSE).

---

## Support / Поддержка

For questions or support, please visit: [https://t.me/glaz_reg](https://t.me/glaz_reg)

По вопросам или поддержке, пожалуйста, посетите: [https://t.me/glaz_reg](https://t.me/glaz_reg)