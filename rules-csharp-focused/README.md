# C#/.NET Focused Cursor Rules

Эта папка содержит наиболее полезные `.cursorrules` файлы для C# и .NET разработки, адаптированные под современные стандарты Microsoft и лучшие практики экосистемы .NET.

## Содержимое

### 1. Code Style Consistency
**Путь**: `code-style-consistency-cursorrules-prompt-file/.cursorrules`

Универсальный набор правил для поддержания единого стиля кода в C#/.NET проектах. Включает:
- Анализ существующего кодовой базы для определения стиля
- Следование Microsoft C# Coding Conventions
- Современные возможности C# 12 (records, nullable reference types, pattern matching, primary constructors)
- Правила для Entity Framework Core, ASP.NET Core, Dependency Injection
- Руководство по async/await, LINQ, тестированию (xUnit, NUnit, MSTest)

**Применение**: Для любого C#/.NET проекта, где важно поддерживать единообразие стиля.

### 2. Code Guidelines
**Путь**: `code-guidelines-cursorrules-prompt-file/.cursorrules`

Общие принципы и лучшие практики для C#/.NET разработки:
- Принципы написания качественного кода
- Безопасность и производительность
- Обработка ошибок и логирование
- Модульный дизайн и SOLID принципы
- Тестирование и документация
- Современные практики C# (async/await, LINQ, nullable reference types)

**Применение**: Базовый набор правил для любого C# проекта.

### 3. ASP.NET ABP Framework
**Путь**: `aspnet-abp-cursorrules-prompt-file/.cursorrules`

Специализированные правила для разработки на ABP Framework:
- Архитектура ABP (Domain, Application, Infrastructure, HttpApi слои)
- Entity Framework Core интеграция
- Dependency Injection паттерны
- Async/await для I/O операций
- Тестирование с xUnit и NSubstitute
- API дизайн и документация (Swagger/OpenAPI)

**Применение**: Для проектов использующих ABP Framework.

## Технологический стек

Все файлы адаптированы под:
- **Язык**: C# 12+
- **Framework**: .NET 8+ (или последняя LTS версия)
- **IDE**: Visual Studio 2022 / Visual Studio Code / JetBrains Rider
- **Тестирование**: xUnit, NUnit, MSTest (с FluentAssertions, Moq/NSubstitute)
- **Code Analysis**: Roslyn Analyzers, StyleCop
- **Документация**: XML Documentation Comments (///)

## Использование

1. Скопируйте нужный `.cursorrules` файл в корень вашего проекта
2. Или используйте содержимое как основу для создания собственного `.cursorrules` файла
3. Настройте правила под специфику вашего проекта

## Дополнительные ресурсы

- [C# Coding Conventions](https://learn.microsoft.com/dotnet/csharp/fundamentals/coding-style/coding-conventions)
- [.NET Design Guidelines](https://learn.microsoft.com/dotnet/standard/design-guidelines/)
- [ASP.NET Core Best Practices](https://learn.microsoft.com/aspnet/core/fundamentals/best-practices)
- [Entity Framework Core Documentation](https://learn.microsoft.com/ef/core)

## Обновления

Эти файлы были обновлены и унифицированы в рамках проекта awesome-cursorrules-csharp-focused для соответствия современным стандартам C#/.NET разработки.

