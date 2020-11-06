# sajariimports

## Test

At root of repository, run this:

```
% go test -count=1 -test.run=TestSimpleCases/sajari_sections/Modules ./internal/imports
```

## Build

At root of repository, run this:

```
% cd cmd/goimports
% go build
```

## Fix imports

Run on your Sajari code:

```
% cd /path/to/sajari/code
% /path/to/tools/cmd/goimports/goimports -w
```
