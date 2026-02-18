# 🚀 Быстрая загрузка на GitHub

## Вариант 1: Через GitHub UI (САМЫЙ ПРОСТОЙ) ✅

### Шаг 1: Открой свой репозиторий
https://github.com/reemir4ik/Rembo1111

### Шаг 2: Загрузи файлы
1. Нажми **Add file** → **Upload files**
2. Перетащи эти файлы:
   - ✅ `index.html` (главный файл)
   - ✅ `README.md` (описание проекта)
   - ✅ `.gitignore` (игнорируемые файлы)
3. Напиши commit message: `Update Creative Engine v5`
4. Нажми **Commit changes**

### Шаг 3: Проверь GitHub Pages
1. Settings → Pages
2. Source: **Deploy from a branch**
3. Branch: `main` / `root`
4. Save

### Шаг 4: Подожди 1-2 минуты
Сайт появится на: https://reemir4ik.github.io/Rembo1111/

---

## Вариант 2: Через Git CLI (для продвинутых)

```bash
# Клонируй репозиторий
git clone https://github.com/reemir4ik/Rembo1111.git
cd Rembo1111

# Скопируй файлы
cp /path/to/index.html .
cp /path/to/README.md .
cp /path/to/.gitignore .

# Загрузи на GitHub
git add .
git commit -m "Update Creative Engine v5"
git push origin main
```

---

## ✅ Проверка работы

После загрузки:
1. Открой https://reemir4ik.github.io/Rembo1111/
2. Заполни форму
3. Нажми **СГЕНЕРИРОВАТЬ**
4. Баннеры должны появиться!

---

## 🆘 Если не работает

### Проблема 1: Страница не загружается
- Подожди 2-3 минуты после коммита
- Проверь Settings → Pages (должно быть включено)

### Проблема 2: Генерация не работает
1. Открой консоль (F12 → Console)
2. Проверь ошибку
3. Убедись что API-ключ добавлен в Vercel:
   - https://vercel.com/reemir4iks-projects/aibuyer-backend/settings/environment-variables

### Проблема 3: CORS ошибка
В Vercel → aibuyer-backend → Settings → Environment Variables:
- Проверь что `OPENAI_API_KEY` существует
- Redeploy проект

---

## 📞 Нужна помощь?

Открой консоль браузера (F12) и скинь скриншот ошибки!
