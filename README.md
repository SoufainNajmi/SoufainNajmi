<h1 align="center">
  <img src="https://media.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif" width="40px" /> 
  Hey, I'm Soufain Najmi - Cybersecurity & Full-Stack Dev Student
</h1>

```python
class Student:
    def __init__(self):
        self.name = "Soufain Najmi"
        self.role = "Cybersecurity & Full-Stack Student"
        self.passions = [
            " Cybersecurity & Ethical Hacking",
            " Network Engineering", 
            " Full-Stack Development",
            " System Administration"
        ]
        self.current_learning = [
            "Network Security Protocols",
            "Web Application Security",
            "Cloud Infrastructure",
            "DevSecOps Practices"
        ]
    
    def say_hi(self):
        return "Welcome to my cyber world! "
    
    def contact_info(self):
        """Return professional contact information"""
        return {
            "github": "https://github.com/SoufainNajmi",
            "linkedin": "https://linkedin.com/in/soufain-najmi",
            "email": "soufainnajmi@gmail.com"
        }
    
    def display_profile(self):
        """Display complete student profile"""
        profile = f"""
   **STUDENT PROFILE**

  **Name**: {self.name}
  **Role**: {self.role}

  **Passions**:
""" + "\n".join([f"   • {passion}" for passion in self.passions]) + f"""

  **Currently Learning**:
""" + "\n".join([f"   • {topic}" for topic in self.current_learning]) + f"""

 **Connect with me**:
   • GitHub: {self.contact_info()['github']}
   • LinkedIn: {self.contact_info()['linkedin']}
   • TryHackMe: {self.contact_info()['tryhackme']}
   • Email: {self.contact_info()['email']}
"""
        return profile

# Create instance and display information
me = Student()
print(me.say_hi())
print(me.display_profile())
```


## 🏆 GitHub Trophies

[![trophy](https://github-profile-trophy.vercel.app/?username=SoufainNajmi&theme=radical&no-frame=true&row=1&column=7)](https://github.com/SoufainNajmi)

 This README positions you as a serious and passionate student, ready to evolve in the cybersecurity field! �
