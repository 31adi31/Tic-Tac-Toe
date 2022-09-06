import tkinter as tk
from replit import audio

root = tk.Tk()
root.wm_geometry("600x800")
root.title("Tic Tac Toe")

xBg = tk.PhotoImage (file = "X01.png")
oBg = tk.PhotoImage (file = "O01.png")

#clear frame and display x and o 

def tictactoex01(): 
  global label1x
  user_button.destroy()
  user_button02.destroy()
  label1x = tk.Label(frame_one, image = xBg).pack()


def tictactoeoy01(): 
  global label1o
  user_button.destroy()
  user_button02.destroy()
  label1o = tk.Label(frame_one, image = oBg).pack()


def tictactoex02(): 
  global label2x
  user_button1.destroy()
  user_button12.destroy()
  label2x = tk.Label(frame_two, image = xBg).pack()

def tictactoeoy02(): 
  global label2o
  user_button1.destroy()
  user_button12.destroy()
  label2o = tk.Label(frame_two, image = oBg).pack()

def tictactoex03(): 
  global label3x
  user_button2.destroy()
  user_button22.destroy()
  label3x = tk.Label(frame_three, image = xBg).pack()
  

def tictactoeoy03(): 
  global label3o
  user_button2.destroy()
  user_button22.destroy()
  label3o = tk.Label(frame_three, image = oBg).pack()
  
  
  
def tictactoex04(): 
  global label4x
  user_button3.destroy()
  user_button33.destroy()
  label4x = tk.Label(frame_four, image = xBg).pack()
  #label4x = tk.Label(root, image = xBg)


def tictactoeoy04(): 
  global label4o
  user_button3.destroy()
  user_button33.destroy()
  label4o = tk.Label(frame_four, image = oBg).pack()
  
def tictactoex05(): 
  global label5x
  user_button4.destroy()
  user_button44.destroy()
  label5x = tk.Label(frame_five, image = xBg).pack()
  

def tictactoeoy05(): 
  global label5o
  user_button4.destroy()
  user_button44.destroy()
  label5o = tk.Label(frame_five, image = oBg).pack()
  
def tictactoex06(): 
  global label6x
  user_button5.destroy()
  user_button05.destroy()
  label6x = tk.Label(frame_six, image = xBg).pack()

def tictactoeoy06(): 
  global label6o
  user_button5.destroy()
  user_button05.destroy()
  label6o = tk.Label(frame_six, image = oBg).pack()
  
def tictactoex07(): 
  global label7x
  user_button6.destroy()
  user_button06.destroy()
  label7x = tk.Label(frame_seven, image = xBg).pack()
def tictactoeoy07(): 
  global label7o
  user_button6.destroy()
  user_button06.destroy()
  label7o = tk.Label(frame_seven, image = oBg).pack()
def tictactoex08(): 
  global label8x
  user_button7.destroy()
  user_button07.destroy()
  label8x = tk.Label(frame_eight, image = xBg).pack()

def tictactoeoy08(): 
  global label8o
  user_button7.destroy()
  user_button07.destroy()
  label8o = tk.Label(frame_eight, image = oBg).pack()

def tictactoex09(): 
  global label9x
  user_button8.destroy()
  user_button08.destroy()
  label9x = tk.Label(frame_nine, image = xBg).pack()


def tictactoeoy09(): 
  global label9o
  user_button8.destroy()
  user_button08.destroy()
  label9o = tk.Label(frame_nine, image = oBg).pack()


def play_doja():
  source = audio.play_file("Doja.mp3")

def play_Weeknd():
  source = audio.play_file("The Weeknd.mp3")

def play_kanye():
  source = audio.play_file("kanye.mp3")
  
frame_one = tk.Frame(root, background= "violet")
frame_one.config(width="100", height="100")
frame_one.grid(row = 0, column = 0)

frame_two = tk.Frame(root)
frame_two.config(background="green", width="100", height="100")
frame_two.grid(row=0, column=1)

frame_three = tk.Frame(root)
frame_three.config(background= "red", width="100", height="200" )
frame_three.grid(row=0, column=2)

frame_four = tk.Frame(root)
frame_four.config(background= "brown", width="100", height="100")
frame_four.grid(row=1, column=0)

frame_five = tk.Frame(root)
frame_five.config(background= "yellow", width="100", height="100")
frame_five.grid(row=1, column=1)

frame_six = tk.Frame(root)
frame_six.config(background= "blue", width="100", height="100")
frame_six.grid(row=1, column=2)

