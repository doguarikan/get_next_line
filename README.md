# get_next_line
A C project to access line by line the contents of a file

## Running the project
- First create a file
- And write a main like this
```
...
int main()
{
  int fd = open("a.txt", O_RDWR);
  get_next_line(fd);
}
```
