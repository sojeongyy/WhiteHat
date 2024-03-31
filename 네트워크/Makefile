all : pcap_test

pcap_test: main.o
	g++ -g -o PCAP main.o -lpcap

main.o:
	g++ -g -c -o main.o PCAP.c

clean:
	rm -f PCAP
	rm -f *.o
