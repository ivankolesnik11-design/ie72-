
import tkinter as tk
from PIL import Image, ImageTk # Импорт на будущее
import random
import time

class ThermalApp:
    def __init__(self, root):
        self.root = root
        self.root.title("Система Термографии")
        self.root.geometry("800x600")

if __name__ == "__main__":
    root = tk.Tk()
    app = ThermalApp(root)
    root.mainloop()
