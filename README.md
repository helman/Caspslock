# CapsLock

* CapsLock Enhancement (mac) is based on Project [`Karabiner-Elements`](https://pqrs.org/osx/karabiner/)

* Current release of karabiner works on following macOS:

  * macOS High Sierra (10.13)
  * macOS Sierra (10.12)
  * macOS EI Capitan (10.11)

* For older OS X user, refers to [old](../mac-old) `karabiner` XML-Format configuration script.



## Install (mac)

1. Download [Karabiner-Elements](https://pqrs.org/osx/karabiner/) and Install
2. Copy URL to your browser to import configuration script.

```bash
# This Repo (open in safari)
karabiner://karabiner/assets/complex_modifications/import?url=https%3A%2F%2Fraw.githubusercontent.com%2Fhelman%2FCaspslock%2Fmaster%2Fkarabiner.json
```

3. Open Karabiner, Tab "ComplexModification", Button "Add Item", and enable entries you like.
4. Default conf file path is `$HOME/.config/karabiner/assets/complex_modifications`. Modify it if you like.
5. Enable functions: `[App] karabiner-elements -> [Tab] Complex Modification -> Add Item`

### Basic

`✱` Hyper actually maps to `⌃⌥⇧⌘` (all right modifiers) , It works well with additional left modifiers. And compatible with most application. Hold CapsLock to enable `Hyper` funcationality while press it will emit an `Escape`.

| Origin    | Maps to    | Comment                    |
| --------- | ---------- | -------------------------- |
| `⇪` Press | `⎋` Escape | Single press to escape     |
| `⇪` Hold  | `✱`  Hyper | Enable Hyper Functionality |

### Navigation

- Hold  `✱` Hyper to enable navigators
- Hold additional `⇧` Command for **selection** . (just like holding ⇧shift in normal)
- Hold additional `⌘` with `HJKL` for **switching tab/app**

| Origin | Maps to         | Comment                    |
| ------ | --------------- | -------------------------- |
| `H`    | `←` LeftArrow   | cursor left                |
| `J`    | `↓` DownArrow   | cursor down                |
| `K`    | `↑` UpArrow     | cursor up                  |
| `L`    | `→` RightArrow  | cursor right               |
| `U`    | `⇞` PageUp      | cursor page up             |
| `6`    | `↖` Home        | cursor to line(doc) head   |
| `4`    | `↘`  End        | cursor to line(doc) end    |
| `P`    | `⇟` PageDn      | cursor page down           |
| `⇧H`   | `⇧←` LeftArrow  | cursor left and selection  |
| `⇧J`   | `⇧↓` DownArrow  | cursor down and selection  |
| `⇧K`   | `⇧↑` UpArrow    | cursor up and selection    |
| `⇧L`   | `⇧→` RightArrow | cursor right and selection |
| `⇧6`   | `⇧↖` Home       | cursor to line(doc) head and selection   |
| `⇧4`   | `⇧↘`  End       | cursor to line(doc) end and selection    |
