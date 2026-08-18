# Soluções dos Desafios Linux

## p1-b 
`tar -xzf challenges.tar.gz`

## p2-b
`cd challenges`

## p3-b
`ls challenges`

## p4-b
`mkdir foo`

## p5-i
`mkdir -p foo/bar/1/2/3`

## p6-b
`rm -rf foo`

## p7-b
`echo "Hello Worls"`

## p8-b
`touch hello.txt`
`echo "Hello World" > hello.txt`

## p9-b
`touch empty.txt`

## p10-b
`rm empty.txt`

## p11-i
`> empty.txt`

## p12-i
`cat /dev/null > empty.txt`

## p13-b
`cp hello.txt goodbye.txt`

## p14-b
`mv goodbye.txt hello_copy.txt`

## p15-i
`diff -s hello.txt hello_copy.txt`

## p16-b
`cat hello.txt hello_copy.txt > 2_hellos.txt`

## p17-b
`pwb`

## p18-b
`ls -l`

## p19-b
`chmod u+w restricted.txt`
`echo "texto adicionado" >> restricted.txt`

## p20-b
`./hello_executable`

## p21-b
`chmod +x challenge_20`
`./challenge_20`

## p22-b
`gcc compile_me.c -o programa_compilado`
`./programa_compilado`

## p23-a
`./redirect &> output.txt`

## p24-b
`date`

## p25-b
`ps aux`

## p26-b
`nproc`

## p27-b
`uname -r`

## p28-b
`grep -rl "You found the needle in the haystack!" bunch_of_files/`
