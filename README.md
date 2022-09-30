# Terminal-ASCII-Art-Header-Tutorial
Basically, I wanted to make pixel art for my terminal header, and since I'm on mac its confusing as hell since theres like 0 resources on how to do it. Open the README file for the instruction on how to make it work. Usually the default shell for Mac is zsh, even if you're set in something else like bash.

1. Open Terminal up.
2. Follow this sequence
- $ touch ~/.zshrc
- $ nano ~/.zshrc
3. Then at the top you can use $ cat << "EOF"
4. Fill in your pixel art and make sure its spaced correctly
5. Return at the bottom and write $ EOF
6. Press CMD+X and save your .zshrc file.
7. CMD+Q out of terminal and restart it.
8. You should be able to see your pixel art now at the top header.

Should look something like this...

<img width="465" alt="Screen Shot 2022-09-30 at 10 29 16 AM" src="https://user-images.githubusercontent.com/80769456/193304864-7b564252-d2ab-48b6-88a7-5f5c1cd2eef1.png">
