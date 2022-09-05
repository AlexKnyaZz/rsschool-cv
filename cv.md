[Contacts](#contacts) | [About me](#aboutMe) |  [Skills](#skills) | [Code examples](#codeExamples) | [Work experience](#workExperience) | [Education](#education) | [Languages](#languages)
#Korendyaseva Ekaterina Alexandrovna 
![me](https://avatars.githubusercontent.com/u/66380389?v=4)
 
---
<a id="contacts"></a>
##Contacts:
* __Discord:__ AlexKnyaZz#5949
    * __on server:__ (@AlexKnyaZz)
* __Mail:__ AlexKnyaZz@yandex.ru
---
<a id="aboutMe"></a>
##About me
I'm a russian student which loves to creating some interesting things. Sometimes I've created 3D models in 3Ds Max, but now I'm use Blender for this. Also, sometimes I spending my time in Unity. Now I'm learning to create and administer ERP and CRM systems - this is my future specialisation, - but also I want to become a front-end developer to help others develop their own websites.
In the future, I wanna be better.

---
<a id="skills"></a>
##Skills
* __Soft-skills:__
    * stress resistance
    * punctuality
    * accuracy
    * ability to work with information
    * creativity
    * ability to learn
* __Hard skills:__
    * knowledge of programming languages: C++, python, java, JS
    * ability to work in programs: Unity, Blender, Microsoft Office, Gradle, Docker, Ramus, ERWin Data Modeller
    * ability to work with GitHub: console/webpage
    * knowledge of bots creating: discord, telegram

---
<a id="codeExamples"></a>
##Code examples
>Example 1. "Greetings", C++
```
#include <iostream>
#include <windows.h>
using namespace std;

void setColorGreen(HANDLE h) {
    SetConsoleTextAttribute(h, FOREGROUND_GREEN);
}
void setColorStandart(HANDLE h) {
    SetConsoleTextAttribute(h, FOREGROUND_INTENSITY);
}

int main(){
  HANDLE handle = GetStdHandle(STD_OUTPUT_HANDLE);
  setColorGreen(handle);
  cout << "Greetings. Have a nice day!" << endl;
  setColorStandart(handle);
  return 0;
 }
```
>Example 2. https://www.codewars.com/kata/5a2b703dc5e2845c0900005a
```
function isDivideBy(number, a, b) {
  if ((number % a === 0) && (number % b === 0))
  {
    return true
  }
  else
  {
    return false
  }
}
```
>Example 3. https://www.codewars.com/kata/595970246c9b8fa0a8000086, JS
```
function capitalizeWord(word) {
    n = word.length;
    let i = 1;
    let wordM = "";
    for(i; i < n; i += 1){
        wordM = wordM + word[i];
    }
  newWord = word[0].toUpperCase() + wordM;
  return newWord;
}
```

---
<a id="workExperience"></a>
##Work experience
* _Experience in creating websites:_ Tilda
* https://github.com/AlexKnyaZz/rsschool-cv
---
<a id="education"></a>
##Education
* __Secondary general education__ (done)
* __MIREA__ (student)
---
<a id="languages"></a>
##Languages:
* __Russian__
* __English (intermediate)__
