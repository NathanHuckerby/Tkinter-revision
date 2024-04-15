# Tkinter-revision

Creating a top bar:
topFrame=Frame(forecast_page, background="lightgrey", height=25)topFrame.pack(side="top", fill=X)


Navigation bar:
label1 =Label(forecast_page, relief="raised", width=15)
label1.place(x=130, y=350)
label2 =Label(forecast_page, relief="raised", width=15)
label2.place(x=130, y=410)
label3 =Label(forecast_page, relief="raised", width=15)
label3.place(x=130, y=465)

navbar_frame=Frame(forecast_page, bg="lightgrey")navbar_frame.pack_forget()

Putting buttons on nav bar:
buttonExample =Button(navbar_frame, text="Button 1", command=switchToAirQuality)
buttonExample.pack(pady=15)



Scrollable frames:
 v = Scrollbar(root)
 v.pack(side = RIGHT, fill = Y)

 Pop up message box:
 messagebox.askquestion("Form", "Do you want to Submit")
