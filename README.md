
This is a fork of [gpui-component](https://github.com/huacnlee/gpui-component).

It has a complete identical copy of the workspace crate with a much reduced story set
that mainly deals with the textinput widget and its associated cohorts that show
functionality of the textinput widget.

The stories that it shows are the following:

- Buttons
- Input
- Switch
- Popup
- List
- Icon
- Scrollable

It points at the `workspace` branch of this repository for its dependencies.

```rust
ti = { git = "https://github.com/stormasm/textinput.git", branch = "workspace" }
```

Note that the complete identical copy of the *workspace* crate means the only change was
that the `ui` crate was renamed to `ti` so that it could be used in conjunction with
[textinput](https://github.com/stormasm/textinput).

But if you look at the file sizes of the two crates they are identical because 'u' was replaced with 't' in the crate name.
