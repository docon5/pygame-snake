# pygame-snake
import tkinter as tk
import random
import time

main = tk.Tk()
HEIGHT = main.winfo_screenheight()
WIDTH =main.winfo_screenwidth()
main.geometry('%dx%d+0+0' % (WIDTH,HEIGHT))
ny_canvas = tk.Canvas(main, width = WIDTH, height = HEIGHT, bg = 'black')
ny_canvas.pack()
