# Tmux Plugin
For tmux plugin you should run the following:
```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

# Tmuxifier
For installing tmuxifier run:

```bash
git clone https://github.com/jimeh/tmuxifier.git ~/.tmuxifier
```

Then add these to `~/.zshrc`:

```bash
export PATH="$HOME/.tmuxifier/bin:$PATH"
eval "$(tmuxifier init -)"
```

