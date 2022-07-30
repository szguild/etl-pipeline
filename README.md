# etl-pipeline
any etl pipeline using python


# embulk setting (linux or macOS)
1. install embulk
- curl --create-dirs -o ~/.embulk/bin/embulk -L "https://dl.embulk.org/embulk-latest.jar"
- chmod +x ~/.embulk/bin/embulk
- echo 'export PATH="$HOME/.embulk/bin:$PATH"' >> ~/.bashrc
- source ~/.bashrc

2. gem install
- embulk gem list
- get search : gem search -r text

- embulk gem install jdbc;
- embulk gem install embulk-input-jdbc;
- embulk gem install embulk-input-postgresql;
- embulk gem install embulk-output-postgresql;



