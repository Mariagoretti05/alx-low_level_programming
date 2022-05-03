   FILE I/0


       REQUIREMENTS
Language: C OS: Ubuntu 20.04 LTS Compiler: gcc 11.2.0 Style guidelines: Betty style

          DESCRIPTION OF EACH FILE

0. A function that reads a text file and prints it to the POSIX standard output.

Prototype: ssize_t read_textfile(const char *filename, size_t letters);

1. A function that creates a file.

Prototype: int create_file(const char *filename, char *text_content);
2. A  function that appends text at the end of a file.

Prototype: int append_text_to_file(const char *filename, char *text_content);

3. A program that copies the content of a file to another file.

4. A program thta displays the information contained in thr ELF header at the start of an ELF file
