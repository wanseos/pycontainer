FROM mcr.microsoft.com/devcontainers/python:1-3.12-bookworm

USER vscode
RUN pip install pre-commit
RUN git clone https://github.com/zsh-users/zsh-history-substring-search ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-history-substring-search
RUN echo "plugins=(git zsh-history-substring-search)" >> ~/.zshrc

RUN unset LOG_LEVEL
