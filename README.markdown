# DocSentry

**DocSentry** is an open-source, AI-powered tool that extracts protocol-specific details (UART, I2C, SPI, GPIO) from MCU datasheets, supporting ARM-based MCUs like STM32F4 and others. Using natural language processing, it parses PDFs to deliver register maps, protocol configurations, and query responses in JSON, streamlining embedded development. Designed to run locally on a PC, DocSentry is built for flexibility.

## Features
- **Datasheet Parsing**: Extracts register maps and protocol settings (UART, I2C, SPI, GPIO) from MCU datasheets.
- **Query Support**: Answers questions like “What are STM32F4’s I2C registers?”
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

## License
MIT License. See [LICENSE](LICENSE).
