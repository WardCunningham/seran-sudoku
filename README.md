# Seran Sudoku

Collection of sudoku solvers. The original version is Ward Cunningham's perl version.

* Original perl source is here: http://c2.com/~ward/sudokant.txt
* Input your own puzzle here: http://c2.com/~ward/sudokant.cgi
* Try this example: http://c2.com/~ward/sudokant.cgi?1..2..5.....3..6...2.4..7...1..4..3..7..2..8..6..1..9...6..9.7...5..1.....3..8..2
* Read how it works: http://ward.asia.wiki.org/sudoku-helper.html

To compile the rust version, run `./build-rust.sh`.

After installing deno, run `./file_server.ts`, and then go to http://localhost:4507/

Then compare these examples:
* http://localhost:4507/sudoku-perl.html?1..2..5.....3..6...2.4..7...1..4..3..7..2..8..6..1..9...6..9.7...5..1.....3..8..2
* http://localhost:4507/sudoku-ts.html?1..2..5.....3..6...2.4..7...1..4..3..7..2..8..6..1..9...6..9.7...5..1.....3..8..2
* http://localhost:4507/sudoku-js.html?1..2..5.....3..6...2.4..7...1..4..3..7..2..8..6..1..9...6..9.7...5..1.....3..8..2
* http://localhost:4507/sudoku-rust-port.html?1..2..5.....3..6...2.4..7...1..4..3..7..2..8..6..1..9...6..9.7...5..1.....3..8..2
