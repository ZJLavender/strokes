Strokes v1.0
============

Strokes is a project meant to help you learn Chinese characters.

Currently it allows you to create a printable worksheet that will teach you
stroke order and Pinyin pronunciation of any of over 9000 supported characters.
Here's an example of what happens when you enter 一二三四:

![Strokes - example output](docs/example_defaults_yi_to_si.png?raw=true)

You are expected to print out the PDF generated by the project and fill in the
blank space within the strokes marked in bold.

As you can see, each stroke is drawn four times: 1) alone, 2) with all strokes
introduced so far, 3) in context and 4) in context but with no aid, so that
you can practice the proportions on your own. At the end of each pair you are
supposed to rehearse by drawing complete characters, which should help you
memorize strokes for all characters introduced so far. The way it is set up
by default, you should actually not only train your short-term memory, but also
long-term, making you remember characters longer!

All HSK 1-6 characters all supported.

Usage
=====

Installation
------------

Unfortunately, the project is not trivial to run for non-programmers. You will
need to learn how to run Docker applications in order to start it.

Assuming that your system already has both docker and docker-compose installed,
starting should be as easy as running `docker-compose up` as `root` (e.g. by
adding `sudo ` at the beginning of the command). After a few moments, you
should see the following text in your terminal:

`server_1    |  * Running on http://0.0.0.0:5000/ (Press CTRL+C to quit)`

Assuming that this happened, Strokes should be available using your browser.
Just visit the following URL: http://localhost:5000/

Author, license, acknowledgements
=================================

This application was written by Jacek Wielemborek <d33tah@gmail.com>. My blog
can be found here: http://d33tah.wordpress.com

If you're not a viagra vendor, feel free to write me an e-mail or file
a Github issue with feedback, I'll be more than happy to hear that you use
this program! I might even improve it for you if your needs align with my
vision of the project :)

This program is Free Software and is protected by GNU General Public License
version 3. Basically, it gives you four freedoms:

Freedom 0: The freedom to run the program for any purpose.

Freedom 1: The freedom to study how the program works, and change it to make
    it do what you wish.

Freedom 2: The freedom to redistribute copies so you can help your neighbor.

Freedom 3: The freedom to improve the program, and release your improvements
    (and modified versions in general) to the public, so that the whole
     community benefits.

In order to protect that freedom, you must share any changes you did to the
program with me, under the same license. For details, read the COPYING.txt
file attached to the program.

This application uses data from open-source Inkstone application by Skishore.
For licensing information, consult the following repository:

https://github.com/skishore/inkstone
