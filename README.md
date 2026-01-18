# ps-notes-21

A small PowerShell tool that computes text statistics for notes.

## Objective
- Provide quick text metrics for notes documents.
- Report top word frequencies for fast inspection.

## Use cases
- Validate notes drafts for repeated terms before review.
- Summarize notes notes when preparing reports.

## Usage
pwsh -File main.ps1 -Path data/sample.txt -Top 5

## Output
- lines: total line count
- words: total word count
- chars: total character count
- top words: most frequent tokens (case-insensitive)

## Testing
- run `bash scripts/verify.sh`

## Notes
- Only ASCII letters and digits are treated as word characters.
