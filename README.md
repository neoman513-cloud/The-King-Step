<img width="800" height="640" alt="image" src="https://github.com/user-attachments/assets/0741e3d2-5d29-4d69-ab45-1fc4e397c76e" />

1) there are 1 million threads each starts at random place of the specified range
2) the last parameter specified THE SIZE OF THE STEP - its a 64 bit int, so try not to exceed it
3) each thread will walk with that specified step from his own starting point
4) when one of the threads reaches the maximum it will wrap around to minimum again

Run (dont include puzzle number in the command, its just for info):

`main.exe 100000 1fffff 29a78213caa9eea824acf08022ab9dfc83414f56 1234` - puzzle 21\
`main.exe 1000000 1ffffff 2f396b29b27324300d0c59b17c3abc1835bd3dbb 55555` - puzzle 25\
`main.exe 10000000 1fffffff 5a416cc9148f4a377b672c8ae5d3287adaafadec 7457547` - puzzle 29\
`main.exe 20000000 3fffffff d39c4704664e1deb76c9331e637564c257d68a08 98686869` - puzzle 30\
`main.exe 100000000 1ffffffff 4e15e5189752d1eaf444dfd6bff399feb0443977 432432546` - puzzle 33\
`main.exe 200000000 3ffffffff f6d67d7983bf70450f295c9cb828daab265f1bfa 74746757` - puzzle 34\
`main.exe 1000000000000000000 1ffffffffffffffffff 105b7f253f0ebd7843adaebbd805c944bfb863e4 111111111111111111` - puzzle 73

you can convert any bitcoin address to hash160 using this site: https://cointools.org/address-to-hash

just in case if you will edit this code further, you can compile it with the command:

`nvcc -o main main.cu`

in case if this was useful to you, can you please donate BTC:

`bc1q8n38pk3urztlt4vceq0h089l9jdcw58l2c0e80`

so i will be more motivated to develop further this project

author: https://t.me/biernus
