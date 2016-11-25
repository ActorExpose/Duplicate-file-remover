# PySpace
PySpace is a python program that looks for duplicate files on your computer and deletes them to save space

Looking for duplicate files and then removing them manually proved annoying and boring to me, plus you might have 2 different files in 2 different directories with the same name, leading to confusion. So I wrote this program to automate the boring stuff, and because it relies on calculating md5 checksums for the files (something humans can't do) rather than just reading their names, it's less likely to make a mistake.

Big thanks to the guys at codereview.stackexchange.com for great suggestions.

Hope you find it useful.

Update: Because 2 different files of different lengths (i.e size) can yield the same md5 checksum, I added file size checking to the program. 2 files can't have the same size and the same md5 checksum unless they have the same content.
