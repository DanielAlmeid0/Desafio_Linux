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

## p29-b
`head -n 25 people.csv`

## p30-b
`tail -n 25 people.csv`

## p31-i
`diff greeting1.txt greeting2.txt`

## p32-i
`echo "Hello"; sleep 5; echo "world!"`

## p33-i
`dd if=/dev/zero of=arquivo1mb.txt bs=1M count=1`

## p34-i
`dd if=/dev/urandom of=arquivo2mb.txt bs=1M count=2`

## p35-i
`wc -l README.txt`

## p36-b
`tac README.txt`

## p37-i
`cut -d ',' -f 2 people.csv`

## p38-a
`cut -d ',' -f 2 people.csv`

## p39-a
`tail -n +2 people.csv | cut -d ',' -f 2 | sort | uniq | wc -l`

## p40-a
`sed '1d' people.csv | cut -d ',' -f 2 | sort | uniq | wc -l`

### p41-a
`time tail -n +2 people.csv | cut -d ',' -f 2 | sort | uniq | wc -l`
`time sed '1d' people.csv | cut -d ',' -f 2 | sort | uniq | wc -l`

## p42-a
`grep -c "Josiah" people.csv`

## p43-i
`find . -maxdepth 1 -type f | wc -l`

## p44-i
`find . -mindepth 1 -maxdepth 1 -type d | wc -l`

## p45-i
`rm *deleteme*`

## p46-i
`sed -i 's/You found the needle in the haystack!/The needle has been removed./' agulha.txt`

## p47-a
`tr ',' '|' < people.csv > people_pipe.csv`
