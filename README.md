import tkinter as tk
from PIL import Image, ImageTk
import random
import time

class ThermalApp:
    def __init__(self, root):
        self.root = root
        self.root.title("Система Термографии")
        self.root.geometry("800x600")
        self.main_frame = tk.Frame(root)
        self.main_frame.pack(fill=tk.BOTH, expand=True)
        
self.show_initial_selection()

def show_initial_selection(self):
     pass         

if __name__ == "__main__":
    root = tk.Tk()
    app = ThermalApp(root)
    root.mainloop()
