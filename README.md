# get_next_line
```
$ A C project where we can access the contents of a file line by line.
```
```
How to use this project:
$ First you should create file and write something in this file.
$ You should write main like this :
```
```
...
int main()
{
  int fd = open("a.txt", O_RDWR);
  get_next_line(fd);
}
```

$ After you should compile get_next_line.c and get_next_line_utils.c
