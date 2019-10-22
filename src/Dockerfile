FROM circleci/python:3.8.0

RUN sudo pip uninstall -y poetry && \
    curl -sSL https://raw.githubusercontent.com/sdispater/poetry/master/get-poetry.py | python && \
    $HOME/.poetry/bin/poetry self:update --preview && \
    echo 'export PATH="$HOME/.poetry/bin:$PATH"' >> $HOME/.bashrc
