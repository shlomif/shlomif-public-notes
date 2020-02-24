I am trying to get [fortune-mod](https://github.com/shlomif/fortune-mod) which
is an open source C project to build and pass tests on AppVeyor / MS Windows 10 x64 , but currently the rudimentary and reduced executable crashes there without
outputting the strings in the `printf()` calls.

You can find the [offending github branch](https://github.com/shlomif/fortune-mod/tree/appveyor-mswindows-runtime-failure-reduce-branch)
and [the latest commit](https://github.com/shlomif/fortune-mod/tree/7d7f36fe6fe73866da8be0b43d6e2e4aa89b428a) which reproduce the issue:

```
[00:03:27] Running [cd . &&  c:/foo/games/fortune.exe]
[00:03:28] Can't spawn "cmd.exe": No such file or directory at CI-testing/continuous-integration-testing.pl line 17.
[00:03:28] Running [cd . &&  c:/foo/games/fortune.exe] failed! at CI-testing/continuous-integration-testing.pl line 19.
[00:03:28] c:\foo\games\fortune
[00:03:28] Command exited with code -1073741515
```

See the [AppVeyor build](https://ci.appveyor.com/project/shlomif/fortune-mod/builds/31015919).

I use CMake with some glue in perl 5 and other languages and [the master branch](https://github.com/shlomif/fortune-mod/tree/c7b184194147a822ae41883aeaa032631a662423) passes all tests on travis-CI using Ubuntu Linux 18.04 (and works fine locally on mageia linux v8).

What is the issue and how can it be fixed?
