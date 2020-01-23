# First Ocaml

## vscode拡張

* Ocaml and Reason IDE
* Ocaml Debugger

## デバッグ

### コンパイル

```bash
$ ocamlc -g main.ml
```

### launch.json

```json
{
    "version": "0.2.0",
    "configurations": [
        {
            "name": "OCaml Debug",
            "type": "ocaml-debugger",
            "request": "launch",
            "program": "${workspaceFolder}/a.out"
        }
    ]
}
```