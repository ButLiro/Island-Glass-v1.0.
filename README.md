# Island Glass 🪟

**RU:** LSPosed-модуль для HyperOS, который делает остров (Dynamic Island) полупрозрачным, «стеклянным». Свёрнутая капсула больше не чёрная, а развёрнутая карточка становится прозрачнее вместе с функцией «Улучшенные текстуры».

**EN:** An LSPosed module for HyperOS that makes the Dynamic Island semi-transparent ("glass"). The collapsed capsule is no longer solid black.

## ✅ Проверено / Tested
- Redmi Note 14
- HyperOS 3 (3.0.303.0WOGRUXM.C08)
- Android 16

На других устройствах и версиях может не работать. / May not work on other devices or versions.

## Требования / Requirements
- Root (KernelSU)
- Zygisk Next
- LSPosed 2.x (Zygisk)

## Установка / Install
1. Скачайте APK из раздела **Releases** и установите.
2. LSPosed → Модули → **Island Glass** → включить.
3. Область действия: отметьте **System UI** (`com.android.systemui`).
4. Перезагрузите телефон.

## Прозрачность / Opacity
Значение задаётся в коде: `GLASS = 0x60000000`. Число `60` это плотность: `40` прозрачнее, `80`/`A0` плотнее. После изменения пересоберите проект (GitHub Actions → Run workflow).

## Как удалить / Uninstall
Выключите модуль в LSPosed и перезагрузите телефон.

## Известные ограничения / Known limitations
- Развёрнутая карточка меняется не везде; лучше включить «Улучшенные текстуры».
- После обновления системы имена ресурсов могут измениться, и модуль перестанет работать.

## ⚠️ Disclaimer
Используйте на свой страх и риск. / Use at your own risk.

Автор / Author: **ButLiro**
