# xkpasswd.go

*Memorable password generator. A clone of my [xkpasswd-node](https://github.com/vot/xkpasswd-node) module, written in Go.*

## How it works

```
$ ./xkpasswd-go
offramps#schappes#skywrite
```


## Quickstart

You can [download Mac and Linux binaries](https://github.com/vot/xkpasswd-go/releases/tag/0.0.1).
Make sure to grab `words.txt` too and put it in the same folder as the binary.

You can then execute it with `./xkpasswd-go`.

You may need to set permissions with `chmod +x xkpasswd-go` before running it.


## Options

At this point xkpasswd-go only takes options: `number`.

By specifying it you can generate multiple passwords.

```
$ ./xkpasswd-go -n 3
maidenweed#hetairismic#linned
keratomata#generals#cithara
anticorruption#conspire#spritzer
```

For now to change the pattern you have to edit code (it's hardcoded, see `patternToArray` function).

## Building project

Checkout a copy of this project
```
git clone https://github.com/vot/xkpasswd-go
cd xkpasswd-go
```

To build the project run:
`go build`
