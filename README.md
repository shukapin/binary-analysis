# binary-analysis
## Commands
```bash
FNAME=xxx
# Build C source code
gcc -o $FNAME $FNAME.c

# Get assembly code
$ objdump -d -M intel $FNAME > $FNAME.txt
```