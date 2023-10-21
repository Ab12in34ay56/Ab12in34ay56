- 👋 Hi, I’m @Ab12in34ay56
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Ab12in34ay56/Ab12in34ay56 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

def isLeapYear(year):
  if (year % 4 == 0 and year % 100 !=0) or year % 400 ==0:
    return True
  else:
    return False

year=int(input("Enter a year :"))

if isLeapYear(year):
  print('{} is a leap year.'.format(year))
else:
  print('{} is a not leap year.'.format(year))
