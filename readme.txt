There are three major changes from this code and the original wordpress code
The first can be found within the wp-config.php -> line 23 - 32
Here is where the connections to the database are listed, this is by far not best practice and needs to be hid using a .ignore file but is left in for the sake showcasing development.

the second can be found within wp-content -> themes -> twentyeleven -> custom.css
This file is here to contain the custom css that I wanted applied to the theme.

the third change can be found within wp-content -> themes -> twentyeleven -> functions.php -> line 298 & 302
the first line is the way in which wordpress can handle the variant css file and the second line is displaying the file on the website at the end of the queue system
