# Extensions

## Description

This is a really weird text file TXT? Can you find the flag?

## Hints

- How do operating systems know what kind of file it is? (It's not just the ending!)
- Make sure to submit the flag as picoCTF{XXXXX}

## Points
150

## Approach

Firstly, let's try to open the file and see what information we get. As expected, we can't open it.

Ok, we can use the `file` command to collect information about the file.

Judging by the output, it looks like the file is not a `txt` file but an image one with a `png` format. Let's change the file extension to `png`

We can now open the file.

    picoCTF{now_you_know_about_extensions}
