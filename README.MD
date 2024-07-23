# VS Code setup guide for C++ in mac

## For VS code editor setup.

- Watch [Striver's video](https://www.youtube.com/watch?v=h3uDCJ5mvgw&list=PLgUwDviBIf0oF6QL8m22w1hIDC1vJ_BHz&index=3) for setting up the workspace.
- Read through the [article](https://takeuforward.org/set-up/how-to-set-up-visual-studio-code-for-c-cp-and-dsa/) for more detailed explanation.
- I am using g++-13 in my machine so, I have just updated the command to
  `g++-13 -std=c++17 -o ${fileBasenameNoExtension} ${file} && ./${fileBasenameNoExtension} < input.txt > output.txt`

## Formatting guide

- To setup formatter for c++ code, download clang-format tool from homebrew using this command `brew install clang-format`
- After installing the tool just install [clang-format extension](https://marketplace.visualstudio.com/items?itemName=xaver.clang-format) from VS code marketplace
- Follow the instructions on the extension page to complete the setup.
