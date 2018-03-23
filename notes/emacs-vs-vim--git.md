```
shlomif@telaviv1:~/Download/unpack/to-del$ time git clone https://git.savannah.gnu.org/git/emacs.git
Cloning into 'emacs'...
remote: Counting objects: 818615, done.
remote: Compressing objects: 100% (147482/147482), done.
remote: Total 818615 (delta 671052), reused 817417 (delta 670128)
Receiving objects: 100% (818615/818615), 254.13 MiB | 4.63 MiB/s, done.
Resolving deltas: 100% (671052/671052), done.
Checking out files: 100% (3857/3857), done.

real    3m44.981s
user    6m44.075s
sys     0m7.694s
shlomif@telaviv1:~/Download/unpack/to-del$ time git clone https://github.com/vim/vim.git
Cloning into 'vim'...
remote: Counting objects: 79334, done.
remote: Compressing objects: 100% (16/16), done.
remote: Total 79334 (delta 9), reused 10 (delta 3), pack-reused 79315
Receiving objects: 100% (79334/79334), 77.33 MiB | 3.68 MiB/s, done.
Resolving deltas: 100% (66162/66162), done.

real    0m34.121s
user    0m31.088s
sys     0m2.457s
shlomif@telaviv1:~/Download/unpack/to-del$ date
Tue 20 Mar 14:22:27 IST 2018
```

I wonder how much worse it was when Emacs was using bzr (see
http://blog.taz.net.au/2012/04/14/why-is-bzr-so-slow/ and
https://shlomif-tech.livejournal.com/41922.html ).
