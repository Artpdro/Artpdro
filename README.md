class Arthur():
    
  def __init__(self):
    self.name = "Arthur Pedro"
    self.username = "ArtPdro"
    self.location = "Recife, Pernambuco"
    self.web = "www.linkedin.com/in/arthurpedrodev"
    self.email = "arthurpedro.profissional@gmail.com"
    self.hardskill = "Python, MySQL, Pandas"
  
  def __str__(self):
    return self.name

if __name__ == '__main__':
    me = Arthur()
