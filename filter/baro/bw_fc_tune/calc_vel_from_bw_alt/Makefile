all:
	g++ main.cpp -o main.out -std=c++11 -lm
clean:
	rm main.out all.txt
plot:
	gnuplot -e "plot 'all.txt' using 1:2 title 'raw' with lines,\
		'all.txt' using 1:3 title '1.0' with lines lw 2,\
		'all.txt' using 1:4 title '2.0' with lines lw 2, \
		'all.txt' using 1:5 title '2.5' with lines lw 2, \
		'all.txt' using 1:6 title '3.0' with lines lw 2, \
		'all.txt' using 1:7 title 'vel1' with lines lw 2, \
		'all.txt' using 1:8 title 'vel2' with lines lw 2, \
		'all.txt' using 1:9 title 'vel3' with lines lw 2, \
		'all.txt' using 1:10 title 'vel4' with lines lw 2, \
		; pause -1"

