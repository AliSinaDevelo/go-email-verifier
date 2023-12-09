# Domain Checker

This Go program checks various DNS records for a given domain and outputs the results in CSV format.

## Features

- Checks for MX records.
- Looks up TXT records and identifies SPF (Sender Policy Framework) records.
- Searches for DMARC (Domain-based Message Authentication, Reporting, and Conformance) records.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/AliSinaDevelo/go-email-verifier.git
   cd go-email-verifier

2. Run the program:

    ```bash
    go run main.go

3. Enter domain names when prompted

## Output

The program outputs results in CSV format with the following columns:

DOMAIN
hasMX
hasSPF
spfRecords
hasDMARC
dmarcRecord

## Dependancies

Go

## Licence

This Project is licensed under the MIT License.