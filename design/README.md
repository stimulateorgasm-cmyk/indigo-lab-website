# Дизайн-система Indigo Lab

## Источники
- [b2b.indigolab.pro](https://b2b.indigolab.pro) — SPA на React + Tailwind
- [certified.indigolab.pro](https://certified.indigolab.pro) — SPA на React + Tailwind

## Стек
- **Фреймворк**: React 18+ (Vite)
- **Стили**: Tailwind CSS 4 + CSS-переменные (oklch)
- **Шрифты**: Google Fonts (Manrope + Fraunces)
- **Цветовая схема**: Dark-only (class="dark" на html)
- **Компоненты**: shadcn/ui (Radix-подобные)

## Ключевые цвета
| Токен | Значение | Использование |
|---|---|---|
| `--background` | `#13102a` | Основной фон |
| `--primary` | magenta `#cd637c` | Основной акцент |
| `--accent` | violet `#903999` | Вторичный акцент |
| `--cyan` | `#06b6d4` | Акцент для "научности" |

## Градиенты
- **CTA-кнопки**: violet → magenta → розовый (115deg)
- **Фон**: тройной radial-gradient (nebula effect)
- **Текст**: белый → светло-серый (180deg)

## Типографика
- **Заголовки**: Manrope (300–700 weight)
- **Декоративные заголовки**: Fraunces (300–600 weight)
- **Текст**: Manrope (400–500)

## Характерные приёмы
- Стеклянные карточки (glassmorphism)
- Градиентные CTA-кнопки с ховер-эффектом свечения
- Тёмный фон с nebula-градиентом
- Акцентные линии и бордеры с низкой прозрачностью
- Плавные анимации появления (fade-in + slide-up)
