# language-pshdl package

Syntax definition for [PSHDL](http://pshdl.org), the Plain & Simple Hardware Description Language.

I recommend adding some styles to your style-sheet:

```CSS
atom-text-editor.editor .syntax--storage.syntax--modifier.syntax--register.syntax--pshdl {
  color: @syntax-color-function;
}
atom-text-editor.editor .syntax--storage.syntax--modifier.syntax--direction.syntax--pshdl {
  color: lighten(@syntax-color-function, 15%);
}
atom-text-editor.editor .syntax--comment.syntax--block.syntax--documentation.syntax--pshdl {
  color: #81a2be;
}
atom-text-editor.editor .syntax--comment.syntax--line.syntax--documentation.syntax--pshdl {
  color: #81a2be;
}
atom-text-editor.editor .syntax--storage.syntax--type.syntax--annotation.syntax--pshdl {
  color: darken(@syntax-color-function, 15%);
}
atom-text-editor.editor .syntax--storage.syntax--type.syntax--primitive.syntax--pshdl {
  color: lighten(@syntax-color-class, 10%);
}
```
