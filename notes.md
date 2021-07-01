# 1. Shell Tools and scripting
## 1.1 Shell Scripting:
    - Assign var: foo=bar not foo = bar (space = argument splitting)
    - Difference between '' and "": echo "$foo" 


# 2. Vim
## Command-line
    - :wq - save & quit
    - :e {name} - rename
    - :ks - show open buffer
    - :help {topic}
## Movement
    - Basic: h(left), j(down), k(up), l (right)
    - Words: w(next), b(beginning), e(end)
    - Lines: 0 (beginning), ^(first non-blank character), $(end)
    - Screen: H(top), M(middle), L(bottom)
    - Scroll: ^U (up), ^D (down)
    - File: gg (beginning), G(end)
    - Line number: :{number}

## Selection
    - Visual: v
    - Visual line: V
    - Visual block: ^V

## Edit
    - i: insert mode
    - o/O: insert below, above
    - d: delete
        - dw: delete word
        - d$: delete until end
        - d0: delete from beginning
    - x: delete character
    - cw: change word
    - s: substitute
    - u: undo, ^r: redo
    - y: copy
    - p: paste