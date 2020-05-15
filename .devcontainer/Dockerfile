FROM node:12

USER root

RUN yarn global add eslint typescript prettier prettier-eslint tslint hendrix

RUN apt-get update -y \
&& apt-get install zsh -y \
&& sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)" 

RUN curl https://raw.githubusercontent.com/seanWLawrence/dotfiles/master/.zshrc-node > ~/.zshrc