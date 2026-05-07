<div align="left">

# Мои дополнения для Construct 3

### 📑 Весь список
1. [**Dictionary+**](#-dictionary-plus) — Умный словарь с авто-сохранением.
2. [**SkyShader**](#-skyshader-advanced) — Продвинутая система процедурного неба.

</div>

---

## 📦 Dictionary Plus

<div align="center">
  <img width="60" height="60" src="https://github.com/user-attachments/assets/1da611a5-4e51-4c09-a5c6-0e61ab388da9" />
  <h3>Улучшенный словарь с авто-сохранением</h3>
</div>

**Dictionary+** — это расширенная версия стандартного плагина Dictionary, дополненная инструментами для работы с `localStorage`.

### ✨ Ключевые фишки
- 🚀 **Native Experience:** Полная совместимость со стандартной логикой Construct.
- 💾 **Persistent Storage:** Встроенные слоты сохранения/загрузки данных.
- ⚙️ **Worker Mode Ready:** Стабильная работа в режиме **Web Worker**.
- 🛠️ **Enhanced Debugger:** Счетчик ключей и живое редактирование в реальном времени.

### ❓ Почему стоит использовать?
Избавляет от необходимости вручную связывать Dictionary и LocalStorage в списке событий. Все управление данными теперь находится в одном объекте.

---

## 🌌 SkyShader Advanced

<div align="center">
<img width="855" height="443" alt="image" src="https://github.com/user-attachments/assets/bced11bd-5096-4078-94cf-986a2b6adfb3" />

  <h3>Процедурная система неба на Three.js</h3>
</div>

**SkyShader** — высокопроизводительная система динамического неба с полным 24-часовым циклом и атмосферными эффектами.

### ✨ Ключевые фишки
- ☀️ **Dynamic Day/Night:** Плавный переход времени, движение солнца и фазы луны.
- ☁️ **Procedural Clouds:** Анимированные облака с настройкой скорости и масштаба.
- 🌟 **Anime Stars:** Стилизованные мерцающие звезды, появляющиеся только ночью.
- 🎮 **Total Control:** Управление скоростью времени, цветами и углом наклона камеры (Yaw/Pitch).

### ⚠️ Важное требование
Для работы плагина **необходимо отключить Web Worker** в настройках проекта (`Advanced` -> `Use worker` -> `No`), так как система использует прямой рендеринг через Three.js.

---

### 📸 Скачать
> [Перейти на itch.io](https://loyamir.itch.io/) (Скоро здесь появятся прямые ссылки)

<div align="center">
  <sub>Developed for Construct 3 SDK v2 by EwenLoy</sub>
</div>
