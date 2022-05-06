# FastAWSCLI
AWS CLI wrapper which forks into background daemon and client CLI

Based on:
https://dzone.com/articles/how-i-made-aws-cli-300-faster-full-disclosure
https://github.com/janakaud/aws-cli-repl/blob/master/awsr

Improvements:
Replaced file I/O with multiprocessing.connection TCP communication. This allows parallel requests to be processed sequentially.
