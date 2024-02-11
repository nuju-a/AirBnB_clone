The AirBnB clone is part of a the course work for the alx-se the idea is to replicate the website in stages.
It kicks offf with the creating 'The Console' which will involve the following - creating my own data model -manage(create,update,destroy) objects via the console -storing and persist object to a file (JSON FILE).
The command intepreter(cmd) will help achieve this instantiate a cmd class that call Cmd and its objects.
example of how tio use will look like:
"""
import cmd
class UCmd(cmd.Cmd):
	prompt = '>>>' # the prompt string to be displayed
 def do grees(self, line):
	 """an example of cmd object to greet user"""
	print('Hello Nuju')

if __name__ == '__main__':
	UCmd().cmdloop()
	""" anothe cmd object that keeps interactive console in a loop"""
