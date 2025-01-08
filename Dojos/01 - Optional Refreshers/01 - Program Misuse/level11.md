`od -c -A n /flag | tr -d '[:space:]'`

Breakdown:
`-c`: Character output
`-A n`: Don't show offsets
The output is piped into `tr` to remove spaces and newlines.