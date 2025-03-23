This is my nvim config.

I started from [kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim) and have made some changes to it.

To use it, just clone it into your ~/.config folder.

```bash
cd ~/.config
git clone https://github.com/endikallanomatxin/nvim.git
```

There are some external dependencies that have to be installed:

- git

- make

- unzip

- gcc

- ripgrep

- A clipboard manager:
    - xclip (Linux)
    - wl-clipboard (Wayland)
    - pbcopy (macOS)
    - clip.exe (Windows)

- A nerd font

- Language specific dependencies:

    - npm
    - go
    - rustup

    - Java
        - jdtls
        - openjdk
        - Put this into your bashrc or zshrc:
            ```bash
            export PATH="/usr/local/opt/openjdk/bin:$PATH"
            export CPPFLAGS="-I/usr/local/opt/openjdk/include"
            ```

    - ...