frame_seven = tk.Frame(root)
frame_seven.config(background= "light blue", width="100", height="100")
frame_seven.grid(row=2, column=0)

frame_eight = tk.Frame(root)
frame_eight.config(background= "gray", width="100", height="100")
frame_eight.grid(row=2, column=1)

frame_nine = tk.Frame(root)
frame_nine.config(background= "white", width="100", height="100")
frame_nine.grid(row=2, column=2)

frame_ten = tk.Frame(root)
frame_ten.config(background= "white", width="100", height="100")
frame_ten.grid(row=0, column=3)

frame_eleven = tk.Frame(root)
frame_eleven.config(background= "white", width="100", height="100")
frame_eleven.grid(row=1, column=3)

#import images 
popsmoke_music = tk.PhotoImage(file="button (14).gif")
doja_music = tk.PhotoImage(file = "button (16).gif") 
weeknd_music = tk.PhotoImage(file = "button (19).gif")


#Frame_ten elements 
musicLabel = tk.Label(frame_ten, text = "Music").pack()
popsmokeButton = tk.Button(frame_ten, image = popsmoke_music, command = play_kanye).pack()
dojaButton = tk.Button(frame_ten, image = doja_music, command = play_doja).pack()
weekndButton = tk.Button(frame_ten, image = weeknd_music, command = play_Weeknd).pack()


def ratingFunction():
  ratingStored = ratingTextBox.get()
  saveFile = open("Ratings.txt", "a")
  saveFile.write(ratingStored,"\n")
#Frame_eleven element
ratingLabel = tk.Label(frame_eleven, text = "Ratings").pack()
ratingTextBox = tk.Entry(frame_eleven)
ratingTextBox.pack()
submitButton = tk.Button(frame_eleven, text="Submit", command = ratingFunction)
submitButton.pack()






#user_input = tk.Entry(frame_main, bd=3)
#user_input.pack(padx=20, pady=30)

user_button = tk.Button(frame_one, text='x',command = tictactoex01)
user_button.pack(padx=70, pady=25)
user_button02 = tk.Button(frame_one, text='o', command = tictactoeoy01)
user_button02.pack(padx=70, pady=25)

user_button1 = tk.Button(frame_two, text='x', command = tictactoex02)
user_button1.pack(padx=70, pady=25)
user_button12 = tk.Button(frame_two, text='o', command = tictactoeoy02)
user_button12.pack(padx=70, pady=25)

user_button2 = tk.Button(frame_three, text='x', command = tictactoex03)
user_button2.pack(padx=70, pady=25)
user_button22 = tk.Button(frame_three, text='o', command = tictactoeoy03)
user_button22.pack(padx=70, pady=25)

user_button3 = tk.Button(frame_four, text='x', command = tictactoex04)
user_button3.pack(padx = 70, pady = 25 )
user_button33 = tk.Button(frame_four, text='o', command = tictactoeoy04)
user_button33.pack(padx = 70, pady = 25 )

user_button4 = tk.Button(frame_five, text='x', command = tictactoex05)
user_button4.pack(padx = 70, pady = 25 )
user_button44 = tk.Button(frame_five, text='o', command = tictactoeoy05 )
user_button44.pack(padx = 70, pady = 25 )

user_button5 = tk.Button(frame_six, text='x', command = tictactoex06)
user_button5.pack(padx = 70, pady =25 )
user_button05 = tk.Button(frame_six, text='o', command = tictactoeoy06)
user_button05.pack(padx = 70, pady = 25 )

user_button6 = tk.Button(frame_seven, text='x', command = tictactoex07)
user_button6.pack(padx = 70, pady = 25 )
user_button06 = tk.Button(frame_seven, text = 'o', command = tictactoeoy07)
user_button06.pack(padx = 70, pady = 25 )

user_button7 = tk.Button(frame_eight, text='x', command = tictactoex08)
user_button7.pack(padx = 70, pady = 25 )
user_button07 = tk.Button(frame_eight, text='o', command = tictactoeoy08)
user_button07.pack(padx = 70, pady = 25 )

user_button8 = tk.Button(frame_nine, text='x', command = tictactoex09)
user_button8.pack(padx = 70, pady = 25 )
user_button08 = tk.Button(frame_nine, text='o', command = tictactoeoy09)
user_button08.pack(padx = 70, pady = 25 )

#tictactoe game logic





root.mainloop()
