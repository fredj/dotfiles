# github.com/fredj/dotfiles

My dotfiles, managed with [`chezmoi`](https://github.com/twpayne/chezmoi). Personal secrets are stored in [LastPass](https://lastpass.com).

Install them with:

    sudo apt install lastpass-cli
    lpass login <email>
    sh -c "$(curl -fsLS https://chezmoi.io/get)" -- init --apply fredj
