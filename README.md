# AI-менеджер по продажам бурового оборудования

## Описание проекта
Система промптов для создания AI-ассистента, специализирующегося на продажах бурового оборудования для алмазной промышленности.

## Структура проекта
```
├── prompts/
│   ├── system/
│   │   ├── main/
│   │   │   └── system_prompt.md
│   │   ├── core/
│   │   │   ├── memory_system.md
│   │   │   ├── personalization.md
│   │   │   └── chain_of_thought.md
│   │   └── special_cases/
│   │       ├── edge_cases.md
│   │       └── multilingual.md
│   ├── knowledge/
│   │   ├── company_info.md
│   │   ├── product_line.md
│   │   └── sales_process.md
│   └── scenarios/
│       ├── initial_contact.md
│       ├── technical_consultation.md
│       └── closing_deal.md
├── tests/
│   ├── test_cases.md
│   └── validation_criteria.md
└── docs/
    ├── architecture.md
    └── maintenance.md
```

## Основные компоненты
1. Системные промпты:
   - Основные промпты (main)
   - Ядро системы (core)
   - Обработка особых случаев (special_cases)
2. Информационная база (knowledge)
3. Сценарии диалогов (scenarios)
4. Тестовые кейсы (tests)

## Использование
1. Изучите документацию в директории `docs/`
2. Используйте промпты из директории `prompts/`
3. Проверьте работу с помощью тестовых кейсов из `tests/`

## Требования
- GPT-4 или аналогичная модель
- Поддержка markdown
- Возможность сохранения контекста диалога