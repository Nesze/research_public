**Research Projects & Lecture Content**
===================
More on the Quantopian Lecture Series at [quantopian.com/lectures](https://www.quantopian.com/lectures)

<a href="https://www.quantopian.com/lectures"><img src="http://i.imgur.com/KzPuAuJ.png"></a>


### Python 3ify (WIP)

Original content is in python 2.

Changes to 3ify the notebooks are documented below:

```bash
$ cd notebooks/lectures
$ sed -I '' -r 's/"print (.+)?(\\n)?"(,)?/"print (\1)\2"\3/' */**ipynb 
$ sed -I '' -r 's/"print (.*)\\n\)"(,)?/"print \1)\\n"\2/' */**ipynb
```
