---
title: Arch — архив диаграмм
tags: [meta, index, diagrams]
created: 2026-06-22
---

# Arch — архив диаграмм

Самодостаточные SVG-схемы (встроенные стили и цвета — открываются прямо на
GitHub, без внешних зависимостей). Каждая привязана к атомарной заметке.

| Диаграмма | Заметка | Что показывает |
|---|---|---|
| [p11-4-peptide.svg](p11-4-peptide.svg) | [[p11-4-peptide]] | путь пептида от нанесения до нового слоя эмали |
| [usag-1.svg](usag-1.svg) | [[usag-1]] | молекулярный каскад: антитело размораживает рост зуба |
| [crispr-antimicrobials.svg](crispr-antimicrobials.svg) | [[crispr-antimicrobials]] | фаг + CRISPR точечно убивают S. mutans, союзники целы |
| [dentition-context-map.svg](dentition-context-map.svg) | [[dentition-domain]] | DDD: два контекста зубов, общее ядро, перенос возможности |
| [human-tooth-anatomy.svg](human-tooth-anatomy.svg) | [[human-teeth-ddd]] | слои зуба человека как блоки DDD |
| [human-teeth-ddd.svg](human-teeth-ddd.svg) | [[human-teeth-ddd]] | DDD-агрегат зубов человека |
| [arctic-shark-jaw.svg](arctic-shark-jaw.svg) | [[arctic-shark-teeth-ddd]] | зубной конвейер акулы (polyphyodont) |
| [arctic-shark-teeth-ddd.svg](arctic-shark-teeth-ddd.svg) | [[arctic-shark-teeth-ddd]] | DDD-агрегат зубов акулы |
| [aging-repair-vs-prevention.svg](aging-repair-vs-prevention.svg) | [[longevity-by-design]] | две стратегии: ремонт vs замедление повреждений |
| [damage-rate-integral.svg](damage-rate-integral.svg) | [[rate-limiter-aging]] | старение как интеграл; наклон = dDamage/dt |
| [longevity-by-design-map.svg](longevity-by-design-map.svg) | [[longevity-by-design]] | карта четырёх архитектурных сущностей |
| [longevity-stack.svg](longevity-stack.svg) | [[longevity-by-design]] | трёхуровневый стек антиэйдж-технологий |

Обзор подходов — [[dental-regeneration]]. Доменная модель — [[dentition-domain]].
Паттерн долголетия — [[longevity-by-design]].

## Соглашение

- `viewBox="0 0 680 H"`, `width="100%"` — масштабируется под контейнер.
- Цвета заданы явными hex (фон белый) — читаемо в любой теме просмотрщика.
- Один файл = одна диаграмма, имя файла совпадает с именем заметки.
