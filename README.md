# holy-C-Extension
Extension for holy C programming language syntax for vs code

## struct

holyc-vscode/            # Корень расширения
├── .vscodeignore        # Файлы и папки, которые не включать в пакет
├── package.json         # Мета-информация и вкладки contributes
├── tsconfig.json        # Настройки TypeScript
├── language-configuration.json  # Комментарии, скобки и авто‑закрытия
├── syntaxes/
│   └── holy c.tmLanguage.json   # TextMate grammar для HolyC
└── src/
    └── extension.ts     # Точка входа (пустая, так как у нас только грамматика)
