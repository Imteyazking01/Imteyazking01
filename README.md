- 👋 Hi, I’m Imteyaz
- 👀 I’m interested in ... Python coding
- 🌱 I’m currently learning ...B.tech 1 year
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Imteyazking01/Imteyazking01 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
          💌Contact me
       mdimteyazm72@gmail.com

https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif

https://telegra.ph/file/1e6dac2c0323c1d1e46ca.jpg
​
import json
from dataclasses import asdict, dataclass


@dataclass
class Stack:
    languages   : tuple[str, ...] = ("Python", "Bash", "HTML", "CSS")
    misc        : tuple[str, ...] = ("Docker", "Linux", "FastAPI")
    ongoing     : tuple[str, ...] = ("Django", "Java", "JavaScript")

    def serialize(self):
        return json.dumps(asdict(self), indent=4)


stack = Stack()
print(stack.serialize())
printf("Thank You Very Much. Stay Tuned With Us !!"
​

