# My personal starship configuration

Played around with [starship](https://starship.rs) for a bit and settled on
this as my preferred configuration.

Took inspiration from the
[Tokyo Night](https://starship.rs/presets/tokyo-night.html) and
[Pastel Powerline](https://starship.rs/presets/pastel-powerline.html) starship
[presets](https://starship.rs/presets) and copied the os.symbols from the
[Nerd Font Symbols Preset](https://starship.rs/presets/nerd-font.html).

Things I set up differently than any of the presets:

- I'm not using the built-in [python module](https://starship.rs/config/#python)
  of starship because I'm not interested in having my system python version
  displayed whenever I happen to be in a folder with some .py files.

  Instead I want to be alerted when I'm about to use something else than my
  system python and *then* want to know its version.

- I'm currently not using the [os module](https://starship.rs/config/#os)
  either because starship currently doesn't cache the os info between prompts,
  and regenerating an almost never changing bit of info all the time seems
  wasteful to me.

I also added a few custom modules that are rather specific to my work
requirements just to get a feel of what's possible (check out [custom.gtn] and
[custom.iwc].

