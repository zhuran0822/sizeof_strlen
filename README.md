# sizeof_strlen
Some common output about sizeof and strlen

# ./a.out
(ubuntu 18.04 64bit)
sizeof(char) = 1
sizeof(char*) = 8
sizeof(int) = 4
sizeof(int*) = 8
sizeof(long) = 8
sizeof(long*) = 8
sizeof(double) = 8
sizeof(double*) = 8
char a[]="hello";
char b[]={'h', 'e', 'l', 'l', 'o', 'w', 'o', 'r', 'l', 'd'};
char *c="abcdef";
char d[]="abcdef";
char e[]={'a','b','c','d','e','f'};
sizeof(a) = 6, strlen(a) = 5
sizeof(b) = 10, strlen(b) = 10
sizeof(c) = 8, strlen(c) = 6
sizeof(d) = 7, strlen(d) = 6
sizeof(e) = 6, strlen(e) = 12

# ./a.out 100
//...(more)
