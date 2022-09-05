# github.com/fredj/dotfiles

My dotfiles, managed with [`chezmoi`](https://github.com/twpayne/chezmoi). Personal secrets are stored in [LastPass](https://lastpass.com).

Install them with:

    lpass login <email>
    sh -c "$(curl -fsLS https://chezmoi.io/get)" -- init --apply fredj
