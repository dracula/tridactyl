### [Tridactyl](https://github.com/tridactyl/tridactyl)

#### Install

To install run:

```sh
:colourscheme --url https://raw.githubusercontent.com/dracula/tridactyl/main/dracula.css dracula
```

### Customization

- Fork the repo;
- Edit CSS vars to change colors/font to your preference;
- Use `:colourscheme --url https://raw.githubusercontent.com/<user>/tridactyl/main/dracula.css dracula_custom` command to set your custom theme.

#### Examples

`--tridactyl-url-fg: var(--pink);` will change `--pink` to the color you prefer.

Available colors correspond to [Dracula colors](https://draculatheme.com/contribute): pink, purple, red, etc...

To change the font:

`--font: "FiraCode Nerd Font Mono";` to: `--font: "font-of-your-choice";`

> Based on [base16-tridactyl](https://github.com/bezmi/base16-tridactyl)
