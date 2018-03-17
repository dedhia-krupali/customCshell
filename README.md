# customCshell
# Programmer: Krupali Dedhia

1.	The myshell.c program is a simple custom shell
2.	It performs the commands performed by the shell
3.	It also performs complex commands such as input output file redirection and the piping commands
4.	It performs multiple commands separated by a semicolon
5.	How to run this program:

  •	Start the command prompt in your void Linux VM
  •	Go to the directory where these programs are stored using the command cd
  •	Run the command “gcc myshell.c –o output”
  •	This would create an executable output file named output
  •	Now when this program has been compiled:
  •	Open the executable output file and  then use it as your shell
  •	Run commands ls, cd, pwd
  •	Run multiple commands pwd; ls –l
  •	Run piping commands ls | grep my | wc –l
  •	Run input output redirection commands ls > list, cat list
