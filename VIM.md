#### Vim ref

* Move: 	hjkl
* Exit: 	:q!
* Save:		:wq
* Edit:		:e [FILE]

* Delete char: 	x
* Delete:	d[+MOTION]
* Delete line:	dd

* Insert:	i
* Append e.l.:	A
* Append:	a
* Replace:	r[CHAR]
* Replace(ins)	R
* Change:	c[MOTION]
* New line:	o
* New l(above)	O

* Position top:	z ENTER
* Position end:	z-
* Position mid: z.
* Motions:
  *		w - start of next word
  *		e - end of current word
  *		$ - end of line

* Undo:		u
* Undo line:	U
* Redo:		CTRL-R

* Put:		p
* Copy:		y (as operator as well)

* Cursor location:
  * 		CTRL-G - shows location in file
  *		G - move to bottom of file
  *		gg - move to beggining of the file
  *		[NUM]G - move to line

* Search:	/[WORD]
* Repeat:	n
* In opposite:	N
* Backward:	?[WORD]
* Go back:	CTRL-o
* Go forwards:	CTRL-i

* Match parent:	%

* Substitute:
  * :s/old/new		substitute old for new (first occurence)
  * :s/old/new/g	substitute old for new (current line)
  * :#,#s/old/new/g	substitute old for new in range #
  * :%s/old/new/g	every old for new
  * :%s/old/new/gc	every old for new with prompt

* Execute external commands: :!

* Visual sel:	v

* Retrieve:	:r [FILENAME] - inserts contents of file

* Set options:	:set [OPTIONS]

* Autocomplete:	CTRL-D or TAB
