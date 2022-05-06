# Based on:
https://github.com/janakaud/aws-cli-repl

# Improvements:
Replaced file I/O with multiprocessing.connection TCP communication. This allows parallel requests to be processed sequentially.
