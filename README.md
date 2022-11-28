## yasl

2022.11/25 11:42 ~ 11/27 23:41  

language : yasl  
(old language functionning with multiple reversed stacks)  

man : [yasl.0.txt](tools_from_42/yasl.0.txt)  

<br>

[yasl_hw](yasl_hw)
```
$ ./yasl_hw
Hello world
```

[yasl_aff_param](yasl_aff_param)
```
$ ./yasl_aff_param Hello 42 "a b 0"
Hello
42
a b 0
```

[yasl_do](yasl_do) : +, -, *, /, %, <, >, <=, >=, ==, !=
```
$ ./yasl_do 12 + 345
357
```

[yasl_repeat](yasl_repeat) : start_num val1 val2 ...
```
$ yasl_repeat 3 a b c d
aaa
bbbb
ccccc
dddddd
```

[yasl_fact](yasl_fact) : n !
```
$ ./yasl_fact 5
120
```

[yasl_split](yasl_split)
```
$ ./yasl_split a a1a22a333a4444aaa
1
22
333
4444
```

[yasl_interactive](yasl_interactive) : same behavior as yasl interpretor
```
$ ./yasl_interactive
12
345
+
"\n"
+
print
357
^D
$
```

[display_b64](display_b64) : decode base 64 img and display on the terminal
```
cat img/img5.rgb.b64 | ./display_b64
```
![demo](png/operahouse_256.png)

```
cat img/img5.rgb.b64 | ./display_b64_rgb
```
![demo](png/operahouse_rgb.png)