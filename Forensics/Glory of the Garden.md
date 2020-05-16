# Glory of the Garden

## Description

This garden contains more than it seems. You can also find the file in /problems/glory-of-the-garden_4_cf9f4aaf458caf5268f8cf0a6465eb98 on the shell server.

## Approach

Having in mind this challenge is in the forensics cateogry and that the file we need to analyze is an image, we could say the information we are looking for is hidden in the image via steganography techniques.

The image displays a garden, nothing out of the ordinary here.

Mmm, let's see if some basic Linux commands can reveal further information. Let's start with `strings`.

Ok, it looks like it wasn't necessary to use any steganography decoder for this. The `strings` command provides us with the flag.

    picoCTF{more_than_m33ts_the_3y36BCA684D}


