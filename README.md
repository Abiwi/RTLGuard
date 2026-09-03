# RTLGuard
Open-source plugin that automatically detects and fixes Arabic and mixed RTL/LTR text direction issues across apps and interfaces. I’ll use AI-assisted development to improve accuracy, edge-case handling, compatibility, and testing, while keeping it free and open source for Arabic-speaking users and developers.

# Arabic Direction Fix

The goal is simple: make Arabic text display correctly, consistently, and naturally — especially when Arabic is mixed with English, numbers, links, punctuation, code, or other left-to-right content.

## Why this project?

Arabic interfaces often suffer from direction problems that make text difficult to read or visually inconsistent.

Common examples include:

- Arabic text rendered in the wrong direction
- English words breaking Arabic sentence flow
- Numbers, URLs, emails, and punctuation appearing in confusing positions
- Mixed RTL/LTR content being aligned incorrectly
- UI components inheriting the wrong text direction
- Developers having to manually handle many RTL edge cases

Arabic Direction Fix aims to provide a reusable solution instead of forcing every developer to solve these problems independently.

## Example

### Before

```text
قم بزيارة https://example.com لتحميل Version 2.0 من التطبيق
```

Depending on the application or rendering engine, mixed Arabic, URLs, numbers, and English words may appear in an incorrect or confusing order.

### After

The plugin detects the language direction and applies the appropriate RTL/LTR handling while preserving the intended reading order.

```text
قم بزيارة https://example.com لتحميل Version 2.0 من التطبيق
```

The visible text remains the same, but its direction, isolation, and layout behavior are corrected automatically.

## Project goals

- Automatically detect Arabic and RTL content
- Handle mixed Arabic and English text correctly
- Improve rendering of numbers, URLs, emails, punctuation, and technical terms
- Reduce manual RTL handling for developers
- Work reliably across common UI and text-rendering environments
- Cover difficult Unicode Bidirectional Algorithm edge cases
- Provide clear tests and documentation
- Stay completely free and open source

## AI-assisted development

AI-assisted development will be used to help improve:

- RTL/LTR detection logic
- Unicode and bidirectional-text edge-case analysis
- Automated test coverage
- Compatibility across frameworks and platforms
- Performance
- Documentation
- Code review and refactoring

AI is a development tool for the project, not a replacement for testing or validation. Changes should be reproducible, reviewed, and covered by tests whenever possible.

## Who is this for?

This project is intended for:

- Arabic-speaking users
- Open-source developers
- Web developers
- Mobile app developers
- Desktop application developers
- UI framework and component authors
- Localization and internationalization teams

While Arabic is the primary focus, the architecture may later support additional RTL languages where appropriate.

## Planned capabilities

- [ ] Automatic RTL/LTR detection
- [ ] Mixed Arabic/English text handling
- [ ] Numbers and punctuation correction
- [ ] URL and email isolation
- [ ] Direction-aware UI helpers
- [ ] Unicode BiDi edge-case handling
- [ ] Configurable correction rules
- [ ] Automated test suite
- [ ] Framework integrations
- [ ] Developer documentation and examples

## Open source

Arabic Direction Fix is intended to remain free and open source for everyone.

The project welcomes bug reports, test cases, documentation improvements, feature proposals, and code contributions from the community.

## Contributing

Contributions are welcome.

If you encounter an Arabic or mixed-direction text case that is rendered incorrectly, please open an issue with:

1. The original text
2. The expected result
3. The actual result
4. The platform or framework where the issue occurs

Small reproducible examples are especially valuable because bidirectional-text bugs can depend heavily on rendering context.

## Status

This project is in early development.

The initial focus is building a robust direction-detection and correction engine, followed by integrations for commonly used development environments.

## License

A permissive open-source license will be selected before the first stable release.
