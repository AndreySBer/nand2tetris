# nand2tetris directory


>The directory contains all the files for Research Seminar
>
>"Component-Oriented Programming" in HSE.


#### Stuff used to make this:

 * [Online Markdown editor](https://jbt.github.io/markdown-editor) for Markdown parsing
 * [From NAND to Tetris](http://www.nand2tetris.org/) for the whole idea
```
CHIP Not {
    IN in;
    OUT out;

    PARTS:
    Nand(a=in,
		    b=in,
		    out=out);
}
```
