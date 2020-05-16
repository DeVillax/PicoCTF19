# So Meta

## Description

Find the flag in this picture. You can also find the file in /problems/so-meta_3_6dc950904c3ee41f324ae8d9f142f2b8.

## Approach

The challenge is about anylizing a picture. Following the same approach we did back in the Glory of the Garden challenge, let's start by using a `strings` command.

Right, we can find the flag by using it. Also, `grep` can help us out here to only retrieve the flag.

    strings pico_img.png | grep picoCTF

Flag:

    picoCTF{s0_m3ta_43f253bb}


