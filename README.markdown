# DocSentry

**DocSentry** is an open-source, AI-powered tool that extracts protocol-specific details (UART, I2C, SPI, GPIO) from MCU datasheets, supporting ARM-based MCUs like STM32F4 and Samsung S3D350A. Using natural language processing, it parses PDFs to deliver register maps, protocol configurations, and query responses in JSON, streamlining embedded development. Designed to run locally on a PC or Raspberry Pi, DocSentry is built for flexibility and community collaboration.

## Features
- **Datasheet Parsing**: Extracts register maps and protocol settings (UART, I2C, SPI, GPIO) from MCU datasheets.
- **Query Support**: Answers questions like “What are S3D350A’s I2C registers?”
- **MCU Flexibility**: Adapts to any ARM-based MCU via datasheet analysis.
- **Integration**: Outputs JSON for code analysis tools (e.g., **CodeSentry**, in development).
- **Local & Open-Source**: Uses `pdfplumber`, Mistral-7B, LangChain (MIT/Apache licenses).

## Why DocSentry?
DocSentry saves embedded engineers hours of datasheet navigation by providing structured protocol data for diverse MCUs, enhancing productivity and reducing errors.

## Getting Started
DocSentry is in early development. Soon, you’ll be able to:
1. Clone the repo: `git clone https://github.com/EmbeddedAIVentures/DocSentry.git`
2. Install dependencies (TBD: Python, `pdfplumber`, Mistral-7B).
3. Parse a datasheet and query MCU details.

## Contributing
We welcome contributions! Help with:
- Parsing new MCU datasheets (e.g., ESP32).
- Improving NLP for protocol extraction.
- Adding protocol support.

See [CONTRIBUTING.md](CONTRIBUTING.md) for details. File Issues, join Discussions, or submit Pull Requests.

## Roadmap
- **v0.1 (Q3 2025)**: UART/I2C parsing for STM32F4, S3D350A.
- **v0.2 (Q4 2025)**: SPI/GPIO support.
- **v1.0 (Q1 2026)**: Multi-MCU support with community testing.

Track progress in our [GitHub Project](https://github.com/orgs/EmbeddedAIVentures/projects).

## License
MIT License. See [LICENSE](LICENSE).

## Contact
- **Issues**: [github.com/EmbeddedAIVentures/DocSentry/issues](https://github.com/EmbeddedAIVentures/DocSentry/issues)
- **Discussions**: [github.com/EmbeddedAIVentures/DocSentry/discussions](https://github.com/EmbeddedAIVentures/DocSentry/discussions)
- **Community**: X (#EmbeddedAI), r/embedded