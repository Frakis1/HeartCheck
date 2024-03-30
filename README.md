txt_file = 'Здоровье'
win_x, win_y = 200,100
win_width, win_heigth = 1000,600 

class МainWin(QWidget):
  def set_appear(self):
    self.setWindowTitle(txt_title)
    self.resize(win_width, win_heigth)
    self.move(win_x, win_y)
  def __init__(self):
    super().__init__()
    self.set_appear()
    self.initUI()
    self.connects()
    self.show()
  
