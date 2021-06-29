![bear_hi](https://media.giphy.com/media/c9ndlj2AUhaqk/giphy.gif)
```Python
class AlexBlain():
  def __init__(self):
      self.university = "Newcastle University"
      self.degrees_earned = ["Bsc(Hons) Biomedical Science", "MRES Cancer Research"]
      self.degree_inprogress = "PhD in lymphoma genomics"
      self.pronouns = "she/her"
      self.languages = ["R", "Python","Bash"]
      self.additional_skills = ["HTML", "basic CSS"]
      self.career_aim = "postdoctoral cancer researcher"
      self.interests = ["hiking/weight training", "rock music", "horror films", "bee immunology"] 
      self.current_projects = ["PhD project", "100 Days of Code"]
      self.email = "a.e.blain1@newcastle.ac.uk"
      
    def say_hi(self):
        print(f"""Hi!
        I'm currently completing a {self.degree_inprogress} at {self.university} in the UK.
        I would like to become a {self.career_aim}, undertaking projects requiring a mix of lab based and bioinformatics skills.
        During my PhD I have learned {self.languages} and want to continue my coding journey.
        Some of my personal interests include {self.interests} which have been keeping me sane during the pandemic!
        If you would like to contact me, please use {self.email}""")


me = AlexBlain()

me.say_hi()
```
