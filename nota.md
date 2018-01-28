# NOTA
 ---
 ``` python
 from Tkinter import *

root = Tk()
root.title ("Inventario")
root.iconbitmap('ico-inventario.ico')





frame=Frame(root)
frame.pack (fill='both',expand=1)
frame.pack(),  
frame.config (width=500, height= 300)
frame.config ( bg= "#034C3C")

label=Label(frame, text= "Panel de inventario")
label.place (x=0, y=0)
label.config ( bg= "#034C3C",font=("Segoe UI Negra", 24),fg='red')
 ´´´