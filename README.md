# -simple-interest-calculator
A simple Bash script to calculate simple interest.

# Simple Interest Calculator

A simple Bash script that calculates simple interest based on the principal amount, annual interest rate, and time period.

## Overview

This project provides a command-line calculator for determining simple interest. It is intended for educational purposes and to demonstrate basic open-source project practices using Git and GitHub.

## Formula

Simple Interest is calculated using the following formula:

**Simple Interest = (Principal × Rate × Time) / 100**

Where:
- **Principal:** Initial amount of money.
- **Rate:** Annual rate of interest, expressed as a percentage.
- **Time:** Duration in years.

## Prerequisites

- A Unix-like operating system or compatible shell environment.
- Bash.
- The `bc` utility for arithmetic calculations.

## Installation

Clone the repository:

```bash
git clone https://github.com/raptoradassault/simple-interest-calculator.git
```

Navigate to the project directory:

```bash
cd simple-interest-calculator
```

## Usage

Make the script executable:

```bash
chmod +x simple-interest.sh
```

Run the calculator:

```bash
./simple-interest.sh
```

Enter the principal amount, annual interest rate, and time period when prompted.

## Example

For a principal of 1000, an annual interest rate of 5%, and a time period of 2 years:

```text
Simple Interest = (1000 × 5 × 2) / 100
Simple Interest = 100
```

## Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting changes.

## Code of Conduct

All contributors are expected to follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## License

This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.
