# Testing module for 1st IOS project

The corona script should be placed in the same folder where the repository is located.

Attention: the tasks tests are using file osoby.csv,
which is not included in the repository.

## Using tests
```sh
Usage: ./test [OPTIONS]
  -h, --help                  Print this help
  -s, --script                Set script to use for tests
  -d, --dir                   Set directory where the tests are located
  -t, --task                  Use tests supplied in task
```

## Generating own tests

```sh
Usage: ./gen_tests [OPTIONS]
  -h, --help                  Print this help
  -a, --after                 Set after date
  -b, --before                Set before date
  -f, --file, --files         Set files to use for tests generation
                              (example: '-f file1.csv file2.csv')
  -c, --command, --commands   Set commands to use for tests generation
                              (example: '-c infected age merge')
                              To use all commands, use 'all'
  -s, --script                Set script to use for tests generation
  -o, --output                Set output directory
  -t, --task                  Use tests supplied in task
```