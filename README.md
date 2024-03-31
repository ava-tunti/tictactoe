## Tic Tac Toe - Ava Tunti
# Tic Tac Toe
This program puts the classic game of Tic Tac Toe into a web application! The rules and logic is exactly the same.

# Future Improvements
Possible future improvements could include: unmounting the board/not allowing the user to click anymore when there is a winner specified. Another one includes not letting the opposite player click a button that has already been clicked. For example, if Player X clicks the first square, Player O can't click that first square anymore.

Implementing the features:

Unmounting the board could involve conditional statements within the parent component. If we were to just make it so that the user can't click any squares but can still view the board (not sure the specific way to do that), we could edit some conditional logic within the child component.

If the square has already been clicked, we would need to keep track of the state and innerHTML in order to see whether the square already contains O or X. It also would include conditional logic.
#
**MIT License**

Copyright (c) 2020 John Williams

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
