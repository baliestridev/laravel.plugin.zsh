<p align="center">
  <a href="#gh-dark-mode-only" target="_blank" rel="noopener noreferrer">
    <img src=".github/assets/night.svg" alt="laravel.plugin.zsh">
  </a>

  <a href="#gh-light-mode-only" target="_blank" rel="noopener noreferrer">
    <img src=".github/assets/day.svg" alt="laravel.plugin.zsh">
  </a>
</p>

Plugin for skipping the `php` command when running artisan commands and `./sail` or `./vendor/bin/sail` when running sail commands.

## Preview

![](.github/assets/preview.gif)

## Installation

#### [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh)

```shell
git clone https://github.com/baliestridev/laravel.plugin.zsh.git $ZSH_CUSTOM/plugins/laravel
```

```shell
~/.zshrc
plugins=(... laravel)
```

#### [zinit](https://github.com/zdharma-continuum/zinit)

```shell
zinit light baliestridev/laravel.plugin.zsh
```

#### [zi](https://github.com/z-shell/zi)

```shell
zi light baliestridev/laravel.plugin.zsh
```

#### [zgenom](https://github.com/jandamm/zgenom)

```shell
zgenom load baliestridev/laravel.plugin.zsh
```

#### [zplug](https://github.com/zplug/zplug)

```shell
zplug baliestridev/laravel.plugin.zsh
```

## Usage

```bash
cd /path/to/laravel/project # or subdirectory
artisan # instead of php artisan
sail # instead of ./sail or ./vendor/bin/sail
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
